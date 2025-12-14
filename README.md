<div align="center">

<!-- Animated Header -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&multiline=true&repeat=false&width=600&height=100&lines=Hey+%F0%9F%91%8B+I'm+Alfred;Blockchain+Engineer+%7C+DeFi+Builder)](https://git.io/typing-svg)

<img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%">

</div>

---

## 🧑‍💻 About Me

```solidity
// SPDX-License-Identifier: MIT
pragma solidity 0.8.31;

/**
 * @title Alfred
 * @author blablalf
 * @notice Blockchain Engineer | DeFi Builder
 * @dev Currently building the future of tokenized funds
 */
contract Alfred {
    /// @notice Core identity
    string public constant NAME = "Alfred";
    string public constant PSEUDO = "blablalf";
    string public constant LOCATION = "Switzerland 🇨🇭";


    /// @notice Deploys Alfred to the blockchain
    constructor() {
        primaryRole = Role({
            position: "Backend Engineer",
            company: "RA2Tech",
            focus: "Building DeFi Protocols"
        });

        founderRole = Role({
            position: "CTO & Co-Founder",
            company: "T3tris",
            focus: "EVM Tokenized Funds Protocol"
        });

        currentFocus = "Building T3tris - EVM Tokenized Funds Protocol";

        passions[0] = Passion.DeFi;
        passions[1] = Passion.SmartContracts;
        passions[2] = Passion.YieldFarming;
        passions[3] = Passion.Trading;
    }

    // ═══════════════════ The Boring Stuff™ ═══════════════════

    /// @notice Professional roles
    struct Role {
        string position;
        string company;
        string focus;
    }
    
    /// @notice Areas of expertise
    enum Passion {
        DeFi,
        SmartContracts,
        YieldFarming,
        Trading
    }

    /// @notice Current focus project
    string public currentFocus;

    /// @notice All passions mapped by index
    mapping(uint256 => Passion) public passions;

    /// @notice Professional roles
    Role public primaryRole;
    Role public founderRole;

    /// @notice Emitted when focus changes
    /// @param oldFocus The previous focus
    /// @param newFocus The new focus
    event FocusUpdated(string oldFocus, string newFocus);

    /// @notice Returns current focus area
    /// @return The current project being built
    function getCurrentFocus() external view returns (string memory) {
        return currentFocus;
    }

    /// @notice Returns all professional roles
    /// @return primary The main employment role
    /// @return founder The startup founder role
    function getRoles() external view returns (Role memory primary, Role memory founder) {
        return (primaryRole, founderRole);
    }
}
```

<div align="center">

### 🏢 Where I Build

| Role | Company | Focus |
|:----:|:-------:|:-----:|
| **Backend Engineer** | [RA2Tech](https://ra2tech.com) 🇨🇭 | Building DeFi Protocols |
| **CTO & Co-Founder** | [T3tris](https://t3tris.io) 🇫🇷 | EVM Tokenized Funds |

</div>

---

## ⚡ Tech Stack

<div align="center">

### Languages
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)

### Blockchain & Web3
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-1C1C1C?style=for-the-badge&logo=foundry&logoColor=white)
![Hardhat](https://img.shields.io/badge/Hardhat-FFF100?style=for-the-badge&logo=hardhat&logoColor=black)

### Frameworks & Tools
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Security & Testing
![Medusa](https://img.shields.io/badge/Medusa-FF6B6B?style=for-the-badge&logoColor=white)
![Soldeer](https://img.shields.io/badge/Soldeer-7C3AED?style=for-the-badge&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=blablalf&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6366F1&icon_color=6366F1&text_color=C9D1D9" width="49%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=blablalf&theme=tokyonight&hide_border=true&background=0D1117&ring=6366F1&fire=6366F1&currStreakLabel=6366F1" width="49%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=blablalf&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6366F1&text_color=C9D1D9" width="40%" />

</div>

---

## 🌐 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/alfred-gaillard)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/0xblablalf)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@alfred-gaillard.fr)

</div>

---

<div align="center">

### 💡 Currently Building the Future of DeFi

<img src="https://komarev.com/ghpvc/?username=blablalf&color=6366F1&style=for-the-badge&label=Profile+Views" />

</div>

<!-- Activity Graph -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=blablalf&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=6366F1&line=6366F1&point=FFFFFF" width="100%"/>
