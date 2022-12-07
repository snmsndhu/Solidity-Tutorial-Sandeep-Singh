# Loops in **Solidity** are same same as the other Programing Languages.

## **Solidity** supports for, while, and do while **Loops**.

If you have previous **Experience** in **Programing**, then it's pretty much same as other **Language**.

So, Let's dive into coding.

```solidity

//SPDX-Licence-Identifier: MIT

pragma solidity ^0.8.4;

contract Loops {
function loops () public {
    for(uint i = 0; i < 10; i++){
        if( i == 3 ) {
        continue;
        }
        if ( i == 5 ) {
        break;
        }
    }
}
}
```
