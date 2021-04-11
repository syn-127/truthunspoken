# truthunspoken

*Current version: 1.3.5*

**Truth Unspoken** is a minimalist, open source online [pastebin](https://en.wikipedia.org/wiki/Pastebin)
where the server has zero knowledge of pasted data.

Data is encrypted and decrypted in the browser using 256bit AES in [Galois Counter mode](https://en.wikipedia.org/wiki/Galois/Counter_Mode).

This is a fork of ZeroBin, originally developed by
[Sébastien Sauvage](https://github.com/sebsauvage/ZeroBin). ZeroBin was refactored
to allow easier and cleaner extensions. Truth Unspoken has many more features than the
original ZeroBin. It is, however, still fully compatible to the original ZeroBin 0.19
data storage scheme. Therefore, such installations can be upgraded to PrivateBin
without losing any data.

This also forks : Private Bin https://github.com/PrivateBin/PrivateBin/releases/latest

## What Truth Unspoken provides

+ As a server administrator you don't have to worry if your users post content
  that is considered illegal in your country. You have no knowledge of any
  of the pastes content. If requested or enforced, you can delete any paste from
  your system.

+ Pastebin-like system to store text documents, code samples, etc.

+ Encryption of data sent to server.

+ Possibility to set a password which is required to read the paste. It further
  protects a paste and prevents people stumbling upon your paste's link
  from being able to read it without the password.
