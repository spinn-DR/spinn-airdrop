# spinn-airdrop
How to redeem Spinn Airdrop.

## Beware

NEVER ENTER A PRIVATE KEY INTO AN ONLINE MACHINE.

Also watch out for various scams and phishing attempts. Revealing your private key to anyone __is
never necessary__ to redeem an airdrop. If you are asked to visit a website for the airdrop that is not this github repository or provide your keys to anyone DON'T DO IT!

`bitcoin-core` (for advanced users) or `spinn-airdrop.html` (easiest for most users) are the only tools recommended for airdrop redemption. Use anything else at your own risk.

# Snapshot date: 05 October 2022
# Mainnet Launch date: 05 December 2022

## How It Works

The Spinn airdrop is eligible to anyone who owns non-custodial bitcoin ($BTC) as of the __snapshot date__, and posts a signed message to our bitcointalk thread prior to mainnet launch (05 December 2022). 

* The first 100 valid claims to be identified will redeem at a rate of 10,000/1 their BTC holdings at the time of the snapshot. 

* The next 150 valid claims (101 - 250) to be indentified will redeem at a rate of 1,000/1 their BTC holdings at the time of the snapshot.

* Everyone else will redeem at a rate of 200/1 their BTC holdings at the time of the snapshot.


## Usage

* Clone or Download this repository. Save it to a USB drive.

* Using an __offline machine__, locate the downloaded files on your USB drive and open the `spinn-airdrop.html` file 

* This is a simple open source interface, easy to audit, that uses bitcoinjs-lib and bitcoinjs-message to allow easy signing of bitcoin messages.

* Choose the addres type you are signing for (Legacy, P2SH Segwit, or Native Segwit).

* Create a receiving Spinn address and keep it safe! (https://github.com/spinn-DR/spinn-wallet/releases) or create your own using our address specification (https://github.com/spinn-DR/Spinn/blob/main/spinn-address.md)

* Input your message to sign "Claiming the Spinn Airdrop to my Spinn Address REPLACE-WITH-YOUR-SPINN-RECEIVING-ADDRESS" (MUST INCLUDE YOUR SPINN ADDRESS)

* Enter your private key and click Sign Message

* Copy the entire output and post it to our airdrop page(https://spinnairdrop.000webhostapp.com/). 


## Privacy

An airdrop to Bitcoin addresses presents an obvious privacy concern: 
Bitcoin addresses and their transactions are on a public ledger and airdrop claims are public. 

Consider using an address that is not associated with any of your known address.

WE WILL NOT ACCEPT SIGNED MESSAGES VIA PRIVATE MESSAGE, DM OR OTHER METHOD. We believe there needs to be complete transparency in conjunction with the distribution.

The full list of claims will be reviewed, recorded, and archived upon mainnet launch.


## Security

If you're uncomfortable running third party software on an air-gapped machine, you can sign a bitcoin message using your own software or bitcoin-core.


## License

See LICENSE for more info.

