## Gitcoin: 11) Use A Tron Wallet To Execute A Smart Contract Call


### 1- A screenshot of the accounts you created (account list)

<img src="https://github.com/buketmizrak/gitcoin-nervos-hackathon/blob/master/task%20-%2011/accs.png" />

### 2- A link to the Layer 1 address you funded on the Testnet Explorer

- <a href="https://explorer.nervos.org/aggron/address/ckt1qyqgd5uuhluxfeepv0v9agfxnkztkv2xhtxsrf3nxx"> Explorer Link </a>

### 3- A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2

<img src="https://github.com/buketmizrak/gitcoin-nervos-hackathon/blob/master/task%20-%2011/deposit.png" />

### 4- A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

<img src="https://github.com/buketmizrak/gitcoin-nervos-hackathon/blob/master/task%20-%2011/contra.png" />

### 5- The transaction hash of the "Contract call" from the console output

```bash
0xc6e9a6b52b2205e6dfc425e678d2c3594e8b9759f55c51529dc764110c334e83
```

### 6- The contract address that you called

```bash
0x30d04e8a5f054e0765EC1E7447c2e783dF14Ad28
```


### 7- The ABI for contract you made a call on

```javascript
[
    {
      "inputs": [],
      "stateMutability": "nonpayable",
      "type": "constructor"
    },
    {
      "anonymous": false,
      "inputs": [
        {
          "indexed": false,
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "indexed": false,
          "internalType": "string",
          "name": "text",
          "type": "string"
        }
      ],
      "name": "CodeCreated",
      "type": "event"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "codes",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "text",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "totalCodes",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_text",
          "type": "string"
        }
      ],
      "name": "createCodeSnippet",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    }
  ]

```


### 8- Your Tron address

```bash
TXtqSwqAXWF9Ay9frAyiiZZqf8QimbMN8n
```

