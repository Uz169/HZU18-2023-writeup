# roxy
***
Easy 
,1000 points
,5 solves

## Description
you know what to do
``` 333020424c176e0a53093c2d3c420b1736665c57262924025d7b202c6e4a793d3d060735 ```

Hint - 	key=HZU18
## Solve
Уг challenge -н нэрнээс xor гэдгийг нь харж болох ба hint дээр key нь HZU18 гэдэг нь өгөгдсөн key,cipheredtext 2 байгаа учир тайлахад
хялбар болно. 

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

Дээрх script-г ажиллуулахад flag нь ``` {just_4_b1twis3_l3monsq3e3zy_r1gh7?} ``` гэж гарна.


