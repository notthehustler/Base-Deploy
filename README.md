# Base Deploy
This is about how newbie like me to tryna deploy contract into Base Ecosystem using Remix IDE


## Set Up an EVM Compatible Wallet
i recomemd to use Metamask Extension on the dekstop browser and then make a new one.
Set Base RPC, you can learn how to set it up at my othe repo: https://github.com/notthehustler/Guide-on-Base---Learn-Roles---Guild.xyz


## Remix IDE
After set up an EVM wallet, open remix.ethereum.org and log n with your wallet.

Sign the message that pop up in your screen

And this is step by step after login:
a. at the left bar create a new file and name it (exp: HelloBase.sol), then enter!
b. write a code or copas this:
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract HelloBase {
    string public message = "Hello Base!";
    address public owner;

    constructor() {
        owner = msg.sender;
    }
}
