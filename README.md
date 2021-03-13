# NAND to Tetris

This repository contains my coursework for the course 
[From Nand to Tetris
Building a Modern Computer From First Principles](https://www.nand2tetris.org/).

This project-centered course through which we will be building a modern computer system, from the ground up. The course teaches many major computer science (CS) abstractions through the construction of a modern, full-scale computer system - hardware and software - from the ground up.

## Resources
Website: [nand2tetris.org](http://nand2tetris.org/)

Coursera: Build a Modern Computer from First Principles: Nand to Tetris Part [I](https://www.coursera.org/learn/build-a-computer) | [II](https://www.coursera.org/learn/nand2tetris2)

Book: [The Elements of Computing Systems](https://www.amazon.com/Elements-Computing-Systems-Building-Principles/dp/0262640686/ref=ed_oe_p), By [Noam Nisan](http://www.cs.huji.ac.il/~noam/) and [Shimon Schocken](http://www.shimonschocken.com/) (MIT Press).

## Projects
All projects for Nand2Teris

* Project 0: Introduction 
* Project 1: Boolean Logic
* Project 2: Boolean Arithmetic
* Project 3: Sequential Logic   
* Project 4: Machine Language 
* Project 5: Computer Architecture  
* Project 6: [Assembler](https://github.com/GopalKrishna-P/HackAssembler)   
* Project 7: VM I: Stack Arithmetic   
* Project 8: VM II: Program Control   
* Project 9: High-Level Language  
* Project 10: Compiler I: Syntax Analysis   
* Project 11: Compiler II: Code Generation   
* Project 12: Operating System 


## Getting Started

Download the [Nand to Tetris Software Suite](https://drive.google.com/open?id=1xZzcMIUETv3u3sdpM_oTJSTetpVee3KZ).

It contains all the tools and files necessary for completing all the projects described in this site, and in the book The Elements of Computing Systems.

Follow the setup guide as mentioned [here](https://www.nand2tetris.org/software) to get up and running.

The file in Nand to Tetris Software Suit are organized as follows.

> /projects/ : contains all the project files
> /tools/    : contains nand2tetris software tools

In order to use the tools, your computer must be equipped with a Java Run-time Environment.

Before running the scripts, you must first change their file attributes to include "executable". You can then run the scripts by typing their name, as well as the .sh extension, in the terminal environment.
```
chmod +x HardwareSimulator.sh
```

If you want to avoid typing the 'sh' extensions, you can create (once and for all) symbolic links in your ~/bin directory. Here is an example how to do it for, say, the HardwareSimulator tool:
```
ln -s ~/nand2tetris/tools/HardwareSimulator.sh HardwareSimulator
```


In order to shorten the COMMAND, you can add tools folder to path variable.
```
$ echo "export PATH=$PATH:<path_to_directory>/nand2tetris/tools" >> ~/.zshrc $ source ~/.zshrc
```

To verify path of the script
```
$ where HardwareSimulator.sh
```

*NOTE: In few cases the may not have access to execute. we can use chmod command to modify the access.




## Helpful Links

[Nand guide](https://en.wikipedia.org/wiki/NAND_logic#:~:text=If%20the%20truth%20table%20for,will%20trigger%20a%20high%20output.)

[Logical adders](https://en.wikibooks.org/wiki/Practical_Electronics/Adders)

[Digital Registers](https://www.tutorialspoint.com/computer_logical_organization/digital_registers.htm)

[How Does a Transistor Work?](https://www.youtube.com/watch?v=IcrBqCFLHIY)

[16-bit Arithmetic Logic Unit (ALU) Built in Minecraft](https://www.youtube.com/watch?v=LGkkyKZVzug)

[Easy 6502 Assembly Tutorial](http://skilldrick.github.io/easy6502/)

[Visual 6502 CPU Simulator](http://www.visual6502.org/JSSim/)

[A homebrew 8-bit computer built entirely out of NAND gates](https://hackaday.io/project/9795-nedonand-homebrew-computer)





