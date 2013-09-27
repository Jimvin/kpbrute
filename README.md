kpbrute
=======

A dictionary-based brute force tool for KeePass 1.x databases


Example Usage
-------------
A sample KDB file and dictionary are supplied to test the script.
kpbrute will try all of the dictionary entries and stop when it either
finds the correct passphrase or runs out of passphrases to test.

```
localhost:kpbrute jimvin$ ./kpbrute  --kdb=sample_database.kdb --dict=sample_dictionary.txt 
Password This is a banana does not work
Password This is a hammock does not work
Password This is a basketball does not work
Password This is a monkey does not work
Password This is a password works!
```
