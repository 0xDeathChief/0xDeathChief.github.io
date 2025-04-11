---
title: Reverse Engineering
date: 2025-04-11 06:06:00 +0800
categories: Red Teaming
tags: Red_Team
---

# Concept:

* how computer work
* numeric systems (binary, hex, decimal)
	* how to convert between them

* processes, handles, threads
* memory, "the stack", etc
* high level understanding of machine code

---
#### Problem solving:

- programming teaches you how to problem solve
- learn how to google things and utilize documentation, chat-gpt, etc.
- figure out errors on your own, and if you can't. reach out to others for help

---
# STAGE 01:

1. Language Types:
	1. Complied Language:
		1. rely on a **Compiler** to turn the human readable syntax into an executable file

2. Interpreted Language:
	2. rely on a **interpreter** to turn the human readable syntax into machine code (executed in memory)

#### 3 Types of Learn:

1. Low Level Compiled Language
	1. C
	2. C++
	3. C#
	   
2. High Level Compiled Language
	4. Nim
	5. Go
	6. Rust
	   
3. Native Interpreted Language
	1. PowerShell
	2. Batch
	3. VisualBasicScript
	4. Bash (Linux)


### Why No Python ?

- Although Python is a interpreted Language, it is not native. So it is not ideal for the development of malware
  
- However, it can be useful for malware processes that do not directly run on the target (C2, Network handling, etc.)



### Personal Recommendations:

1. C++
2. PowerShell
3. Nim
4. Basic Assembly
5. Python

### Building Out An Arsenal:

- A good malware developer should never limit themselves to a few language. Once you build a strong foundation, move on to learning more complex concepts.

---
# STAGE 02

#### Cybersecurity Fundamentals

- Basic Hacking:
	1. Reconnaissance { not necessary }
	2. Scanning & Enumeration { Scanning necessary but Enumeration Not }
	3. Exploitation
	4. Persistence
	5. Covering Tracks


- Familiarization with tools:
	1. Metasploit
	2. Wireshark
	3. NMAP & NCAT
	4. Hashcat / John
	5. Popular malware

#### Basic Cryptography:

- Basic encryption / decryption
- different ciphers and algorithms
	- AES, XOR, Base64
- obfuscation


---
# STAGE 03
#### Networking Fundamentals

- Networking Concepts:
	1. Different Protocols
		1. TCP, SSH, HTTP, etc.
	2. 3 Way Handshake
	3. Utilize protocols for remote connectivity and exfiltration

---
# STAGE 04
#### Malware development

- Topics:
	1. Windows API
	2. Shellcode Embedding
	3. Process & DLL Injection
	4. AV Evasion
	5. Trojan Development

---
# Reverse Engineering:

- Light reverse engineering and malware analysis can go a long way. It will teach you how the malware actually works and runs through the system. It will also teach you about the latest trends and techniques in development

---
