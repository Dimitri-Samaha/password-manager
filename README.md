# Password Manager

A simple command-line password vault. Register a username/password (validated for length and character mix), log in, or play as a guest; accounts are stored in plain text in `p_file.txt`. Also exposes `log_sign_func()`, meant to be imported by another program to gate access behind a login screen.

**Note:** accounts are stored in plaintext with no encryption — this is a learning exercise, not a real password manager.

## Requirements
No external dependencies (standard library only).

## Running it
```
python password_manager.py
```
