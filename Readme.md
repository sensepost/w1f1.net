# Wifi Hacking Tools Collection

These are a set of tools for wifi hacking using rogue access points, released as part of a [Defcon 26 talk](https://www.youtube.com/watch?v=eYsGyvGxlpI) and maintained by [@singe](https://twitter.com/singe).

## Rogue AP

The core of the rogue access point toolkit.

* [hostapd-mana](https://github.com/sensepost/hostapd-mana/)
* [Wiki](https://github.com/sensepost/hostapd-mana/wiki)
* [eaphammer](https://github.com/s0lst1c3/eaphammer) - an alternative implementation, with many of mana's capabilities as well as many more, and a simple command line interface. By [@s0lst1c3](@http://twitter.com/s0lst1c3). There is also a comprehensive [wiki](https://github.com/s0lst1c3/eaphammer/wiki)
* [hostapd-wpe](https://github.com/aircrack-ng/aircrack-ng/tree/master/patches/wpe/hostapd-wpe) - the aircrack maintained original hostapd-wpe patch. Tracks upstream hostapd faster.

## Orchestration

A fork of the create_ap tool to configure common access points modes and their networking by [@_cablethief](https://twitter.com/_cablethief). Supports most of mana's capabilities.

* [berate_ap](https://github.com/sensepost/berate_ap)

## EAP Relay

Relay EAP authentication to get authenticated without cracking MSCHAPv2 by [@_cablethief](https://twitter.com/_cablethief).

* [wpa_sycophant](https://github.com/sensepost/wpa_sycophant)

## PitM

The defacto PitM tool, built by [@evilsocket](https://twitter.com/evilsocket), and the replacement for the now deprecated mana-toolkit scripts.

* [bettercap](https://github.com/bettercap/bettercap)

## Practise

Practise without needing hardware or breaking the law.

* [katacoda](https://katacoda.com/singe) Free online interactive training scenarios
* [shinai-fi](https://github.com/sensepost/shinai-fi) Docker image of the same scenarios

## Frequency Hacking

Avoid local regulatory restrictions on wifi frequencies.

* [wifi-frequency-hacker](https://github.com/singe/wifi-frequency-hacker)
