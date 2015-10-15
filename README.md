eth-stratum-mining-proxy
====================

This fork of proxy created by Slush. 

Application providing bridge between Ethereum HTTP/getwork protocol and Stratum mining protocol
as described here: http://mining.bitcoin.cz/stratum-mining.

Installation on Windows
-----------------------

1. Download official Windows binaries (EXE) from https://github.com/Coinotron/eth-stratum-mining-proxy/releases/tag/v1.0
2. Open downloaded file. It will open console window. Using default settings, proxy connects to Coinotron
3. Another way to start proxy: mining_proxy.exe -o coinotron.com -p 3344 
4. If you want to connect to another pool or change other proxy settings ( for example define custom worker and password ), type "mining_proxy.exe --help" in console window.

Installation on Linux 
---------------------------------------

1. install twisted apt-get: 
	install python-twisted
2. download https://github.com/coinotron/eth-stratum-mining-proxy/
3. run proxy: 
	python ./mining-proxy.py -o coinotron.com -p 3344
4. If you want to connect to another pool or change other proxy settings ( for example define custom worker and password ), type "mining_proxy.py --help".



Contact
-------

You can contact the author by email coinotron(at)gmail.com.


