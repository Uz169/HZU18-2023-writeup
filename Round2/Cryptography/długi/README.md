# długi
***
Easy 
,1000 points
,1 solve

## Description
1774087024706539038751564925929662035515511965610064028029

Hint - байт хүртэл урт
## Solve

```
long_integer = 1774087024706539038751564925929662035515511965610064028029
bytes_data = long_integer.to_bytes((long_integer.bit_length() + 7) // 8)

print(bytes_data)

```
ажиллуулахад flag нь : 
```
b'HZU18{l0ng_t0_byt3s_1!!}'
```
гэж олдоно
