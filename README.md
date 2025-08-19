# CTF-Writeup
CTFlearn writeups of all the challenges I have solved. It covers all the domains including Forensics,Pwning and other misc problems.
# Challenge 1 – RICK

**Category:** Forensics / Steganography

**Description:**
A few days ago, my friend Rick sent me an image file, but when I tried to open it, I was unable to view it clearly. I think the file is corrupted. Could you help me fix it? The corrupted image might hide a secret.

**🔎 Approach**
The given image looked corrupted with lines and distortions.
Uploaded it to FotoForensics (an online tool for analyzing images).
Observed that the distortion revealed hidden text.
Carefully checking the image, I noticed embedded characters spelling out the flag.


**✅ Solution**
Hidden inside the corrupted image was the flag:
  flag{n3v3r_g0nn4_g1v3_y0u_up}


# Challenge 2 - WINDING ROADS

**Category:** Reverse Engineering / Misc

**Description:**
A labyrinth of winding roads, each one leading deeper into uncertainty, yet only one shines with the promise of light. Reverse the file provided and find the secret.

**🔎 Approach**
The hint about "winding roads" suggested multiple layers or a recursive structure.
Extracted the contents of the ZIP file and inspected the source code inside.
The source code appeared to perform multiple checks, making it hard to trace manually.
Inserted print statements into the code to understand its flow and brute-forced possible paths.
Eventually, one correct execution path revealed the hidden flag.


**✅ Solution**
Final flag discovered:
    flag{GGCIKNAKOEDKSTCK}
