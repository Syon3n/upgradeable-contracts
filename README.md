# upgradeable-contracts

## Step1: Create a Upgrade Project
#### Create a folder of your choice and type the following command.
```
mkdir [NAME OF YOUR PROJECT]
cd [NAME OF YOUR PROJECT]

npm init -y
npm install dotenv
npm install --save-dev @openzeppelin/hardhat-upgrades
npm install --save-dev @nomiclabs/hardhat-ethers ethers @nomiclabs/hardhat-waffle ethereum-waffle chai
npx hardhat
```

#### Answer some of the following questions
```
What do you want to do?
 - Select "Create an empty hardhat.comfig.js"
```
Then you will see ```Config file created```.

#### Then, add the following code to the hardhat.config.js file
```
require("@nomiclabs/hardhat-waffle");
require("@nomiclabs/hardhat-ethers");
require("@openzeppelin/hardhat-upgrades");
```