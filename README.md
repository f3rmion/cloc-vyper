# Introduction

Line counter for Vyper code using [Count Lines of Code](https://github.com/AlDanial/cloc) (cloc).

# Setup

Install `cloc` according to instructions in their [repository](https://github.com/AlDanial/cloc).

# Application

Read in the Vyper custom cloc language definitions to count LOC of your smart contracts having the file extention `*.vy`.

```bash
> cloc --read-lang-def=vyper.txt src/tokens/ERC20.vy
       1 text file.
       1 unique file.
       0 files ignored.

github.com/AlDanial/cloc v 1.96  T=0.02 s (59.3 files/s, 44675.2 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Vyper                            1            117            420            216
-------------------------------------------------------------------------------
```
