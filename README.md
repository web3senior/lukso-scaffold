# Lukso Scaffold
Pure HTML and JS code can be used to deploy a smart contract on the Lukso blockchain by leveraging the UP browser extension 🆙

<a href="//lukso.network">![Lukso Badge](assets/badge-lukso.svg "Lukso")</a>

## Important
> On LUKSO, users currently get a free monthly quota of 20.000.000 GAS when creating a Universal Profile through the Universal Profile Browser Extension.

## Sample Contract & Bytecode
```
// SPDX-License-Identifier: MIT
pragma solidity 0.8.24;

contract Sample {
    function Hello() public pure returns (string memory) {
        return "Hello Lukso!";
    }
}
```

```
0x608060405234801561000f575f80fd5b506101688061001d5f395ff3fe608060405234801561000f575f80fd5b5060043610610029575f3560e01c8063bcdfe0d51461002d575b5f80fd5b61003561004b565b6040516100429190610112565b60405180910390f35b60606040518060400160405280600c81526020017f48656c6c6f204c756b736f210000000000000000000000000000000000000000815250905090565b5f81519050919050565b5f82825260208201905092915050565b5f5b838110156100bf5780820151818401526020810190506100a4565b5f8484015250505050565b5f601f19601f8301169050919050565b5f6100e482610088565b6100ee8185610092565b93506100fe8185602086016100a2565b610107816100ca565b840191505092915050565b5f6020820190508181035f83015261012a81846100da565b90509291505056fea2646970667358221220d1424793985e3f18e60a90ece02e7a464be30a65fbabc713e811c16d4d6d6ed264736f6c63430008180033
```

**What you need is the bytecode of your contract:**
## Remix IDE
<a href="//twitter.com/atenyun">![X Badge](/assets/remix.png "HardHat")</a>

## Hardhat
<a href="//twitter.com/atenyun">![X Badge](/assets/hardhat.png "HardHat")</a>


## How to run
To deploy a contract on Lukso, open "index.html" in your browser and use the Universal Profile extension to deploy the contract. 🚀

## Demo

### https://lukso-scaffold-contract.vercel.app

### Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

Distributed under the [MIT](https://choosealicense.com/licenses/mit/) License.

[Amir Rahimi](https://universallink.me/u/atenyun) - Fullstack blockchain developer