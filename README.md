# Guessing Game

Based on the [Build an Onchain Guessing Game](https://learn.calyptus.co/courses/13-build-an-onchain-guessing-game/)
lesson, this project builds an on-chain guessing using Anchor and the Orao VRF.

## Table of Contents

- [Guessing Game](#guessing-game)
    - [Table of Contents](#table-of-contents)
    - [Getting Started](#getting-started)
    - [Contributing](#contributing)
    - [Questions](#questions)
    - [License](#license)

## Getting Started

To use this fork, you need to have Solana, Anchor and Rust installed on your machine.

- Solana

```bash
sh -c "$(curl -sSfL https://release.solana.com/v1.17.28/install)"
```

- Anchor using avm

```bash
cargo install --git https://github.com/coral-xyz/anchor avm --locked --force

sudo apt-get update && sudo apt-get upgrade && sudo apt-get install -y pkg-config build-essential libudev-dev libssl-dev # for Linux systems only

avm install latest

avm use latest
```

To use the fork, follow the steps outlined below:

1. Clone your forked repo.

```bash
git clone https://github.com/<YOUR-USERNAME>/guessing-game
```

2. Change directory into the root of your cloned repo and run

```bash
anchor build && anchor keys list
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Questions

Did you encounter a challenge following the tutorial or running the fork?
Head over to our [learning support](https://discord.com/channels/1130457754826461216/1132978998155165806) channel on
our [Discord](https://discord.gg/38KftAhW) or alternatively, raise a ticket.

We are always happy to lend a helping hand

## License

All files within this repository are licensed under the MIT License unless explicitly stated otherwise.

100% Open Source software.

© 2023 [Calyptus](https://www.calyptus.co/) - See [LICENSE](https://opensource.org/license/mit/) for details.
