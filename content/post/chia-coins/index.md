---
title: Chia coins
date: 2021-05-05T12:02:28.220Z
draft: false
featured: false
image:
  filename: https://cdn.wccftech.com/wp-content/uploads/2021/05/1-xdY3Q20D6JF5QroT3JpJlg.png
  focal_point: Smart
  preview_only: false
---
<!--StartFragment-->

In Chia coins can be created in two ways; either as a reward to farmers, or as the output of a transaction.

## Chia rewards

The main reward to farmers is currently a fixed amount of 2 XCH per block, with 16 blocks expected every 5 minutes. The coinbase reward amount is halved every 3 years.

The fees coin amount fluctuates as it contains a base amount plus the sum of all transaction fees for the block.

## Chia transactions

Coins are locked by a puzzle, which is a program that takes an input solution, and if you provide the right solution to the puzzle you can spend the coin.

When a coin is spent it is destroyed and it's value is transferred into new coins.

Having ownership of a coin typically means that you control a private key that allows you to solve the puzzle that locks the coin. To transfer the coin to somebody else you solve the puzzle with your private key and create a new coin which has a puzzle that can only be solved by the private key of the receiver. If you are sending and receiving Chia using a wallet this is handled automatically for you by the wallet.

It is also possible to create smart transactions which are programs that do something more sophisticated before creating a new coin. In Chia smart transactions are created using a programming language called Chialisp™.

## Coins in the Chia blockchain™

All coins have an amount, a puzzle hash, and parent coin info. Coinbase coins also have a signature.

* **Amount** - Specifies how much Chia the coin is worth.
* **Puzzle hash** - Hash of the puzzle contained within the coin. In order to spend the coin you need to reveal the puzzle and provide the correct solution.
* **Parent coin info** - For coinbase coins this is the hex value of the height. For transaction fees coins it is the height of the block hashed twice.
* **Signature** - Can be used to prove the authenticity of the coin.