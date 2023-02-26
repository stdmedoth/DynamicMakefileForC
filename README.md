# Dynamic Makefile for C Projects

This is a dynamic Makefile that automatically detects and compiles all the source code files, making it easier to manage large projects.

The Makefile creates separate directories for object files and executable files, and automatically generates them during the build process. It also includes a run target that runs the executable file after it's been built, as well as a clean target that removes all generated files.

## Usage

1. Copy and paste the Makefile into the root directory of your project.

2. Run make in your terminal to build the executable file.

## Notes

- This Makefile assumes that all source code files are located in the src directory and that all header files are located in the includes directory. You may need to modify the SRC and INCLUDE variables if your project has a different directory structure.

- To run the executable file, simply type make run in your terminal.

- To clean up all generated files, simply type make clean in your terminal.

Enjoy!
