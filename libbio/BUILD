load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
	name = "libbio",
	srcs = [
		"bbuffered.c",
		"bfildes.c",
		"bflush.c",
		"bgetc.c",
		"bgetd.c",
		"bgetrune.c",
		"binit.c",
		"boffset.c",
		"bprint.c",
		"bvprint.c",
		"bputc.c",
		"bputrune.c",
		"brdline.c",
		"brdstr.c",
		"bread.c",
		"bseek.c",
		"bwrite.c",
		"lib9.h",
	],
	hdrs = ["bio.h"],
	copts = [
		"-Ilibutf",
		"-Ilibfmt",
		"-Ilibbio",
	],
	deps = [
		"//libutf",
		"//libfmt",
	],
	visibility = ["//visibility:public"],
)
