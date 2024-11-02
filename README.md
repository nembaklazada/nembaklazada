const ChainAbstraction = require('chain-abstraction-sdk');

const tokenName = 'MyToken';
const tokenSymbol = 'MTK';
const tokenDecimals = 18;
const tokenTotalSupply = 1000000;

const token = ChainAbstraction.createToken(tokenName, tokenSymbol, tokenDecimals, tokenTotalSupply);

console.log(token);


simple code to create digital tokens on Chain Abstraction using Chain Abstraction SDK:
