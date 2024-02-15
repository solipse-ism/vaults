[[Computer Science]]
## 03 Hardware 
### Definition Describe Question
- Primary Storage:
	- SRAM/DRAM
	- ROM/PROM/EPROM/EEPROM
- Secondary Storage:
	- Magnet hard disk/Optical disc rw/solid state drive
- Input/Output
- 3DP/LaserP/TouchScreen/VR/Speaker/Mic
- All sensor
### Bigger Idea
![[MaIn Hardware Concept.svg | Main Hardware Concept]]
### Input
#### Mic 
### Output
#### Laser Printer
#### 3DP
#### Speaker
#### VR Headset
### Both I/O
#### Touchscreen
### Memory (Primary Storage)
#### SRAM vs DRAM
|  | SRAM | DRAM |
| ---- | ---- | ---- |
| Storing Data | uses flip-flop(logic Gates) | Uses capacitor that leaks, need to be refresh constantly |
| Cost |  | cheaper |
| Disk Access Time | Faster(use as cache) |  |
| Components per bit stored |  | less => cheaper |
| Power consumption |  | more <- need refresh |
- Buffer is used when data sent faster than it can be received. it stored incoming data
#### ROM PROM EPROM and EEPROM
- **ROM** Data written can't be changes, usually contain bootstrap and other firmware which is copied into RAM on boot so not connected to processor directly
- **PROM** allows programmer to flash their own instruction once
- **EPROM** allows user to be able to erase data by UV
- **EEPROM** allows erasion by electricity
#### RAM vs ROM
|  | RAM | ROM |
| :--- | :--- | :--- |
|  |  | Read only => hard to change |
|  | CPU have Direct Access |  |
|  | Voltile | permanent |
| Stored | buffer, currently running instruction and part of processes | bootstrap, firmware, kernel of OS |
### Storage
#### Magnetic media (watch a video)
- Magnetic Tape Catridge, HDD
- Interaction is controlled by read/write head <-(controlled by) arm <- the electronic circuit
- has one or more platters, each with its own rw head positioned just about its surface, the platters are made of alluminum/glass coated with ferrous oxide (which allow magnitisation)
- Platter mounted on central spindle allowing the disks to rotate at high speed
- each platter's surface is divided into concentric track and sectors
- data is encoded through pattern of manetise block

- When writing to disk, a variation in the current in the head produces a variation in magnetic field on the disk
- When reading from disk, a variation in magnetic field produces a variation in current through the head
![[HDD Internal Structure.png|HDD Internal Structure| 300]]
#### Optical media

### Embedded System
- System not easily altered by the owner
- combination of hardware and software designed for specific function
- it can be integrated into a bigger system
- Uses a MCU(processor, i/o, and memory)
- UI can be implemented
#### Benefit
- easy to mass produce, EOS, cheap to manufacture
- Simple to use
- requires little power
- fast reaction to changing input
- dedicated to one function
- can be controlled remotely
#### Disadvantage
- Difficult to upgrade, if not EEPROM, often thrown away
- Interface can be made confusing
- troubleshoot need specialist
- if IOT, prone to cyber attack
### Monitoring and Control
- Monitoring:
- Control:
- Sensor: temperature, sound, infra-red, pressure
- Actuator
- Feedback:
## 03 Logic Gates and Logic Circuit
## 05 System Software
### Describe/Define Question
- Memory/process/peripheral/security/2ND Storage/Interrupt/UI/SoftwareApp
- Defragmentor/ContentAnalysis&Repair/Formatter/FileCompression/Backup/VirusChecker
### OS Key management
Memory | Process | Peripheral | Security | 2ND Storage
#### Memory
- 
#### Process
- 
#### Peripheral
- 
#### Security
- 
#### 2ND Storage
- 
### Utility Software
#### Disk Formatter
- 
#### Disk Content Analysis and Repair
- 
#### Disk Formatter
- 
#### File Compression
- 
#### Backup
- 
#### Virus Checker
-  
## 15 Hardware and Virtual Machine
## 15 Logic Circuits and Boolean Algebra
## 16 System Software