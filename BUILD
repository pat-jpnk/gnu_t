package(default_visibility = ["//visibility:public"])

filegroup(
    name = "all_files",
    srcs = glob([
        "bin/**",
        "etc/**",
        "include/**",
        "lib/**",
        "libexec/**",
        "share/**",
        "x86_64-pc-linux-gnu/**",
    ]),
)

filegroup(
    name = "compiler_files",
    srcs = glob([
        "bin/x86_64-pc-linux-gnu-gcc-*",
        "include/**",
        "lib/gcc/**",
        "libexec/gcc/**",
        "x86_64-pc-linux-gnu/include/**",
        "x86_64-pc-linux-gnu/sysroot/**",
    ]) + [
        ":as_files",
        "bin/x86_64-pc-linux-gnu-cc",
        "bin/x86_64-pc-linux-gnu-c++",
        "bin/x86_64-pc-linux-gnu-cpp",
        "bin/x86_64-pc-linux-gnu-g++",
        "bin/x86_64-pc-linux-gnu-gcc",
    ]  
)

filegroup(
    name = "linker_files",
    srcs = glob([
        "lib/**",
        "lib/gcc/**",
        "libexec/gcc/**",
        "x86_64-pc-linux-gnu/lib/**",
        "x86_64-pc-linux-gnu/lib64/**",
        "x86_64-pc-linux-gnu/sysroot/**",
        "bin/x86_64-pc-linux-gnu-gcc-*",
    ]) + [
        "bin/x86_64-pc-linux-gnu-g++",
        "bin/x86_64-pc-linux-gnu-gcc",
        "bin/x86_64-pc-linux-gnu-ld",
        "bin/x86_64-pc-linux-gnu-ld.bfd",
        "bin/x86_64-pc-linux-gnu-ld.gold",
    ],
)

filegroup(
    name = "ar_files",
    srcs = glob([
        "lib/bfd-plugins/**",
        "libexec/gcc/**/liblto_plugin.so",
    ]) + [
        "bin/x86_64-pc-linux-gnu-ar",
        "bin/x86_64-pc-linux-gnu-gcc-ar",
        "bin/x86_64-pc-linux-gnu-gcc-ranlib",
        "bin/x86_64-pc-linux-gnu-ranlib",
        "x86_64-pc-linux-gnu/bin/ar",
        "x86_64-pc-linux-gnu/bin/ranlib",        
    ],
)

filegroup(
    name = "as_files",
    srcs = [
        "bin/x86_64-pc-linux-gnu-as",
        "x86_64-pc-linux-gnu/bin/as",
    ],
)

filegroup(
    name = "dwp_files",
    srcs = [
        "bin/x86_64-pc-linux-gnu-dwp",
    ],
)

filegroup(
    name = "objcopy_files",
    srcs = [
        "bin/x86_64-pc-linux-gnu-objcopy",
        "x86_64-pc-linux-gnu/bin/objcopy",
    ],
)

filegroup(
    name = "strip_files",
    srcs = [
        "bin/x86_64-pc-linux-gnu-strip",
        "x86_64-pc-linux-gnu/bin/strip",
    ],
)
