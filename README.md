## Hi there 👋

# 👾 Welcome to the Blockchain Lab of **Codebestia** 🛸

🚀 *Strap in, because we’re about to launch into the decentralized stratosphere!* 🌌

👨‍💻 I’m a blockchain wizard by day, and a Nyctophile by night. 
My quest? To push the boundaries of cryptography, decentralization, and take what belongs to caesar 🙃.

```solidity
pragma solidity ^0.8.19;

contract Profile {
    
    // Developer Info
    string public developerName = "Codebestia";
    string public role = "First Principle Engineer 👨‍💻 ";
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
        role = "Blockchain Developer ⚡ | Researcher 👑 | Crypto Adventurer 🏞️";
        currentQuest = "Building the future of decentralized applications 🌍";
        slogan = "Just do it";
    }

    // Function to get my skills (like a public getter function but cooler)
    function getTechStack() public view returns (string[] memory) {
        return techStack;
    }


    // Function to get my social links (contact me, it would be an adventure )
    function getContact() public view returns (string memory) {
        return (email);
    }

    // Function to describe my current quest
    function getCurrentQuest() public view returns (string memory) {
        return currentQuest;
    }
    
    // Function to display my drive
    function getSlogan() public view returns (string memory) {
        return slogan;
    }

    // Fallback function for fun
    fallback() external payable {
        revert("You've interacted with my profile. Your fund security is my priority 😎?");
    }
}
```

## <img src="https://user-images.githubusercontent.com/74038190/216122065-2f028bae-25d6-4a3c-bc9f-175394ed5011.png" alt="Graph" width="30" /> GitHub Analytics

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=codebestia&show=reviews,prs_merged,prs_merged_percentage&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=codebestia&theme=tokyonight&hide_border=true&layout=compact" />

</div>

## 🏆 GitHub Achievements

<div align="center">
  
[![trophy](https://github-profile-trophy.vercel.app/?username=codebestia&theme=tokyonight&no-frame=true&column=7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

### 🎯 Coding Quote of the Day
[![Readme Quotes](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)](https://github.com/piyushsuthar/github-readme-quotes)


