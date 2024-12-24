# Haskell Head Function Error

This repository demonstrates a common runtime error in Haskell: using the `head` function on an empty list.  The `head` function retrieves the first element of a list; attempting to use it on an empty list results in a runtime exception.  The provided solution shows a safer way to handle this by using pattern matching or a safe function like `listToMaybe` from `Data.Maybe`.

## How to reproduce the error

1. Clone this repository.
2. Compile the `bug.hs` file using a Haskell compiler (e.g., GHC): `ghc bug.hs`
3. Run the compiled executable: `./bug`
4. Observe the runtime exception.