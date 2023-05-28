


```
def xor_decrypt(ciphertext, key):
    key_length = len(key)
    decrypted = ""
    for i in range(len(ciphertext)):
        decrypted += chr(ord(ciphertext[i]) ^ ord(key[i % key_length]))
    return decrypted

ciphertext = "333020424c176e0a53093c2d3c420b1736665c57262924025d7b202c6e4a793d3d060735"
key = "HZU18"

ciphertext_bytes = bytes.fromhex(ciphertext)
ciphertext_str = ciphertext_bytes.decode("utf-8")

decrypted_text = xor_decrypt(ciphertext_str, key)
print(decrypted_text)
```
