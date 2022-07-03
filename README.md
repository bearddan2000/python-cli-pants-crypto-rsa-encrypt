# python-cli-pants-crypto-rsa-encrypt

## Description
Compare hashed passwords. RSA
is an asymmetric algorithm that
uses a 3072 bit key. Encryption is
done by public key while decryption
is by private key.

RSA should never be used to store passwords.

## Tech stack
- pants
- python 3.8

## Docker stack
- pantsbuild/centos7:latest

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
https://cryptobook.nakov.com/asymmetric-key-ciphers/rsa-encrypt-decrypt-examples
