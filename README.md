# 🔑 Va1 ![](https://img.shields.io/apm/l/vim-mode)

![plot](./Screenshots/Va1_main.png)

## What is it?

_Va1_ is a simple character converter. It converts characters into nums, might be used in encryption protocols or as independent algorithm. It is a part of [_RedLibrary_](https://github.com/Red-company/RedLibrary).

## How to use?

Function prototypes:

```C
// Encryption.
const std::string Va1Encode(const std::string_view ToEnc);

// Decryption.
const std::string Va1Decode(const std::string_view ToDec);
```

## Tech notes:

* It also understands characters like '\n', '\\' and some others.
* It's not fast but it still useful.

## Example:

![plot](./Screenshots/Va1_enc.png)

![plot](./Screenshots/Va1_dec.png)

##
All material in this repository is in the public domain.
