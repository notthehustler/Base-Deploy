# Base Deploy
This is about how newbie like me to tryna deploy contract into Base Ecosystem using Remix IDE


## Set Up an EVM Compatible Wallet
i recomemd to use Metamask Extension on the dekstop browser and then make a new one.
Set Base RPC, you can learn how to set it up at my othe repo: https://github.com/notthehustler/Guide-on-Base---Learn-Roles---Guild.xyz


## Remix IDE
After set up an EVM wallet, open remix.ethereum.org and log n with your wallet.

Sign the message that pop up in your screen

## And this is step by step after login:
a. at the left bar create a new file and name it (exp: HelloBase.sol), then enter!

b. write a code or copas this:


```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract HelloBase {
    string public message = "Hello Base!";
    address public owner;

    constructor() {
        owner = msg.sender;
    }
}
```

c. after input the code on the space, click COMPILE or go to compile menu in the left bar, then click COMPILE.
if its work or green checked, there you go!

d. go to menu Deploy and Run in the left sidebar

e. in the "Environment" menu → click dropdown → choose EVM wallet or Wallet Connect → choose wallet that you set it up back then

f. click CONNECT in the mesage that will poping up from your wallet

g. then click DEPLOY!!! 

h. this is the moment that you wait: sign confirmation message from your wallet to pay gas fee and confirmation

i. and last, yeah, if it works then fuckin CONGRATS!!!!!! hahahahaha juh

## Other Code
i will put other code that you can deploy on Remix
