<p align=center>
<br>
<a href="http://makeapullrequest.com"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg"></a>
<img src="https://img.shields.io/badge/os-linux-brightgreen">
<img src="https://img.shields.io/badge/os-mac-brightgreen"></a>
<img src="https://img.shields.io/badge/os-windows-brightgreen"></a>
<img src="https://img.shields.io/badge/os-android-brightgreen"></a>
<br>
<a href="https://github.com/iamchokerman"><img src="https://img.shields.io/badge/maintainer-iamchokerman-purple"></a>

</p>

A cli to watch anime together with syncplay. This tool scrapes the site [gogoanime](https://gogoanime.pe). Most of the code is from ani-cli.

<h1 align="center">
	Showcase
</h1>
<p align="center">
<img src=.assets/ani-sync.gif width="100%">
</p>

## Table of Contents
- [Install](#Installation)
- [Uninstall](#Uninstall)
- [Dependencies](#Dependencies)
- [Contribution Guidelines](./CONTRIBUTING.md)
- [Disclaimer](./disclaimer.md)

## Install

Install dependencies [(See below)](#Dependencies)

```sh
git clone https://github.com/iamchokerman/ani-cli && cd ani-cli
sudo cp ani-cli /usr/local/bin/ani-sync
```

*Note that mpv installed through flatpak is not compatible*

## Uninstall

* remove from path lul

## Dependencies

- grep
- sed
- curl
- openssl
- mpv - Video Player
- aria2 - Download manager
