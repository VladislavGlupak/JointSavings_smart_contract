<!-- Find and Replace All [repo_name] -->
<!-- Replace [product-screenshot] [product-url] -->
<!-- Other Badgets https://naereen.github.io/badges/ -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]

# Fintech-Finder

Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. It is a simple app for learning purposes.

---

## Technologies

This project leverages the following tools for financial analysis:

- [Conda](https://docs.conda.io/en/latest/) - source package management system and environment management system.

- [Pandas](https://pandas.pydata.org) - Python library that’s designed specifically for data analysis.

- [Streamlit](https://streamlit.io) - Streamlit turns data scripts into shareable web apps.

- [Python](https://www.python.org) - is a programming language.

- [Ganache](https://trufflesuite.com/ganache/) - is a local blockchain.

Libraries:

```
import os
from dotenv import load_dotenv
from bip44 import Wallet
from eth_account import Account
from web3.gas_strategies.time_based import medium_gas_price_strategy
from web3 import Web3
```

Ganache network:
`w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))`

---

## How to run

1. Install Streamlit `pip install streamlit`

2. Clone the repository `git clone https://github.com/VladislavGlupak/Fintech-Finder.git`

3. Go to repository folder and run `streamlit run fintech_finder.py`

4. You will see simple FinTech Finder app that enables customers to send cryptocurrency payments to fintech professionals.

## Example of running

Step by step:

1. Select the perfon from the database, input amount of working hours and click send transaction.
   Before sendind, please confirm wallet address and amount of Eth.

![Screenshot](Images/menu.JPG)

In the middle user will see the personal information of the professionals.

![Screenshot](Images/info.JPG)

2. You can use `Ganache` for checking the transaction

Sender and receiver:

![Screenshot](Images/sender_receiver.JPG)

All transactions:

![Screenshot](Images/tx_list.JPG)

Transaction from Sender to Receiver:

![Screenshot](Images/tx.JPG)

---

## Contributors

Glupak Vladislav [Linkedin](https://www.linkedin.com/in/vladislav-glupak/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/VladislavGlupak/Blockchain-based-ledger-system.svg?style=for-the-badge
[contributors-url]: https://github.com/VladislavGlupak/Blockchain-based-ledger-system/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/VladislavGlupak/Blockchain-based-ledger-system.svg?style=for-the-badge
[forks-url]: https://github.com/VladislavGlupak/Blockchain-based-ledger-system/network/members
[stars-shield]: https://img.shields.io/github/stars/VladislavGlupakBlockchain-based-ledger-system.svg?style=for-the-badge
[stars-url]: https://github.com/VladislavGlupak/Blockchain-based-ledger-system/stargazers
[issues-shield]: https://img.shields.io/github/issues/VladislavGlupak/Blockchain-based-ledger-system/network/members?style=for-the-badge
[issues-url]: https://github.com/VladislavGlupak/Blockchain-based-ledger-system/issues

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
