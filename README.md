Clang Plugin
============

A simple XCode project for building Clang plugins.

Instructions
------------
* Run the default target in XCode
* This generated two files, `ClangPlugin.xcconfig` and `ClangPluginUser.sh`
* Download Clang and set the `LLVM_CONFIG` export in `ClangPluginUser.sh` to the path to `llvm-config`
* Run the same target again and verify that `ClangPlugin.xcconfig` contains the correct exports for your environment
* Start from `PrintFunctionNames.cpp` as base
