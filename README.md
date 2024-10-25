# Crowd funding
## Team Members

Uditi Sinha - 16010121194

Kedar Shidhaye - 16010121187
### Project features 

- [x] User can start a fundraising.
- [x] Anyone can contribute.
- [x] End project if targeted contribution amount reached.
- [x] Expire project if targeted amount not fulfills between deadline.
- [x] Contributors can withdraw contributed amount if project expire.
- [x] Owner need to request contributors for withdraw amount.
- [x] Owner can withdraw amount if 50% contributors agree.
- [x] Connect with waller.


### Tech stack & packages used 

| package                                                             | explain                                                               |
| ------------------------------------------------------------------- | --------------------------------------------------------------------- |
| [Next.js](https://nextjs.org/docs/getting-started)                  | For building frontend                                                 |
| [solidity](https://docs.soliditylang.org/en/v0.8.13/)               | For writting smart contracts                                          |
| [tailwind css](https://tailwindcss.com/docs/installation)           | For building design                                                   |       
| [ether.js](https://docs.ethers.io/v5/)                              | Web3 client (contract testing ).                                      |
| [web3.js](https://www.npmjs.com/package/web3)                       | Web3 client (Frontend Next.js).                                       |
| [Chai](https://www.npmjs.com/package/chai)                          | javascript testing framework.                                         |
| [react-toastify](https://www.npmjs.com/package/react-toastify)      | For Notification.                                                     |   
| [hardhat](https://www.npmjs.com/package/hardhat)                    | Ethereum development environment.                                     | 
| [Redux](https://www.npmjs.com/package/hardhat)                      | For managing and centralizing application state.                      |   


----------------

### How to run :

- Run hardhat node
    ```
    npx hardhat node
    ```
- Deploy contract in local hardhat node
    ```
    npx hardhat run scripts/deploy.js --network localhost
    ```
- Run Next.js frontend
    ```
    cd client
    npm run dev
    ```
- Connect account to  website