# J.Crack

## Description 

A tool used to crack json web token secret key

## How to use 

1. Install Requirments 

```bash
pip install -r requirment.txt
```

2. Arguments 

* -i Input : It can be a string or a file
* -w wordlist : The path of the wordlist of the attack (`/usr/share/wordlists/rockyou.txt` by default)
* --rule : 
  * classic : cracking using the lines of the file
  * base32 : encoding lines in base32 before attacking
  * base64 : encoding lines in base64 before attacking

3. Exemple : 

```bash
python util.py -i token --rule base64 
```


<hr>

## Creds :

This work is crafted with &#x2764; and released as an open source . Feel free to remix, share, and build upon this work!

