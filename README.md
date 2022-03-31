# Bitcoin HDWallet Generator (Privatekey + address)
----
Bitcoin started with a very rudimentary address type. In order to get transactions smaller in size and therefor cheaper, new address types got developed that reduce the amount of information necessary to spend a received transaction. Additionally, these addresses types added important new functionalities to bitcoin.


***How to identify a bitcoin address?***


You can identify the type of a bitcoin address by looking at the first letters of it. If it starts with "1", it's a legacy address. If it starts with "3", it's a P2SH address. If it starts with "bc1q", it's a native segwit and if the first 4 letters are "bc1p", it's a taproot address.

***Where can I get a bitcoin address?***

You can generate a bitcoin address by clicking on "Receive" within your bitcoin wallet. You can create as many different bitcoin addresses as you want. For privacy reasons it is advised to not re-use an address.

***How do bitcoin addresses work?***

Bitcoin addresses contain the information about who can access the bitcoin sent to this address. By for example proving that you control the private key to a bitcoin address, you are allowed to send a transaction from it. Without proving ownership of an address, you cannot send a valid transaction.


Bitcoin wallet creat and check private key and address , with total transaction (use HDWallet)
----

![Bitcoin HDWallet Generator (Privatekey + address)](https://raw.githubusercontent.com/Pymmdrza/BTC_HD_Wallet_Checker/main/btchdall.jpg)
----

#### genereted bitcoin wallet private key and address

#### genereted from random private key (hexer)

#### check wallet details and all transaction without apikey 

#### save wallet > 0 on text file

#### easy install windows and linux (00INSTALL.cmd and 00INSTALL.sh)
----
for install package on windows `./00INSTALL.cmd` or this:

```
pip install colorama
pip install hdwallet
pip install lxml
pip install requests

```

for install package on Linux `./00INSTALL.sh` or this:

```
pip install colorama
pip install hdwallet
pip install lxml
pip install requests

```
can use easy running with loop:
use `btcHDall.cmd (btcHDall.py)` For Genereted and  Checked 4 type Address All in One (p2pkh + p2sh + p2wpkh + p2wsh)
```
./btcHDall.cmd
./p2pkh.cmd
./p2sh.cmd
./p2wpkh.cmd
./p2wsh.cmd
```
Linux:

```
sh btcHDall.sh
sh p2pkh.sh
sh p2sh.sh
sh p2wpkh.sh
sh p2wsh.sh

```
----

Genereted p2pkh address use p2pkh.py or `p2pkh.cmd` or `p2pkh.sh` 

![bitcoin p2pkh address generator privatekey](https://raw.githubusercontent.com/Pymmdrza/BTC_HD_Wallet_Checker/main/p2pkh.jpg)
----

Genereted p2wpkh address use p2wpkh.py or `p2wpkh.cmd` or `p2wpkh.sh` 

![bitcoin p2wpkh address generator privatekey](https://raw.githubusercontent.com/Pymmdrza/BTC_HD_Wallet_Checker/main/p2wpkh.jpg)

----

Genereted p2sh address use p2sh.py or `p2sh.cmd` or `p2sh.sh` 

![bitcoin p2sh address generator privatekey](https://raw.githubusercontent.com/Pymmdrza/BTC_HD_Wallet_Checker/main/p3sh.jpg)

----

Genereted p2wsh address use p2wsh.py or `p2wsh.cmd` or `p2wsh.sh` 

![bitcoin p2wsh address generator privatekey](https://raw.githubusercontent.com/Pymmdrza/BTC_HD_Wallet_Checker/main/p2wsh.jpg)

----
```
# ================================================
# DONATE (BTC) : 16p9y6EstGYcnofGNvUJMEGKiAWhAr1uR8
# Website : Mmdrza.Com
# Email : X4@mmdrza.Com
# Dev.to/Mmdrza
# Github.com/Pymmdrza
# ================================================
```
