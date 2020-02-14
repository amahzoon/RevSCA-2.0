Copyright (c) 2020 Group of Computer Architecture. All Rights Reserved.



# RevSCA-2.0

RevSCA-2.0 is an SCA-based formal verification tool that proves the correctness of integer multipliers. It combines the power of reverse engineering and local vanishing removal to verify extremely large and structurally complex multipliers. RevSCA-2.0 has been developed by Alireza Mahzoon, Daniel Große, and Rolf Drechsler. For more information visit [www.sca-verification.org/revsca](http://www.sca-verification.org/revsca) or contact revsca@sca-verification.org.

The older version of RevSCA is also available at [GitHub](https://github.com/amahzoon/revsca).

## How to use

```bash
./revsca <input> <output> [option]

     input:     Multiplier AIG file
     output:    Output file containing the verification data
     option:    -u ---> unsigned multiplier
                -s ---> signed multiplier
```

## RevSCA-2.0 features

* The implementation has been improved significantly, thus the tool is now much faster.
* It supports the verification of signed multipliers.
