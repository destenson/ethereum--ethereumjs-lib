SYNOPSIS  
===========

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ethereum/ethereumjs-lib?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) or on #ethereum on freenode

A Javascript library of core [Ethereum](http://Ethereum.org) functions as described in the [Yellow Paper](https://github.com/ethereum/yellowpaper). This is a simple meta-module that provides the following modules. Most JS modules are tracked in [ethereumjs](https://github.com/ethereumjs)

 - [VM](https://github.com/ethereumjs/ethereumjs-vm) - The Ethereum virtural machine and state processing functions
 - [Blockchain](https://github.com/ethereumjs/ethereumjs-blockchain) - Blockchain managment
 - [Block](https://github.com/ethereumjs/ethereumjs-block) - Block Schema definition and validation
 - [Transaction](https://github.com/ethereumjs/ethereumjs-tx) - Transaction Schema definition and validation
 - [Account](https://github.com/ethereumjs/ethereumjs-account) - Account Schema definition and validation
 - [rlp](https://github.com/ethereumjs/rlp) - Recursive Length Prefix serialization
 - [Trie](https://github.com/ethereumjs/merkle-patricia-tree) - Modified Merkle Patricia Tree
 - [Ethash](https://github.com/ethereumjs/ethashjs) - Ethereum's Proof of Work algorithm
 - [utils](https://github.com/ethereumjs/ethereumjs-util) - Miscellaneous helper functions
 - [devp2p](https://github.com/ethereumjs/node-devp2p) - The networking protocol
 - [devp2p-dpt](https://github.com/ethereumjs/node-devp2p-dpt) - The disputed peer table

# BROWSER
`ethereumjs-lib` can be used with [`browserify`](http://browserify.org/). With the exception of the networking modules. 

# CONTRIBUTIONS

Patches welcome! Contributors are listed in the `package.json` file.
Please run the tests before opening a pull request and make sure that you are
passing all of them.

If you would like to contribute, but don't know what to work on, check
the issues list or ask on the forms or on IRC.

* [issues](http://github.com/ethereumjs/ethereumjs-lib/issues)


# LICENSE
[MPL-2.0](https://tldrlegal.com/license/mozilla-public-license-2.0-(mpl-2))
