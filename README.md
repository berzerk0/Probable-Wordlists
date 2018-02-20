# Probable Wordlists - Version 2.0

 __Do you know what the world's most common passwords are?<br>
Do you know what they look like?<br>
You'll want to avoid them to be secure!__

### Cloners and Zip Downloaders:
This repository does not contain code, but links to a group of lists. <br>
__*A clone may not be necessary to get the files you need*.__

![Probable Wordlists Logo](https://raw.githubusercontent.com/berzerk0/Probable-Wordlists/master/ProbableWordlistLogo.png)

#### Check out the [Password Trend Analysis](https://github.com/berzerk0/GitPage/wiki/Actionable-Password-Advice-Based-on-the-Probable-Wordlists) - and learn!

I visualized the trends of passwords that appeared 10 times or more in the __Version 1__ files.
The charts contain *immediately actionable* advice on how to make your passwords more unique.

## Methodology: Why and How

### The Why

Password wordlists are not hard to find. It seems like every few days we hear about some massive, record-breaking data breach that has scattered millions of login credentials all over the internet for everyone to see. If our data is leaked, we'll change our passwords, the hard-working security teams will address the vulnerabilities and everyone will wait until they hear about the next breach.

While leaks may be published with malicious intent, I see an opportunity here for the average person to make themselves a bit more secure online.

Passwords, by definition, are meant to be secret. If it weren't for these leaks, we might not have any idea what a password looks like. Sure, we might know the password of our friend's home Wifi network, or perhaps of a shared bank account, but passwords are most often intended to be only known by the user and an authentication system.

But, consider this: __*If you are never supposed to tell me your password, and I am never going to tell you mine, how do we know that we aren't using the same one?*__ In fact, __*how do we know we aren't using the same password as millions of other people?*__

If crooks are the only ones that understand what common passwords are, then the rest of us may never change our passwords because we have have no reason to believe they aren't one of a kind.

This is confirmed year after year when `password` is found to be among the top 3 password for the umpteenth time in a row. Unless the average person knows what an overly common password looks like, they will come up with passwords that have appeared in one of these breaches.

If any of your passwords has been published on the internet for everyone to see, then can you really claim it as *your* password?

## The How

While studying password wordlists, it quickly became clear to me that most were either sorted alphabetically, or not sorted at all. To bring rhyme and reason to these lists, they had to be sorted in a manner that __*reflected actual human behavior*__, not an arbitrary alphabet system.

For the better part of a year, I went to sites like SecLists, Weakpass, and Hashes.org to downloaded nearly every single Wordlist containing real passwords I could find. After attempting to remove non-pertinent information, I ended up with nearly 1600 files spanning more than 350GB worth of leaked passwords. Some of these lists were composed of smaller lists, and some lists were exact copies, but I took care that the source material was as "pure" as possible.

For each file, I removed internal duplicates and ensured that they all used the same style of newline character. Then, all files were combined into a single amalgamation that represented all of the source files.

Each time a password was found in this file represented a time it was found in the source materials. __*If a password was found in mulitple files, I considered this to be an approximation of its popularity.*__ If an entry was found in less than 5 files, it isn't commonly used. But, if an entry could be found more than  300 files, it is incredibly popular. The passwords that were found in the highest number of source files are considered to be the most popular and are placed at top of the list. Conversely, files that didn't appear frequently were placed at the bottom.

The giant source file represented nearly *13 billion passwords!* However, since this project aims to find the most popular passwords, and not just list as many passwords as I could find, __*a password needed to be found at least 5 times in analysis to be included on these lists.*__

The end result is a list of approximately __*2 Billion*__ real passwords, sorted in order of their popularity. The sorting of the lists reflects actual human

***

## Real-Passwords
These are __REAL__ passwords.
Every once in a while, a popular site has a high-profile security leak and passwords are released freely across the internet.
Some of these passwords can be found on aggregator sites where they are separated from usernames to protect the unfortunate victim.

The files in this folder come from sites like https://github.com/danielmiessler/SecLists, https://weakpass.com/ and https://hashes.org/

Some files contain entries between 8-40 characters. These can be found in the [Real-Passwords/WPA-Length](Rea-Passwords/WPA-Length) directory.

Lists sorted by popularity will include "probable-v2" in the filename


## Dictionary-Style Lists

Wordlists including dictionaries, encyclopedic lists and miscellaneous. Wordlists in this folder were not necessarily associated with the *"password"* label.

Some technically useful lists, such as common usernames, tlds, subdirectories, etc. are included.


## Analysis Files

This folder contains files for steps useful for password recovery and analysis.
Character masks and Hashcat rules were generated using the


## Tasklist and Plans

### Undetermined Future Plans - For Rev 3+
* [ ] Specialized lists compiled from sources themselves


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

#### You are free to:

#### Share
+ Copy and redistribute the material in any medium or format

#### Adapt
+ Remix, transform, and build upon the material for any purpose, even commercially.

The licensor cannot revoke these freedoms as long as you follow the license terms.

### Under the following terms:

#### Attribution
+ You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
#### ShareAlike
+ If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
#### No additional restrictions
+ You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

#### Notices:
+ You do not have to comply with the license for elements of the material in the public domain or where your use is permitted by an applicable exception or limitation.
+ No warranties are given. The license may not give you all of the permissions necessary for your intended use. For example, other rights such as publicity, privacy, or moral rights may limit how you use the material.


Enjoy!
