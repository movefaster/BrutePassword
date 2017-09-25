# BrutePassword
A simple Python script to brute force a user's password as stored in `/etc/shadow` in a Linux system. It assumes the password is hashed with MD5 and simply tries to compare existing password hashes to hashes of passwords in the dictionary.

# Requirments
1. Python 3.6+
2. `passlib`

# Usage
```bash
$ pip3 install -r requirements.txt
$ python3 brute_password.py -h
```