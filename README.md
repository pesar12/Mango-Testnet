# MANGO TESTNET BOT

## Table Of Contents
- [MANGO TESTNET BOT](#mango-testnet-bot)
  - [Table Of Contents](#table-of-contents)
  - [Prerequisite](#prerequisite)
  - [Register](#Register)
  - [BOT FEATURE](#bot-feature)
  - [Setup \& Configure BOT](#setup--configure-bot)
    - [Linux](#linux)
    - [Windows](#windows)
  - [Update Bot](#update-bot)
  - [IMPORTANT NOTE (READ IT THIS IS NOT DECORATION)](#important-note-read-it-this-is-not-decoration)
  - [CONTRIBUTE](#contribute)

## Prerequisite
- Git
- Node JS (v22)
- Register with my invite code : ZbJll8

# Register 

Mango Testnet

➡️ Register : [HERE](https://task.testnet.mangonetwork.io/?invite=ZbJll8)

- Download Mango Wallet (https://chromewebstore.google.com/detail/mango-wallet/jiiigigdinhhgjflhljdkcelcjfmplnd) (Extension)
- Backup Phrase
- Claim Faucet on your wallet extension
- Go To [Web](https://task.testnet.mangonetwork.io/?invite=ZbJll8)
- Complete Bind Social Media Accounts and JOIN NOW
- Go to [Event Page](https://task.testnet.mangonetwork.io/events)
- Complete Task on the Task List ( Swap , Bridge )
- Login Daily
- Done

## BOT FEATURE
- Multi Account 
- Support PK
- Proxy Support
- Daily Claim Faucet
- Daily Mango Swap 
- Daily BeingDex Beta DAPP
- Daily Check In

## Setup & Configure BOT

### Linux
1. Clone project repo
   ```
   git clone https://github.com/pesar12/mango-testnet-bot.git && cd mango-testnet-bot
   ```
2. Run
   ```
   npm install && npm run setup
   ```
3. Configure your accounts
   ```
   nano accounts/accounts.js
   ```
4. To run Auto TX
   ```
   npm run start
   ```
   
### Windows
1. Open your `Command Prompt` or `Power Shell`.
2. Clone project repo
   ```
   git clone https://github.com/Crypus/mango-testnet-bot.git
   ```
   and cd to project dir
   ```
   cd mango-testnet-bot
   ```
3. Run 
   ```
   npm install && npm run setup
   ```
5. Navigate to `mango-testnet-bot` directory. 
6. Navigate to `accounts` directory.
7. Now open `acccounts.js` and setup your accounts. `
8. Now Back to `mango-testnet-bot` directory and Navigate to `config` directory and adjust the `proxy_list.js` as needed.
9.  Back to `mango-testnet-bot` directory.
10. To start the app open your `Command Prompt` or `Power Shell`
11. To run auto Tx Bot
    ```
    npm run start
    ```

## Update Bot

To update bot follow this step :
1. run
   ```
   git pull
   ```
   or
   ```
   git pull --rebase
   ```
   if error run
   ```
   git stash && git pull
   ```
2. run
   ```
   npm update
   ```
3. start the bot
4. if any eror happen check `log/app.log`


## IMPORTANT NOTE (READ IT THIS IS NOT DECORATION)
DWYOR & Always use a new wallet when running the bot, I am not responsible for any loss of assets.


## CONTRIBUTE

Feel free to fork and contribute adding more feature thanks.
