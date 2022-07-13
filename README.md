# caesar-cypher

> We're going to jump into the theoretical knowledge you'll need when writing the final project. Let's learn more about cryptology and its constituent parts. And at the same time, we'll learn more about the cipher that you will use when writing the final project...

----------------------------------------

## Cryptology, cryptography and cryptanalysis

Let's jump into the theoretical knowledge you'll need when writing the final project. Let's learn more about cryptography and its constituent parts. And at the same time, we'll learn more about the cipher that you will use when writing the final project.

### 1. Cryptology and its constituent parts

Cryptology is a field of knowledge that includes:

- Cryptography (the science of ciphers).

   Cryptography is all about encrypting information to protect it from unauthorized access. This information could be text, a digital image, an audio signal, etc. The encryption process produces an encrypted version of the information (data), which is called the ciphertext or codetext.

- Cryptanalysis (methods for cracking these ciphers).

   Cryptanalysis examines methods of breaking ciphers and how these methods can be applied. In other words, cryptanalysis performs the inverse task, studying ways to turn encrypted information into plaintext.

### 2. Cryptographic key
   A key is a selection of data that is used to encrypt and decrypt information. The ability to successfully decrypt information depends on what key is used. If a key is lost for some reason, then it will be impossible to decrypt the data.

The size of cryptographic keys is measured in bits. And this means that a cryptographic key has a length. Good encryption strength is provided with a length of 128 bits.

#### Types of cryptographic keys:

- Symmetric keys (secret keys). 

   Unsurprisingly, such keys are used in what are known as symmetric-key algorithms. Their main purpose is to perform forward or reverse cryptographic transformations (encryption/decryption, verification of the message authentication code).

- Asymmetric keys. 
     
   They are used in asymmetric-key encryption algorithms (for example, when verifying an electronic digital signature).

Since we'll be working with a symmetric-key encryption algorithm, we won't go into too much detail here.

### 3. Substitution alphabet

A substitution alphabet is a complete set of characters used to encode input characters.

### 4. Approaches to cryptanalysis

There are many different cryptanalysis approaches and methods, i.e. ways to crack ciphers.

We'll describe the simplest of them:

1. Brute force (or brute force search) is trying all possible keys until we find the correct one. The advantage of this method is its simplicity. The disadvantage is that it is not suitable for ciphers involving a large number of possible keys.
2. Cryptanalysis based on statistical data — in this approach, we gather statistics on the occurrence of different characters in the ciphertext, and then we decrypt based on statistics on the frequency of occurrence of different characters in plaintext.

_For example: we know that the frequency of the letter P in English texts is 1.9%. As we analyze the ciphertext, we look for a symbol that occurs with the same frequency and then conclude that it is the letter P._

The disadvantage of this approach is its dependence on the specific language, author, and style of the text.

### 5. Caesar cipher

This is one of the simplest and most well-known encryption methods. Its name, of course, comes from the Emperor Gaius Julius Caesar, who used this method to correspond secretly with generals.

A Caesar cipher is a substitution cipher in which each character in the plaintext is replaced by a character that is some constant number of positions to its left or right in the alphabet.

Let's say we set the shift to 3. In this case, A will be replaced by D, B will become E, and so on.

This is the minimum amount of theory you will need to complete the final project. Let's move on to the task description!
