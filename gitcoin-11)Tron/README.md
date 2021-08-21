# Use A Tron Wallet To Execute A Smart Contract Call (Gitcoin-11)

## 📷 A screenshot of the accounts you created

<img src="https://github.com/taylorkhalifa/nervos-gitcoin-hackathon/blob/master/gitcoin-11)Tron/address-list.png" />

## 🔗 A link to the Layer 1 address you funded on the Testnet Explorer

<a href="https://explorer.nervos.org/aggron/address/ckt1qyqr5j684s7klczgqdqmf8f98lp0azgc38pqxtje7f">Layer1 address explorer link </a>

## 📷 A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2

<img src="https://github.com/taylorkhalifa/nervos-gitcoin-hackathon/blob/master/gitcoin-11)Tron/deposit-tron.png" />

## 📷 A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

<img src="https://github.com/taylorkhalifa/nervos-gitcoin-hackathon/blob/master/gitcoin-11)Tron/call.png" />

## 📓 The transaction hash of the "Contract call" from the console output

```bash
0x108cb3dfffddc8b8789033d0ffd95bbe9ada9e8da20d0dc11e389175d62a89cf
```

## 📓 The contract address that you called

```bash
0xd18a9E9810367AAbE6696901B6B714909A63965E
```

## 📓 The ABI for contract you made a call on

```javascript
[
    {
      "inputs": [],
      "stateMutability": "nonpayable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "movies",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "name",
          "type": "string"
        },
        {
          "internalType": "uint256",
          "name": "rate",
          "type": "uint256"
        },
        {
          "internalType": "uint256",
          "name": "totalRate",
          "type": "uint256"
        },
        {
          "internalType": "uint256",
          "name": "rateSize",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "totalMovie",
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
          "name": "_name",
          "type": "string"
        },
        {
          "internalType": "uint256",
          "name": "_rate",
          "type": "uint256"
        }
      ],
      "name": "createMovie",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_fullName",
          "type": "string"
        }
      ],
      "name": "getGeneratedMovie",
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
          "internalType": "uint256",
          "name": "_movieId",
          "type": "uint256"
        },
        {
          "internalType": "uint256",
          "name": "_rate",
          "type": "uint256"
        }
      ],
      "name": "rateMovie",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    }
  ]

```

## 📓 Your Tron address

```bash
TSDiSshMjjJQKhpHhVeyoRmsqRKbsFnWnA
```

