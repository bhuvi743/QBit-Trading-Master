# QBit-Trading-Master
## Qt Bitcoin Trader

This software helps you open and cancel orders very fast. Real time data monitoring.

Developed on pure Qt, uses OpenSSL, AES 256 key and secret protection.

I want to develop this Trader App so that it can be configured for any rule and strategy.

Next ToDo:
- Add realtime charts
- Make rules more advanced


## Compilation on Linux
* `sudo apt-get install g++ libssl-dev libglu1-mesa-dev qt5-qmake qtscript5-dev qtmultimedia5-dev git`
* `git clone https://github.com/JulyIGHOR/QtBitcoinTrader.git`
* `cd ./QtBitcoinTrader/src`
* `QT_SELECT=5 qmake QtBitcoinTrader_Desktop.pro`
* `make && make install && make clean`






