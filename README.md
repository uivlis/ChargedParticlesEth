## Charged Particles - Solidity Contracts v0.4.2

[![Discord](https://badgen.net/badge/definft/Charged%20Particles?icon=discord&label=discord)](https://discord.gg/Syh3gjz)
[![Twitter Follow](https://badgen.net/twitter/follow/DeFiNFT?icon=twitter)](https://twitter.com/intent/follow?screen_name=DeFiNFT)
[![built-with openzeppelin](https://img.shields.io/badge/built%20with-OpenZeppelin-3677FF)](https://docs.openzeppelin.com/)

[![Coverage Status](https://coveralls.io/repos/github/robsecord/ChargedParticlesEth/badge.svg?branch=master)](https://coveralls.io/github/robsecord/ChargedParticlesEth?branch=master&v=123)
![GitHub last commit](https://img.shields.io/github/last-commit/robsecord/ChargedParticlesEth)
![GitHub package.json version](https://img.shields.io/github/package-json/v/robsecord/ChargedParticlesEth)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/robsecord/ChargedParticlesEth)
![GitHub repo size](https://img.shields.io/github/repo-size/robsecord/ChargedParticlesEth)

**Charged Particles** are Non-Fungible Tokens (NFTs) that are minted with an Underlying Asset (ex: **DAI**) and accrue interest via an Interest-bearing token (ex: **CHAI**) giving the Token a "Charge". 

**Coming Soon**:

- Aave - aTokens
- mStable - mTokens
- Idle Finance - yTokens


---

#### Production Site (Beta, Ropsten Only)
https://charged-particles.eth.link/

#### Staging Site
https://charged-particles.tmnl.co/

---

#### Value
```text
Particle Value
  =
Intrinsic Value (underlying asset, DAI)
  + 
Speculative Value (non-fungible rarity)
  +
Interest value (accrued in CHAI)
```

#### Value Appreciation
Imagine a Babe Ruth rookie card that was stuffed with $1 and earning interest since 1916!  The same might be true
of a Charged Particle NFT in 100 years!

#### Ownership
Charged Particles are non-custodial NFTs that can be "discharged" at any time by the owner, collecting the interest 
from the token. And just like any NFT, they are yours trade, transfer, sell, etc.

They can also be burned (melted) to reclaim the underlying DAI + interest in full, destroying the token.
Charged Particles, therefore, always have an underlying value in DAI. 

#### Custom Mechanics
Based on the amount of "charge" a token has, Smart Contracts and/or Dapps can decide how to handle the token - custom 
mechanics can be designed around the level of "Charge" a token has.

Imagine an NFT that represents a Sword - the power of that sword could be dependant on the amount of "Charge" the token 
has. Or perhaps certain items can only be used once they reach a certain level of charge.

Other possibilities include battling over the "charge" of a particle - the winner earns the interest from their 
competitor's particles.  (Still trying to work this part out, ideas are welcome!)

#### Particle Accelerator
 - Fully-decentralized Public Particle Minting Station
 - Work-in-progress 
 - Repo: https://github.com/robsecord/ChargedParticlesWeb

#### Feedback & Contributions
Feel free to fork and/or use in your own projects!

And, of course, contributions are always welcome!

#### Community
Join our community, share ideas and help support the project in anyway you want!

**Discord**: https://discord.gg/Syh3gjz

---

### Frameworks/Software used:
 - Main Repo:
    - OpenZeppelin CLI **v2.8.0**
    - OpenZeppelin Upgrades **v2.8.0**
    - OpenZeppelin Ethereum Contracts **v3.0.0**
    - Solidity  **v0.6.10** (solc-js)
    - NodeJS **v12.16.3**
    - Buidler **v1.3.5**
    - EthersJS **v4.0.27**

### Prepare environment:
    
 Create a local .env file with the following (replace ... with your keys):
 
```bash
    INFURA_API_KEY="__api_key_only_no_url__"
    
    KOVAN_PROXY_ADDRESS="__public_address__"
    KOVAN_PROXY_MNEMONIC="__12-word_mnemonic__"
    
    KOVAN_OWNER_ADDRESS="__public_address__"
    KOVAN_OWNER_MNEMONIC="__12-word_mnemonic__"
    
    ROPSTEN_PROXY_ADDRESS="__public_address__"
    ROPSTEN_PROXY_MNEMONIC="__12-word_mnemonic__"
    
    ROPSTEN_OWNER_ADDRESS="__public_address__"
    ROPSTEN_OWNER_MNEMONIC="__12-word_mnemonic__"
    
    MAINNET_PROXY_ADDRESS="__public_address__"
    MAINNET_PROXY_MNEMONIC="__12-word_mnemonic__"
    
    MAINNET_OWNER_ADDRESS="__public_address__"
    MAINNET_OWNER_MNEMONIC="__12-word_mnemonic__"
```

### Deploy:

 1. yarn
 2. yarn verify
 2. yarn start

See package.json for more scripts

---

_MIT License_

Copyright (c) 2020 Rob Secord <robsecord.eth>

