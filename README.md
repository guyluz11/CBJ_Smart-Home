<h1 align="center">CyBear Jinni Smart Home</h1>

<div align="center">
  
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0) [<img src="https://badges.frapsoft.com/os/v1/open-source-200x33.png?v=103" alt="Open Source Love" height="20">](https://en.wikipedia.org/wiki/Open_source)

</div>


[<div align="center"><img alt="CyBear Jinni image" height="400" src="https://user-images.githubusercontent.com/9304740/120159847-5103f580-c1fe-11eb-86ca-dc948e887a95.png"></div>](https://github.com/CyBear-Jinni/CBJ_Smart-Home)


# Welcome!

This repository let you **control** your existing smart home.

Here at CyBear Jinni we give the community the power of smart home by providing the code and instructions to set up a Hub that will let you control your smart devices and connect them even if they are from different form factors.  


<img src="https://i.imgur.com/jqDYnBm.gif" height="300">

## Project structure

The project is made out of two main parts:

### CyBear Jinni App

[CyBear Jinni App](https://github.com/CyBear-Jinni/cbj_app) is the app to control your CyBear Jinni Hub.

This is an Android, IOS, Web Browser app written in [Flutter](https://flutter.dev) that let you control the Hub using local Wi-Fi and remotely through [cbj remote pipes](https://github.com/CyBear-Jinni/cbj_remote-pipes) which transfer requests to the Hub without collecting any data.

<a href="https://play.google.com/store/apps/details?id=com.cybearjinni.app">
<img border="0" align="middle" alt="Android Badge" src="https://user-images.githubusercontent.com/9304740/117003444-8b58a080-aced-11eb-94bc-bfb2505f515d.png" width=200>

### CyBear Jinni Hub


[CyBear Jinni Hub](https://github.com/CyBear-Jinni/cbj_hub) is software written in [dart](https://dart.dev) and runs in parallel with MQTT broker.
  
The Hub talks to all the supported smart devices from different form factors and gives the app an easy and uniform way to control them as if they are from the same company.


[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/cbj-hub)
 

# Social Media Links

[<img src = "https://cdn.icon-icons.com/icons2/1099/PNG/512/1485482199-linkedin_78667.png" height = "80" >](https://www.linkedin.com/company/cybear-jinni)

If you have any questions feel free to ask in our Discord server

[<img src="https://cdn.icon-icons.com/icons2/2108/PNG/512/discord_icon_130958.png" height="80">](https://discord.gg/mUXfwUY)

## Disclaimers

**Use at Your Own Risk,**
**we do not take responsibility on any outcome using anything in this repo.**

The project is under heavy work and may contain bugs and incorrect instructions.
