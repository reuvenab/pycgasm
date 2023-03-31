# pycgasm

## About

[`cgasm`](https://github.com/bnagy/cgasm) clone in Python. 

Full match only supported, cgasm has fuzzy match feature.


## Installation

You already had installed Python if you're here

Download pyCgasm.py script 


## Usage

What this VPCONFLICTD is used for ...?
```
host:~ reuvenab$ python .\pyCgasm.py VPCONFLICTD
                                                    Instruction Operand Encoding
     Op/En                Operand 1                      Operand 2                      Operand 3                  Operand 4
       FV               ModRM:reg (w)                  ModRM:r/m (r)                       NA                         NA

Description
Test each dword/qword element of the source operand (the second operand) for equality with all other elements in
the source operand closer to the least significant element. Each element's comparison results form a bit vector,
which is then zero extended and written to the destination according to the writemask.
EVEX.512 encoded version: The source operand is a ZMM register, a 512-bit memory location, or a 512-bit vector
broadcasted from a 32/64-bit memory location. The destination operand is a ZMM register, conditionally updated
using writemask k1.
EVEX.256 encoded version: The source operand is a YMM register, a 256-bit memory location, or a 256-bit vector
broadcasted from a 32/64-bit memory location. The destination operand is a YMM register, conditionally updated
using writemask k1.
EVEX.128 encoded version: The source operand is a XMM register, a 128-bit memory location, or a 128-bit vector
broadcasted from a 32/64-bit memory location. The destination operand is a XMM register, conditionally updated
using writemask k1.
EVEX.vvvv is reserved and must be 1111b otherwise instructions will #UD.
```


## License

GPLv2, see LICENSE.md for details

## TODO

Nothing meanwhile. 

## Contributing

Fork it
