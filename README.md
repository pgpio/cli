# pgp.io CLI helper

A simple Bash script for uploading and downloading from https://pgp.io.

## Usage

Encrypt & Send
 > `echo 'hello' | gpg -aesr '<recipient>' | pgpio`

Receive & Decrypt
 > `pgpio Jag61Hgz19L | gpg -d`

