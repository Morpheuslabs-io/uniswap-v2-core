# Uniswap V2

[![Actions Status](https://github.com/Uniswap/uniswap-v2-core/workflows/CI/badge.svg)](https://github.com/Uniswap/uniswap-v2-core/actions)
[![Version](https://img.shields.io/npm/v/@uniswap/v2-core)](https://www.npmjs.com/package/@uniswap/v2-core)

===================

Morpheus Labs forked this the source code from UniSwap as a reference protocol based on smart contract for providing Decentralized Swap functions like UniSwap. Users can explore, modify and test the protocol on Morpheus Labs SEED platform.

Since this is a GNU License, for SEED platform users or any users who need to fork or clone this UniSwap protocol need to explicitly fork from this repo.

===================

In-depth documentation on Uniswap V2 is available at [uniswap.org](https://uniswap.org/docs).

The built contract artifacts can be browsed via [unpkg.com](https://unpkg.com/browse/@uniswap/v2-core@latest/).

# Local Development

The following assumes the use of `node@>=10`.

## Install Dependencies

`yarn`

## Compile Contracts

`yarn compile`

## Run Tests

`yarn test`

The test suite includes testing the following smart contracts

1. UniswapV2ERC20

Test cases include token deployment/transfer/approve

2. UniswapV2Factory

This contract implements methods for creating pair of tokens.
Test cases include pair creation

3. UniswapV2Pair

This contract implements methods for token pair governance and swap.
Test cases include mint, getInputPrice, swap, burn and etc