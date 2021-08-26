# OneLiners
Random one liner scripts for use in reversing, exploit development etc.
All take input from stdin and print to stdout

## Encode string to bytes in C syntax - python
`print('\\x' + '\\x'.join(str(v) for v in [ord(a) for a in input()]))`

## Simple xor cipher - python
`print('\\x' + '\\x'.join(str(v) for v in [(ord(a) ^ ord('\x44')) for a in input()]))`
