# Probabable Password Trend Analysis

### In order to get a better idea of the trends of secure and insecure passwords, I ran a portion of these lists through [DigiNinja's Pipal.](https://digi.ninja/projects/pipal.php)

Pipal was run on a list of the __Top 32 Most Popular Passwords__ - not the largest list in the repo, 
but sizable enough to encompass common patterns. These patterns lead to easy-to-follow advice to make your password more unique and buck trends. Some passwords can appear secure, but can be easily guessed anyway.

Passwords included in this analysis appeared at least 10 times in the Rev 1.2 Files.

### Scroll down to the bottom to see the advice.

#### CAVEAT: This is not *the* definitive guide to making a password, but it does provide data supported tips.


# 

![Password Length Trends](https://i.imgur.com/KAYUHj3.png)




#

![Password Character Use Trends](https://i.imgur.com/Y5adW1d.png)




#

![Password Character Order Trends](https://i.imgur.com/ei66PJO.png)




For many, it might seem like a cool idea to have such a big list, but it might not be immediately clear how this information can be used. After searching the list and finding that their password(s) were not present, I predict that the majority of people would simply think "Phew, that's a relief," and move on. They might share the list with a few friends, and next time they come up with a new password, they MIGHT check the list again, but it's very likely to be the last time the list, and possibly password security, crosses their mind.

I wanted the list to provide immediately actionable information to everyone, even if their password was NOT found on the list. Armed with DigiNinja's Pipal, I performed an analysis on the list of the Top 32 Million Passwords, not the largest list in the repo, but sizable enough to encompass notable trends. Pipal provided valuable data for me to interpret and chart, and I've presented my findings, along with immediately actionable advice below.

Scroll down a few sections to see the data (with advice and conclusions on the charts), or scroll down just a little bit to see the advice.

### The Power of Hashcat and Other Cracking Tools

No password is "uncrackable," and modern password cracking tools are very powerful. However, a password that is strong, unique and bucks common trends will be the hardest to guess via brute force masking and dictionary attacks. The logic here is simple: if your password isn't on the wordlist, it cannot be guessed via dictionary attack. If it doesn't match the common patterns it will take a brute force attack much longer to reach it.

If a password cracker is brute forcing passwords using a pattern of eight lowercase letters followed by 2 digits then password17 is going to be guessed. Cracking software like hashcat even as the ability to use hybrid attacks that combine a dictionary and a brute force mask. If this dictionary+mask attack was using a list of the most common passwords, password17 wouldn't stand a chance! At the number 2 most common password, it would take just 117 guesses (all 2 digit numbers appended to the No. 1 most common password + 17 guesses using password). This dictionary word + numbers format is very common, and is likely to be one of the very strategies used - it is even included in the hashcat default ruleset. Rules create mutations of wordlist items that are used in a dictionary attack, and will try things like turning the letter "S" into a "$" and other common substitutions.

Note that due to rules, it can be easy to create passwords that might APPEAR to be secure due to character choice and character order, but can be easily guessed if they are common mutations of dictionary words.

password can be mutated into something like P@$$w0rd - which some password "strength" algorithms might rate as strong. It's got capital and lowercase letters, special characters and numbers! How couldn't it be secure?! Well, easily.

The l33tspeak phenomenon has been around for some time now, and it doesn't take a nobel prize winner to guess that s can be swapped for $. Theoretically, almost @ny $3nt3nc3 c@n b3 \/\/r1tt3n 1n l33t and still be legible. If you can read that, then you can figure out how to write a a rule to create mutations yourself. (If you couldn't read it, the l33t section reads "any sentence can be written in leet")

Mutations of dictionary words and other common passwords are easy to guess, and shouldn't form your entire password.

### Make Your Password Buck the Trends With These Tips:

Let's walk through the mutation of a dictionary word password. At the beginning it will be very easily guessed, and when we are done, it will be statistically much harder to guess. However, don't use our final product as your password! Here it is published online!

Starting password: _noodle_

* About 90% of passwords used SOLELY lowercase letters and numbers. 47% used lowercase letters alone.

_noodle17_

* Special Characters appeared in fewer than 4% of the passwords
* Uppercase Letters appeared in fewer than 1%!
* 35% of passwords solely used letters followed by numbers
* Use special characters and capital letters! Hit that shift key!

*Noodle-17*

Just 0.02% of passwords on the list began with special characters.

Character order matters!

*-Noodle17*

* More than 91% of passwords had lengths between 8 and 14 characters. 23% of the passwords used exactly 8 characters.
* About 40% of passwords ended in a number
* Make 13 or 14 your minimum password length and you'll be like the rare 9%
* Pad your password with special characters and relevant words using capital letters to make it longer and even harder to guess

*-Noodle-17-SOUP-*

* The most "natural" way to include a capital letter is to capitalize the first letter of the dictionary word. Don't let that be your only capital! If it's natural for you, it would be natural for the crackers as well.
* So we started with noodle, and ended up with _-Noodle-17-SOUP-_, which includes "friendly" special characters that are likely to be allowed numbers, lowercase capital letters (and not only at the beginning).

This password is much harder to crack than noodle, and is even harder to crack than _n00dl3$0UP_ which might be mutated out of a dictionary word.



