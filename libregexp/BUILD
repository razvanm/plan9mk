load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
	name = "libregexp",
	srcs = [
		"regcomp.c",
		"regerror.c",
		"regexec.c",
		"regsub.c",
		"regaux.c",
		"rregexec.c",
		"rregsub.c",

		"lib9.h",
		"regcomp.h"
	],
	hdrs = ["regexp9.h"],
	copts = [
		"-Ilibutf",
		"-Ilibfmt",
	],
	deps = [
		"//libutf",
		"//libfmt",
	],
	visibility = ["//visibility:public"],
)
