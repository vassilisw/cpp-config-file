# Intro

By Richard J. Wagner  v2.1  24 May 2004


# Instructions

The only necessary files for using this configuration file reader are
"ConfigFile.h" and "ConfigFile.cpp".  The class name is ConfigFile.

Usage examples are in "example.cpp".  Linux or Unix users can type "make" to
compile and then type "make run" to run the example program.

The test program in "tester.cpp" will check that the class properly reads
a variety of simple and complex configuration file entries.  To run the test
program type "make test".

When you are done with the examples and the test program, type "make clean"
to get rid of temporary files.

For Windows or Mac users with a compiler such as Metrowerks CodeWarrior or
Microsoft Visual C++, simply add "example.cpp" and "ConfigFile.cpp" to an
empty C++ console application.  Compile and run to see the configuration
file reader in action.  Do likewise with "tester.cpp" to check that the
code works properly with your compiler.


# Installation

Just copy the files "ConfigFile.h" and "ConfigFile.cpp" to your working
directory or some other place where your compiler can find them.  Add
"ConfigFile.cpp" to your project and put the following line at the top of
your program to access the ConfigFile class:

	include "ConfigFile.h"


# Contents

	README            - this file
	ConfigFile.h      - declaration of ConfigFile class
	ConfigFile.cpp    - definitions of ConfigFile class
	example.cpp       - examples of using ConfigFile
	tester.cpp        - tests ConfigFile class
	example.inp       - configuration file for example program
	test.inp          - configuration file for tester program
	Triplet.h         - sample user-defined data type
	Makefile          - instructions used by "make" command
	ConfigFile.html   - Web page about ConfigFile
	AntBlueMaize.jpg  - background for ConfigFile.html
	ArrowHome.gif     - home icon for ConfigFile.html
	main.css          - style sheet for ConfigFile.html
