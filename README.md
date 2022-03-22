# Personal Password Manager

![Status badge](https://img.shields.io/badge/Status-Archived-important)

**Update** (22 Mar. 2022): Try creating user interface using *Streamlit*

## Requirements

There are some general library requirements for the project and some which are specific to individual methods. The general requirements are as follows.

- `Fernet`
- `Json`

## Usage

### Bot commands

1. Run `v/album` to display list of song tracks
2. Run `v/play` + `[name]` to play songs in the album
3. If cannot find song in **album**, use `v/download` + `[name]` to update new song to the album
4. `v/pause`, `v/stop`, `v/skip`, `v/leave`, `v/join` are used as usual


## Information about other files

- `passwords.txt`: Storing encrypted passwords
- `key.key`: Key to encrypt 
