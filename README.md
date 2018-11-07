# Hybrid Cryptography on Cloud

A python package for hybrid file encryption and decryption. securefile is for n-layer file encryption. This package provides a basic two-way encryption algorithm for a file. It supports approximately all kind of file encoding. The package provides RSA, DES, AES and Shift Cipher and base64 algorithm for file encoding and decoding.

[Full Documantaion](https://www.sixpetal.com/securefile)


## Installation
type `pip install securefile` to install this package in native python

##### Dependency
 - pyserial (use `pip install pyserial` for native python or `conda install -c anaconda pyserial` for anaconda python)



## Data Encryption Standard (DES) Algorithm
The Data Encryption Standard (DES) is a symmetric-key block cipher published by the National Institute of Standards and Technology (NIST). DES is an implementation of a Feistel Cipher.

[Pydes](https://github.com/RobinDavid/pydes)

```python
e = Encrypt('test.md', '1234567812345678')
e.open()
print("Cipher Text:")
print(e.des_encrypt())
print("Orignal Text:")
print(e.des_decrypt())
```
Output
```
Cipher Text:
61 190 197 140 153 91 179 181 82 186 223 39 203 44 111 165 142 72 9 170 31 183 222 247 
Orignal Text:
TEST STRING
```
## Cite

##### A Survey on Performance Analysis of DES, AES and RSA Algorithm along with LSB Substitution Technique:
```
Padmavathi, B. and S. Ranjitha Kumari. "A Survey on Performance Analysis of DES , AES and RSA Algorithm along with LSB Substitution Technique." (2013).
``` 

##### A study of DES and Blowfish encryption algorithm:
```
T. Nie and T. Zhang, "A study of DES and Blowfish encryption algorithm," TENCON 2009 - 2009 IEEE Region 10 Conference, Singapore, 2009, pp. 1-4.    
doi: 10.1109/TENCON.2009.5396115    
keywords: {cryptography;Blowfish encryption algorithm;data security;information security systems;DES;Data security;Public key;Information security;Algorithm design and analysis;Personal digital assistants;Public key cryptography;Data engineering;IP networks;Communication system security;Mobile computing;Encryption Algorithm;DES;Blowfish},
URL: http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5396115&isnumber=5395786
```
