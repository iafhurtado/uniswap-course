# Introduction to Hardhat
### Blockman Uni Masterclass

By the time you've landed in this intro, you will be familiar with at least the Quote section of the course. This is because getting a Quote from the Uniswap protocol doesn't need to write anything on-chain, as opposed to actually Swapping tokens which requires us to alter the state.

Hardhat is a development environment for Ethereum developers.  It's a flexible and extensible task runner that helps you manage and automate the recurring tasks inherent to developing smart contracts and dApps. It's designed around the concepts of **tasks** and **plugins** such as compile and deploy smart contracts, plugins on the other side are bits of reusable configurations developed by the community of developers building on top with and on top of Hardhat.

Tasks can call other tasks, allowing complex workflows to be defined, but for this course, we are going to start from the basics.

## Installation
When you download the code and `npm install` the folder you should have already installed Hardhat. In any case, you can run

`npm install --save-dev hardhat`


