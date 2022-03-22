# Personal Password Manager

![Status badge](https://img.shields.io/badge/Status-Archived-important)

**Update** (22 Mar. 2022): Try creating user interface using *Streamlit*

🔏 A tiny program to encrypt and store password

## Requirements

There are some general library requirements for the project and some which are specific to individual methods. The general requirements are as follows.

- `Fernet`
- `Json`

## Usage

1. Run `manager.py` using command line 
2. Enter `view` to view password list or `add` to add new account
3. Password will then be encrypt using **key** and stored in `passwords.txt`


## Information about other files

- `passwords.txt`: Storing encrypted passwords
- `key.key`: Key to encrypt 
