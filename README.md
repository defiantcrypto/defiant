# Defiant

Defiant is a PoW + PoS-based + Masternode cryptocurrency

Defiant uses libsecp256k1,
			  libgmp,
			  Boost1.55,
			  OR Boost1.57,  
			  Openssl1.01m,
			  Berkeley DB 4.8,
			  QT5 to compile



Ticker: DEFIT
Supply: 500 M
Block Size: 2 MB
Masternode Collateral: 5k DEFIT
Darksend Collateral: 5k DEFIT
Masternode Epochtime: 1604219901 (Halloween November 1)
Pow: 1 DEFIT (Security system)
Pos reward: 50% 
MN reward: 46%
Stake reward: 4%
Block Spacing: 60 Seconds
Stake Minimum Age: 8 Hours
Port: 58755
RPC Port: 58855



BUILD LINUX (see the [Wiki](https://github.com/sagacrypto/Defiant/wiki/Unix-Build) for dependencies)
-----------
1) git clone source

2) cd Defiant/src

3) mkdir obj/crypto

4) chmod +x leveldb/build_detect_platform

5) cd leveldb && make libleveldb.a libmemenv.a

6) cd ..

7) sudo make -f makefile.unix USE_UPNP=    # Headless Defiant

8) strip defiantd

9) sudo cp defiantd /usr/local/bin




