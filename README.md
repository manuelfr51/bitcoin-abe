Script to print all public keys in the blockchain. Based on bitcoin-abe/bitcointools. 
Blocks/tx are not commited to database for speedup. 

Installation and Running
----------------------

    python setup.py install

This will install abe to your system. You may need to install some python
module dependencies. See https://github.com/bitcoin-abe/bitcoin-abe for more
details


To Run execute

    python -m Abe.abe --config abe.conf 

This will read bitcoin blocks from disk and print public keys to file pub_keys.txt.
If you stop the process and restart, it will start again after the last processed
block.   
   
