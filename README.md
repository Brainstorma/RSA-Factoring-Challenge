# RSA-Factoring-Challenge

This is a open source software tool for factoring RSA numbers. It is written in Python and is easy to use for anyone with basic understanding of RSA cryptography.

## Features

The following functions are available in this project:

| Function          | Description                                                                                           |
|-------------------|-------------------------------------------------------------------------------------------------------|
|        | This function takes an RSA number as input and returns the two prime factors of it.                     |
|  | This function generates a public key using two prime factors.                                         |
| | This function generates a private key using two prime factors.                                        |
|          | This function takes a plaintext message as input and encrypts it using the public key given as input.  |
|          | This function decrypts a ciphertext message using the private key given as input.                    |

## Requirements

The following packages are required for this project:

- python >= 3.6
- gmpy2 >= 2.0.8
- pycrypto >= 2.6

## Usage

### Installation

1. Clone the repository: 

   

2. Install dependencies: 

   

### Factorization

The  function takes an RSA number as input and returns the two prime factors.

Example usage:



The  variable would contain the two prime factors of 1234.

### Generating Keys

The  and  functions take two prime factors as input and generate public and private keys respectively.

Example usage:



The  and  variables would contain the generated keys.

### Encryption and Decryption

The  and  functions take a message and a key as input and encrypt/decrypt respectively.

Example usage:



The  variable would contain the encrypted message and the  variable would contain the decrypted message.

## Documentation

For more detailed documentation and tutorials, please refer to our [GitHub Wiki page](https://github.com/brainstorma/RSA-Factoring-Challenge/wiki).
