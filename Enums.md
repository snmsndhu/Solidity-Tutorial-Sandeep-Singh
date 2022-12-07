# Enums are the predefined values in enumerated list.

## Enums are use to make a set of the property, that we want to give it to the integral constants.

Let's have a look on real life examples.

```solidiy

//SPDX-License-Identifier: MIT

pragma solidity ^0.8.4;

contract Enums {

    enum payment {
        Pending,
        Accepted,
        Rejected,
        Canceled
    }
}
```

After defining all the enums, we can use them in varibles.
