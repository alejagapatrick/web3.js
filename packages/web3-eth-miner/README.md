# web3-eth-miner

This is a sub package of [web3.js][repo]

This is the miner package. This is an independent package. If you want to use this package, you need to import this in your project.
Please read the [documentation][docs] for more.

## Installation

```bash
npm install web3-eth-miner
```

## Usage

```js
import {Miner} from 'web3-eth-miner';

const miner = new Miner(
    'http://127.0.0.1:8546',
    null,
    options
);
```

## Types

All the typescript typings are placed in the types folder.

[docs]: http://web3js.readthedocs.io/en/1.0/
[repo]: https://github.com/ethereum/web3.js
