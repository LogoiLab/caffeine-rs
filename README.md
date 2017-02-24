#   c a f f e i n e - r s 

Caffeine-rs uses the shift-release key to keep the screen awake without locking or starting a screensaver.

Cross platform is the goal with an emphasis on Windows which is what the original caffeine application was designed for.

[Original Caffeine By Zhorn Software](http://www.zhornsoftware.co.uk/caffeine/)

Caffeine takes no inputs, but it may read a configuration file of you place one in the same directory as itself. The configuration file is a toml file named `caffeine.toml`. An example `caffeine.toml` file:

> caffeine.toml
```
refresh_rate = 10
```
This modifies the default refresh rate of once every 59 seconds to once every 10 seconds.

Crates Used
===

Universal
---
> chrono ![](https://img.shields.io/crates/v/chrono.svg)

> toml ![](https://img.shields.io/crates/v/toml.svg)

> serde ![](https://img.shields.io/crates/v/serde.svg)

Unix
---
> uinput ![](https://img.shields.io/crates/v/uinput.svg)

Windows
---
> keystroke ![](https://img.shields.io/crates/v/keystroke.svg)
