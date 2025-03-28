## How to Migrate ERC-20 Zilliqa to MainNet $ZIL? [UPDATED]

![image](https://github.com/user-attachments/assets/a6e9f32e-2da4-4b08-908a-c7b0f0c8a537)

Many longtime ZIL supporters still hold their interim ERC20 tokens in their wallets. These old ZIL tokens were created on the Ethereum network and played a pivotal role in the early days of Zilliqa. However, as we move to our independent Mainnet, these tokens are no longer compatible with our dapps and exchanges.

We have started migrating Zilliqa tokens from the interim ERC20 standard to the new ZRC2 standard. New Zilliqa tokens serve an important role as native tokens used on the Zilliqa Mainnet. Zilliqa holders should swap their interim ERC20 ZIL for the new using a migration contract.

> This is a 1:1 swap, meaning anyone who holds the ERC20 token will receive the same amount of ZRC2 tokens. There is no reduction in the token supply

## How to Migrate ZIL Tokens from Ethereum to Zilliqa Mainnet:
For any remaining ZIL ERC20 tokens that have not yet been migrated, we have decided to conduct the migration directly using migration smart contract, rather than using a migration user interface that is no longer supported. This makes the migration process for the remaining old Zilliqa ERC20 token holders simple.

The migration smart contract, created solely for migration purposes, allows you to migrate your ZIL tokens without connecting to any external platforms. The migration smart contract address is open-source, meaning the code is publicly available and can be checked by anyone.

Using the migration contract requires users to pay the gas fee on the Ethereum Blockchain. This means every user who wants to perform migration needs to have ETH in their wallet. The migration process is similar to any other transaction on the Ethereum Blockchain, and the gas fee is the same as any other transaction. We recommend choosing the average (normal) gas fee to avoid any inconvenience.

The migration can be conducted with any wallet you usually use to access the Zilliqa tokens, such as MyEtherWallet, Ledger, MetaMask, Klever, Exodus, Bitpie, Trust Wallet, Atomic Wallet, etc. All wallets support the migration process, and the procedure is the same for all wallets.

## Steps to Start Migration Process**

**Access Your Wallet:** Check your ZIL balance in the list of Ethereum tokens.
**Send Tokens:** Send your old ERC20 ZIL tokens to the migration smart contract address `0xbcEA9ade60dA1f32026c13Ed0405C9e6E847aEA7`. The migration smart contract address begins with `0xbc` and ends with `aEA7`. The case of letters does not matter (lower case or upper case), and apostrophes are not part of the address.
Choose to send the **entire balance** of ZIL tokens. The migration contract will wait for the **full balance** to arrive before initiating the migration process to optimize due to high Ethereum gas fees.
**Confirmation:** After the transaction is confirmed and broadcasted to the blockchain, the migration process will start, and your wallet will be credited with new ZIL tokens. Depending on network usage, it may take 5–30 minutes to process the migration.

## Post-Migration
Your wallet will automatically recognize the new Zilliqa Mainnet, and ZIL will be credited to your wallet once the migration is complete. The public address of your Zilliqa Mainnet wallet will start with „zil” instead of „0x” and look different from your Ethereum address. This is due to different hash algorithms used by Zilliqa Mainnet. However, the migration contract will still know where to send the new migrated tokens. Your new Mainnet ZRC2 ZIL tokens will be tied to the same private key and seed.

Once the migration is complete, you will have new ZIL tokens in your wallet. These tokens can be sold on any exchange that lists Zilliqa, as all exchanges now support the new Zilliqa Mainnet.

Congratulations! You have successfully performed the migration.
