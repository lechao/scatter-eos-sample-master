# scatter-eos-sample

### Scatter API 开发示例（由麦子钱包团队开发）

#### 基于 Scatter 接口的 EOS 基础操作示例

注：浏览器直接打开文件不能测试，需要部署到Web服务器后进行测试

/eos/sample01/index.html - 简洁版本

/eos/sample01/mainnet.html - 主网完整版本（支持登录、登出、转账、日志等）

/eos/sample01/kylin.html - Kylin测试网版本（支持登录、登出、转账、日志等）

测试地址：

http://developer.mathwallet.org/sample01/

https://developer.mathwallet.org/sample01/

### 测试方法

在钱包的 DAPP 中找到【麦子 DAPP 浏览器】应用，粘贴地址即可进行测试，该方式目前只支持主网环境。


### 如何切换 EOS 测试网络

1 在代码中更换 network 参数为测试网络

2 Jungle Testnet 信息

http://jungle.cryptolions.io/#apiendpoints

chainId: 038f4b0fc8ff18a4f0842a8f0564611f6e96e8535901dd45e43ac8691a1c4dca

创建测试账号&申请测试Token：http://jungle.cryptolions.io/

3 使用 Scatter 插件，添加【网络】和【密钥】，然后新建身份，在Chrome中进行debug。

4 Kylin Testnet 信息

https://www.cryptokylin.io/

chainId: 5fff1dae8dc8e2fc4d5b23b2c7665c97f9e9d8edf2b6485a86ba311c25639191

创建测试账号&申请测试Token：https://www.cryptokylin.io/#tools


### 一些其他的有用参考

#### 基于 Scatter 接口的 EOS 原力 基础操作示例

/eosforce/sample02

测试地址：

http://developer.mathwallet.org/sample02/

原力的scatter插件配置方法（测试用）： https://zhuanlan.zhihu.com/p/43034314


#### eosjs说明文档

https://github.com/eoshackathon/eos_dapp_development_cn/blob/master/docs/eosjs_manual.md

#### DAPP开源项目列表

http://blog.eosdata.io/index.php/eosopensource/

#### 环境和常用开发文档

https://github.com/eoshackathon/eos_dapp_development_cn


#### 常用RPC地址（主网）

国内

https://mainnet.eoscannon.io/

http://api.eosbeijing.one/

https://eos.greymass.com/

国外

https://node.betdice.one

https://api.eosnewyork.io/

https://mainnet.eoscanada.com/

https://nodes.get-scatter.com/


#### DAPP上线麦子钱包的方法

http://blog.medishares.org/?p=398