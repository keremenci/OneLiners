# OneLiners
Random one liner scripts for use in reversing, exploit development etc.
All take input from stdin and print to stdout

## Encode string to bytes in C syntax - python
```print('\\x' + '\\x'.join(str(v) for v in [format(ord(a), 'x') for a in input()]))```

## Simple xor cipher to C syntax - python
```print('\\x' + '\\x'.join(str(v) for v in [format(ord(a) ^ ord(<key>), 'x') for a in input()]))```
