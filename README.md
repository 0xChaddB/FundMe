# **Fund Me Project**  
A smart contract project for decentralized funding management.   
This project has been built while following along the Cyfrin Updraft Foundry courses,
---

## **🚀 Features**
- ✅ Fund a project with ETH.  
- ✅ Integrated Chainlink price feeds.  
- ✅ Single-owner with secure withdrawal control.  

---

## **📋 Table of Contents**
1. [Overview](#-overview)  
2. [Technologies Used](#-technologies-used)  
3. [Installation](#-installation)  
4. [Running Tests](#-running-tests)  
5. [Contributors](#-contributors)  
6. [License](#-license)  

---

## **🌟 Overview**
### **FundMe**
A contract that manages ETH contributions and supports secure withdrawals.
Key Functions:

- ``fund()``: Accept ETH contributions.
- ``withdraw()``: Allow the owner to withdraw all funds.
- ``cheaperWithdraw()``: Optimized withdrawal function.
- View functions for retrieving funder information and contract state.

### **PriceConverter (Library)**

Performs ETH/USD conversion using Chainlink price feeds.

Key Functions:

- ``getPrice()``: Fetches the current ETH/USD price.
- ``getConversionRate(uint256)``: Converts a given ETH amount to USD.

---

## **🛠️ Technologies Used**
- [Solidity](https://soliditylang.org/) - Primary language for smart contract development.  
- [Foundry](https://book.getfoundry.sh/) - Framework for testing and deployment.  
- [Chainlink](https://chain.link/) - Oracles for secure price feeds.  

---

## **📦 Installation**
### **Prerequisites**
1. Install [Foundry](https://book.getfoundry.sh/getting-started/installation.html).   

### **Steps**
1. Clone the repository:  
   ```
   git clone https://github.com/your-username/project-name.git
   cd project-name
   ```
2. Install dependencies:
```
forge install
```
Compile the smart contract:
```
forge build
```

## **🧪 Running Tests**

Using Foundry
 1. Configure your environment variables:

```
export SEPOLIA_RPC_URL="https://sepolia.infura.io/v3/your-api-key"
export PRIVATE_KEY="your-private-key"
```

## **🤝 Contributors**

0xChaddB - Security Researcher


## **📜 License**
This project is licensed under the MIT License. See the LICENSE file for more details.