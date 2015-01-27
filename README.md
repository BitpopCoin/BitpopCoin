[RNG] RNGcoin - A coin for the random.

RNGcoin.github.io/


 - 5 minute block targets
 - 500,000,000 total RNGcoins
 - 500 coins per generated block
 - Difficulty retargets every 2 minutes
 - Algorithm: X11
 - PoS: 7% (8 hours - 30 days)
 - 288 blocks per day
 - Only 4 blocks pre-mine
 - ASIC resistant!
 - Launched on Jan. 30, 2015.


Donate Bitcoin: 1JzjrkV7pPJMbMYKRp9XWZrznjcH6V2Zxu

-----------------------------------------------------------------------------------

RNGcoin.conf

server=1

listen=1

daemon=1

rpcuser=bitpop

rpcpassword=bitpop

rpcport=45437

port=45438

rpcallowip=127.0.0.1

dns=1

maxconnections=32

upnp=1

-----------------------------------------------------------------------------------

Compiling

git clone https://github.com/RNGcoin/RNGcoin.git

cd RNGcoin/src

make -f makefile.unix

strip RNGcoind

./RNGcoind

./RNGcoind getinfo
