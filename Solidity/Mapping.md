# Mapping

## Mapping in **Solidity** act like a **Hash-Tables**, where data is stored in **Key-Value** pair.

Let me give you some examples for better understanding.

```solidity
mapping(_key ==> _value) public mappingName;
```

1. Its pretty straight forword, we have to intilize Mapping with **mapping** keyword.
2. Afterthat we have to give in **Key** and **Value** to the mapping.
3. **Key** and **Value** can be any build-in-data type supported by the **Ethereum**.
4. Then all we have to do is give a **Mapping** name.

## Let me give you some more examples with Ethereum Supported KeyTypes.

```solidity
mapping(uint => uint) map;
mapping(address => uint) public address;
mapping(address => bool) public registeredAddress;
```

## We can Map from one Map to another, by just using **mapping**.

Let understand it by examples.

```solidity
mapping(unit => mapping(bool => Data[])) public data;
```

See you in next Seasion.
