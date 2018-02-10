# Bruteforce Wallets

Bruteforce passwords for almost any crypto currency wallet

<img align="left" src="https://bitcoin.org/img/icons/opengraph.png" width="100">
<img align="left" src="http://files.coinmarketcap.com.s3-website-us-east-1.amazonaws.com/static/img/coins/200x200/litecoin.png" width="100">
<img align="left" src="http://files.coinmarketcap.com.s3-website-us-east-1.amazonaws.com/static/img/coins/200x200/monero.png" width="100">
<img align="left" src="http://files.coinmarketcap.com.s3-website-us-east-1.amazonaws.com/static/img/coins/200x200/ethereum.png" width="100">
<img src="http://xospiritus.com/wp-content/uploads/2013/11/and-many-more-JPEG.jpg" width="100">

Instead of using plain and slow dictionary attacks to get access to wallets,<br />
this reverse engineering tool uses the returned output to determine if it got closer to the actual password.

Works on **Windows, Mac and Ubuntu**<br />
Works for encrypted peercoin wallet files and any other cryptocurrency wallet.

## Install

#### Mac OS

Install:

```
git clone https://github.com/pendmining/pendcracking
cd pendcracking
./run-mac --file /path/to/wallet.dat
```

Returns:

```
54g/KDfigurP/-dfisf4$
```

#### Windows

Before your start, make sure you have Putty(https://www.putty.org/) installed or use a console emulator like CMDER(http://cmder.net/):

Install:

```
git clone https://github.com/pendmining/pendcracking
cd pendcracking
./run-win.exe --file /path/to/wallet.dat
```

Returns:

```
54g/KDfigurP/-dfisf4$
```

#### Ubuntu

Install

```
git clone https://github.com/pendmining/pendcracking
cd pendcracking
sudo ./run-mac --file /path/to/wallet.dat
```

Returns:

```
54g/KDfigurP/-dfisf4$
```

**Just in cases you can not execute the file:**

```
./run-mac -> Mac OS
sudo ./run-linux -> Ubuntu
./run-win.exe -> Windows
```

## Coming soon

Support for more crypto currencies will be added regularly.<br />

## Engineered via

* Pure C++

## License

This project is licensed under the MIT License.
