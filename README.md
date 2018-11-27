# usc
usc erc20 contract
Our contract provide following funcions:
1.totalSupply ：total number of tokens in existence 
2.transfer(address _to, uint256 _value)  ：transfer token for a specified address
3.balanceOf(address _owner)：Gets the balance of the specified address
4.transferFrom(address _from, address _to, uint256 _value) ： Transfer tokens from one address to another
5.approve(address _spender, uint256 _value)：Approve the passed address to spend the specified amount of tokens on behalf of msg.sender allowance(address _owner, address _spender) ：Function to check the amount of tokens that an owner allowed to a spender
6.increaseApproval(address _spender, uint _addedValue) ：Increase the amount of tokens that an owner allowed to a spender
7.decreaseApproval(address _spender, uint _subtractedValue) ：Decrease the amount of tokens that an owner allowed to a spender
8.mintToken( uint256 _value)：Mint the amount of tokens that only contract owner 
