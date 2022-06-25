CS152 Project Phase 1 - Lexical Analyzer Generation Using flex
===============================================================


[Home Page - Phase1 Lexer](https://cs152-ucr-gupta.github.io/website/phase1_lexer.html)


## Tools preparation

Make sure you have a Linux environment for this project. You can use 'bolt', your own Linux machine, or Windows Subsystem for Linux(WSL). We highly recommend you directly use 'bolt' since it contains all the necessary tools preinstalled. 

```sh
ssh <your-net-id>@bolt.cs.ucr.edu
```

Make sure you have the following tools installed and check the version:
1. flex -V       (>=2.5)
2. git --version (>=1.8)
3. make -v       (>=3.8)
4. gcc -v        (>=4.8)
5. g++ -v        (>=4.8 optional if you wish to use C++)

## Clone and Build

Use 'git' to clone the project template and build it by typing 'make'

```sh
    git clone <your-repo-link> phase1
    cd phase1 && make
```

## Use the template

You can change any files and add additional C files, but please make sure all files are linked to the final executable file in Makefile. Please don't change the name of 'Makefile' and 'miniL.lex'. After typing make, An executable file 'miniL' is expected to be created as your phase1 lexer.

## Project Submission 

* Start Date: 6/22/2022
* Due Date:   6/29/2022

Submit your project on Elearn. If you are doing the project in a group of two, each group member should submit the project separately. 

## Academic integrity

Copying source code from students in previous semester and other teams will be considered a violation of academic integrity. 
