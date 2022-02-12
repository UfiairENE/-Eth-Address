# -Eth-Address
This repo explains creating a new Ethereum address with Go. This address can be used to interact with the Ethereum blockchain network and perform various operations

To create a module
$ go mod init address
This will ensure the crypto and common packages included in your code are downloaded from GitHub and installed locally. It happens automatically, and the latest version should be pulled into your environment along with built-in Go modules.

To run the module
$ go run main.go

If you followed the instructions correctly and everything goes right, it must output something like this. The first line displays the private key, the Public key is second, and the third line displays your Ethereum address.
