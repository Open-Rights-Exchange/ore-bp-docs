
Thanks for becoming a Block Producer on the Open Rights Exchange (ORE) Blockchain! 

## Getting Started

- Join the [ORE BP Telegram Channel](https://t.me/joinchat/C8vKvxQqx6TNqrYzMYUThA)
- Take a few minutes to learn about our ORE Protocol and Verifier service - in the next few months our block producers will be required to run verifiers in addition to their eosio node
- Download and install your eosio node
- Download the ORE BP config file and add your private key. REMEMBER TO USE BEST PRACTICES FOR BP SECURITY!
- Give us your public key & desired account name. We recommend using the same account name that you use on the EOS main net.
- Once you’ve done that we will create your account and select you as a Block Producer.

### Server Specifications

We expect all BPs to maintain a minimum level of CPU and RAM as needed by the ORE Blockchain. 
We’ve tested on both AWS and Google Cloud. 

Currently minimum requirements are based on our Google Cloud deployment:
- 32 GB of RAM per machine
- 10 GB RAM must be pinned using config file
-  2 Ghz CPU running on 2 or more cores (or equivalent)
100 Mb/s networking

### Security

We recommend the following tools to help secure your BP:
- Standard linux security-related tools (ssh, private/unroutable networks, IPTables and/or firewalls, etc.)
- Patroneos including its components such as fail2ban, HAProxy, etc.

Guidance on techniques found useful by block producers is available from a diverse array of public articles, including:
- [Basic insights](https://eosuk.io/2018/05/17/eos-block-producer-security-done-right)
- [More detailed insights](https://medium.com/eostribe/eos-bp-security-statement-e8cbf0df72db)
- [Audit guidelines](https://github.com/slowmist/eos-bp-nodes-security-checklist/blob/master/audit-en.md)
- [EOS Detroit](https://eosdetroit.io/block-producer/infrastructure)
- [EOS Canada](https://www.eoscanada.com/en/introducing-eos-canada-a-leading-block-producer-candidate#:~:text=We%20are%20pleased%20to%20officially,by%20reputable%20Canadian%20financial%20players.)

Many other mainnet block producers maintain descriptions of their approaches to security

