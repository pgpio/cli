# pgp.io CLI helper

## Encrypt & Send
`echo 'hello' | gpg -aesr '<recipient>' | pgpio`

## Receive & Decrypt
`pgpio https://pgp.io/m/Jag61Hgz19L | gpg -d`

