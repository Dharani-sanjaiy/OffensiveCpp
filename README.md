# OffensiveCpp
Offensive C++ is a collection of offensive security snippets written in C++. It includes various tools for penetration testing and exploit development.

# Table of Contents
* [OffensiveCpp](#offensivecpp)
* [Introduction](#introduction)
* [Why C/C++?](#why-cc)
* [Compiling](#compiling)
* [Reference Libraries](#reference-libraries)
* [Contributing](#contributing)
* [License](#license)

# Introduction
The purpose of this project is to provide colleciton of snippets that can be used for penetration testing and exploit development. Currently, the project contains snippets for:
* AV/EDR Evasion
* Enumeration
* Sandbox Evasion
* Shellcode Execution
* WinAPI Examples

# Why C/C++?
* C/C++ is a compiled language, which means that it can produce code that is optimized for the specific target platform.

* C/C++ is a low-level programming language that offers a high degree of control over system resources.

* C/C++ allows direct memory manipulation and flexibility.

* C/C++ provides a high level of performance and efficiency.

* C/C++ offers the ability to easily interface with other low-level languages like assembly.

* C/C++ has a large and active community of developers, which means that there is a wealth of resources, libraries, and tools available for exploit development.

# Compiling
This repo does not come with precompiled binaries. Before compiling, make sure you have:
1. A C++ compiler: Microsoft Visual C++ compiler is included in Microsoft Visual Studio or you can install the GCC compiler through MinGW or Cygwin.

2. An Integrated Development Environment (IDE), in my case "Visual Studio 2017".

3. The Windows SDK: The Windows SDK includes headers, libraries, and tools that are necessary for developing Windows applications in C++.

# Reference Libraries
Here you can find a list of external open source project I have included.
* [Shellcode Execution](https://github.com/aahmad097/AlternativeShellcodeExec)
* [Sandbox Evasion](https://github.com/Arvanaghi/CheckPlease/tree/master/C)
* [Unhooking NTDLL.dll](https://www.ired.team/offensive-security/defense-evasion/how-to-unhook-a-dll-using-c++)
* [Direct Syscalls](https://github.com/JohnWoodman/stealthInjector)

# Support
You can support my work by becomming my [Patreon](https://www.patreon.com/Lsecqt).
By doing so, you get access to my private packer, while keeping me motivated to produce more and better content.

# Contributing
Contributions to Offensive C++ are welcome. To contribute, please fork the repository and submit a pull request. Please make sure that your code is well-documented and tested.

# License
Offensive C++ is released under the MIT License (https://opensource.org/license/mit/). Please see the LICENSE file for more information.