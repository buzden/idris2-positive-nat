<!-- idris
module README

import Data.Nat1
-->

# Positive natural number `Nat1`

An Idris 2 library with a data type for strictly positive natural number

```idris
five : Nat1
five = 5

failing "Can't find an implementation"
  zero : Nat1
  zero = 0

values : List Nat1
values = [4, 2, 1, 9]

values' : List Nat1
values' = [4 .. 9]
```
