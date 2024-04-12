## Surya install

Pre-requisites:
```
NodeJS
NPM
```
Install Surya using npm:
```
npm install -g surya
```
Navigate to the directory where your solidity contracts are written & execute the following commands:

  - Parse your smart contract (create a tree like structure)
    ```
    surya parse mycontract.sol
    ```
   ![image](https://github.com/binary-lover/Blokchain-notes/assets/95335243/cedc8ee5-d93d-4909-a4f7-cb01d360d1b9)


  - Flatten:
    ```
    surya flatten mycontract.sol
    ```
  - Describe (give a concise summary)
    ```
    surya describe mycontract.sol
    ```
   ![image](https://github.com/binary-lover/Blokchain-notes/assets/95335243/35f2b660-3b1e-471c-bf0d-15a838fd548b)
