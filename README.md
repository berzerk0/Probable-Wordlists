### Rev 1.2 is here! Torrents are here! Seed to support the project!

### To potential cloners and zip-downloaders:
This repository does not contain code, but is a group of lists. More accurately, it is a set of links TO a group a lists. As a result, a clone or zip download is possible, but may not be necessary to get the files you need.


![Probable Wordlists Logo](https://raw.githubusercontent.com/berzerk0/Probable-Wordlists/master/ProbableWordlistLogo.png)


# Probable Wordlists
Wordlists sorted by popularity originally created for password generation and testing

### Why slog through an encyclopedic, alphabetized wordlist when you can start with the words people are most likely to use?
#### Methodology - The Why and How

 While I was able to locate a few Password Wordlists that were sorted by popularity, the vast majority of lists, especially the larger lists, were sorted alphabetically. This seems like a major practicality flaw! If we assume that the most common password is "password," and we are performing a dictionary attack using an English dictionary, we are going to have to slog from "aardvark" through "passover" to get to "password." I don't know off the top of my head just how common "aardvark" is as a password - but we could be wasting a lot of time by not starting with the most common password on our list!

 I went to SecLists, Weakpass, and Hashes.org and downloaded nearly every single Wordlist containing real passwords I could find. These lists were huge, and I ended up with over 80 GB actual, human-generated and used passwords. These were split up among over 350 files of varying length, sorting scheme, character encoding, origin and other properties. I sorted these files, removed duplicates from within the files themselves, and prepared to join them all together.

 Some of these lists were composed of the other lists, and some were exact duplicates. I took care to remove any exact duplicate files - we didn't need to have any avoidable false positives. __*If a password was found across multiple files, I considered this to be an approximation of its popularity.*__ If an entry was found in 5 files, it wasn't too popular. If an entry could be found in 300 files, it was very popular. Using Unix commands, I concatenated all the files into one giant file representing keys to over 4 billion secret areas on the web, and sorted them by number of appearances in the single file. From this, I was able to create a large wordlist sorted by popularity, not the alphabet.

 
### Laser-Guided Wordlist Generator in the works as well - stay tuned
 

## Real-Passwords
These are **REAL** passwords. 
Every once in a while, a popular site has a high-profile security leak and passwords are released freely across the internet.
Some of these passwords can be found on aggregator sites where they are separated from usernames to protect the unfortunate victim.

The files in this folder come from https://github.com/danielmiessler/SecLists, https://weakpass.com/ and https://hashes.org/

*NOTE THAT UNTIL REV 2.0, ALL NON-ASCII CHARACTERS HAVE BEEN REMOVED*
 * A more inclusive, and thus, more accurate list is in the works.

*NOTE THAT THE DUE TO THE NEWLINE DUPLICATES ISSUE, 'WPA-Length' LISTS MAY INCLUDE LINES OF 7 CHARACTERS*
 * This will be fixed in Rev 2.0


Lists sorted by popularity will include "probable" in the filename


## Dictionary-Style Lists

Wordlists including dictionaries, encyclopedic lists and miscellaneous.


## Tasklist and Plans

### Rev 1.2 Task List
* [x] Re-include Largest Wordlists in Repo (passwords appearing at least twice)
* [x] Include 'Case Variants' for Dictionary Style Wordlists
* [x] Fix Newlines in Dict-Style
* [x] Include Secret message somewhere in repository  (not in wordlists)
* [x] Create and Add Torrents

### Rev 2.0 Plan - Expected June 2017
* Include truly accurate WPA-Length sorting
* More sources (Contributions open, with strict terms. See Contributions page)
* Bigger sources
* Non-ASCII Sources
* Specialized lists compiled from sources themselves
* Totally Recompile wordlists for improved accuracy, no duplicates from the get-go.

### Undetermined Future Plans
* [x] Come up with poetic name for 'things that'd be cool that I'm not sure when I'll do'
* [ ] Create list of "pure" common passwords for use with rule-based cracking


## Attributions
 * [Ian Norden](https://github.com/iancnorden) for helping with duplicates and volunteering his time to make me a little less noobish
 * The folks over at [OWASP's SecLists](https://www.owasp.org/index.php/Projects/OWASP_SecLists_Project) for providing sources and inspiration
 * Sources like [Weakpass](https://weakpass.com/), [Crackstation](https://crackstation.net/), [Hashkiller](https://hashkiller.co.uk/) and [Hashes.Org](https://hashes.org/) for inspiration and lists.
 * [Hack-With-Github](https://github.com/Hack-with-Github) for including this repository on the [Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking) repository. 



## Disclaimer and License
 + These lists are for LAWFUL, ETHICAL AND EDUCATIONAL PURPOSES ONLY.
 + The files contained in this repository are released "as is" without warranty, support, or guarantee of effectiveness. 
 + *However, I am open to hearing about any issues found within these files and will be actively maintaining this repository for the foreseeable future. If you find anything noteworthy, let me know and I'll see what I can do about it.*
 
I did not steal, phish, deceive or hack in any way to get hold of these passwords. 
All lines in these files were obtained through freely available means.
 
 
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

