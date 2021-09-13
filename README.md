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
| enode://37b503a96340560bebbe62b2bb82c85552701011c02b84ac2b07e3a0e1de0550b937fbfb50d5d5a99c8525221ed09f7547efc0abe3ff5c3b4ddb91b92c41260e@31.210.159.189:30303 |
| enode://83be3068d059674b927556fed8b34a233b69bc4799e887e72e59da4364353f5e0b601039a2fc85b0821688998a07f1e8b44abd2f9f76f5441d2ae0b7ee4c8f08@31.210.159.190:30303 |
| enode://718e42c3d756df072eb601c30583ff925b9eecc9204bb880acd108c163dabc76a1213d9c6767f5a3baae350c93a96e5eb57fdc31dd4f359c50ec48dfa92fa384@152.228.180.128:30303 |
| enode://234345d954085ef1ed57e8376528694d1cae8169c621a840e020ddc6d028ca858ba48bdc453240074805c458c44510e71786a4e3f025192ebb6f71a5fe001552@176.31.72.208:30303 |
| enode://41ca36181923fb99a8d88e62b6892eac548205c8fb7cd088e081bbb948a7267c37a9bc035c8a86707443066a258adafe069db5572c34d99fa42556b2bd79d9f2@95.216.106.234:30303 |
| enode://bbcd4de4330356efcd188669bc13758e5eac868408c08124a271ac2513982e2ac14ed62ea158abb98ae9cdc51550fc2719580c6a27a1bbf262780e5f2baa9376@95.216.106.237:30303 |
| enode://15cbe4091f0ff05f8a20f5f664ad3bc9fcbd52397144e183032ec7d0e4b0ee3c457166a3eda83e077c581ea805a575e430abae14497a06d368c9c9b02333ab87@37.247.100.12:30303 |

## Authority WalletIDs

|WalletID |Owner |
|--|--|
| 0x4b9600CDF17968A4Aca4AE8Cd7E122436E7Ba08F| ParadoxChain Team |
| 0xd43150B32b200b3784AFe25475CD2aE05ca29a93| ParadoxChain Team |
| 0x8880FC76b680dfCAe151B9B1375FD5E76C79D864| ParadoxChain Team |

## PreBalanced WalletIDs

|WalletID |StartBalance  |
|--|--|
| 0xB83d64Bd25f5aAFe9D0373Cd6EF41A98dB7F4e48|  100.000.000 OXO|


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

