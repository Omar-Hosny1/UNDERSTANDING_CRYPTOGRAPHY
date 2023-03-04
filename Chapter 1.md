# Chapter 1

### What is a cryptographic system?

- A cryptographic system is a set of rules and procedures for secure communication between two or more parties.

### What are the two types of cryptographic systems?

- The two types of cryptographic systems are symmetric-key cryptography and public-key cryptography.

### What is a key in cryptography?

- A key is a piece of information used by cryptographic algorithms to encrypt and decrypt data.

### What is a plaintext?

- A plaintext is the original message that is to be encrypted.

### What is a ciphertext?

- A ciphertext is the encrypted message produced by a cryptographic algorithm.

### What is encryption?

- Encryption is the process of converting plaintext into ciphertext using a cryptographic algorithm and a key.

### What is decryption?

- Decryption is the process of converting ciphertext back into plaintext using a cryptographic algorithm and a key.

### What is modular arithmetic?

- Modular arithmetic is a way of performing arithmetic in a finite set of integers.

### What is an example of a finite set of integers?

- An example of a finite set of integers is the hours on a clock.

### What is the shift cipher (or Caesar cipher)?

- The shift cipher is a historical cipher that involves shifting every plaintext letter by a fixed number of positions in the alphabet. It is a special case of the substitution cipher.

### What is the difference between cryptology and cryptography?

- Cryptology is the most general term and includes both cryptography and cryptanalysis. Cryptography is the science of secret writing with the goal of hiding the meaning of a message, while cryptanalysis is the science and sometimes art of breaking cryptosystems.

### What are the two main branches of cryptology?

- The two main branches of cryptology are cryptography and cryptanalysis.

### What is the science of secret writing called?

- The science of secret writing is called cryptography.

### What is the science of breaking cryptosystems called?

- The science of breaking cryptosystems is called cryptanalysis.

### Who is usually involved in cryptanalysis?

- Respectable researchers in academia are usually involved in cryptanalysis nowadays.

### Why is cryptanalysis important for modern cryptosystems?

- Cryptanalysis is important for modern cryptosystems because it is the only way to assure that a cryptosystem is secure.

### What is the focus of this book?

- The main focus of this book is on cryptography, specifically the introduction of the most important practical crypto algorithms in detail.

### What are symmetric algorithms in cryptography?

- Symmetric algorithms are encryption and decryption methods for which two parties share a secret key. All cryptography from ancient times until 1976 was exclusively based on symmetric methods.

### What are asymmetric algorithms in cryptography?

- Asymmetric algorithms, also known as public-key algorithms, were introduced in 1976. In public-key cryptography, a user possesses a secret key as in symmetric cryptography but also a public key.

### What is public-key cryptography?

- Public-key cryptography is a type of cryptography in which a user possesses both a secret key and a public key.

### What are cryptographic protocols?

- Cryptographic protocols deal with the application of cryptographic algorithms. Symmetric and asymmetric algorithms can be viewed as building blocks with which applications such as secure Internet communication can be realized.

### What is an example of a cryptographic protocol?

- An example of a cryptographic protocol is the Transport Layer Security (TLS) scheme, which is used in every Web browser.

### What are the strengths and weaknesses of symmetric and asymmetric algorithms?

- The reason for using both families of algorithms (symmetric and asymmetric) is that each has specific strengths and weaknesses.

### What is the main focus of this book in terms of cryptographic algorithms?

- The main focus of this book is on symmetric and asymmetric algorithms, as well as hash functions.

### Besides cryptographic algorithms, what else will be introduced in this book?

- Besides cryptographic algorithms, this book will also introduce basic security protocols, several key establishment protocols, and what can be achieved with crypto protocols, such as confidentiality of data, integrity of data, authentication of data, and user identification.

### What is classical cryptanalysis?

- Classical cryptanalysis is the science of recovering the plaintext or key from ciphertext in a cryptosystem.

### What are analytical attacks in cryptanalysis?

- Analytical attacks exploit the internal structure of the encryption method to break the cryptosystem.

### What are brute-force attacks in cryptanalysis?

- Brute-force attacks treat the encryption algorithm as a black box and test all possible keys to break the cryptosystem.

### What is side-channel analysis?

- Side-channel analysis is a method of obtaining a secret key by measuring physical characteristics such as power consumption, electromagnetic radiation, or runtime behavior of an algorithm.

### What is a social engineering attack?

- Social engineering attacks involve manipulating people into divulging sensitive information, such as a secret key, by tricking or deceiving them.

### What is security by obscurity?

