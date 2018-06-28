## Release Notes

### v0.0.1
- Added `--backup-blockchain` `--backup-wallet` command-line flags to `bytecoind` and `walletd` resp. to hot-copy blockchain and wallet data (wallet file and wallet cache).
- Fixed behavior of the `walletd`'s methods such as `get_balance`, which until now returned zero balance for addresses not belonging to the opened wallet file.
