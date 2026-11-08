# Personal Secure Wallet
A Python App to view and save encrypted data such as passwords and other secrets.

All encryption is done before storing the data on disk by using existing third-party software, such as OpenSSL and 7-Zip.

Before saving data, a passphrase should be defined, otherwise the file is saved in plain text.
Once entered, the passphrase will be used for the whole session or until is is set to something else), to either load other files or to save the current file.

The encryption method set in the external commands will ve AES-256.

## 📖 The Book

This project is **Chapter 2, "Personal Secure Wallet"**, in a book:

**Chips, Code, and Cartridges: Turn Curiosity into Creation with 13 Hands-On Projects, from 8-bit Classics to FPGAs**

It walks through thirteen of my own hardware and software projects, from 8-bit classics to FPGAs, for beginners and curious makers. Each chapter explains how one project works and how to build it, with colour diagrams and real code from its repository.

### 👉 [Get the book on Amazon](https://link.amazon/B013Yaq9y)

<sub>As an Amazon Associate, the author earns from qualifying purchases. Buying through this link
supports these projects at no extra cost to you.</sub>

# Quick Start Guide
All you need is "PersonalSecureWallet.pyw"

Use the Edit -> Options menu to hoose the encryption software to use (must be insalled on your computer)

Use Edit -> Passphrase to define the password to encrypt the file 

Enter the data you want in the text area, then use File -> Save As.. to save to disk

Do not forget your password, or your data will be definitively lost.
