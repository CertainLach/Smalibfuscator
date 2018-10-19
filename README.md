# Smalibfuscator
Smali and jasmin obfuscator

Disassembles .jar/.dex, rewrites .j/.smali, assembles back

## Parts
- parser (Open source, in this repo. Written in Node.JS (+PEG))
    - Parses .smali
    - Writes .json
- processors (Closed source. Modular, written in Node.JS / Python / Java)
    - Parses .json
    - Applying obfuscation
    - Writes .json
- compiler (Closed source. Written in Node.JS)
    - Parses .json
    - Writes .smali
