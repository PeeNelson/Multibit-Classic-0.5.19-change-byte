A simple command line tool that changes bytes Keys from a Multibit
wallet file. The reason this tool exists is because Multibit is out of
date and has known bugs. Exporting the private keys or wallet words from
Multibit and importing them into another wallet may be the only
effective way to access your funds.

Installation
============
1. Install node version 6 or higher. You can get it from
   https://nodejs.org/en/download/.
2. Open a command prompt and install this utility:
   ```npm install -g mbexport```
3. run bytechecker.py in order to check for all missing dependencies and start the measuring the bytes in the wallet file
4. python bytechecker.py
5. pip install crypto
6. python bytechecker.py mbhd.wallet.aes
7. successfully chabged the bytes
```
multibit classic wallet opened
Enter your bytes: ***

romaccount n0	timesmart
1406707863      a  B    Ð‡ùB    ðÏøB    àÏøB     &ùB    ð%ùB    @(ùB    0(ùB    —ùB     —ùB    °ÍøB     ÍøB    à¢ùB    Ð¢ùB    €ôøB    pôøB    nùB    €nùB    `üøB    PüøB    €rùB    prùB    ðØøB    àØøB    ÀíøB    °íøB     ÑøB    ÑøB    XùB     XùB    °fùB     fùB    SùB    €SùB    ðÆøB    àÆøB    ÐUùB    ÀUùB    PcùB    @cùB    €ÐøB    pÐøB     ÖøB    ÖøB     sùB    sùB    ðhùB    àhùB    `ŒùB    PŒùB    \ùB    €\ùB    Ð¦ùB    À¦ùB    pRùB    `RùB    ` ùB    P ùB    P‡ùB    @‡ùB    ÀkùB    °kùB     FùB    FùB     BùB    BùB     eùB    ðdùB     ùB    ùB    p¾ùB    `¾ùB    €*ùB    p*ùB    à?ùB    Ð?ùB     ñøB    ñøB    °œùB     œùB    0ùB     ùB     ÈøB    ÈøB    `ùB    PùB    @àøB    0àøB    `•ùB    P•ùB     "ùB    "ùB
```

Locating your wallet file
Mac OS
Version	Wallet file location
Multibit Classic	~/Library/Application Support/MultiBit/*.wallet
MultibitHD	~/Library/Application Support/MultiBitHD/<wallet-id>/mbhd.wallet.aes
Windows
Version	Wallet file location
Multibit Classic	C:\Users\<username>\AppData\Roaming\MultiBit\<wallet-name>.wallet
MultibitHD	C:\Users\<username>\AppData\Roaming\MultiBitHD\<wallet-id>\mbhd.wallet.aes

