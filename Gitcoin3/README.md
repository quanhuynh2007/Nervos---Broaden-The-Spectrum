Gitcoin: 3) Issue A Smart Contract Call To The Deployed Smart Contract

https://gitcoin.co/issue/nervosnetwork/grants/4/100026210

1. A screenshot of the console output immediately after you have successfully issued a smart contract call.

![image](https://user-images.githubusercontent.com/29400517/128827460-f70ac5c8-5fa9-4f76-ad5a-9194b7668e37.png)


2. The transaction hash from the console output (in text format).

`0x5c80afa1b75c88bc03b7a59e25a2bb90b3102f2a75a6ad7616eb2f086c35302f`

3. The contract address that you called (in text format).

`0x2F72d9065ACf46cb33C3CFaBBe9E300969845abc`

4. The ABI for contract you made a call on (in text format).

```
[
    {
        "inputs": [],
        "stateMutability": "payable",
        "type": "constructor"
    },
    {
        "inputs": [
            {
                "internalType": "uint256",
                "name": "x",
                "type": "uint256"
            }
        ],
        "name": "set",
        "outputs": [],
        "stateMutability": "payable",
        "type": "function"
    },
    {
        "inputs": [],
        "name": "get",
        "outputs": [
            {
                "internalType": "uint256",
                "name": "",
                "type": "uint256"
            }
        ],
        "stateMutability": "view",
        "type": "function"
    }
]
```
