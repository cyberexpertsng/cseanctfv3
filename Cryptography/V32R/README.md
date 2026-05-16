### Challenge
- **Challege Name** - V32R
- **Author** - h4cky0u
- **Points** - 100
- **Description** - I don't usually do ciphers, but 🥀 The challenge name says all and remember CSEAN is the key

### Solution

We are given just this text

```
RNDGX2FIRFEX6RPUZHMJ62K7BTQLS4GFEZSS64VXRBLIKC27MIBYO3TSO5MBM6MYYNTUKQ3SMSUPKYL=
```

From the challenge name it hints towards the decoding steps

Just decode from Vignere Cipher with key `CSEAN`, then base32 decode and reverse the string

Here's the cyber chef recipe:
- [decoded](https://gchq.github.io/CyberChef/#recipe=Vigen%C3%A8re_Decode('CSEAN')From_Base32('A-Z2-7%3D',true)Reverse('Character')&input=Uk5ER1gyRklSRkVYNlJQVVpITUo2Mks3QlRRTFM0R0ZFWlNTNjRWWFJCTElLQzI3TUlCWU8zVFNPNU1CTTZNWVlOVFVLUTNTTVNVUEtZTD0&oeol=FF)
  
### Flag

```
cseanctf26{vigenere_cipher_decrypt_i_hate_cipher}
```
