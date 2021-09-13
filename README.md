# ParadoxChain

Paradox Chain is an Ethereum-based PoA blockchain. 
Paradox Smart Chain uses the Proof-of-Authority consensus.

## Websites

|SiteName|URL|
|--|--|
|Main Web|https://paradoxchain.com|
|Node Stats|http://stats.paradoxchain.com|

| P2P Nodes                                                    |
| ------------------------------------------------------------ |
| enode://690629ea6430ea5ce3288f7b1727ade9f66b503bb12a7e39fe4db4605289b7e1977434c7a591fe85635b83a0d476f54b0f1b57a8a1daa233a011a0fa923fe858@152.228.159.11:36901 |
| enode://c8adc00a73a1e314d7acae4aa7e915656d5d5570870113c4e79efb5f23b62bf3cae9cdbc0b07ed56dd588f5923514235ad1467471372ad66ec76513d085dd78f@152.228.159.11:36902 |
| enode://9227695ca12cb7f4d6a27ff188093a7e6688e0fe9918357a2747d991750b1f2d668210857eda4c97b61bd20bfb91c8abf5efd48fa1ccb9a02b85de90635bd634@152.228.159.11:36903 |

## Authority WalletIDs

|WalletID |Owner |
|--|--|
| 0x4b9600CDF17968A4Aca4AE8Cd7E122436E7Ba08F| ParadoxChain Team |
| 0xd43150B32b200b3784AFe25475CD2aE05ca29a93| ParadoxChain Team |
| 0x8880FC76b680dfCAe151B9B1375FD5E76C79D864| ParadoxChain Team |

## PreBalanced WalletIDs

|WalletID |StartBalance  |
|--|--|
| 0xB83d64Bd25f5aAFe9D0373Cd6EF41A98dB7F4e48|  100.000.000 DOX|


## For Metamask/PocketToken

You can use it with an RPC connection with a wallet such as Metamask. 

||Detail|
|--|--|
| RPC|  https://rpc.paradoxchain.com|
| ChainID |  36900|
| Symbol|  DOX|

## Popular token contract addresses

|Token|Name|Contract Address  |Total Supply|*
|--|--|--|--|--|
|||||Mintable/Burnable|

## genesis.json

```json
{
  "config": {
    "chainId": 36900,
    "homesteadBlock": 0,
    "eip150Block": 0,
    "eip150Hash": "0x0000000000000000000000000000000000000000000000000000000000000000",
    "eip155Block": 0,
    "eip158Block": 0,
    "byzantiumBlock": 0,
    "constantinopleBlock": 0,
    "petersburgBlock": 0,
    "istanbulBlock": 0,
    "clique": {
      "period": 15,
      "epoch": 30000
    }
  },
  "nonce": "0x0",
  "timestamp": "0x613f0899",
  "extraData": "0x00000000000000000000000000000000000000000000000000000000000000004b9600cdf17968a4aca4ae8cd7e122436e7ba08f8880fc76b680dfcae151b9b1375fd5e76c79d864d43150b32b200b3784afe25475cd2ae05ca29a930000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
  "gasLimit": "0x47b760",
  "difficulty": "0x1",
  "mixHash": "0x0000000000000000000000000000000000000000000000000000000000000000",
  "coinbase": "0x0000000000000000000000000000000000000000",
  "alloc": {
    "b83d64bd25f5aafe9d0373cd6ef41a98db7f4e48": {
      "balance": "100000000000000000000000000"
    }
  },
  "number": "0x0",
  "gasUsed": "0x0",
  "parentHash": "0x0000000000000000000000000000000000000000000000000000000000000000",
  "baseFeePerGas": null
}

```

