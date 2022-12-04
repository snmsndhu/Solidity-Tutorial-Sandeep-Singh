#Today We are going go discuse about the ERC20 tokens.
##Ether gives us the power to generate our own cryptocurrency with just few line of code.

###SO lets Begin with the code.

```solidity
//SPDX-Licence-Identifier: MIT
pragma solidty ^0.8.4;

import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/ERC20.sol";


contract Token is ERC20 {
constructor(string memory _name, string memory _symbol) ERC20 (token, TK){
_mint(msg.sender, 1000);
}
}
```

Let me Explain it to you
In First two line of the code we just defined the licence provide and the solidty version, which is universal, which we have to set for all the contracts.
After that, we are importing the ERC20 token functions from the OpenZeppenlin,
which will provide us the InBuild Functionality for our Token.

After defining the all the initial points of our smart contract, we are going to start working on our final part, which is just the three lines of code.
First of all, we are initializing our Contract and giving it a name Token and in same line we are mentioning, it is ERC20 token.
In second line we are defing properties of our smart contract, by using Constructor and giving it to properties in the string \_name and \_symbol, which we can use to give a name and the symbol to our ERC20 token.
\_mint is inBuild function from the solidity, which is mint the token to msg.sender(who is using that mint function), 10 \* 10 \*\* 18 is used here for the floating numbers.
