# BIP39 Mnemonic Arithmetic Adder

Simple HTML/JS web app that takes a BIP39 mnemonic, interprets its entropy as an integer, adds a given index *I*, and returns a new valid mnemonic with the checksum corrected.

## Live demo

https://b4n6-b4n6.github.io/bip39-mnemonic-adder/

## Usage

1. Enter a 12/15/18/21/24-word English BIP39 mnemonic
2. Enter an integer index *I* (can be large or negative)
3. Click “Compute new mnemonic”

The app runs entirely in the browser (no server, no external dependencies).