- Security by obscurity is the practice of keeping the details of a system hidden in order to make it appear more secure. This is generally ineffective, as these systems are often weak and easily broken once their design is reverse-engineered or leaked out through other means.

### What is Kerckhoffs' Principle?

- Kerckhoffs' Principle is a principle in cryptography that states that the security of a cryptosystem should rely solely on the secrecy of the key, rather than the secrecy of the algorithm or system design.

### Why is it important to choose strong algorithms in cryptography?

- Strong algorithms are necessary to ensure that cryptosystems cannot be easily broken by analytical attacks or brute-force attacks.

### Why are implementation attacks mostly relevant against cryptosystems with physical access?

- Implementation attacks involve exploiting physical characteristics of a system, such as power consumption or runtime behavior, which can only be measured if an attacker has physical access to the system.

### Why is it important to make sure that social engineering and implementation attacks are not practical?

- Social engineering and implementation attacks can be quite powerful in practice, and are often used by attackers to bypass traditional cryptographic defenses. Therefore, it is important to take steps to make these types of attacks more difficult or impossible to execute.

### What was the public discussion during the 1990s regarding ciphers?

- The public discussion during the 1990s was about the key length of ciphers.
  When is the discussion of key lengths for symmetric crypto algorithms relevant?
  The discussion of key lengths for symmetric crypto algorithms is only relevant if a brute-force attack is the best known attack.

### What is important to remember about key lengths for symmetric and asymmetric algorithms?

- The key lengths for symmetric and asymmetric algorithms are dramatically different.

### What is the implication of Moore’s Law in cryptography?

- The computing power doubles every 18 months while the costs stay constant. This means that in the future, computing power will increase, and the cost to break a cipher will decrease.

### How does Moore's Law behave?

- Moore's Law behaves similarly to a bank account with a 50% interest rate: the compound interest grows very quickly.

### What is modular arithmetic and why is it important in cryptography?

- Modular arithmetic is a simple way of performing arithmetic in a finite set of integers. It is important in cryptography because almost all crypto algorithms, both symmetric ciphers and asymmetric ciphers, are based on arithmetic within a finite number of elements.

### Give an example of a finite set of integers from everyday life.

- An example of a finite set of integers from everyday life is the hours on a clock.

### How can regular arithmetic be performed in a finite set of integers?

- Regular arithmetic can be performed in a finite set of integers as long as the results are smaller than the maximum integer in the set. If the result is larger than the maximum integer, the result is divided by the maximum integer and only the remainder is considered.

### What is the rule for performing arithmetic operations that result in a number larger than the maximum integer in a finite set?

- If the result of an arithmetic operation is larger than the maximum integer in a finite set, the result is divided by the maximum integer and only the remainder is considered.

### What is the remainder when 24 is divided by 7 in modular arithmetic?

- The remainder when 24 is divided by 7 in modular arithmetic is 3.

### What is the result of 5^3 mod 7?

- The result of 5^3 mod 7 is 1.

### What is the result of 15^-1 mod 17?

- The result of 15^-1 mod 17 is 3.

### What is the modular multiplicative inverse of 3 in mod 11?

- The modular multiplicative inverse of 3 in mod 11 is 4.

### What is the Euler’s totient function of 12?

- The Euler’s totient function of 12 is 4.

### What is the relationship between the Euler’s totient function and the modular multiplicative inverse?

- The Euler’s totient function and the modular multiplicative inverse are related by Euler’s theorem, which states that if a and m are coprime, then a raised to the power of Euler’s totient function of m is congruent to 1 modulo m. This relationship is used to find the modular multiplicative inverse of a in mod m.

### What is the shift cipher?

- The shift cipher is a historical cipher that involves shifting every plaintext letter by a fixed number of positions in the alphabet. It is also known as the Caesar cipher and was allegedly used by Julius Caesar with a three-position shift.

### How does the shift cipher work?

- The shift cipher involves replacing each plaintext letter with a letter that is a fixed number of positions away in the alphabet. For instance, if the shift is 3, A would be replaced by D, B by E, etc. The letters towards the end of the alphabet "wrap around", so X becomes A, Y becomes B, and Z becomes C.

### What is the mathematical description of the shift cipher?

- The shift cipher can be described mathematically using modular arithmetic. Let x be the numerical value of a plaintext letter (with A = 0, B = 1, etc.) and let k be the shift amount. The ciphertext letter y is given by y ≡ (x + k) mod 26, where 26 represents the number of letters in the alphabet.

### What is the weakness of the shift cipher?

- The shift cipher is a very weak cipher because there are only 26 possible shift amounts, which can be easily brute-forced. Additionally, the frequency distribution of letters in English text remains unchanged, allowing for frequency analysis attacks.
