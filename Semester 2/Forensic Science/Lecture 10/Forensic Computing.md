- Tons of information through digital devices
- The diversity of device formats is immense

Metadata on a floppy disk
- Edited by dennis
- Christ Lutherine Church

# Key Point 1
- Digital evidence is any stored or transmitted data in binary format that may be useful in a criminal or civil investigation
# Digital Data
- Stored in bits
- Many different forms
	- Hard Drives
	- SSDs
	- Cell phones
	- Mobile storage media (cloud)
	- Networks, etc.
- Can be involved with any sort of crime
	- Suspects email/cell **phone**
	- Locations at the time of a crime
	- Relationships to victim/suspect

Some crimes are solely digital
- Child exploitation
- fraud
- extortion
- prostitution
- gambling
- Counterfeiting
---
# Meta-Data
- Data about data
	- a photo taken on a device saves time, location, format, etc.

# Key Point 2
Being able to identify digital devices - and the components within - is helpful

# Device Basics
- Hardware
	- Anything physical in a computer
- Software
	- Set of instructions compiled into a program that performs a particular task

## Key Termonology
- Case - Holds all the components in a box
- Power Supply - Turns the outlet power to a more usable format
- Motherboard - Main circuit board
- System Bus - Contained on the motherboard, the systemm bus is a ==vast complex network of wires==
- ROM - Read only Memory
- CMOS - Complementary metal-oxide semiconductor - allows you to exercise set-up control over several components
- Together, ROM and CMOS create the BIOS

- RAM - Memory that always changes, info lost when powered down
- CPU - the brain
- Input devices - mouse, keyboard, joystick
- Output devices - monitor, printer, etc.

- HDD - The storage, permanent storage, even when unpowered
	- They're mapped (formatted) to find information

# Key Point 3
Understanding how data is stored in a computer is critical - it helps you know how best to retrieve it.

# HDDs
Each OS has a different way of formatting drives
- Windows
	- Fat16
	- Fat32
	- NTFS
- Mac
	- HPFS
- Linux
	- Ext2
	- Ext3

## Logically defined
- Sectors
	- 512 bytes
- Clusters
	- Groups of sectors
	- Either 2, 4, 6, 8, 10, 12, etc.
- Tracks
	- Concentric circles that are defined around the platter
- Cylinders
	- Groups of tracks that reside directly above and below each other

## How Data is stored
- Generally, HDDs need to have ==their space defined==
- Partition: ==a contiguous set of blocks that are defined and treated as an independant disk==
- When partitioned, HDDs are mapped (formatted) and have a defined layout
- After the partitioning and formatting processes are complete, the HDD will have a map of the layout of the defined space in that partition
	- Maps are:
		- File Allocation Tables "FAT"
		- Master File Tables "MFT"

- It is sufficient for purposes here, however, to merely visualize the partition table as ==a map to where the data is located==
- This map uses numbering sectors, clusters, tracks, and cylinders ==to keep track of the data==

# Key Point 4
The types of data you can find can vary! This will affect where you need to look for the data, and if you'll need any special equipment to extract it

# Visible Data
**All data that the operating system is presently aware of and thus is readily accessible to the user**

Common types of visible data:
1. Data/Work Product Files
	1. From an evidentiary standpoint, it can encompass any type of user created data, such as:
		1. Word processing documents
		2. Spread sheets
		3. Accounting records
		4. Databases
		5. Pictures
2. Swap File Data
	1. A  file or defined space on the HDD used to conserve RAM
		1. Data is swapped or paged to this file or space to free RAM for applications
3. Temporary Files
	1. Temporary files, created by programs as a sort of "back-up on the fly" can also prove valuable as evidence.

# Latent Data
Areas of HDD that aren't apparent to you
- The OS says "don't look here"
- We use programs to view the binary level of this data

# Slack Space
Empty space on a hard disk drive created because of the way the HDD stores files
![[Pasted image 20260417093707.png]]

# Unallocated Space
Evidentiary latent data can also be found in unallocated space
- Unallocated space is that space on a HDD the operating system sees as empty and ready for data

# Key Point 5
Processing the electronic crime scene has a lot in common with processing a traditional crime scene

# Crime Scene Analysis
Like a traditional CS, an electronic crime scene involves:
- Warrants
- Documentation
- Quality Investigation Techniques

After documentation there are three options for investigators:
- Perform a live acquisition of the data
- Perform a system shut down
- Pull the plug from the back of the computer

## Shutdown vs. Pulling the Plug
Several factors influence this decision:
- Do I think encryption is being used?
	- If yes, data may become unreadable
- Do I think some crucial evidence exists in the RAM that has not been saved to the HDD?
	- Might be lost if we discontinue power
- Regardless, the equipment will most likely be seized

# Live Acquisition
- The investigator needs to work with the computer system which means there ==will be changes made to data
- Investigator must consider an “order of volatility”
- Allows the investigator to develop a ==sequence of steps== that will limit the effects of each change on the subsequent steps and collection methods
- Allows you to collect the ==greatest amount== of unaltered evidentiary data

## Live Acquisition Steps
- Photograph all sections of the conversation screen to document
- Acquire all sections of the RAM
	- Depends on investigators' skill level
- Copy and paste conversation
- If encrypted, may image entire drive
- Important questions to consider:
	- What type of case is it
	- What is the evidence I seek?
	- How can I acquire it without contaminating other evidence
	- What order should I take those steps (order of volatility)
	- Do I have the training, education, experience, equipment, and tools to accomplish this? Or do I need assistance

# Forensic Image Acquisition
- Now that items have been seized
	- Use least invasive method first to get data
	- Goal is to obtain data without changing even one "bit" of data
- HDD is typically plugged into special forensic computer
- Occasionally, in cases of specialized or unique equipment or systems, the image of the HDD must be obtained utilizing the seized computer
- Examiner needs to prove that not bit of information obtained was changed (writes)

# Computer Fingerprint
- A "fingerprint" of the drive is taken before and after imaging
- Done through an Message Digest 5 (MD5), Secure Hash Algorithm (SHA), or similar system
- Algorithm is run and 32 character alphanumeric string is produced
- Then run after imaging and if the same string is returned, it proves nothing has changed on the drive

# Analysis of Internet Data
- Internet provider rolls over for the law
- Internet cache
- Cookies
- Internet History

## Internet Protocol (IP)
Address to your system, as provided by your internet provider
- Can lead to identity of real person
- ###.###.###.### integer, between 0 and 255

# Hacking
A slang term frequently used to refer to performing an unauthorized computer or network intrusion
**Investigators focus on:**
- Log files
- Volatile Memory (RAM)
- Network traffic
- Firewall is a system designed to prevent hacking or intrusions

# Mobile Phones
1. Cell pings to a tower
2. Tower connects to tower (Through your cell provider)
3. Recipient phone receives through towers

Phones provide huge evidentiary data in an investigation
- Placing it in communication barrier to block signals prevents data change
- Extracting data from a phone is hard bc different phones store data in different ways
- Less standardization in phones
- Some phones have remote kill features
- Battery must stay charged to be transported