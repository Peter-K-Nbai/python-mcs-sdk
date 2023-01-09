# python-mcs-sdk

[![Made by FilSwan](https://img.shields.io/badge/made%20by-FilSwan-green.svg)](https://www.filswan.com/)
[![Chat on discord](https://img.shields.io/badge/join%20-discord-brightgreen.svg)](https://discord.com/invite/KKGhy8ZqzK)

# Table of Contents <!-- omit in toc -->

- [Introduction](#introduction)
  - [For Onchain Storage](#onchain)
  - [For Buckets Storage](#buckets)
  
- [Getting Started](#started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Examples](#examples)
  - [Documentation](#documentation)
- [Contributing](#contributing)

# ℹ️ [Introduction](#introduction)

A python software development kit for the Multi-Chain Storage (MCS) https://www.multichain.storage/ service. It provides a convenient interface for working with the MCS API. This SDK has the following functionalities:

### ℹ️ [For Onchain Storage](#onchain)

---

- **POST**    Upload file to Filswan IPFS gateway
- **POST**    Make payment to swan filecoin storage gateway
- **POST**    Mint asset as NFT
- **GET**     List of files uploaded
- **GET**     Files by cid
- **GET**     Status from filecoin

### ℹ️ [For Buckets Storage](#buckets)

---

* **POST** Create a bucket
* **POST** Create a folder
* **POST** Upload File to the bucket
* **POST** Rename bucket
* **GET** Delete bucket
* **GET** Bucket List
* **GET** File List
* **GET** File information
* **GET** Delete File

### 🆕 [Getting Started](#started)

---

* [**Prerequisites**](#prerequisites)

  * [web3](https://pypi.org/project/web3/) - web3 python package to process contract 

  - Polygon Mainnet Wallet - [Metamask Tutorial](https://docs.filswan.com/getting-started/beginner-walkthrough/public-testnet/setup-metamask)

  - Polygon Mainnet RPC endpoint - https://polygon-rpc.com (USDC and Matic are required if you want to make payment.)

* ### **[Installation](#installation)**

  1. Method 1. Pip install (Recommended):

      Install python SDK using pip https://pypi.org/project/python-mcs-sdk/

     ```
     pip install python-mcs-sdk
     ```

  2. Method 2. Build from source

     Install python SDK from GitHub (checkout to the main branch for main net support) and install requirements using pip:

     ```
     git clone https://github.com/filswan/python-mcs-sdk.git
     git checkout main
     pip install -r requirements.txt
     ```

### 👨‍💻 [Examples](#examples)

---

Here is the demo to get you started; you can get more information in the [documentation.](#https://docs.filswan.com/multi-chain-storage/developer-quickstart/sdk)

1. Set Up Wallet Information

   1. Create a .env file that includes the following content.

      ```
      private_key="<PRIVATE_KEY>"
      rpc_endpoint="<RPC_ENDPOINT>"
      
      api_key="<API_KEY>"
      access_token="<ACCESS_TOKEN>"
      ```

      > The "rpc_endpoint" is the one mentioned above
      > "Private_key" will be obtained from the wallet
      > The "api_key", and "access_token" can be generated from the Setting page in the [multichain.storage](#https://www.multichain.storage/) page

      b. Install dotenv

      ​	`pip install python-dotenv`

2. Login to MCS

   ```
   
   ```

   **For Onchain Storage** 

   ---

   * Upload File to Onchain storage

     ```
     
     ```

   * Get file information

     ``` 

   **For Bucket Storage**

   ---

   * Create a bucket

     ```
     
     ```

   * Upload a file to the bucket

     ```
     ```

   * Get file list

     ```
     
     ```

   * Get Bucket list

     ``` 

   * Get file & folder list.

     ```
     
     ```

   For more examples, please see the [SDK documentation.](https://docs.filswan.com/multi-chain-storage/developer-quickstart/sdk)

# Contributing

Feel free to join in and discuss. Suggestions are welcome! [Open an issue](https://github.com/filswan/python-mcs-sdk/issues) or [Join the Discord](https://discord.com/invite/KKGhy8ZqzK)!

## Sponsors

Filecoin Foundation sponsors this project

[Flink SDK - A data provider offers Chainlink Oracle service for Filecoin Network ](https://github.com/filecoin-project/devgrants/issues/463)

<img src="https://github.com/filswan/flink/blob/main/filecoin.png" width="200">
