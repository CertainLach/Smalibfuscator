# Smalibfuscator
Smali obfuscator
> Work in progress, will eat your cat!

## Parts
- parser (Written in Node.JS (+PEG))
    - Parses .smali
    - Writes .json
- processor (Written in Python)
    - Parses .json
    - Applying obfuscation
    - Writes .json
- compiler (Written in Node.JS)
    - Parses .json
    - Writes .smali