![](https://www.youtube.com/watch?v=EZf9ut9Y8xQ)
## Benefits of Networking
- Resource sharing (software, hardware, data)
- Reduce Cost
- Remotely perform task
- Communication between users
- LAN is faster
## LAN VS WAN 
- WAN has a larger geographical area coverage than LAN 
- LAN is usually more secure than a WAN because protection is easier to implement in a smaller network
- WAN's ownership can be pubilc or private; LAN's is private
- LAN has a high data transfer rate
- (NOT SURE) LAN's connections are usually physical while; WAN are often virtual
## NETWORK MODEL
### 1. Client-Server
- architecture: client runs an application that is serve by server on a network
- Usually use when
	- server store a database accessed by the client
		- web application allow the client system to find or, sometimes, supply information.
		- web application allows the client system to carry out an e-commerce or financial transaction.
- Benefit
	- allow control download and use of file
	- file store on one server that is regularly scan by anti malware software, => more secure (P2P is as secure as the least secure device)
- #### 1. Thin Client
	- server performs all processes required by the start (including storing data)
	- client only sends requests to the server and displays the returned result

- #### 1. Thick Client
	- Task can be done by the client![[Pasted image 20231216154130.png]]
### 2. P2P
![[Pasted image 20231216151148.png | 300]]
- All computer serves as Client and Server simultaneously, where each peer store some files to be request
- Benefit
	- Avoid congestion where many client attempt to download files
	- parts of file can be download separately
	- parts are avaiable from multiple hosts
## TOPOLOGY
- 5 requirements for a data communication system
	1. Sender
	2. Receiver
	3. Mediumd
	4. Data
	5. Protocol
### Transmission Mode ![[Transmission Mode.png]]
### Transmission Method ![[Transmission Method.png]]
### Topologies![[Network Topology.png]]
1. Point-to-Point
	- Connection between 2 devices
	- Simplex
	- unicast
2. Bus
	- Connection many devices(workstation) with one **main** communication cable
	- Broadcast
	- Benefit: A failure of one node do not impact network usability of another device
3. Mesh
	- Each devices are connected together, (atleast one other device)
	- The devices can transfer with unicast, multicast or broadcast transmission method.
	- Each devices can act as a relay, passing packet toward the final destination
	- transmission mode: duplex 
	- Anycast (any of the three transmission method)
	- use for LAN/Routers in a network
4. Star
	- Devices are connected to a central hub/switch for communication
	- Duplex
	- Anycast
		- Benefit: Failure of one node do not impact network usability, Data is more secure(when not broadcast), Switch store buffer of incoming message and send when the cable is free => no CSMA/CD needed
5. Hybrid
	- Combination of many topologies
	- Benefit: help acheive specific performance, scalability or reduncy goals
	- Allow flexibility with topology use in a LAN that align with their purpose
## HARDWARE
### cable![[Pasted image 20231216164314.png]]![[Pasted image 20231216164117.png]]
### Wireless ![[Pasted image 20231228210354.png]]
### Sattelite
- GEO: orbit around eath at the same rate, 3 sattelite for full Earth coverage, use for distant telephone and "internet" connection
- MEO: provide GPS, around 10 for full Earth coverage.
- LEO: use for aiding mobile phone networks, around 50 for full Earth coverage
- Disadvantage: Large distance can cause delay and attenuation
### benefit of wired
- wire doesn't suffer the latency of wireless connection(less interference) which increase performance, therefore a faster connection to internet or database server
- more secure as there is less chance of interference, therefore student can open and store confidential data
### benefit of Wireless 
- students can be mobile and move around. This is good for ergonomic and health
- students can connected multiple devices and not limited by the port available on the device ![[Pasted image 20231216164535.png]]
## LAN Hardware
- Terminator - ensure data continuity, prevent signal from reflecting back down the bus
- Repeater - links 2 cable, takes input signal, generate new signal at full strength
- Connects 2 LAN
	- Bridge - With same protocol
- NIC - allow device to connect and communicate within the network, using its MAC address as a unique id as an end-system
- Switch/hub - Routing data in and out of network to the correct ip address. Hub will broadcast the data 
- WLAN/Wi-Fi - uses radio
- WAP - central device, establish communication with end-system which has WNIC - same as NIC, it has antenna and communicate with radio waves
###  Router
- Function
	
## Ethernet - protocol, ports, cables and computer chips
- CSMA/CD
	1. workstaton check the voltage on the main cable[]
	2. if it indicate no activity, start transmission and continuously check for collision
	3. if collision occurs, both stop transmission, transmit a jamming signal to warn all end-stations; after a random time, try again
	4. each time collision occurs the radom wait time increases
## Internet
- Structure of Internet![[Pasted image 20231217110958.png]]
- PSTN - public switch telephone network, using modem to dial-up
- Modem - modulate(DAC) and demodulate(ADC) data. 
- Dedicated Lines - setup in WAN by PSTN company (link branches of the organisation)
- Cell Phone Network - cell tower connects mobile device wirelessly to the internet
## APPLICATION OF INTERNET
- WWW
	- Distributed aplication available on the internet
	- Collection of webpages made of HTML
- Cloud Computing
	- Public - owned by 3rd Party cloud service provider
	- private - owned by the organisation/outsource to a 3rd party to create and manage
- [Bit Streaming ](https://learnlearn.uk/alevelcs/bit-streaming/)
	- On demand - bits are sent from the server to the buffer created on the user's computer; the machine has media player software htat takes media data form buffers and play it 
	- Real-time - live streaming, content is being generated as the bit is being delivered
	- Bit-rate - number of bit transmitted per unit time
	- Schematic diagram of bit streaming![[Pasted image 20231216200439.png]]
## IP ADDRESSING
- IPV4 - 4 octet, sep by . 
- !PV6 - 8 hextet, sep by :, zero compression
- CIDR - No class, use suffix to show number of bit use for netid
- Sub-netting - separate not the net id, use a portion of hostid to show different class
- NAT - convert each device private ip to public ip 
- ![[Pasted image 20231228222425.png]]
- Static - ip doesn't change every session
- Dynamic - ip changes every session
## DOMAIN NAMES
- DNS

### Mesh vs Bus
- Bus has a single point of failure
- collision are more likely on Bus
- Bus is less secure as data are broadcast through single main cable
- mesh allow unicast (dedicated connection) which is more secure
- nodes can be add without interruption with other node
