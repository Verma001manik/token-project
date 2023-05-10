# token-project
This is a simple solidity project done as a final assessment in the metacrafter's solidity beginner's course . 

# Description
This simple project was programmed in solidity language using Remix editor (https://remix.ethereum.org). In this project we have created a token of our own choice and it consist's of name,abbrevation and total supply and we also had 2 function's which are to mint the token and burn the token . 

```
function mint (address _address, uint _value) public{
    //the value gets added to the total supply and also it is added to the balances of the given address
        totalSupply += _value;
        balances[_address] += _value;
  ```
  * This function take's 2 parameter's address and value.
  * value is added to the totalSupply and also balances[_address]

# Authors 
Metacrafter Chris 
@metacraftersio

# License 
This project is licensed under MIT License
