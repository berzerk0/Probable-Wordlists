# What am I looking at?

### "Sorted-Into-Chunks"
  * This folder contains all the passwords, sorted by probability, broken into files about 24MB in size
### "WPA-Length" 
  * This folder contains passwords at least 8 characters long, but less than 40 characters. This is the format used by routers protected by WPA/2 security
### Files not in any folders
  * THESE ARE THE PASSWORDS!  
  * Their length is in their title
  * I generated files by the number of times each line appeared in my analysis. Files are available for 75, 50, 25, 10, and 5 appearances.
  * Top 220 - appeared at least 75 times - these are the MOST common passwords
  * Top 5446 - appeared at least 50 times
  * Top 125 Thousand - appeared at least 25 times
  * Top 35 Million - appeared at least 10 times
  * Top 297 Million - appeared at least 5 times
  
  To get the list of approximately 2 Billion, you will need to look in the "Sorted-Into-Chunks" folder.
  
  Using the full 2-billion-line wordlist loose is possible, but pretty cumbersome and inefficient.
  
  *If you clone the repo, files Sorted-Into-Chunks folder can be joined back together with a command like `cat`*

These are **REAL** passwords. Every once in a while, a popular site has a high-profile security leak and passwords are released freely across the internet.
Some of these passwords can be found on aggregator sites where they are separated from usernames to protect the unfortunate victim.

The files in this folder come from https://github.com/danielmiessler/SecLists, https://weakpass.com/ and https://hashes.org/
I've taken nearly all of the real passwords from these sites, combined them into a single list, removed duplicates and sorted by popularity. I couldn't find many lists that weren't sorted alphabetically - it seems like a dictionary attack should reflect actual human behavior as opposed to the alphabet.

### NOTE THAT FOR THIS FIRST VERSION, ALL NON-ASCII CHARACTERS HAVE BEEN REMOVED.
A more inclusive, and thus, more accurate list is in the works.

Lists sorted by popularity will include "probable" in the filename

I did not steal, phish, deceive or hack in any way to get hold of these passwords. 
All lines in these files were obtained through freely available means. 

![Probable Wordlists Logo](Probable_Wordlist_Logo.png)
