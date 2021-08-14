# Random Movie Generator from User Name (Gitcoin-7)

## 📷 Screenshots && Video
- <a href="https://youtu.be/iO081W0vut0"> GO TO PROJECT VIDEO </a>
<img src="https://github.com/taylorkhalifa/nervos-gitcoin-hackathon/blob/master/gitcoin-7)%20Porting%20Dapp/movie.png"/>
<hr/>
<img src="https://github.com/taylorkhalifa/nervos-gitcoin-hackathon/blob/master/gitcoin-7)%20Porting%20Dapp/movie2.png"/>

## 🔗 Link to the GitHub Repo
- <a href="https://github.com/taylorkhalifa/nervos-random-movie-task7"> GO TO GITHUB REPO </a>

## 📓 Deployed Contract --->Transaction hash, contract adress,and ABI

Transaction Hash: ```0xab589887dc479049553fe3643854031f5c3230f86aef91047339172ffdc7083a```

Deployed contract address: ```0xd18a9E9810367AAbE6696901B6B714909A63965E```

ABI:

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
