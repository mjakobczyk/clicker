# clicker

Library for performing MinHash algorithm using SIMD.

## Gettig started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. Download listed tools and libraries.

### Tools

* [CMake](https://cmake.org/) - crossplatform tool for generating makefiles

### Libraries

* [SFML] (https://www.sfml-dev.org/index.php) - application GUI

### CMakeLists.txt

CMakeLists is a file that CMake looks for. Depending on specified instructions and directories CMake generates Makefile for the target application.

## Installation

### Windows 10

Download **Tools** from section **Getting started**.

### MacOS

Use *homebrew* for downloading dependencies.

```bash
brew install cmake
```

## Run

First, clone the repository using https or SSH. Example:

```git clone https://github.com/mjakobczyk/minhash.git```

Second, run CMake with a compiler that you like. On Windows the default compiler will be the one from Visual Studio IDE if it is installed on the machine. Suggested solution is to use Visual Studio 2017.

### Windows 10

```cd build/; cmake ../ . -G "Visual Studio 15 2017" -DSFML_ROOT=D:/SFML .; make;```

### MacOS

```cd build/; cmake ../ .; make;```

Finally, run the application using generated target file:

``` ./program```
