Or **Public-key cryptography** is the field of crypto systems that use pairs of related keys. Each pair consists of a public key and a corresponding private key. Security of public-key cryptography depends on keeping the private key secret; the public key can be openly distributed without compromising security.

In a **public-key encryption** system, anyone with a public key can encrypt a message, yielding a ciphertext, but only those who know the corresponding private key can decrypt the ciphertext to obtain the original message.

In a digital signature system, a sender can use a private key together with a message to create a signature. Anyone with the corresponding public key can verify whether the signature matches the message, but a forger who does not know the private key cannot find any message/signature pair that will pass verification with the public key.

Compared to [[Symmetric encryption]], asymmetric encryption is rather slow, too slow for many purposes. Today's cryptosystems (such as TLS, Secure Shell) use both symmetric encryption and asymmetric encryption, often by using asymmetric encryption to securely exchange a secret key, which is then used for symmetric encryption.

#asymmetric_cryptography #public_key_cryptography

Links:
https://en.wikipedia.org/wiki/Public-key_cryptography