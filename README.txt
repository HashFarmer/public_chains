#### public_chains

比较归纳理解各种公链的异同

1、公链本质上都是做为数据库存在的，与之交互需要通过命令行，对应的区块浏览器可以说是一个可以窥视其一斑的窗口






#### Ethereum
以太坊，如果我们不借助于web3.js，ethers.js，web3.py，怎么与之交互？
geth？ curl 的post命令？

geth可以设置成很多形式，json-rpc, http, websocket, ipc, graphql



区块链的数据存储、P2P的分布式网络、JSON-RPC的SERVER，最终汇合而成Crypto

JSON-RPC可以通过两种方式调用？
1、http，2、websocket，通过json-rpc与以太坊交互，不需要安装geth，只需要可以连接到一个node即可

很多语言把把以太坊json-rpc做了封装例如，web3.js是js封装版本，web3.py是python的封装版本

不用把自己的电脑加入ethereum 网络即可访问ethereum网络，因为ethereum网络上的节点对外提供服务：
curl --url https://goerli.infura.io/v3/{your_api_key} 
-X POST 
-H "Content-Type: application/json" 
-d '{"jsonrpc":"2.0","method":"eth_blockNumber","params":[],"id":1}'
原则上，json-rpc所有的api都可以用curl方式访问

"method": {可选项}
"eth_blockNumber", "eth_getBalance", "eth_accounts", "eth_sendTransaction"








#### BNB Chain



#### Atom



#### Sonala


#### Avalanche
