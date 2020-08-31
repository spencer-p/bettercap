我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

<p align="center">
  <img alt="BetterCap" src="https://raw.githubusercontent.com/bettercap/media/master/logo.png" height="140" />
  <p align="center">
    <a href="https://github.com/bettercap/bettercap/releases/latest"><img alt="Release" src="https://img.shields.io/github/release/bettercap/bettercap.svg?style=flat-square"></a>
    <a href="https://github.com/bettercap/bettercap/blob/master/LICENSE.md"><img alt="Software License" src="https://img.shields.io/badge/license-GPL3-brightgreen.svg?style=flat-square"></a>
    <a href="https://travis-ci.org/bettercap/bettercap"><img alt="Travis" src="https://img.shields.io/travis/bettercap/bettercap/master.svg?style=flat-square"></a>
    <a href="https://goreportcard.com/report/github.com/bettercap/bettercap"><img alt="Go Report Card" src="https://goreportcard.com/badge/github.com/bettercap/bettercap?style=flat-square&fuckgithubcache=1"></a>
    <a href="https://codecov.io/gh/bettercap/bettercap"><img alt="Code Coverage" src="https://img.shields.io/codecov/c/github/bettercap/bettercap/master.svg?style=flat-square"></a>
    <a href="https://repology.org/project/bettercap/versions"><img src="https://repology.org/badge/tiny-repos/bettercap.svg" alt="Packaging status"></a>
  </p>
</p>

bettercap is a powerful, easily extensible and portable framework written in Go which aims to offer to security researchers, red teamers and reverse engineers an **easy to use**, **all-in-one solution** with all the features they might possibly need for performing reconnaissance and attacking [WiFi](https://www.bettercap.org/modules/wifi/) networks, [Bluetooth Low Energy](https://www.bettercap.org/modules/ble/) devices, wireless [HID](https://www.bettercap.org/modules/hid/) devices and [Ethernet](https://www.bettercap.org/modules/ethernet) networks.

![UI](https://raw.githubusercontent.com/bettercap/media/master/ui-events.png)

## Main Features

* **WiFi** networks scanning, [deauthentication attack](https://www.evilsocket.net/2018/07/28/Project-PITA-Writeup-build-a-mini-mass-deauther-using-bettercap-and-a-Raspberry-Pi-Zero-W/), [clientless PMKID association attack](https://www.evilsocket.net/2019/02/13/Pwning-WiFi-networks-with-bettercap-and-the-PMKID-client-less-attack/) and automatic WPA/WPA2 client handshakes capture.
* **Bluetooth Low Energy** devices scanning, characteristics enumeration, reading and writing.
* 2.4Ghz wireless devices scanning and **MouseJacking** attacks with over-the-air HID frames injection (with DuckyScript support).
* Passive and active IP network hosts probing and recon.
* **ARP, DNS and DHCPv6 spoofers** for MITM attacks on IP based networks.
* **Proxies at packet level, TCP level and HTTP/HTTPS** application level fully scriptable with easy to implement **javascript plugins**.
* A powerful **network sniffer** for **credentials harvesting** which can also be used as a **network protocol fuzzer**.
* A very fast port scanner.
* A powerful [REST API](https://www.bettercap.org/modules/core/api.rest/) with support for asynchronous events notification on websocket to orchestrate your attacks easily.
* **A very convenient [web UI](https://www.bettercap.org/usage/#web-ui).**
* [More!](https://www.bettercap.org/modules/)

## About the 1.x Legacy Version

While the first version (up to 1.6.2) of bettercap was implemented in Ruby and only offered basic MITM, sniffing and proxying capabilities, the 2.x is a complete reimplementation using the [Go programming language](https://golang.org/). 

This ground-up rewrite offered several advantages:

* bettercap can now be distributed as a **single binary** with very few dependencies, for basically **any OS and any architecture**.
* 1.x proxies, although highly optimized and event based, **[used to bottleneck the entire network](https://en.wikipedia.org/wiki/Global_interpreter_lock)** when performing a MITM attack, while the new version adds almost no overhead.
* Due to such **performance and functional limitations**, most of the features that the 2.x version is offering were simply impossible to implement properly (read as: without killing the entire network ... or your computer).

For this reason, **any version prior to 2.x is considered deprecated** and any type of support has been dropped in favor of the new implementation. An archived copy of the legacy documentation is [available here](https://www.bettercap.org/legacy/), however **it is strongly suggested to upgrade**.

## Documentation and Examples

The project is documented [here](https://www.bettercap.org/).

## License

`bettercap` is made with ♥  by [the dev team](https://github.com/orgs/bettercap/people) and it's released under the GPL 3 license.

## Stargazers over time

[![Stargazers over time](https://starchart.cc/bettercap/bettercap.svg)](https://starchart.cc/bettercap/bettercap)
