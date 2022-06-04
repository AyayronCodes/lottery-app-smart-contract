# lottery-app-smart-contract

2
Lottery application that allows wallets to join the lottery and manager to randomly pick a winner. </br>
3
Works with MetaMask. </br>
4
</br>
5

1. in lottery folder's deploy.js, update pneumonic phrase and endpoint (I went to infura.io for rinkeby endpoint)
   6
2. open terminal, 'npm install', then 'npm run deploy' to deploy contract
   7
3. console should display both the abi(array) and address of the contract (need to copy paste later)
   8
4. go to lottery-react folder, open terminal, 'npm install' for dependencies
   9
5. copy paste abi (array) and address (string) from step 2 into src/lottery.js
   10
6. 'npm run start'
