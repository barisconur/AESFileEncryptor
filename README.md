#AESFileEncryptor
A simple python program that encrypts and decrypts a file with AES-256, based on a generated key from the
plain password, salt and secure random IV.

## Prerequisites
* Make crypto file an executable program
```
chmod +x crypto
```
* Change python path (Line 1 at crypto). Use your own python location. Simply run below command to find your python path
```
whereis python
```

 ## Demo
* The command will create a file called cipher in the sample folder.
```
sudo ./crypto -enc sample/file2encrypt.txt sample/cipher
```
* The command will decrypt cipher and creates a file caled plaintext. And only if you enter correct password, you will access unencrypted data.
```
sudo ./crypto -dec sample/cipher sample/plaintext
```
