## Password cracking references: ##

https://www.netmux.com/

https://hashcat.net/wiki/doku.php?id=example_hashes

https://hashcat.net/wiki/doku.php?id=mask_attack

## Wordlists: ##
https://hashes.org/leaks.php

https://hashkiller.co.uk/Downloads/Wordlists

## Custom rules: ##
https://www.notsosecure.com/one-rule-to-rule-them-all/

https://github.com/praetorian-code/Hob0Rules

## Pass-phrases ##
A pass phrase is defined as multiple dictionary words appended to each other.
People wrongfully assume that a pass phrase is secure.

Using a combinator attack we can combine together a passphrase wordlist and get 2 to 4 word length passphrases without too much difficulty.

## Methodology ##
If we are trying to crack real user passwords we want to start by thinking of a hash dump as a micro community. The community rules are enforced by the website and/or domain that the passwords come from. If we know password limits we can tailor our wordlists to meet those limits.
