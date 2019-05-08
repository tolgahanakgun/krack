# PoC Krack (Key Reinstallation AttaCKs)

Proof of concept for Krack attack using channel-based MitM

## Theory

French article on [hackndo](http://beta.hackndo.com/krack/)

## Environment

* WPA2 with CCMP
* Python 2.7
* Scapy 2.4

## TODO

- [X] Use CSA (Channel Switch Announcement) to make client switch channel after deauth
- [ ] Save data sent by client
- [ ] Break cryptography with known plain text when counter is reinitialized
