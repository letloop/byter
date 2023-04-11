# `(import (letloop byter))`

Export two procedures that pack lexicographically Scheme types.

### `(byter-pack . args)` → `bytevector?`

### `(byter-unpack bytevector)`

### `(byter-next-prefix bytervector)` → `bytevector?`

Returns the first bigger bytevector that is not prefix of `BYTEVECTOR`.
