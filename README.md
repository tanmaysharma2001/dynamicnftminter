# Dynamic_NFT_bot
<h3>This is a Telegram bot that allowes you to mint dynamic NFTs.</h3><h4>I have created this bot using Solidity, Infura, MongoDB, OpenZeppelin, Python and pyTelegramBotAPI.</h4>

<!-- <br/><br/>
<p align="center">
<img src="https://github.com/tasneem22/DynamicNFTMinterBot/blob/main/images/1.png" width="190" height="270">
<img src="https://github.com/tasneem22/DynamicNFTMinterBot/blob/main/images/2.png" width="190" height="270">
<img src="https://github.com/tasneem22/DynamicNFTMinterBot/blob/main/images/3.png" width="190" height="270">
</p><br>

<p align="center">
<img src="https://github.com/tasneem22/DynamicNFTMinterBot/blob/main/images/4.png" width="290" height="300">
<img src="https://github.com/tasneem22/DynamicNFTMinterBot/blob/main/images/5.png" width="290" height="300">
</p><br> -->

## Prerequisites
Please install or have installed the following:

- [Python](https://www.python.org/downloads/)
- [Telegram](https://telegram.org/)
- [Metamask](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjtl7Oi6N_4AhWei_0HHbjzDH4QjBB6BAgHEAE&url=https%3A%2F%2Fmetamask.io%2Fdownload%2F&usg=AOvVaw049ASZIf5umKu9KN8vjUeH)


## Installation
[Install virtualenv](https://virtualenv.pypa.io/en/latest/installation.html), if you haven't already. Here is a simple way to install venv.

```bash
python -m pip install --user virtualenv
python -m virtualenv --help
```
<br/>
Or, if that doesn't work, via pipx

```bash
pipx install virtualenv
virtualenv --help
```

Create a Virtual Environments and active venv
```bash
python3 -m virtualenv venv
cd venv/bin
source activate
```

<br/>After that you need install telebot, web3.py and ipfs that we're going to use it to store our metadata 
```bash
pip install web3
pip install eth-brownie
pip install ipfshttpclient
pip install pyTelegramBotAPI
```

# Usage
Run this command to initalize ipfs:
```bash
ipfs daemon 
export IPFS_FILE_URL = "File_url"
export IPFS_CONNECT_URL= "Connect_url"
```

<br>Deploy the smart contract using brownie:<br>
First clone this repository and then deploy the smart contract. I used Remix for compiling and deploying the contract. 

<br>Now you need to set your Api_key and web3_provider(Alchemy or Infura)<br>
Use @botFather to create your bot and get Api_key
```bash
export WEB3_PROVIDER= "Web3_provider"
export API_KEY= "Api_key"
```


<br>Finally use this command to run the bot.
```bash
python3 main.py
```
