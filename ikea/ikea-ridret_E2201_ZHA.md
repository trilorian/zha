I have expanded on [damru](https://community.home-assistant.io/u/damru/summary)'s blueprint for controlling the Rodret dimmer from IKEA, so that it now handles triple click.

It's a very simple remote with only two buttons:
![IKEA_Rodret|200x300](upload://vgztk24OsrTmkjMOAuCyaZR9KLg.png)

## Controls
```
    - Click the **on** or **off** buttons
    - Click and hold the **on**/**off** buttons (optional)
    - Double click the **on** or **off** buttons (optional)
    - Triple click the **on** or **off** buttons (optional)
```
## Actions
Every event can trigger any amount of actions as usual:
![Actions|597x500](upload://umLmzIbXI0RRGaSQrXYtuqA5uE6.jpeg)

## Blueprint
Click the badge to import the blueprint:
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgist.github.com%2Ftrilorian%2Fee957a682ab6a3765e8fbb19502e9bfb)

## Code
The code can be found [here](https://gist.github.com/trilorian/ee957a682ab6a3765e8fbb19502e9bfb).