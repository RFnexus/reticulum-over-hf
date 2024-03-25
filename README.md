# Reticulum over HF
HF radio is a useful tool for bridging local line of sight Reticulum networks across vast distances over a direct point to point connection. Reticulum only requires a 500 bit per second connection, which is easily achievable over HF. The main drawback to using HF is the limited bandwidth available. 

Using propogation modes like NVIS can overcome the rapidly changing propogation conditions and are ideal for briding regional networks within the range of 0 - 500 kilometers ( 0 to 300 miles). NVIS can also accomodate higher bandwidths when compared to traditional HF modes of propogation. At the time of making this video I'm currently working on a dedicated software data modem for packet radio designed for Reticulum which I plan to release by the end of this year. 

## Video : 

---

## Software used:

1. **NomadNet** https://github.com/markqvist/NomadNet 
2. **freedvtnc2** https://github.com/xssfox/freedvtnc2
## Equipment used:

![Diagram](https://raw.githubusercontent.com/RFnexus/reticulum-over-hf/main/Connection%20Diagram%20for%20ICOM%207300.png)

Reticulum supports most  data modems  through the `TCPClientInterface` with `KISS_FRAMING` enabled or through the serial interface
- https://reticulum.network/manual/interfaces.html#tcp-server-interface
- https://reticulum.network/manual/interfaces.html#tcp-client-interface

For software modems like Direwolf or FreeDVTNC, they both use the TCPClientInterface with KISS_FRAMING enabled


## List of Radio Packet Modems supported by Reticulum
### Software: 
1. **Direwolf TNC** https://github.com/wb2osz/direwolf
2. **freedvtnc2** https://github.com/xssfox/freedvtnc2
### Hardware:
 1. **OpenModem** https://unsigned.io/openmodem/ 
