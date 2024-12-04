# TOPS Variables Description

This document provides descriptions for all variables related to TOPS used in the system.

## CMAKE_TOPS_COMPILER_TOOLKIT_ROOT

This variable contains the path to folder of TOPS toolkit

## TOPSToolkit_TOPSCC_EXECUTABLE

This variable contains the path to topscc executable

## TOPSToolkit_BIN_DIR

This variable contains the path to folder containing topscc executable

## TOPSToolkit_ROOT_DIR

This variable contains the path to folder of TOPS toolkit

## CMAKE_TOPS_COMPILER

Contains path to the topscc executable

## TOPS_PATH

This variable contains the path to folder of TOPS toolkit

## TOPS_TOPSRT

Contains path to libtopsrt.so shared library

## TOPSToolkit_VERSION

Contains the exact version of the TopsToolkit found (as reported by topscc --version)

## TOPSToolkit_VERSION_MAJOR

Contains the MAJOR part of  version of the TopsToolkit found (as reported by topscc --version)
Complete version is of the format: MAJOR_VERSION.MINOR_VERSION.PATCH_VERSION

## TOPSToolkit_VERSION_MINOR

Contains the MINOR part of  version of the TopsToolkit found (as reported by topscc --version)
Complete version is of the format: MAJOR_VERSION.MINOR_VERSION.PATCH_VERSION

## TOPSToolkit_VERSION_PATCH

Contains the PATCH part of  version of the TopsToolkit found (as reported by topscc --version)
Complete version is of the format: MAJOR_VERSION.MINOR_VERSION.PATCH_VERSION

## CMAKE_TOPS_COMPILER_INIT

This variable is used to store the return value of condition check that checks whether CMAKE_TOPS_COMPILER has been initialized

## CMAKE_TOPS_COMPILER_ENV_VAR

Contains name of environment variable to be searched for finding path to topscc executable

## CMAKE_TOPS_HOST_COMPILER_ENV_VAR

Contains name of environment variable to be searched for finding path to host compiler

## CMAKE_TOPS_IMPLICIT_LINK_DIRECTORIES

Contains path to the directories where libraries to be linked to targets created using topscc need to be searched

## CMAKE_TOPS_IMPLICIT_LINK_LIBRARIES

Contains path to the libraries to be linked to targets created using topscc

## CMAKE_TOPS_IMPLICIT_INCLUDE_DIRECTORIES

Contains path to the include directories where header files required for compilation of .tops files need to be searched

## CMAKE_TOPS_TOOLKIT_INCLUDE_DIRECTORIES

Contains the path to include directories with topsrt related headers

## CMAKE_TOPS_STANDARD

This variable contains the compilation standard to be used for compilation of TOPS files.Currently standards C++11,C++14,C++17 are supported by TOPS. Standards C++98 and C++20 are not supported.

## CMAKE_TOPS_STANDARD_REQUIRED

Contains a boolean value that ensures that CMAKE_TOPS_STANDARD is followed for .tops files

## CMAKE_TOPS_FLAGS

This variable contains compilation flags to be used for compilation of TOPS files

## CMAKE_TOPS_OUTPUT_EXTENSION

This variable contains list of extensions for output files after compilation of TOPS files

## CMAKE_TOPS_SOURCE_FILE_EXTENSIONS

This variable contains list of extensions that can be used for source files for TOPS language
