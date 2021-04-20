# Rust Bot
A template bot made in Rust for Rocket League made with the [RLBot framework](https://github.com/RLBot/RLBot).

## Setup and run
- Install Rust and Cargo.
- Install [RLBotGUI](http://rlbot.org/). See the [install guide](https://www.youtube.com/watch?v=oXkbizklI2U) for guidedance.
- Run RLBotGUI, press "Add > Add config" and select `rustbot_dev/rustbot.cfg`. The bot should now appear in the GUI.
- Add the bot to a team and start a match. Rocket League should open and immediate start a match with the bot.

## Distribution
When the bot is ready to be distributed (e.g. submitted to a tournament):
- Run `cargo build --release`.
- Put the resulting `target/release/rustbot.exe` in `rustbot/`.
- Zip `rustbot/` and submit it.
