┌──(kali㉿DESKTOP)-[~]
└─$ echo 'c4n y0u c4p7u23 7h3 f149?' | sed -e 's/4/a/g' -e 's/0/o/g' -e 's/7/t/g' -e 's/2/r/g' -e 's/3/e/g' -e 's/1/l/g' -e 's/9/g/g'
```can you capture the flag?```

┌──(kali㉿DESKTOP)-[~]
└─$ echo "MJQXGZJTGIQGS4ZAON2XAZLSEBRW63LNN5XCA2LOEBBVIRRHOM======" | base32 --decode
```base32 is super common in CTF's```

┌──(kali㉿DESKTOP)-[~]
└─$ echo 'RWFjaCBCYXNlNjQgZGlnaXQgcmVwcmVzZW50cyBleGFjdGx5IDYgYml0cyBvZiBkYXRhLg==' | base64 --decode
```Each Base64 digit represents exactly 6 bits of data.```

┌──(kali㉿DESKTOP)-[~]
└─$``` echo '68657861646563696d616c206f72206261736531363f' | xxd -r -p```
```hexadecimal or base16?```

┌──(kali㉿DESKTOP)-[~]
└─$```echo "Ebgngr zr 13 cynprf!" | tr 'A-Za-z' 'N-ZA-Mn-za-m'```
```Rotate me 13 places!```

┌──(kali㉿DESKTOP)-[~]
└─$ ```echo "*@F DA:? >6 C:89E C@F?5 323J C:89E C@F?5 Wcf E:>6DX" | tr '!-~' 'P-~!-O'```
```You spin me right round baby right round (47 times)```

https://morsecode.world/international/translator.html

```morse
- . .-.. . -.-. --- -- -- ..- -. .. -.-. .- - .. --- -.

. -. -.-. --- -.. .. -. --.
```
```telecommunication encoding```

```Deximal to Text
85 110 112 97 99 107 32 116 104 105 115 32 66 67 68
```
```Unpack this BCD```
