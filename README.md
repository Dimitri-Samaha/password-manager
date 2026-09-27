# Password Manager

A simple password vault for the command line. Register a username and password (validated for length and character mix), log in, or play as a guest; accounts are stored in plain text in `p_file.txt`. It also exposes `log_sign_func()`, meant to be imported by another program to gate access behind a login screen.

**Note:** accounts are stored in plaintext with no encryption. This is a learning exercise, not a real password manager.

## Requirements
No external dependencies; the standard library is enough.

## Running it
```
python password_manager.py
```
