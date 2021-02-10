# SetheumDinar Token Contract
The SetheumDinar (DNAR) ERC-20/BEP-20 token contract is created with the [OpenZeppelin Contracts Ethereum Package](https://github.com/OpenZeppelin/openzeppelin-contracts). 

It is deployed on the Ethereum Mainnet at [`0x91FC92fA9830e5FFdA31fB3401B80EE58e8166Fd`](https://etherscan.io/address/0x91fc92fa9830e5ffda31fb3401b80ee58e8166fd#code).

It is also deployed on the Ropsten Testnet at [`0xc176921d5379aCc47A47cE7717394abE5cAd4A89`](https://ropsten.etherscan.io/address/0xc176921d5379acc47a47ce7717394abe5cad4a89).

The token is an ERC20 token implementing the IERC20 interface.

## Installation

To begin with the project you need to install a usual NodeJS environment and yarn. You must also install the Open Zeppelin SDK CLI and the Ganache CLI:

```bash
$ npm install -g @openzeppelin/cli ganache-cli
```

After that, you can start fetching vendored dependencies:

```bash
$ npm install
```

To deploy the Injective Token to your development network, initialize your local Ganache instance:

```bash
$ ganache-cli --deterministic
```

Then in a separate Terminal tab, initialize the Open Zeppelin SDK project:
```bash
$ oz init
