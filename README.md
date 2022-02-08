<p align=center>
<br>
<a href="http://makeapullrequest.com"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg"></a>
<img src="https://img.shields.io/badge/os-mac-brightgreen"></a>
<img src="https://img.shields.io/badge/os-linux-brightgreen"></a>
<br>
<a href="https://github.com/kalix123"><img src="https://img.shields.io/badge/maintainer-kalix123-purple"></a>
<a href="https://github.com/iamchokerman"><img src="https://img.shields.io/badge/maintainer-iamchokerman-purple"></a>

</p>

A cli to watch anime together with syncplay. Most of the code is from [ani-cli](https://github.com/pystardust/ani-cli). This tool scrapes the site [gogoanime](https://gogoanime.pe). All credits go to Pystardust and the maintainers of [ani-cli](https://github.com/pystardust/ani-cli).

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

## Install

- Install dependencies [(See below)](#Dependencies)
- Install and setup syncplay (the script will automatically play the video in the last room you connected to)

```sh
git clone https://github.com/iamchokerman/ani-sync && cd ani-sync
sudo cp ani-sync /usr/local/bin/
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
