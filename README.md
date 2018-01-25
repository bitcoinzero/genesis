# Bitcoin Zero Genesis Block
Unzip these blocks in the corresponding datadir (default ~/.bitcoinzero). Then initialize your Bitcoin Zero node with zcashd -reindex option.
## blocks
Main net genesis block. Default path ~/.bitcoinzero/blocks. If error occurs or being killed because of lacking memory during the initializing reindex, please try *blocks_for_low_memory.tar.gz*.
## testnet3/blocks
Test net genesis block. Default path ~/.bitcoinzero/testnet3/blocks.
## blocks_for_low_memory.tar.gz
Main net genesis block. Default path ~/.bitcoinzero/blocks. Use this on a low memory machine. However, as stated on <https://github.com/zcash/zcash/wiki/1.0-User-Guide>, 3 GB of free RAM is needed after all.
