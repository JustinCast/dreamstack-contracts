<p align="center">
	</a>
	<a href="https://git.io/col">
		<img src="https://img.shields.io/badge/%E2%9C%93-collaborative_etiquette-brightgreen.svg" alt="Collaborative Etiquette">
	</a>
  <a href="https://developers.blockmatic.io">
		<img src="https://img.shields.io/badge/code%20style-blockmatic-brightgreen.svg" alt="Blockmatic Standard">
	</a>
	<img src="https://img.shields.io/dub/l/vibe-d.svg" alt="MIT" />
	<a href="https://twitter.com/intent/follow?screen_name=blockmatic_io">
		<img src="https://img.shields.io/twitter/follow/blockmatic_io.svg?style=social&logo=twitter" alt="Follow on Twitter" />
	</a>
	<a href="https://t.me/blockmatic">
		<img src="https://img.shields.io/badge/-Chat%20on%20Telegram-blue?style=social&logo=telegram" alt="Chat on Telegram">
	</a>
</p>

# TELOS Smart Contracts Starter

Jumpstart smart contract development on TELOS following best practices.

## TELOS

Best in class C++ EOSIO protocol technology providing fast, scalable and eco-freindly blockchain augmented by a growing library of Telos services and innovations. Free accounts, work proposals, dapp grants, decentralized exchange, dstor, bancor protocol, telos community and foundation.

## Disclaimer

This is a work in progress. Feel free to reach us out on telegram for clarifications.
https://t.me/blockmatic

## Features

- Build with cmake.
- Include headers.
- Ricardian contract tooling.
- Coding guidelines & best practices documention.

## Best Practices

- How to react to receiving tokens to execute an action (payable actions)
- How to have a reliable id index in eosio
- When use blockchain storage when use offchain even with blockchain verification 
- Best way to CRUD
- How to decide scopes
- Easier way to do table migrations

## Getting Started

- install eosio/telos https://github.com/Telos-Foundation/telos  
- install eosio.cdt https://eosio.github.io/eosio.cdt/latest/index 

## Build and Deploy

- cd to `build/` directory
- run the command `cmake ..`
- run the command `make`
 
After build 
 
- The built smart contract is under the 'teloscontracts' directory in the 'build' directory
- You can then do a 'set contract' action with 'cleos' and point in to the './build/teloscontracts' directory

Additions to CMake should be done to the CMakeLists.txt in the './src' directory and not in the top level CMakeLists.txt

## eosio-init

This project was boostrapped using `eosio-init` utility from the EOSIO Contract Development Toolkit.

## Contributing

Read the [contributing guidelines](https://developers.blockmatic.io) for details.

## Contributors ✨

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table>
  <tr>
    <td align="center"><a href="https://gaboesquivel.com"><img src="https://avatars0.githubusercontent.com/u/391270?v=4" width="100px;" alt="Gabo Esquivel"/><br /><sub><b>Gabo Esquivel</b></sub></a><br /><a href="#ideas-gaboesquivel" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/telosdreamstack/telos-contracts-starter/commits?author=gaboesquivel" title="Code">💻</a></td>
    <td align="center"><a href="http://lucca65.github.io"><img src="https://avatars1.githubusercontent.com/u/1082127?v=4" width="100px;" alt="Julien Lucca"/><br /><sub><b>Julien Lucca</b></sub></a><br /><a href="#ideas-lucca65" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="http://CryptoLions.io"><img src="https://avatars2.githubusercontent.com/u/37701692?v=4" width="100px;" alt="Bohdan Cryptolions"/><br /><sub><b>Bohdan Cryptolions</b></sub></a><br /><a href="#ideas-ansigroup" title="Ideas, Planning, & Feedback">🤔</a></td>
  </tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->
Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

## TELOS DreamStack

This repository is part of the TELOS DreamStack Project which provides set of guidelines, tools and starters to speed up dApp development following best practices for security, performance and maintainability of your application.

The code style convention aims to maximize reusability and facilitate collaboration. We have chosen the stack carefully so that it allows us to write robust and performant applications with more concise and readable code.

## Blockmatic

Blockmatic is building robust ecosystem of people and tools for development of decentralized applications.

[blockmatic.io](https://blockmatic.io)

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->

<!-- display the social media buttons in your README -->

[![Blockmatic Twitter][1.1]][1]
[![Blockmatic Facebook][2.1]][2]
[![Blockmatic Github][3.1]][3]

<!-- links to social media icons -->
<!-- no need to change these -->

<!-- icons with padding -->

[1.1]: http://i.imgur.com/tXSoThF.png (twitter icon with padding)
[2.1]: http://i.imgur.com/P3YfQoD.png (facebook icon with padding)
[3.1]: http://i.imgur.com/0o48UoR.png (github icon with padding)

<!-- icons without padding -->

[1.2]: http://i.imgur.com/wWzX9uB.png (twitter icon without padding)
[2.2]: http://i.imgur.com/fep1WsG.png (facebook icon without padding)
[3.2]: http://i.imgur.com/9I6NRUm.png (github icon without padding)


<!-- links to your social media accounts -->
<!-- update these accordingly -->

[1]: http://www.twitter.com/blockmatic_io
[2]: http://fb.me/blockmatic.io
[3]: http://www.github.com/blockmatic

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->
