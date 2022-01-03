# decentralized-bank
<p> The smart contract accepts ether and erc-20 tokens deposit and sends it to the rinkeby compound smart contract to get interest on the deposit.<br>
Incase of erc-20 token deposit, it swaps the token to ether using the uniswap smart contract before sending to compound.<br>
The user can also withdraw the deposit + interest in either ether or any erc-20 token specified. Incase of erc-20 withdrawal, the ether from compound is swapped with uniswap before it can be withdrawn by the user..
