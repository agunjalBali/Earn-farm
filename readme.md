Earn farm
=======

Earn farm is an Liquidity pool miner. where users provide liquidity by staking their crypto currencies (mDai) to the smart contract system running on the ethereum test net Rinkeby. Earn farm is powered by smart contracts using solidity on the eth blockchain. Truffle, ganache and Web3 is also used. 

The user stakes their crypto currency in the smart contract portal made using react. After staking their liquidity will be used to provide favorable bid-ask spreads to other users looking to exchange their tokens. The fees collected (2%) is distributed 50% to all the LP miners and 50% to users who have staked their LP tokens.

This is similar to a simpler version of [uniswap](https://uniswap.org/) 


steps to install and execute
=======


```javascript

npm install --g truffle@5.1.39
 
npm i

run ganche quickstart etherium

truffle compile

truffle migrate --reset

truffle console

mDai = await DaiToken.deployed()

mDai

web3.eth.getAccounts().then(function(acc){ accounts = acc })

accounts [1]

balance = await mDai.balanceOf(accounts [1])

balance.toString()

exit 

truffle test

npm run start

truffle exec scripts/issue-token.js
```
