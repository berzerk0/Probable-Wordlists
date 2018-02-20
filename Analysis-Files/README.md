# Analysis Files



The files reached through this directory will assist in password analysis and recovery.<br>

__Most files can only be accessed via torrent or MegaLink.__ <br>
A few files are included in the repository, however,

All rules and masks were generated using the [PACK](https://github.com/iphelix/pack) project.



## Rules

HashCat rulesets allow for automatic modification of wordlist items during use of the HashCat software. These modifications can include changes in capitalization, the addition of characters, manipulation of a whole string and more.


Use of a ruleset takes `password` as an input and generates outputs like `PASSWORD`, `p455w0rd`, `dr0wssap`, etc.


*A mutation will be generated for __every__ rule in a ruleset.* Consider a ruleset with 5 entries and a wordlist with 20 lines. When combined, the functional size of the wordlist is increased from 20 to 100. Keep in mind that the smallest ruleset provided here is *26* entries long.

The use of rulesets increases the functional size of a wordlist, but may quickly result in far too many entries for practical use.

In order to limit this, I've divided the rules generated from `Top29Million-probable-v2.txt` into smaller, __cumulative__ files. These rules are sorted by probability, with the most common rules at the top of the list.

At 2.2GB, the largest ruleset should be used with only the shortest wordlists.<br>
Its use is not practical for any other purpose.


## Masks

__Masks are not included the repository and must be downloaded via torrent or MegaLink.__

HashCat uses character descriptions to outline password composition. They are similar to regular expressions.

* `?l` represents any character  `abdcdefghijklmnopqrstuvwxyz`
* `?u` represents `ABCDEFGHIJKLMNOPQRSTUVWXYZ`
* `?d` represnts `0123456789`

These are used repeatedly to create __"Masks"__ that are used to describe combinations of characters.

`?l?l?l?d?d?d` represents all combinations of lowercase letters and numbers from `aaa000` through `zzz999`.


These masks are used to describe composition patterns in the list.
Two files are included:

* `ProbWL-mask-probable-v2.mask` contains all masks found in `Top2Billion-probable-v2.txt`, sorted by popularity
* `ProbWL-mask-probable-v2-counts.txt` contains the same contents as the first file, but each entry is paired with the number of times a password matching that mask appeared in the wordlist.


<br>

#### Recommended Unarchivers:
* Windows: 7Zip
* Mac: Keka
* Linux: Command Line, p7zip

#### Recommended Torrent Client:
* __Deluge__ gave me the best results in terms of connecting to the seedbox.


***

![Probable Wordlists Logo](https://raw.githubusercontent.com/berzerk0/Probable-Wordlists/master/ProbableWordlistLogo.png)

## Disclaimer and License
 + These lists are for LAWFUL, ETHICAL AND EDUCATIONAL PURPOSES ONLY.
 + The files contained in this repository are released "as is" without warranty, support, or guarantee of effectiveness.
 + *However, I am open to hearing about any issues found within these files and will be actively maintaining this repository for the foreseeable future. If you find anything noteworthy, let me know and I'll see what I can do about it.*

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




__Enjoy!__


<br>
This file was last updated on 20 Feb, 2018.
