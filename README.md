
<!-- Find and Replace All [repo_name] -->
<!-- Replace [product-screenshot] [product-url] -->
<!-- Other Badgets https://naereen.github.io/badges/ -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]



# Blockchain With Python
This repository contains a Python file named app.py which uses Python modules to create a temporary blockchain called PyChain. Using Streamlit, a web interface can be generated which takes (3) different inputs, sender information, receiver information and the amoutn being sent. Using the Streamlit application, you can generate several different block that are chained together using sha-256 hashing. You can also validate the blockchain by clicking "Validate Chain" in which each block is validated by comparing the previous-hash of the block to the data attribute in the new block that contains the previous hash. If they match, that block is validated and gets added to the blockchain.

---

## Technologies

This project leverages the following tools for financial analysis:

- Conda
- Python 3.7
- Pychain
- Streamlit
- VSCode
- Git Bash

---
## Streamlit Interface

The following screenshot below shows the validity of the blockchain, a drop-down menu in which you may choose which block you would like to view its data such as the hash, date created etc.

![Blockchain_Validity_and_Drop_Down_Menu](https://user-images.githubusercontent.com/96163075/166614798-4f28d302-d86e-4425-a223-21bcc4f73182.PNG)

---

## Contributors
David Lee Ping [Linkedin](https://www.linkedin.com/in/david-lee-ping/)

---
Other Acknowledgements
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/davidlp94/18-Blockchain-With-Python.svg?style=for-the-badge
[contributors-url]: https://github.com/davidlp94/18-Blockchain-With-Python/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/davidlp94/18-Blockchain-With-Python.svg?style=for-the-badge
[forks-url]: https://github.com/davidlp94/18-Blockchain-With-Python/network/members
[stars-shield]: https://img.shields.io/github/stars/davidlp94/18-Blockchain-With-Python.svg?style=for-the-badge
[stars-url]: https://github.com/davidlp94/18-Blockchain-With-Python/stargazers
[issues-shield]: https://img.shields.io/github/issues/davidlp94/18-Blockchain-With-Python/network/members?style=for-the-badge
[issues-url]: https://github.com/davidlp94/18-Blockchain-With-Python/issues
[license-url]: https://choosealicense.com/licenses/mit/#

---
## License

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
