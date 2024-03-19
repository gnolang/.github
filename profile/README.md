<pre>
      ____ _____  ____      Discover:  <a href="https://www.gno.land/">Homepage</a> - <a href="https://github.com/gnolang/gno">Main repo</a>
     / __ `/ __ \/ __ \     Networks:  <a href="https://test3.gno.land">Test3 (latest)</a> - <a href="https://staging.gno.land">Staging</a>
    / /_/ / / / / /_/ /     Learn:     <a href="https://docs.gno.land">Official Documentation</a> - <a href="https://gno-by-example.com">Gno by Example</a> - <a href="https://github.com/gnolang/awesome-gno">Awesome Gno</a>
    \__, /_/ /_/\____/      Social:    <a href="https://twitter.com/_gnoland">Twitter</a> - <a href="https://discord.gg/tF2X8M6cVj">Discord</a> - <a href="https://reddit.com/r/gnoland">Reddit</a> - <a href="https://youtube.com/@_gnoland">YouTube</a>
   /____/                   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
</pre>

***

## Overview
<details><summary>Why Gno?</summary>

- A better programming language for smart contracts: Gno.land utilizes the Gno programming language, which is an interpreted variation of Go. It is executed through a specialized virtual machine called the GnoVM, purpose-built for the Gno.land blockchain. There are some differences among the languages: Gno does not support Goroutines, channels and non-deterministic libraries like `crypto/rand`, and it supports additional features like automatic persistence of global variables for storing state.

- Consensus Protocol: Gno.land achieves consensus between nodes using the Tendermint2 consensus algorithm. Tendermint2 is a variation on the well-established [Tendermint consensus algorithm](https://docs.tendermint.com/v0.34/introduction/what-is-tendermint.html) used in many Cosmos blockchains, which is Byzantine Fault Tolerant, has instant finality (Users can be sure their transactions are finalized as soon as a block is created, unlike Bitcoin) and can easily be extracted to create new interoperable TM2-based blockchains.

- Inter-Blockchain Communication (IBC): In the future, Gno.land will be able to communicate and exchange data with other blockchain networks within the Cosmos ecosystem through the Inter-Blockchain Communication (IBC) protocol.
</details>

<details><summary>Why Go Based?</summary>
The decision to base Gno.land's language on Go was influenced by the following factors:

- An established language: using Go instead of creating a new programming language enables existing Go developers to bring over their knowledge to Gno, making adopting the language not an intrinsic time investment on the success of the blockchain. Gno re-uses the syntax and a majority of the standard libraries, adapts Go's package model and adapts it for the blockchain context.
- Security through the package model: by leveraging Go's existing package model, which distinguishes between exported and unexported symbols, realms (smart contracts) are capable of simply discriminating what functionality, types and data should be available for consumption outside of the realm. By enforcing all on-chain published code to be open source and creating a public on-chain registry of published re-usable packages, Gno realms (smart contracts and packages can be easily audited and build upon each other's reputation.
</details>

<details><summary>Coming from other blockchains like Ethereum?</summary>

Gno.land offers a few distinct advantages to Ethereum:

1. Transparent and Auditable Smart Contracts: Gno.land Smart Contracts are fully transparent and auditable by users because the actual source code is uploaded to the blockchain. In contrast, Ethereum uses Solidity, which requires precompilation into bytecode, leading to less transparency as bytecode is stored on the blockchain, not the human-readable source code.

2. General-Purpose Language: Gno.land's Gno is a general-purpose language, similar to Go, extending its usability beyond the context of blockchain, and allowing Gno to tap into the already existing ecosystem of Go packages. In contrast, Solidity is designed specifically for Smart Contracts on the Ethereum platform.
</details>


## Choose your path:
<details><summary>Build on Gno.land</summary>

- \[Blockchain Background] [I want to learn a bit of blockchain's foundational elements first](https://github.com/gnolang/guide/blob/main/docs/knowledge-corner/blockchains-101/blockchain.md)

- \[Getting Started] [I want to get started with Gno as fast as possible](https://github.com/gnolang/getting-started)

- \[Setup] [I want to jump in and get started hacking on Gno.land](https://github.com/gnolang/guide/blob/main/docs/engineering/gno.land/setup.md)

- \[Tools] [I want to have a look at some of the code-editor support for Gno](https://github.com/gnolang/guide/blob/main/docs/engineering/gno.land/tools.md)

- \[Team] [I want to understand more about the team behind Gno.land](https://github.com/gnolang/guide/blob/main/docs/engineering/gno.land/team.md)

- \[Workshops] [I want to know more by reviewing some of your previous workshops at various conferences/hackathons](https://github.com/gnolang/workshops)

- \[Cosmos] [I want to understand more about Cosmos](https://github.com/gnolang/guide/blob/main/docs/knowledge-corner/cosmos.md)
</details>

<details><summary>Learn how to write Smart Contracts with Gno</summary>

- \[Quickstart] [I want to get write a simple contract in Gno](https://github.com/gnolang/gno/blob/master/docs/how-to-guides/simple-contract.md)

- \[Playground] [I want to learn Gnolang by writing and testing code on the Gno Playground](https://play.gno.land)

- \[Code-Editor Support] [I want to have a look at which code editors are supported for Gno development](https://github.com/gnolang/guide/blob/main/docs/engineering/gno.land/tools.md)
</details>

<details><summary>Contributing</summary>

- [I want to contribute to Gno](https://github.com/gnolang/gno/blob/master/CONTRIBUTING.md)

- [I want to understand more about your Grants & Ecosystem development](https://github.com/gnolang/ecosystem-fund-grants)

- [I want to learn more about incentivized contribution; ie, Game of Realms](https://gno.land/game-of-realms)
  
- [I want to see what other hackers are building on Gno.land](https://github.com/gnolang/hackerspace)

- [I want to contribute to your documentation efforts](https://github.com/gnolang/guide/blob/main/docs/engineering/conventions/documentation.md)

- [I want to understand more about your code contribution best practices](https://github.com/gnolang/guide/blob/main/docs/engineering/conventions/go.md)
</details>

# Resources
<details><summary>Developer Resources</summary>

- [Official Documentation](https://docs.gno.land): The official documentation of Gno.land.
- [Gno CLI](https://github.com/gnolang/gno): The Gno CLI is Gno’s primary development and testing environment. All main realms and packages can be found here.
- [How-To-Guides](https://docs.gno.land/how-to-guides/simple-contract)
- [Local Setup](https://docs.gno.land/getting-started/local-setup)
- [Gno By Example](https://gno-by-example.com/)
- [Awesome-Gno](https://github.com/gnolang/awesome-gno)
- **Clients:**
  - [Gno JS Client](https://github.com/gnolang/gno-js-client)
  - [TM2 JS Client](https://github.com/gnolang/tm2-js-client)
</details>

<details><summary>Wallets</summary>

- [Adena](https://adena.app/): Currently, Gno has one main wallet to choose from that any developer can [fork](https://github.com/onbloc/adena-wallet) and extend to build their own.
</details>

<details><summary>Partners</summary>

- [Berty](https://berty.tech/)
- [OnBloc](https://onbloc.xyz/)
- [Teritori](https://teritori.com/)
</details>

<details><summary>Community</summary>

- [Discord](https://discord.gg/S8nKUqwkPn)
- [Twitter](https://twitter.com/_gnoland)
- [Telegram](https://t.me/gnoland)
- [YouTube](https://www.youtube.com/@_gnoland)
</pre>
</details>
