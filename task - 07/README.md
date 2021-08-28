## Gitcoin: 7) Port An Existing Ethereum DApp To Polyjuice

### 1- Screenshots or video of your application running on Godwoken

### - React Code Snippets DApp
<hr/>
You can share react code snippets to the Nervos Network and see them in a good fashion

- Check out <a href="https://youtu.be/xleyD5SqMKc"> VIDEO </a> to see how DApp works.

<img src="https://github.com/buketmizrak/gitcoin-nervos-hackathon/blob/master/task%20-%2007/dapp.png" />

### 2- Link to the GitHub repository

- <a href="https://github.com/buketmizrak/Nervos-Code-Snippets-Dapp"> GITHUB REPO LINK </a>

### 3- Transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract

Transaction hash: ```0x77f470a3742bd66aa279fb4d63a074bd04277d794e485dd692492d20a46e50b3 ```

Contract Address: ``` 0x30d04e8a5f054e0765EC1E7447c2e783dF14Ad28 ```

ABI:

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
