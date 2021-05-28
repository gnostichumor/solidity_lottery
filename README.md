-- This is a Smart Contract template for a simple lottery system --
-- This contract was built from the Udemy class: https://www.udemy.com/share/1013FsBkoddl9VQng=/ --
-- I highly recommend this class for anyone getting started in Blockchain development! --

To run you will need to have a MetaMask wallet and an Infura.io account.

--Setup and Deploy--

1. Run npm install.
2. Set credentials in 'deploy.js'.
3. Run node deploy.js in terminal.
4. Lottery.test.js can be used to test contract functionality.
5. To test Lottery contract in a local React app see project:

--METAMASK--

1. It is advised that you create a new Chrome/Brave profile and setup a Metamask account specifically for development and testing. DO NOT ENTER SEEDPHRASES CONNECTED TO ACCOUNTS WITH ACTUAL ETHER IN THEM.
2. Install and setup Metamask here: https://metamask.io/
3. Request some Rinkerby Ether from the faucet here: https://faucet.rinkeby.io/
4. Enter your Metamask Seed Phrase in the 'deploy.js' script under newHDWalletProvider()

--Infura--

1. Create an Infura account here: https://infura.io/
2. Create a new project and choose the Rinkerby endpoint.
3. Enter your Rinkerby endpoint in the 'deploy.js' script under newHDWalletProvider()
