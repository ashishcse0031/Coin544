# Coin544
A litecoin based alt-coin

$ bitcoin-cli getinfo

2019-04-10T17:39:43Z Bitcoin Core version v0.18.99.0-23712f8 (release build)
2019-04-10T17:39:43Z Assuming ancestors of block 0000000000000000000f1c54590ee18d15ec70e68c8cd4cfbadb1b4f11697eee have valid signatures.
2019-04-10T17:39:43Z Setting nMinimumChainWork=0000000000000000000000000000000000000000051dc8b82f450202ecb3d471
2019-04-10T17:39:43Z Using the 'sse4(1way),sse41(4way)' SHA256 implementation
2019-04-10T17:39:43Z Using RdSeed as additional entropy source
2019-04-10T17:39:43Z Using RdRand as an additional entropy source
2019-04-10T17:39:43Z Default data directory /home/altcoin/.bitcoin
2019-04-10T17:39:43Z Using data directory /home/altcoin/.bitcoin
2019-04-10T17:39:43Z Config file: /home/altcoin/.bitcoin/bitcoin.conf (not found, skipping)
2019-04-10T17:39:43Z Using at most 125 automatic connections (1024 file descriptors available)
2019-04-10T17:39:43Z Using 16 MiB out of 32/2 requested for signature cache, able to store 524288 elements
2019-04-10T17:39:43Z Using 16 MiB out of 32/2 requested for script execution cache, able to store 524288 elements
2019-04-10T17:39:43Z Using 2 threads for script verification
2019-04-10T17:39:43Z scheduler thread start
2019-04-10T17:39:43Z HTTP: creating work queue of depth 16
2019-04-10T17:39:43Z No rpcpassword set - using random cookie authentication.
2019-04-10T17:39:43Z Generated RPC authentication cookie /home/altcoin/.bitcoin/.cookie
2019-04-10T17:39:43Z HTTP: starting 4 worker threads
2019-04-10T17:39:43Z Using wallet directory /home/altcoin/.bitcoin/wallets
2019-04-10T17:39:43Z init message: Verifying wallet(s)...
2019-04-10T17:39:43Z Using BerkeleyDB version Berkeley DB 4.8.30: (April  9, 2010)
2019-04-10T17:39:43Z Using wallet /home/altcoin/.bitcoin/wallets
2019-04-10T17:39:43Z BerkeleyEnvironment::Open: LogDir=/home/altcoin/.bitcoin/wallets/database ErrorFile=/home/altcoin/.bitcoin/wallets/db.log
2019-04-10T17:39:43Z init message: Loading banlist...
2019-04-10T17:39:43Z ERROR: DeserializeFileDB: Failed to open file /home/altcoin/.bitcoin/banlist.dat
2019-04-10T17:39:43Z Invalid or missing banlist.dat; recreating
2019-04-10T17:39:43Z Cache configuration:
2019-04-10T17:39:43Z * Using 2.0 MiB for block index database
2019-04-10T17:39:43Z * Using 8.0 MiB for chain state database
2019-04-10T17:39:43Z * Using 440.0 MiB for in-memory UTXO set (plus up to 286.1 MiB of unused mempool space)
2019-04-10T17:39:43Z init message: Loading block index...
2019-04-10T17:39:43Z Opening LevelDB in /home/altcoin/.bitcoin/blocks/index
2019-04-10T17:39:43Z Opened LevelDB successfully
2019-04-10T17:39:43Z Using obfuscation key for /home/altcoin/.bitcoin/blocks/index: 0000000000000000
2019-04-10T17:39:43Z LoadBlockIndexDB: last block file = 0
2019-04-10T17:39:43Z LoadBlockIndexDB: last block file info: CBlockFileInfo(blocks=0, size=0, heights=0...0, time=1970-01-01...1970-01-01)
2019-04-10T17:39:43Z Checking all blk files are present...
2019-04-10T17:39:43Z Initializing databases...
2019-04-10T17:39:43Z Pre-allocating up to position 0x1000000 in blk00000.dat
2019-04-10T17:39:43Z Opening LevelDB in /home/altcoin/.bitcoin/chainstate
2019-04-10T17:39:43Z Opened LevelDB successfully
2019-04-10T17:39:43Z Wrote new obfuscate key for /home/altcoin/.bitcoin/chainstate: af44f1261712edf4
2019-04-10T17:39:43Z Using obfuscation key for /home/altcoin/.bitcoin/chainstate: af44f1261712edf4
2019-04-10T17:39:43Z init message: Rewinding blocks...
2019-04-10T17:39:43Z  block index              17ms
2019-04-10T17:39:43Z init message: Loading wallet...
2019-04-10T17:39:43Z BerkeleyEnvironment::Open: LogDir=/home/altcoin/.bitcoin/wallets/database ErrorFile=/home/altcoin/.bitcoin/wallets/db.log
2019-04-10T17:39:43Z [default wallet] nFileVersion = 189900
2019-04-10T17:39:43Z [default wallet] Keys: 0 plaintext, 0 encrypted, 0 w/ metadata, 0 total. Unknown wallet records: 0
2019-04-10T17:39:43Z [default wallet] Performing wallet upgrade to 169900
2019-04-10T17:39:44Z [default wallet] keypool added 2000 keys (1000 internal), size=2000 (1000 internal)
2019-04-10T17:39:44Z [default wallet] Wallet completed loading in             988ms
2019-04-10T17:39:44Z [default wallet] setKeyPool.size() = 2000
2019-04-10T17:39:44Z [default wallet] mapWallet.size() = 0
2019-04-10T17:39:44Z [default wallet] mapAddressBook.size() = 0
2019-04-10T17:39:44Z UpdateTip: new best=000000000019d6689c085ae165831e934ff763ae46a2a6c172b3f1b60a8ce26f height=0 version=0x00000001 log2_work=32.000022 tx=1 date='2009-01-03T18:15:05Z' progress=0.000000 cache=0.0MiB(0txo)
2019-04-10T17:39:44Z Failed to open mempool file from disk. Continuing anyway.
2019-04-10T17:39:44Z mapBlockIndex.size() = 1
2019-04-10T17:39:44Z nBestHeight = 0
2019-04-10T17:39:44Z torcontrol thread start
2019-04-10T17:39:44Z Bound to [::]:8333
2019-04-10T17:39:44Z Bound to 0.0.0.0:8333
2019-04-10T17:39:44Z init message: Loading P2P addresses...
2019-04-10T17:39:44Z ERROR: DeserializeFileDB: Failed to open file /home/altcoin/.bitcoin/peers.dat
2019-04-10T17:39:44Z Invalid or missing peers.dat; recreating
2019-04-10T17:39:44Z init message: Starting network threads...
2019-04-10T17:39:44Z init message: Done loading
2019-04-10T17:39:44Z addcon thread start
2019-04-10T17:39:44Z net thread start
2019-04-10T17:39:44Z dnsseed thread start
2019-04-10T17:39:44Z Loading addresses from DNS seeds (could take a while)
2019-04-10T17:39:44Z opencon thread start
2019-04-10T17:39:44Z msghand thread start
2019-04-10T17:39:46Z New outbound peer connected: version: 70015, blocks=570920, peer=0
2019-04-10T17:39:47Z New outbound peer connected: version: 70015, blocks=570920, peer=1
2019-04-10T17:39:48Z New outbound peer connected: version: 70015, blocks=570920, peer=2
2019-04-10T17:39:50Z Warning: Please check that your computer's date and time are correct! If your clock is wrong, Bitcoin Core will not work properly.
Warning: Please check that your computer's date and time are correct! If your clock is wrong, Bitcoin Core will not work properly.
2019-04-10T17:39:50Z New outbound peer connected: version: 70015, blocks=570920, peer=3
2019-04-10T17:39:50Z 281 addresses found from DNS seeds
2019-04-10T17:39:50Z dnsseed thread exit
2019-04-10T17:39:51Z New outbound peer connected: version: 70015, blocks=570920, peer=4
2019-04-10T17:39:58Z New outbound peer connected: version: 70015, blocks=570920, peer=5
2019-04-10T17:40:00Z New outbound peer connected: version: 70015, blocks=570920, peer=6
2019-04-10T17:40:49Z New outbound peer connected: version: 70015, blocks=570920, peer=7
^C2019-04-10T17:41:43Z tor: Thread interrupt
2019-04-10T17:41:43Z Shutdown: In progress...
2019-04-10T17:41:43Z torcontrol thread exit
2019-04-10T17:41:43Z addcon thread exit
2019-04-10T17:41:43Z net thread exit
2019-04-10T17:41:44Z msghand thread exit
2019-04-10T17:41:44Z opencon thread exit
2019-04-10T17:41:44Z scheduler thread interrupt
2019-04-10T17:41:44Z Dumped mempool: 5e-06s to copy, 0.003291s to dump
2019-04-10T17:41:46Z [default wallet] Releasing wallet
2019-04-10T17:41:46Z Shutdown: done
