---
creation date: August 3rd 2023
last modified date: August 3rd 2023
aliases: []
tags: #📖
---

Primary Categories: [[01 - Malware Analysis]] 
Secondary Categories: [[]] 
Links: [[]] 
Search Tag: #📖  

# [[03 - Shell Code Analysis]]  


![[Pasted image 20230803210523.png]]

Using python we can pull this shell code into something usable
```python
#1/user/bin/env python3

with open("shellcode.txt", "r") as f:
	hex_string = f.read().replace("0x","").replace("byte[] rsrc = new byte[464] {","").replace("};","").replace(",","")

	hex_encode = hex_string.encode()

#print(hex_string)

#print(hex_encode)

with open ("out.bin", "wb") as out:
	out.write(hex_encode)
```



___

## Resources:

| Hyperlink | Info |
| --------- | ---- |


Created Date: August 3rd 2023 (09:24 pm) 
Last Modified Date: August 3rd 2023 (09:24 pm)
