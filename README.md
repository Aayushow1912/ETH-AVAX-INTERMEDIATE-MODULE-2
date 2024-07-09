#Metamask Wallet Connection
# Steps to run the codebase 

$ npm install
$ npm start

navigate browser to localhost:3000

-----------------------------

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

# Structure of files in the codebase

src Folder -
    WalletCard.js - 
## In WalletCard.js you can find all these functions

connectWalletHand - For connecting the metamask wallet
AccoutChangedHand - Chainging account from metamask can cause this function to work
chainChangedHand - Chainging the chain network in the metamask can cause this function to work
getAccountBalance - Get the Balance of the token/coin in your metamask wallet. 

