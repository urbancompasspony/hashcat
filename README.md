# hashcat

Cracking lots of hashes!

# Installation

sudo apt install hashcat

# Configuration

Create a MD5 hash:
echo -n "PASSWORD" | md5sum

Basic:
hashcat -a 0 -m 0 hashes wordlist -r rule1 -o cracked

Agressive:
hashcat -a 0 -m 0 hashes wordlist -r rule2 -o cracked

I do not offer wordlist. Use your own!
