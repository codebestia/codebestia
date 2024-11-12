## Hi there 👋

# 👾 Welcome to the Blockchain Lab of **Codebestia** 🛸

🚀 *Strap in, because we’re about to launch into the decentralized stratosphere!* 🌌

👨‍💻 I’m a blockchain wizard by day, and a mad scientist by night. 
My quest? To push the boundaries of cryptography, decentralization, and *maybe* a few digital dragons along the way. 🐉

```solidity
pragma solidity ^0.8.19;

contract Profile {
    
    // Developer Info
    string public developerName = "Codebestia";
    string public role = "Blockchain Wizard 👨‍💻 ";
    string public currentQuest = "Exploring the decentralized multiverse 🚀";
    string public slogan = "Decentralized everything. Centralized nothing. 🛸";
    
    // Skills & Tech Stack
    string[] public techStack = [
        "Solidity 🛠️",
        "Rust 🦀",
        "Web3.js 🌐",
        "Ethers.js ⚡",
        "Brownie 🍲",
        "NFTs & DeFi 👑",
    ];
    
    // Contact Details (like a smart contract, but for your social life)
    string public email = "codebestia@gmail.com";
    
    // Constructor to initialize the Profile
    constructor() {
        developerName = "Codebestia"; // You're awesome, no need to change this!
        role = "Blockchain Developer ⚡ | Meme King 👑 | Crypto Adventurer 🏞️";
        currentQuest = "Building the future of decentralized applications 🌍";
        slogan = "In crypto, we trust... and maybe in a little bit of code too. 🖥️";
    }

    // Function to get my skills (like a public getter function but cooler)
    function getTechStack() public view returns (string[] memory) {
        return techStack;
    }


    // Function to get my social links (contact me if you dare 😎)
    function getContact() public view returns (string memory, string memory, string memory, string memory) {
        return (twitter, linkedin, email, discord);
    }

    // Function to describe my current quest
    function getCurrentQuest() public view returns (string memory) {
        return currentQuest;
    }
    
    // Function to display the blockchain future we're building (spoiler alert: it's decentralized)
    function getSlogan() public view returns (string memory) {
        return slogan;
    }

    // Fallback function for fun
    fallback() external payable {
        revert("You've interacted with my profile. Your fund security are my priority 😎?");
    }
}
```
