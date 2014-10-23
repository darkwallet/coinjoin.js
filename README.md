CoinjoinJS [![Build Status](https://drone.io/github.com/darkwallet/coinjoin.js/status.png)](https://drone.io/github.com/darkwallet/coinjoin.js/latest) [![Coverage Status](https://img.shields.io/coveralls/darkwallet/coinjoin.js.svg)](https://coveralls.io/r/darkwallet/coinjoin.js)
==========

Coinjoin library included in DarkWallet. Depends on bitcoinjs-lib.

Assumptions
-----------

Bitcoin privacy leaks are [dangerous](https://bitcointalk.org/index.php?topic=334316.msg3588908#msg3588908) both for users, value and [fungibility](https://bitcointalk.org/index.php?topic=333882.0). All wallets should support mixing techniques so tainting analysis can be foiled and preserve users privacy.

At the moment, we have the following base proposals:

* [CoinJoin](https://bitcointalk.org/index.php?topic=279249.0)
* [CoinSwap](https://bitcointalk.org/index.php?topic=321228.0)

