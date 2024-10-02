# Malware analysis 

Only for  acadedemic reasons!

### Techniques:

**1.Basic static analysis**

-Examining the executable file without viewing the actual instructions

-Can confirm if the file is malicious

-Provide information about its functionality, sometimes provide info that will allow you
to produce simple network signatures

-Sometimes ineffective against sophisticated malware


**2.Basic Dynamic analysis**

-Running and observing its behavior on the system in order to remove the infections, produce effective signatures, or both.


**3.Advanced static analysis**

-reverse-engineering the malware's internal by loading the executable into a disassembler and looking at
the program instructions in order to discover what the program does.

-ASA has a steeper learning curve than the basic static analysis and requires specialized knowledge of disassembly, code constructss, and Windows OS concepts.

**4.Advanced Dynamic Analysis**

-Uses a debugger to examine the internal state of a running malicious executable.




### Types of malware:
1.Backdoor

2.Botnet

3.Downloader 

4.Information-stealing malware (sniffers, password hash grabbers, keyloggers)

5.Launcher

6.Rootkit (backdoor with no detection)

7.Scareware

8.Spam-sending malware

9.Worm or viruses


# Basic static techniques

-Antivirus scanning

	-file signatures

	-heuristics


-Hashing

	-MD5

	-SHA-1

-Finding Strings

-Packed and Obfuscated Malware
