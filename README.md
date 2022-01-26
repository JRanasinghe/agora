# Agora

Agora is a set of Plutus scripts that compose together to form a governance system.

### What is Agora

Goals:

-   Agora aims to reduce duplication in Liqwid and LiqwidX and to serve as a one-size-fits-all governance library for projects on the Cardano blockchain.
-   Agora aims to be modular and flexible for specific needs but presents an opinionated architecture.

Non-goals:

-   Agora is not a DAO. It doesn't have tokenomics or even a token. It is simply a library for governance.
-   Agora doesn't aim to provide any primitive tools for Plutus that are not governance-specific. For this, see [plutus-extra](https://github.com/Liqwid-Labs/plutus-extra/).

## Project setup

An up to date version of the [`nix` package manager](nixos.org) (>=2.3) is required to build this project. For information on how to install, see the [nixos website](https://nixos.org/download.html). Important: See also [this section](https://github.com/input-output-hk/plutus#nix-advice) on binary caches.

Open a dev-shell with `nix develop` and build with `cabal build`.

## Documentation

Documentation for Agora may be found in [docs](./docs).

## Road-map

### v1

-   [ ] Governor
-   [ ] Treasury
-   [ ] Staking pool
-   [ ] Proposals
-   [ ] Effects

### v2

-   [ ] Rewards distribution

### Beyond

-   [ ] ...
