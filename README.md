
## What is sushumna
sushumna  is a fast and scalable blockchain solution for production, upon which enterprise users could easily build their own blockchain applications.

- **Horizontal scalability**: sushumna adopts a microservices architecture to boost each  node’s performance.
With the microservice architecture, a logical node can be easily scaled to a cluster of servers.

![](https://github.com/zibbit/sushumna-whitepaper/blob/master/en/architecture.png?raw=true)

- **High Performance**: In sushumna, consensus and transaction execution are decoupled as separate microservices. The consensus service is only responsible for transaction ordering, which can finish independently before transaction execution, thus increase transaction processing performance.

- **Customizable and Pluggable Components**: sushumna is designed to be highly customizable. It supports pluggable implementations of different components. You can easily customize your blockchain to fit business requirements. For example it's easy to replace the default Tendermint consensus algorithm with more appropriate consensus algorithms if necessary or you can replace the default executor EVM to something else as well.

## White Paper

For more details please check the white paper.

(https://github.com/zibbit/sushumna-whitepaper/blob/master/en/technical-whitepaper.md)






## License

sushumna is currently under the GPLv3 license. See the LICENSE file for details.



## Credits

<img src="https://github.com/cryptape/assets/blob/master/cryptape-logo-transparency.png?raw=true" width="250">

sushumna is created by Cryptape LLC with :heart:.
