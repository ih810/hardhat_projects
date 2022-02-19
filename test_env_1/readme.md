https://hardhat.org/tutorial/

install  
> $ mkdir hardhat-tutorial  
> $ cd hardhat-tutorial  
> $ npm init --yes  
> $ npm install --save-dev hardhat  
init hardhat  
> $ npx hardhat  
> $ Create an empty hardhat.config.js
Select the compiler version in the config file  
> $ npm install --save-dev @nomiclabs/hardhat-ethers ethers @nomiclabs/hardhat-waffle ethereum-waffle chai  

Place contract in a folder name "contracts"  
Compile project
> $ npx hardhat compile

Place test in a folder name "test"  
> $ npx hardhat test