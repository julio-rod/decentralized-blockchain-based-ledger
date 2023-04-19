# Decentralized Blockchain Based Ledger
### This repository is for educational purposes only! 
This web interface, enables partners to perform financial transactions (money transfers between senders and receivers) and verify the data's integrity within the ledger.
# Features
- Create and store financial transaction records in a secure, decentralized blockchain ledger
- User-friendly web interface for creating and validating transactions
- Proof of Work consensus algorithm for mining new blocks
- Blockchain validation to ensure data integrity
# Installation and Setup
1. Clone this repository to your local machine.
bash

Copy code
git clone https://github.com/yourusername/yourrepository.git

2. Navigate to the project directory.
bash

Copy code
cd yourrepository
	
3. Install the required Python packages.

Copy code
pip install -r requirements.txt
	
4.	Run the Streamlit application.
arduino

Copy code
streamlit run pychain.py
	
5.	Open the Streamlit application in your browser using the URL provided in the terminal.
# Usage 
1. Use the Streamlit sidebar to adjust the block difficulty as needed.
2. Enter sender, receiver, and amount information for the financial transaction.
3. Click the "Add Block" button to mine a new block with the transaction record.
4. Repeat steps 2-3 to add multiple blocks to the ledger.
5. Use the drop-down menue to inspect the individual blocks in the chain.
6. Click the "Validate Chain" button to check the integrity of the blockchain.
# Technologies
- Python
- Streamlit
- Dataclasses
- Hahlib
