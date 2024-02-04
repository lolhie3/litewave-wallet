# Litewave Wallet
<p align="center">
  <img src="https://github.com/lolhie3/litewave-wallet/assets/96627041/fe214be6-423c-4bb4-b01a-d692bb851343">
  <h3 align="center">Litewave</h3>
  <p align="center">StupidWallet client with CLI</p>
</p>

## Getting started
First, create or import your wallet:
`create` or `import <walletfile.sw>`

After `creat`ing, your wallet's private key will be stored in the file `.\main.sw` 
and will be imported every time you start Litewave Wallet.

When `import`ing, wallet will be imported only for one time (you'll have to import it everytime, or use the `main.sw` file)
## Usage
Basic commands are:
`info` - show currently imported wallet info

```
> info
Address: SW_0xc0000000000
Is frozen: False
Boost: True
```
`balance` - show all of the coins you have

```
> balance
wavacoin: 0.0 WAV
```

`send <amount> <id> <recipient-data>` - it does what it says

```
> send 1 3 SW_0xczr5c36i4sj
Success
```
