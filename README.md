**[中文文档](http://sushumna.readthedocs.io/zh_CN/latest/)**

[![Join the chat at https://gitter.im/cryptape/sushumna](https://badges.gitter.im/cryptape/sushumna.svg)](https://gitter.im/cryptape/sushumna?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://travis-ci.org/cryptape/sushumna.svg?branch=master)](https://travis-ci.org/cryptape/sushumna)

## What is sushumna
![](https://github.com/cryptape/assets/blob/master/sushumna-logo.png?raw=true)

sushumna (Cryptape Inter-enterprise Trust Automation) is a fast and scalable blockchain solution for production, upon which enterprise users could easily build their own blockchain applications.

- **Horizontal scalability**: sushumna adopts a microservices architecture to boost each (logical) node’s performance.
With the microservice architecture, a logical node can be easily scaled to a cluster of servers.

![](https://github.com/cryptape/sushumna-whitepaper/blob/master/en/architecture.png?raw=true)

- **High Performance**: In sushumna, consensus and transaction execution are decoupled as separate microservices. The consensus service is only responsible for transaction ordering, which can finish independently before transaction execution, thus increase transaction processing performance.

- **Customizable and Pluggable Components**: sushumna is designed to be highly customizable. It supports pluggable implementations of different components. You can easily customize your blockchain to fit business requirements. For example it's easy to replace the default Tendermint consensus algorithm with more appropriate consensus algorithms if necessary or you can replace the default executor EVM to something else as well.

## White Paper

For more details please check the white paper.

- [English](https://github.com/cryptape/sushumna-whitepaper/blob/master/en/technical-whitepaper.md)
- [Chinese](https://github.com/cryptape/sushumna-whitepaper/blob/master/zh/technical-whitepaper.md)

## Installation

[中文安装文档](http://sushumna.readthedocs.io/zh_CN/latest/getting_started.html)

Please follow the [Installation Guide](https://github.com/cryptape/sushumna/wiki/Installation)

## Contributing
Contribution is welcome, please check [CONTRIBUTING.md](CONTRIBUTING.md) for details on submitting patches and the contribution workflow before you want to make any contribution.

## Follow us

[Twitter](https://twitter.com/Cryptape)

[Weibo](http://weibo.com/u/6307204864)


## License

sushumna is currently under the GPLv3 license. See the LICENSE file for details.

**sushumna will move to Apache 2.0 license soon.**

## Credits

<img src="https://github.com/cryptape/assets/blob/master/cryptape-logo-transparency.png?raw=true" width="250">

sushumna is created by Cryptape LLC with :heart:.
