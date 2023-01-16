# BF-mini-interpreter
The repository contains a compact implementation (25 lines of C-flavored C++ code) of what I called an 'interpreter' for Brainf***. Compressing the length of the code inevitably reduces the readability and maintainability. I made this project as a mere challenge, and I may make a more sophisticated and detailed version in the future.

# How to use

1.  If your are in BF-interpreter/README.md, please go back to the previous page by clicking this link (https://github.com/Erics-Lab/BF-interpreter).
2.  Give the little green button on the top right corner with the label 'Code' a push, a dialog should show up. Press 'Download ZIP' in the dialog.
3.  Once the zip file is downloaded, open it with your archive manager and extract the files to a arbitrary destination (I would extract the files to the Desktop).
4.  Open the terminal (If you don't know how to open the terminal, feel free to use the built-in search function in your system to find it.). Type the following:

```bash
cd Desktop/BF-Interpreter-main
```
  From there, you could type the following if you want to compile it by yourself,
```bash
g++ interpreter.cpp
```
```bash
./a.out
```
  Or you can just "run" the object file (well actually, you can't run an object file, this command is just creating linkings) I provided by typing,
```bash
./a.out
```
5.  The output should be:

```bash
This interpreter is useless.
```
  
  You can always change the output by modifying the BF code in ```test.bf```.
