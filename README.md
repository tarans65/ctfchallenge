Challenge 1: Crypto 
Name: Echoes of Guilt (Medium)

Description: Attached unknown.wav file

Hint (Will Cost Some # of Points) - "Reversed"

How To Solve:
   - Open .wav file in a hex editor
   - Reverse each individual byte in the first three rows
   - Save the file and open it in a Sonic Visualiser
   - View a spectrum of the wave to reveal the flag

Flag: dfend{happy_mack}
_______________________________________________________________________________________________________________________________
Challenge 2: OSINT
Name: Firm vs. Firm (Medium)

Description: In recent years, the Law Offices of Mack, Cole & Slaw have had some serious competitors.
There is one firm in particular that has been our biggest competitor, and this competition between the firms has been going on for years. 
We need to find out what the name of this law firm is, but more importantly, the name of one of their clients, who claims that "they can not say enough good things". 
The only clue we have is this image of a nearby gym and lake. Help out the Law Offices of Mack, Cole & Slaw and end this competition once and for all! The flag format is dfend{firstname_lastnameinitial} - all lowercase - example: dfend{bob_g} Attached: clue.png

Hint (Will Cost A Lot of Points) - Our competitor has represented Michael Phelps

How to Solve:
   - Reverse image search
   - Find the law firm and check its website
   - Go to testimonials and scroll down
     
Flag: dfend{ashley_t}
_______________________________________________________________________________________________________________________________

Challenge 3: Forensics
Name: Paper Trail (Easy)

Description:
There is a rumor that an employee of the Law Offices of Mack, Cole, and Slaw is smuggling sensitive data in plain sight. The Law Offices of Mack, Cole & Slaw intercepted this file and believe it contains a key piece of evidence, but they need your help to extract it. Don’t trust what you see on the surface. The real truth might be zipped in deeper. Attached: receipt.pdf

Hint (Will Cost A Lot of Points): The real truth might be zipped in deeper.

How to Solve:
   - Open receipt_polyglot.pdf normally (you’ll see a regular receipt)
   - Rename the file extension from .pdf to .zip
   - Open the .zip file using WINRAR
   - Extract DO_NOT_OPEN.exe --> Alt V
   - The flag will be revealed

Flag: dfend{judg3_0v3rru13d}
