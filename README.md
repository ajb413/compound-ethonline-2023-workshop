# Compound III Developer Workshop - ETHOnline 2023 Hackathon

Example app that uses Compound III for supplying and borrowing on Mainnet or Base.

## Video Workshop

This workshop video walks through building the app. The code from the video is in this repository.

https://youtu.be/OjYe_5sVcTM

## Install

Install Node.js at https://nodejs.org/

```
git clone https://github.com/ajb413/compound-ethonline-2023-workshop.git
cd compound-ethonline-2023-workshop.git/
npm install
```

## Run

Set your Metamask to Localhost network. Select your first developer mnemonic account. Navigate to http://127.0.0.1:3008/ in a web browser. The dApp files are in the `public/` folder.

```bash
## Get your own JSON RPC URLs for free at alchemy.com

MAINNET_PROVIDER_URL="_your_rpc_url_here_" npm start mainnet

## or

BASE_PROVIDER_URL="_your_rpc_url_here_" npm start base
```
