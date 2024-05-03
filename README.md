 <h1 align="center">Awesome 3074</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
  </p>

  <p align="center">📖 A curated list of resources dedicated to EIP-3074</p>
  <p align="center">Please check the <a href="CONTRIBUTING.md">contribution guidelines</a> for information on formatting and writing pull requests.</p>

## Learning Resources
A list of useful resources to learn about EIP-3074 and its implications.

### Blogs
- [A note on EIP-3074](https://hackmd.io/@matt/note-on-3074)
- [ERC-4337 vs EIP-3074: False dichotomy](https://notes.ethereum.org/@yoav/erc-4337-vs-eip-3074-false-dichotomy)
- [Can EIP-3074 and ERC-4337 be used together?](https://notes.ethereum.org/@yoav/eip-3074-erc-4337-synergy)
- [3074 ideas/use-cases](https://notes.ethereum.org/@lightclient/ryK4ktOxA)
- [How to preserve EOA check on your contract post EIP-3074?](https://github.com/mattdf/EIP3074Protection)
- [EIP-3074: Risks/Opportunities for Smart Account Adoption (and why we need EIP-5003)](https://safe.global/blog/eip-3074-risks-opportunities-for-smart-account-adoption)
- [Is EIP-3074 the Next Step for Account Abstraction?](https://blog.ambire.com/eip-3074-explained)
- [The pitfalls of EIP-3074, and how to avoid them](https://docs.zerodev.app/blog/3074-pitfalls) ([Twitter thread](https://twitter.com/decentrek/status/1784919543036719251))

### Videos
- [EIP-3074 and the role of the EVM in a L2 world](https://www.youtube.com/watch?v=eEOb0hlrCLU)
- [EIP-3074 - Matt Garnett](https://www.youtube.com/watch?v=AffftIs6XFE)
- [An introduction to EIP-3074](https://www.youtube.com/watch?v=zToZVpKPW6Q)

### Podcasts
- [3074 vs 4337 with Matt Garnett, Gregory Markou, and Joseph Delong](https://open.spotify.com/episode/7kxqs2b7GCYrQZdUfPSOIF)


## 3074 invoker implementations

All of these implementations are for batched transactions. **None of these implementations are audited.**

### Use-case: Batched Transactions

- [eip-3074-foundry](https://github.com/anton-rs/3074-invokers/tree/main) ([clabby](https://github.com/clabby), [anna-carroll](https://github.com/anna-carroll))
- [account-abstraction-invoker](https://github.com/0xPolygon/account-abstraction-invoker) ([ZeroEkkusu](https://github.com/ZeroEkkusu), [gretzke](https://github.com/gretzke), [web3security](https://github.com/web3security), [mt-polygon-technology](https://github.com/mt-polygon-technology))
- [eip3074-example-contracts](https://github.com/quilt/eip3074-example-contracts/tree/master) ([adietrichs](https://github.com/adietrichs))
- [invoker](https://github.com/wevm/invoker) ([wevm](https://github.com/wevm))
- [transaction-invoker](https://github.com/Mrtenz/transaction-invoker/tree/main) ([Mrtenz](https://github.com/Mrtenz), [adlerjohn](https://github.com/adlerjohn))
- [EIP3074-Invokers](https://github.com/Amxx/EIP3074-Invokers/tree/master) ([Amxx](https://github.com/Amxx)) (This repo has some obvious bugs like passing an [empty commit](https://github.com/Amxx/EIP3074-Invokers/blob/70d2fee4c250561d0996b57e74446e29acaeeab9/contracts/modules/BatchInvoker.sol#L16))
- [InvokerDemo](https://github.com/jayden-sudo/InvokerDemo) ([jayden-sudo](https://github.com/jayden-sudo))

### Use-case: Showing how an EOA could migrate to a Smart Wallet by allowing it to use the EOA funds

- [Coinbase hackathon project](https://github.com/coinbase/smart-wallet/pull/61) ([wilsoncusack](https://github.com/wilsoncusack))

### Use-case: Turning ETH into an ERC-20 compatible token

- [WETH3074](https://github.com/axic/weth3074) ([axic](https://github.com/axic))

## Dev Tools

- [alphanet](https://github.com/paradigmxyz/alphanet): Reth AlphaNet is a testnet OP Stack rollup aimed at enabling experimentation of bleeding edge Ethereum Research. AlphaNet currently supports EIP-3074.
- [kakarot](https://github.com/kkrt-labs/kakarot/pull/1104): Kakarot's EIP-3074 implementation in Cairo.
- [dahe](https://github.com/quilt/dahe): a CLI tool for signing EIP-3074 auth messages.
- [eip3074-snap](https://github.com/gretzke/eip3074-snap): Experimental MM snap for EIP-3074.
- [remix-eip3074-signer-plugin](https://github.com/quilt/remix-eip3074-signer-plugin): Remix editor for EIP-3074.
