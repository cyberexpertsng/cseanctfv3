### Challenge
- **Challege Name** - Bases
- **Author** - h4cky0u
- **Points** - 100
- **Description** - ICAgICAgJyNzeDgxJDIrdWcaKD0cMiseKy0wKiUnLTQaMi0rNigkMw==

### Solution

Just base64 decode it then xor it with `CSEAN`:
- [decoded](https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)XOR(%7B'option':'UTF8','string':'CSEAN'%7D,'Standard',false)&input=SUNBZ0lDQWdKeU56ZURneEpESXJkV2NhS0QwY01pc2VLeTB3S2lVbkxUUWFNaTByTmlna013PT0&oeol=VT)

### Flag

```
cseanctf26{base64_is_an_encoding_scheme}
```
