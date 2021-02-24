load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
	name = "libutf",
	srcs = [
		"rune.c",
		"runestrcat.c",
		"runestrchr.c",
		"runestrcmp.c",
		"runestrcpy.c",
		"runestrdup.c",
		"runestrlen.c",
		"runestrecpy.c",
		"runestrncat.c",
		"runestrncmp.c",
		"runestrncpy.c",
		"runestrrchr.c",
		"runestrstr.c",
		"runetype.c",
		"utfecpy.c",
		"utflen.c",
		"utfnlen.c",
		"utfrrune.c",
		"utfrune.c",
		"utfutf.c",

		"plan9.h",
		"utfdef.h",
	],
	hdrs = ["utf.h"],
	copts = [
		"-Wno-parentheses",
	],
	visibility = ["//visibility:public"],
)
