# Z80 Assembly Language Development with Pasmo in Visual Studio Code

This template provides a basic setup for developing Z80 assembly language programs in Visual Studio Code using the Pasmo assembler and the z80-macroasm extension. The template includes a tasks.json file that defines a build task for compiling your Z80 source code into a binary file using Pasmo.

Requirements
Before using this template, you will need to have the following software and extensions installed on your system:

* Visual Studio Code: https://code.visualstudio.com/
* Pasmo Assembler: http://pasmo.speccy.org/
* z80-macroasm extension for Visual Studio Code: https://marketplace.visualstudio.com/items?itemName=mborik.z80-macroasm

## Getting Started

To use this template, follow these steps:

* Clone or download the template to your local machine.
* Open the template folder in Visual Studio Code.
* Modify the tasks.json file to match the path and command line arguments for your Pasmo installation.
* Create a new Z80 assembly language file (with a .z80 extension) in the src folder or use the `hello.z80` Hello World code in the template folder
* Write your Z80 assembly language code in the new file.
* Press `Ctrl+Shift+B` to build your code using the assemble task.

>If the build is successful, a binary file with the same name as your source file and a .com extension will be created in the same folder as your source file. `pasmo` task runs with debbugging information `pasmo -d`

### Debugging

You might want to debug your Z80 assembly language code with emulator. You can use an emulator like SIMH, MAME or QEMU, which support a wide range of Z80-based systems including those running CP/M. Alternatively, you can use an external debugger like GDB in combination with an emulator or hardware emulator to debug your code.

### Additional Resources

* Pasmo documentation:  https://pasmo.speccy.org/pasmodoc.html
* Z80 assembly language tutorial: https://www.tutorialspoint.com/microprocessor/microprocessor_z80_assembly.htm


## Drop a Star ⭐ ##

If you like this project then drop a Github star by pressing the Star button ⭐

>License: This template is licensed under the MIT license. See LICENSE for details.
