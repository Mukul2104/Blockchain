For our project, we require some files to be installed. We can check them in distribute.js file. Here it is mentioned that fs, big number, dot env , web3, Ethereumjs-tx is what we required to run the node JS application. They are installed with the help of below command.
npm i fs big-number dotenv web3 ethereumjs-tx
After installing this, we can run the node JS application. To begin with the process we need to some accounts initially. Metamask account, Infura account, Remix IDE and some source code editor like Visual Studio Code. Please note node should be installed in visual studio code. To check the version of node we can use command ‘node -v’.
After all the installation, go to Remix Ethereum IDE.
Steps to perform in Remix IDE:
•	Create a new workspace if not created before.
•	Create a new file and name it <name.sol>
•	Write your solidity program which will help to deploy the smart contract. 
•	Note: we need to give your name to contract in line 147. 
•	On line 167 give your name to token and and symbol as your initials. This info will be displayed when we distribute the tokens with the help of our node JS application.
•	After this we need to compile our code. On left side there is solidity compiler. Make sure to 	 select the compiler version which you have mentioned in your program start. Click on compile button.
•	If there is no error in your code then it is compiled successfully. You will get a green mark on the compiler button.
•	After compiling, we will deploy the contract using Deploy and run transactions option right below the solidity compiler. 
•	Make sure to select the environment of Injected web3. In account section make sure your main metamask account id is displayed. In contract, select your name of contract which you have mentioned above in step 4. Click on deploy. 
•	After deploying on contract, it will ask for your permission. Click on confirm.
•	You can view status of your contract in the terminal. You will get a green tick if the contract is successfully deployed. 
•	After successful deployment, we need to run the node JS application.

Steps to perform in Visual code or any source code editor which we are using:
•	Make sure you have installed package.json and node_module. These are required to run the application. To install them use the command <npm i>. 
•	Make sure to move these installed packages to your root directory where your distribute.js file is residing. 
•	Run the application that is distribute.js file. To run this file use command <node distribute.js>
•	After you run this command, you will see transactions happening. As we are transferring the tokens in 10 different accounts it will take some time to complete all the transactions. You can see the transactions in Etherscan. 
Steps to perform in Etherscan. 
•	Search with the contract id which you have created after deploying the smart contract. 
•	You can see your 10 transactions along with the contract creation entry.

