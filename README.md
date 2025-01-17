# KoalaGPT API Plugin
The official **KoalaGPTApi Plugin** gives you access to the **KoalaGPT API** in **Unreal Engine**. It is compatible with 4.26, 4.27, 5.0, 5.1 and 5.2

![Imgur](https://i.imgur.com/pBrl1GM.png)

## Installation

The recommended way to install the plugin is to use pre-built binaries.


- Download the Plugin [[here](https://github.com/CyberKoalaStudios/KoalaGPTAPI-UE/releases)](https://disk.yandex.ru/d/fVJ_LypyG6-70Q)
- Create a `Plugins` folder under your project folder
- Copy the plugin to it, so you have `YourProject/Plugins/KoalaGPTAPI`

---

## Quick Start

See [Video](https://www.youtube.com/watch?v=)

[![](http://img.youtube.com/vi//0.jpg)](http://www.youtube.com/watch?v= "KoalaGPT API Quick Start Tutorial")


## Types of Authentication
There are two ways to set the Api Key
- Assign the Api key directly in blueprints.

- Set the Api Key as an environment variable


![Imgur1](https://i.imgur.com/boKUC6j.png)
> **ADVICE**: Pay attention to security and encrypt your assets before packaging.


![Imgur2](https://i.imgur.com/ehmPDNk.png)
> **ADVICE**: Create the environment variable `KOALAGPT_API_KEY` and use your Api key as the value.


## Blueprint Nodes
#### KoalaGPT Call Chat

- This async node sends an HTTP request using your `ChatSettings`.

![Imgur3](https://i.imgur.com/2eg0MJ9.png)
> **NOTE**: Async nodes can only be called from a blueprint's `Event Graph`. 
#### Make Chat Settings

- This node allows you to set the `Messages`.

![Imgur4](https://i.imgur.com/C2Nn8CG.png)

#### Break Chat Completion Simple

- This node is used to access the values included in a `completion` or `choice`

![Imgur5](https://i.imgur.com/SSOnsCT.png)

## Usage

This example show you how to use KoalaGPI 's chat endpoint in blueprints.

![Imgur6](https://i.imgur.com/p4iwNRc.png)


[Get This Blueprint](https://blueprintue.com/render/vvxdk-wi/)

## References
- [KoalaGPT's API Support](https://beta.cyberkoala.ru/)

## Supported Platforms
Windows, Mac, Android
