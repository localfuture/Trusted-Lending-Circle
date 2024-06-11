# Trusted Lending Circle
To promote financial inclusion to wide range of people, by including greater transparency, enhanced security, improved
traceability, increased efficiency and speed of transactions, and reduced costs.
To implement a rotating savings and credit association system using Ethereum blockchain. The basic principle is that
each member of the group makes a standard contribution to a common fund once per time period. Then each period the total
contributions are disbursed to a single member of the group.
Trusted Lending Circles are used in almost every corner of the world. In India, they are known as chits. In Mexico,
they’re called cundinas. They’re also known as hui (China), susu (West Africa and the Caribbean),
Game’ya (the Middle East), pandeiros (Brazil), tanomosiko (Japan), and tandas (Latin America).
A blockchain based financial platform can reduce the high fees, low liquidity, accounting records, potential fraud from
organizers and automates an existing concept already proven in communites worldwide.
Trusted Lending circles in past have helped humans to get finacial support. In the future more autonomous machines will
have wallet during industrialisation 4.0. So if we implement such a system in blockchain it will be helpful for the
autonomous machines to borrow and lend by minimizing human intervention and provide financial stability to the autonomous
machines with are connected to the blockchain.
Trusted Lending Circle Project Submission Template
## Setting Up:
# Step 1: Download the repostory using the command:
Git Clone "https://gitlab.com/KeralaBlockchainAcademy/sms-the_project_submission_template.git"
# Step 2: Install the dependecies using the command:
npm Install
# Step 3: Use the following command to compile smart contract:
cd Ethereum
truffle compile
# Step 4: Use one of the following commands to connect to the private or public chain:
Private chain:
geth --identity "tlc" --networkid "5777" --datadir "data" --http --http.port "8545" --unlock "0x416B38D4E430c4f9EBc0853962544b2076B7CD30" --http.corsdomain "*" --http.api "miner,eth,net,web3,personal" --allow-insecure-unlock --nodiscover --ipcpath "~/.ethereum/geth.ipc"
start mining using the following command, before doing any transaction:
miner.start()
Password: Enter Key
# Step 5: Use the following command to deploy the smart contract to the connected chain:
cd Ethereum truffle migrate
# Step 6: Run the dapp using the command
cd ..
npm start
Execution Flow:
# Step 7: Go http://localhost:3000/, Provide the student details and click Set Student
sign up with wallet address and login
as foreman and create new fund
sign up with wallet address and login
as subscriber and join in new fund
END
