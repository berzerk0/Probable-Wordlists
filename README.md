# Probable Wordlists - Version 2.0

 __Do you know what the world's most common passwords are?<br>
Do you know what they look like?<br>
You'll want to avoid them to be secure!__<br>

### Thinking of Cloning?
This repository does not contain code, but links to a group of lists. <br>
__*A clone may not be necessary to get the files you need*.__ <br>
Visit the __[downloads](Downloads.md)__ page for more information.


![Logo](https://raw.githubusercontent.com/berzerk0/Probable-Wordlists/master/ProbableWordlistLogo.png)


#### Check out the [Password Trend Analysis](https://github.com/berzerk0/GitPage/wiki/Actionable-Password-Advice-Based-on-the-Probable-Wordlists) - and learn!


I visualized the trends of passwords that appeared 10 times or more in the __Version 1__ files.
The charts contain *immediately actionable* advice on how to make your passwords more unique.

## Methodology: Why and How

### The Why

Password wordlists are not hard to find. It seems like every few weeks we hear about a massive, record-breaking data breach that has scattered millions of credentials across the internet for everyone to see. If our data is leaked, we'll change our passwords, the hard-working security teams will address the vulnerabilities and everyone will wait until they hear about the next breach.

While leaks may be published with malicious intent, I see an opportunity here for the us to make ourselves a bit more secure online.

Passwords, by definition, are meant to be secret. If it weren't for these leaks, we might not have any idea what a password looks like. Sure, we might know the password to a friend's home Wifi network, or for a company expense account, but passwords are usually only intended to be known by the user and an authentication system.

But, consider this:<br>
If you are never supposed to tell me yours, and I am never going to tell you mine... <br>
 __How do we know that we aren't using the same passwords?__<br>

 __How do we know we aren't using the same passwords as *millions* of other people?__

If crooks are the only ones who understand what common passwords look like, then the rest of us may never change our passwords! Without this knowledge, we may just continue believing that our password is one of a kind.  Data shows that frequently, passwords certainly are *not* one of a kind.


This is confirmed year after year when `password` is found to be among the top 3 password for the umpteenth time in a row. Until we know what common passwords look like, we will come up with passwords that appear on dozens of leaks.


If any of your passwords has been published on the internet for everyone to see, then can you really claim it as __*your*__ password?

## The How

While studying password wordlists, I noticed most were either sorted alphabetically or not sorted at all. This might be okay computerized analysis, but I wanted to learn something about the way people think.

I determined that for the most practical analysis, lists had to be sorted in a manner that reflected __actual human behavior__, not an arbitrary alphabet system or random chronology.

For the better part of a year, I went to sites like SecLists, Weakpass, and Hashes.org to download nearly every single Wordlist containing real passwords I could find. After attempting to remove non-pertinent information, this harvest yielded 1600 files spanning more than 350GB worth of leaked passwords.

For each file, I removed internal duplicates and ensured that they all used the same style of newline character. Some of these lists were composed of smaller lists, and some lists were exact copies, but I took care that the source material was as "pure" as possible. Then, all files were combined into a single amalgamation that represented all of the source files.

Each time a password was found in this file represented a time it was found in the source materials. __I considered the number of times a password was found across all of the files to be an approximation of its overall popularity.__ If an entry was found in less than 5 files, it isn't commonly used. But, if an entry could be found more than 350 files, it is incredibly popular. The passwords that were found in the highest number of source files are considered to be the most popular and are placed at top of the list. Files that didn't appear frequently were placed at the bottom.

The giant source file represented nearly *13 billion passwords!* However, since this project aims to find the most popular passwords, and not just list as many passwords as I could find, __a password needed to be found at least 5 times in analysis to be included on these lists.__

The end result is a list of approximately __*2 Billion*__ real passwords, sorted in order of their popularity, not by the alphabet.

***

## Directories In This Repository <br>

__Files sorted by popularity will include `probable-v2` in the filename__

### [Real-Passwords](Real-Passwords)
These are __REAL__ passwords.

The files in this folder come from sites like https://github.com/danielmiessler/SecLists, https://weakpass.com/ and https://hashes.org/

Some files contain entries between 8-40 characters. These can be found in the [Real-Passwords/WPA-Length](Real-Passwords/WPA-Length) directory.


### [Dictionary-Style Lists](Dictionary-Style)

Files including dictionaries, encyclopedic lists and miscellaneous. Wordlists in this folder were not necessarily associated with the *"password"* label.

Some technically useful lists, such as common usernames, tlds, directories, etc. are included.


### [Analysis Files](Analysis-Files)

Files useful for password recovery and analysis. Includes HashCat Rules and Character Masks.

These files were generated using the [PACK](https://github.com/iphelix/pack) project.


## Attributions
 * [Ian Norden](https://github.com/iancnorden) for helping with duplicates and volunteering his time to make me a little less noobish
 * The folks over at [OWASP's SecLists](https://www.owasp.org/index.php/Projects/OWASP_SecLists_Project) for providing sources and inspiration
 * Sources like [Weakpass](https://weakpass.com/), [Crackstation](https://crackstation.net/), [Hashkiller](https://hashkiller.co.uk/) and [Hashes.Org](https://hashes.org/) for inspiration and lists.


### People Are Talking About Probable-Wordlists?!
*Note that the author is not affiliated with or officially endorsing the visiting of any of the links below.*

I found most (if not all) of these mentions by simply searching for the project in various engines

* [Netmux/Joshua Picolet's __Hashcrack 2.0__](https://www.amazon.com/Hash-Crack-Password-Cracking-Manual/dp/1975924584/ref=sr_1_fkmr0_1?ie=UTF8&qid=1517462487&sr=8-1-fkmr0&keywords=hashcrack+2.0) - CreateSpace Independent Publishing Platform; 2 edition (September 1, 2017) - ISBN: 978-1975924584
*  Probable-Wordlists has made the [__Security Now Podcast__!](https://youtu.be/DC3RsyrCYfw?t=1h8m7s) Shout out to Steve Gibson and Leo Laporte!
* [The Legendary AIRCRACK!](https://www.aircrack-ng.org/doku.php?id=faq)
* [Pinned Tweet on the also legendary L0phtcrack!](https://twitter.com/L0phtCrackLLC/status/874266579516747777)
* [Centrify's Ben Rice](https://blog.centrify.com/do-you-know-how-easy-is-it-to-guess-your-password-hint-you-dont-want-to-read-this/)


Thanks for the shout-outs!


***

## Disclaimer and License
 + These lists are for LAWFUL, ETHICAL AND EDUCATIONAL PURPOSES ONLY.
 + The files contained in this repository are released "as is" without warranty, support, or guarantee of effectiveness.
 + *However, I am open to hearing about any issues found within these files and will be actively maintaining this repository for the foreseeable future. If you find anything noteworthy, let me know and I'll see what I can do about it.*

The author did not steal, phish, deceive or hack in any way to get hold of these passwords.
All lines in these files were obtained through freely available means.

The author's intent for this project is to provide information on insecure passwords in order to increase overall password security. The lists will show you what passwords are the most common, what patterns are the most common, and what you should avoid when creating your own passwords.


 [![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

 __This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License.](https://creativecommons.org/licenses/by-sa/4.0/)__

<br>

## Enjoy!
