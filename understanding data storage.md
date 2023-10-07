# Understanding data storage

## Bit

A `bit` is the most basic unit of information in computing and digital communications. The bit represents a logical state with one of two possible values.

![bit](https://media.gcflearnfree.org/content/5be310a59fcfff1378ff8923_11_07_2018/binary_bit.jpg)

## Byte

The `byte` is a unit of digital information that most commonly consists of eight bits. Historically, the byte was the number of bits used to encode a single character of text in a computer and for this reason it is the smallest addressable unit of memory in many computer architectures.

![byte](https://qph.cf2.quoracdn.net/main-qimg-6cb48afa501798231d3260bfa6cdf8cf)

## Negative numbers in binary representation

In order to represent a negative number in binary representation you need to follow 3 steps:

1. Convert the number to binary representation
2. Get the 1's complement of the binary number
3. Add `1` to the number

> The above step is equivalent to finding the 2's complement of the of a binary number.

## Character Set

To represent text digitally, each character needs to have its own unique bit-pattern. Bit-patterns are combinations of 1s and 0s used to represent data inside of a computer. The bit-pattern used for each character becomes a numeric character code.

A character can be any of the following:

- Letters (upper and lower case letters have separate codes)
- Punctuation (e.g. ? / | \ £ $)
- Numbers (0–9)
- Non-printing commands (e.g. Enter, Delete, F1)

For computers to be able to communicate and exchange text between each other efficiently, they must have an agreed standard that defines which character code is used for which character. A standardised collection of characters and the bit-patterns used to represent them is called a `character set`.

## ASCII representation

Computers can only understand numbers, so an ASCII code is the numerical representation of a character such as 'a' or '@' or an action of some sort. ASCII was developed a long time ago and now the non-printing characters are rarely used for their original purpose. Below is the ASCII character table and this includes descriptions of the first 32 non-printing characters. [ASCII representation](https://www.asciitable.com/)

## Unicode representation

One of the main issues with `ASCII` is that it is only able to represent up to `128 characters`, which means that it can only be used with the roman (English) alphabet. There are simply not enough bits available to represent all of the characters required to communicate internationally using other languages.

This is when Unicode comes in.

Unicode uses between 1 and 4 bytes to store each character, which means that its character set could potentially contain over 4 billion possible characters. It is backwards compatible with 7-bit ASCII too, so the first 127 characters are still exactly the same. It’s just that in Unicode, additional characters are represented as well.

Another advantage of Unicode is that it can represent far more symbols than `ASCII` can. For example, emoji, which are greatly changing how we communicate.
