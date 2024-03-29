---
creation date: July 22nd 2023
last modified date: July 22nd 2023
aliases: []
tags: #📖
---

Primary Categories: [[000 - Global Index]]
Secondary Categories: [[01 - Malware Analysis]]
Links: [[]] 
Search Tag: #📖  

# [[03 - Basic Static Analysis]]  

---
## Hashing Malware Samples

Using Cmder on FlareVM we can get the Hash values for the "suspected" malware or known sample.

![[Pasted image 20230722125546.png]]
![[Pasted image 20230722125642.png]]

```text
SHA256SUM - 92730427321a1c4ccfc0d0580834daef98121efa9bb8963da332bfd6cf1fda8a *Malware.Unknown.exe

MD5SUM - 1d8562c0adcaee734d63f7baaca02f7c *Malware.Unknown.exe
```

---
## Malware Repositories: VirusTotal

Submitting to Virus total the SHA256

![[Pasted image 20230722130058.png]]

---
##  Strings & FLOSS: Static String Analysis

Floss is a FlareVM tool made by FireEye that will pull out any strings over 4 characters.
	This can sometimes show us interesting and telling information

![[Pasted image 20230722131628.png]]
![[Pasted image 20230722204926.png]]

Tip: FLOSS can be run with the "-n" argument to specify your desired minimum string length. Sometimes, longer strings can be more useful to an analyst than your standard string of len(4).

For example, if I want to pull all strings of length 6 or greater, I can issue the following command:

floss.exe -n 6 `malware_name.exe`

---
## Analyzing the Import Address Table

PEview provides a quick and easy way to view the structure and content of 32-bit Portable Executable (PE) and Component Object File Format (COFF) files. This PE/COFF file viewer displays header, section, directory, import table, export table, and resource information within EXE, DLL, OBJ, LIB, DBG, and other file types.

### After Opening a Sample

#### Image NT Headers
	Image File Header - this can give us a `time date stamp` for when the sample was compiled, though this is not always reliable.

![[Pasted image 20230722210331.png]]

#### Image Section Header
	We can compare the `Virtual Size` and the `Size of Raw Data` fields to identity if the size is the same or perhaps the Virtual Size is larger and we are dealing with a packed binary.

![[Pasted image 20230722210741.png]]

#### IMPORT Address Table
	This section is important for getting clues on the type of Windows API calls being made. 

![[Pasted image 20230722211034.png]]

## malapi.io 
	A Mitre Attack Framework type website that has various Windows API calls and if they are particularly interesting as far as malware is concerned.

---
## Packed Malware Analysis

Packing is a common technique used by malware authors to hide their malicious code from antivirus software and to make the job of malware analysts harder. Here are the main points to understand:
- **What is it?**: Packed malware is a malicious program that has been compressed or obfuscated with a "packer".
- **Why is it used?**: Packing makes the malware's binary code harder to read and understand, which can make it more difficult for antivirus software to detect. It's like wrapping the malware in a layer of protective bubble wrap.
- **How it works?**: When the packed malware is executed, a stub, which is a piece of code, decompresses the original code into memory, where it can then be executed.
- **Detection**: Packed malware can often be detected because the packer leaves signs that analysts can look for, such as an unusually small size of the code section in relation to the program’s functionality, or entropy analysis can show high randomness in the packed section of the code. Can be identified by the `Size of Raw Data` not matching or reading zero vs `Virtual Size`.
- **Unpacking**: To analyze packed malware, analysts usually have to "unpack" it first to expose the original code. This can be a complex process that involves using a debugger to find the point in the code where the unpacking process is finished, and the original code is exposed.

![[Pasted image 20230723135601.png]]
 

### Preferred Tools

PEStudio

	Does a lot of the manual work and multiple tools used outlined above into one nice program. 

![[Pasted image 20230723140048.png]]









___

## Resources:

| Hyperlink | Info |
| --------- | ---- |


Created Date: July 22nd 2023 (12:35 pm) 
Last Modified Date: July 22nd 2023 (12:35 pm)
