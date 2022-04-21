<h1 align="center"> Hash Codes ⚔️</h1>

<p align="justify">
  Cryptography foundations inbuilt in the python language while developing their own encryption software using multiple hashing techniques. In this project I use python’s hashlib library to use its SHA256 and MD5 algorithms.
  
Installation of the packages:
  Windows User:
1. On the console type **pip install simple-crypt --no-dependencies** and press enter.
2. On the console type **pip install pycryptodome** and press enter.
  
 Mac User:
1. type **pip install simple-crypt** and press enter

Goal:
● Study the Encryption and Decryption Algorithms and create a console based application to demonstrate the encryption and decryption process.

1) Cryptography is used to protect and secure the data during communication.
Cryptography is a science of protecting the information by transforming it into a secured format. This process has been used for centuries to send the secret messages, where the message to be sent can not be read by the unauthorised users and can only be ready by the intended receiver.
So cryptography can be done in two ways to protect the data

2) Hashing requires a hash() function, and these hash() functions are very useful and are used in various information security applications. A hash function is a mathematical function which converts the numerical or string
input/message to another compressed and complex numeric value and in unreadable form.

![exemplo](https://user-images.githubusercontent.com/100588945/164342688-4e6d9a18-2409-4c7d-9c40-c66416bef7c2.png)

  
3) Encryption and Decryption :- Encryption basically is a process which transforms the original data into an unrecognisable or unreadable form. In this the encryption algorithms are used to convert the data into unreadable form. That's the reason why the hackers can't hack these data. Once encryption is done and sends the data, at the receiver’s end the data is again converted to the original form and hence it is called as the Decryption.

4) Key -A key in encryption and decryption is any string which is used to encode and decode the data. This key helps to make the encoding more strong. This key is the
most important part while encrypting the data into ciphertext and this same key is used to decrypt the data while performing the decryption that is converting the ciphertext to the original plain text. If the same key is not used for decryption then you won’t get the plain text.
  
  
  <h2 align="center">Functions or Modules</h2>
  
1) hashlib :- python comes with the inbuilt hashing module which is the Hashlib module. Python’s hashlib module is an interface for hashing messages easily.
This contains various methods which will perform hashing on any string and encrypt it. The core purpose of this module is to use a hash function on a string,
and encrypt it so that it is very difficult to decrypt it.

The hashlib module consists of various hashing algorithms by which we can encrypt our string like ‘whirlpool’, sha256, md5, sha3-224, sha3-256 etc. But we will be using the sha256 and md5 algorithms for hashing the data.

● Sha256 - SHA(Secure Hash Algorithm) which is a set of cryptographic hash functions used to encrypt the data in a non readable form. Here the
SHA256 is the 256 bit hashing algorithm, which has a mechanism of converting the original data into 64 character hexadecimal values.
- **Hexadecimal Values:** It is a number representation technique in which the values has base 16, means there are 16 symbols/characters/digits from 0,1,2,3,4,5,6,7,8,9 and alphabets from A,B,C,D,E,F(that is replacements of 10,11,12,13,14,15).

![HEXA](https://user-images.githubusercontent.com/100588945/164342399-2d54e53d-0360-459a-a28c-4f168e4cba1d.png)

● MD5 - (Message Digest 5) converts the original data into 128 bit length hash and represents it into 32 hexadecimal characters.

2) Simplecrypt- This is a library which is used to perform encryption and decryption on the data.
● Encryption:- It is converting the plain text into a ciphertext using a key.
● Cipher text is the plain text which is converted into the encrypted text using the encryption algorithm and this cipher text is in unreadable format.

For example: if we have to decrypt the above encrypted message we will use the decrypt() function and we will get the original data back.
  </p>
