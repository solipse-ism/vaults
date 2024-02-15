## Operating System Management
- Key Management: UI, Memory, Secondary Storage, Peripheral, Process, Security, platform for application softwarez
### User Interface
- CLI and GUI allows interaction
- Allows human to interact with software directly
### Memory
- Only one process is run per address
- organise the memory for finite RAM
	- VM and Segmentation
	- move data betwene RAM VM and processor
### Secondary Storage
- Storage space divided into file allocation units
- Spaced allocated to particular files
- Maintain file directory and FAT
- Provide file naming convention
- Control access of files and directory
### Security
- Perform recovery when data is lose 
- Provides User account and encryption
- prevent unauthoriseed access
- ensure data privacy
### Peripheral
- auto install of appropriate driver
- control access to data sending between peripheral and the OS
- control access to peripheral
- manage communication between software and hardware
### Interrupt
- Halts the execution of the current process
 • Stores the values of the current process on the stack
 • Loads and executes the appropriate ISR code
 • Use of priorities for handling simultaneous interrupts
 • Saves data on power outage
### Process
- Allocation of processor time 
- Scheduling of processes
- Support for multitasking
- Conflict resolution when 2 processes require the same resource
- Allocate processing power and RAM space for the processes 
## Utility Software (part of OS)
### Disk Defragmentation 
- Re-organises the disk contents
- Moves split files so they are contiguous
- Creates a larger area of contiguous free space
- improve disk access time, as it reduce the read/write head's movement
### Disk Formatter
- partitioning disk into logical drive
- Prepares disk for initial use
- set up specified file system for the OS
- May check for error on the disk
- make existing ata inacessible
### Disk Content Analysis and Repair 
- **Analysis**: check for errors with the disk "bad sector"
	- due to physical defects from mishandling the system, manufacturing
	- due to files may be unuseable from Loss of power
- **Repair Error**: attemp to fix error (Don't use/repair bad sector)
	- repair/delete data
- Prepare the disk for initial use again
### Disk Mirroring
- use one disk to copy the main disk data simultaneously
- if the first disk fails, the data can be access/retrieve from the second disk
### **Back-up**
- make copy of data stored elsewhere at regular intervals
- if files are lost/corrupted, it can be retrived
### **Virus Checker**
- regular patches(update) requied
- scan all files regulary for virus comparing it to known database
- If found, virus is quarantine or remove form the system
- it can be schedule and run in background
- notifies user of a possible virus when downloading, and check for virus on the newly connected disk
### File compression
- Reduce the file size by using algorithm to change the data
- can be lossless or lossy
- allow more storage for other files
- uses less upload and download bandwidth
## Library
### General library
- time efficient
	- make use of others knowledge
	- easy to read
	- don't have to start over
- Pre-tested (industry standard) -> relatively no error -> robust program
### DLL
- Why not STT
	- **potential memory inefficiency**, all the code in the method file need to be compile with the program
	- **increase memory usage** (when multiple processes use the same routine), each process loads its own copy into memory. 
### Why use DLL?
- specific subroutine code can be include -> less storage space and memory requirement
- easy to upgrade, just upgrade the DLL subroutine files
### Disadvantage of DLL
- Require the libraries without corrupted or incompatability to work as expected
- user not understand how to use the subroutine, as they can't see the code
- runtime linking can -> delay in program execution
---
## Language Translator
### Assembler - Assembly Language
- instruction in the source code consists of an op and operand code
### Compiler
1. analyse line by line
2. source code -> intermediate code
3. if error -> list the errors
4. intermediate code -> object code (.exe files, similar to machine code)
- EXE file produce
	- no access to source code
		- less secure: could have viruses
	- no need for translator software
	- run fast
	- easy to use for the user
- Cross-compilation, the program can be compiled to run on different platforms
### Interpreter, (client-side script webpage)
1. analyse code line by line
2. if error -> stop and report
3. source code -> Intermediate code(middle-level language, like assembly language) and use it to do required action
-  easy to debug - time efficient for dev (single error can cause multiple additional error)
	- Errors found are corrected in real time
	- translation continue from stoping point
	- code effect seen immediately
	- part of program can be tested without entire code available
		- unused part may contain error, not seen until later
	- no wait time for the whole source code to be read and analyse
- No exe file produced
- source code is distributed and can be editted
- source code is needed at run time with translation software(extra CPU resource maybe required)
	- Execution time increase
### Java
- java code is partially interpret, partially compiled
- Java use a two-step translation process
	- code is translateed into bytecode, by java compiler
	- bytecode is interpret by the JVM (Java Virtual Machine)
- any machine with the JVM can run the java program
---
## Integrated Development Environment, IDE
### Coding
- Context-sensitive prompts - display menu hint of keyword that can be use based on what is type
- Auto-Complete
- Auto-Correct
### Initial Error Detection
- Dynamic Syntax check - check for syntax everytime somethings is type and alert syntax error
### Presentation
- Pretty printing
	- Colour-code keywords, function calls, comments, strings, indentatiton. syntax highlighting
- Code Block (collapse and Expand) - reduce scrolling in huge program code with many lines
### Debugging (i.e. Variable, expression)
- Single stepping - Execute code line by line.
	- Breakpoint - Line where program halt execution to check current state of variable
		- Variable/expresssion watch/report window - monitor varible/expressiono values as program is beinig executed