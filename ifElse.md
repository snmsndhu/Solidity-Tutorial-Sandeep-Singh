# If/Else in **Solidity** are same same as the other Programing Languages.

If you have previous **Experience** in **Programing**, then it's pretty much same as other **Language**.

So, Let's dive into coding.

```solidity
//SPDX-Licence-Identifier: MIT

pragma solidity ^0.8.4;

contract IfElse {
    function IfElse(uint x) public pure returns (uint) {
        if(i < 5){
            return 0;
        }else if (i < 10){
            return 1;
        } else {
            return 2;
        }
    }
}
```

# We can implement this with Shorter Code.

Lets Check it out.

```solidity
    function ternary(uint x) public pure returns (uint) {
        return x < 5 ? 1 : 2;
    }
```

This **IfElse** Statement is way more shorter than the upper statment. Let me Explain it.

**Here** if x is less than 5 it will return 1, otherwise it will return 2. **?** is called **Ternary**
