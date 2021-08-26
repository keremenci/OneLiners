# OneLiners
Random one liner scripts for use in reversing, exploit development etc.

## Encode string to bytes in C syntax

`print('\\x' + '\\x'.join(str(v) for v in [(ord(a) ^ ord('\x44')) for a in input()]))`
