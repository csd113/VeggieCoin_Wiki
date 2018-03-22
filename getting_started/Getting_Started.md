# Getting Started

## Downloading the wallet

The most up-to date wallet release can be [found on the Bitcoin talk ann here.](https://bitcointalk.org/index.php?topic=2544075.0;all)

Alternatley you can download directly form these links below.

Windows: [Download.](https://veggiecoin.io/Veggie-qt1.3.exe)

Mac: [Download.](https://www.veggiecoin.io/Veggie-Qt.dmg)

## Installing

### Installing on Windows

Simply [download](https://veggiecoin.io/Veggie-qt1.3.exe) the wallet from either the [Bitcoin talk ann here](https://bitcointalk.org/index.php?topic=2544075.0;all) or the [official veggiecoin website](https://www.veggiecoin.io/)

### Installing on Mac

[Download](https://www.veggiecoin.io/Veggie-Qt.dmg) and open the Veggie-qt.dmg and drop the Veggie-qt wallet into your applications folder.

## Synchronizing the Blockchain

Running `Veggie-qt` will automatically connect to the Veggie network and begin downloading and verifying the blockchain.  
Because the blockchain is constantly growing, the file size is always increasing, and `Veggie-qt` must verify each block (CPU intensive) it may take some time for the blockchain to sync.

### Windows

Run the `Veggie-qt.exe` executable downloaded from an official source.

### Mac

Run the `Veggie-qt` binary downloaded from an official source.

### Creating a Wallet

Upon first launch of the wallet program, a private key and wallet.dat file containing said private key will be generated, there is not work needed on the users part.

### Viewing Wallet Address

Select the *Receive* tab in the Veggie Coin wallet program, click the *Request payment*, then at the bottom of the new tab which poped up click the *Copy Address* button.  You have now copied your public key, use this when people want to send you Veggie coins.

![](/Images/receive-tab.png)

![](/Images/copy-button.png)

### Encrypting your wallet

For saftey it is highly recomended you encrypt your wallet, to do this:
1. Within the wallet, navigate to the *Settings* tab at the top of the wallet.
2. Click *Encrypt wallet...*
3. Enter a secure passphrase you will not forget. **If you forget this password you will not be able to access your coins.**

### Exporting Keys

In order to access your private key there's a few steps you will need to take.
1. Have your VeggieCoin wallet open
2. On the top bar of the wallet select: Help, then Debug window, and now within the popup click on the *Console* option at the very top.  You must now type `walletpassphrase <your_wallet_encryption_password> 9999` if you have encrypted your wallet.

![](/Images/debug-button.png)

3. Once your wallet is unlocked, type `dumpprivkey <youreraaddress>`, the console will now print out your wallets private key.
4. Save your private key to a safe location where it cannot be accessed from the internet. NEVER show this key to anyone else, with this key anyone can have access to all your ERA.
5. Once you have saved your private key to a secure location make sure you re-lock your wallet my typing into the console `walletlock`.
