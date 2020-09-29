# Bevy Simple Networking (Prototype)
This crate provides basic network functionality for the Bevy engine. While it is in a prototype stage, it is relatively easy to use and has been tested to work.

It currently implements a **TCP-based client and server** as well as a **UDP-based client and server**.

As it is not on [crates.io](https://crates.io), to install it follow the directions below:
  1. Open a terminal instance in your project's root directory
  2. Run `git clone https://github.com/0x22fe/bevy_prototype_simple_net`
  3. Add `bevy_prototype_simple_net = { path = "bevy_prototype_simple_net", version = "0.1" }` under the dependencies section in your Cargo.toml file

You can then import it with `use bevy_prototype_simple_net;` and start using it. For more information and to see it in action, check out the [examples](./examples/README.md) and view/run an example (eg. `cargo run --example net_server`).

# Contributing
If you have any suggestions, create an issue and I'll take a look at it. If you wish to contribute, simply create a pull request and I'll review it. If you feel like you have contributed a significant amount of code, feel free to add yourself to the authors list in the `Cargo.toml` file.

# License
Licensed under the [MIT License](./LICENSE).
