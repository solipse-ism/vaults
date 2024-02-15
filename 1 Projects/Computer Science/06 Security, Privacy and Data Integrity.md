## General Definition
- Security - Protecting Data from loss/corruption and illegal access
- Integrity - Ensuring data is consistent and valid/accurate e.g. data not corrpupted after transmission
- Privacy - Ensuring data is kept confidential and only seen by authorised user

- data protection law - any data bleach will violate this law, promotes privacy of data 
## Computer System Secuirty & data stored Treats
### Users don't take care of their devices
- allow malicious software enter system
	- no antimalware
	- no awareness and recognition
- weak security
	- weak password
	- no 2fa
	- doesn't use Biometric
### System and Environment
- Operating system and Anti malware: Lack security and patches
- internal mismanagement
- Buffer overflow in C program
- natural disaster
## Malware - software with harmful intent
### Types of Malware
- Virus - try replicate inside otherr executable coded
- Worm - run independently, transfer itself to other network host
- Logic bomb - inactive until condition is met
- trojan horse - replace all part of previously useful program, disguise as legitimate program
- Spyware - collect information(keylogger) and transmit to other system
- Bot - takes control of another computer, usees it to launch attack
### Malware Activity
- Phishing - Emails disguise as legitimate source request confidential information
- Pharming - bogus website that appears to be legitimate
- keylogger - monitor keyboard usage remotely from another system
## Preventing Threats
### System (os) and application
- regular update/patches
- Finding, fixing and preventing security vulnerabilities in any (installed) application
### access rights - use authentication/user account
- restrict action - read, read-write of specific user
### user authentication
- Biometric - unqiue feature that can't be guess
- username and strong password(only correct combination of character)
- 2FA - verification code sent over mobile phone/other device
### Stop using portable storage device
### Firewall
- denies access to data that does not conform to set rules
- maintains a blacklist/whitelist of IP addresses
### Proxy
- denies access to data that does not conform to set rules
- prevents some requests ever reaching the server
### Digital Signature
- The sender hashes digital signature to produce a digest
- The sender encrypts the digest with the sender's private key to create a digital signature
- the message and the signature is sent to the receiver
- the receiver decrypts the signature with the sender's public key to reproduce a digest
- the receiver uses the same hashing algorithm on the document receive to produce a second digest
- the receiver compares this digest with the one from the digital signature if both digests are the same the document is authentic
### Anti-malware
- Scans for malicious software  
- Quarantines or deletes any malicious software found
- Scans can be scheduled at regular intervals
- Should be kept up to date
### Encryption - Contents are scrambled -> doesn't make sense without a decryption key
### Auditting
- Loggin all action/change to system
- iden any unauthorise use
### Backup - copy of data and stored in another location
- Regular copies of the data are made
- disk-mirroring - duplicate data into another disk in real time, if one fails then the other is the backup
## Preventing Integrity problem 
### Validation check - reasonable
#### data input
- type - numeric, date, string
- Range - value lies in range
- format - pattern need in the data e.g. date format
- length - how many char/digit
- presence - not blank
- limit - maxinum values
#### files
- existence - files exist
#### during transfer
- check digit - check no error occur during transmission
### Verification check - same as intended/original
#### Data input
- Visual Check
- double entry
#### during transfer
- parity check
- checksum