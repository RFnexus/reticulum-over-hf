# Reticulum over HF demo

## Video:  https://www.youtube.com/watch?v=blwNVumLujc
HF radio is a useful tool for bridging local line of sight Reticulum networks across vast distances over a direct point to point connection. Reticulum only requires a 500 bit per second connection, which is easily achievable over HF. The main drawback to using HF is the limited bandwidth available. 

Using propogation modes like NVIS can overcome the rapidly changing propogation conditions and are ideal for briding regional networks within the range of 0 - 500 kilometers ( 0 to 300 miles). NVIS can also accomodate higher bandwidths when compared to traditional HF modes of propogation. 

https://github.com/RFnexus/FreeDVInterface
https://github.com/RFnexus/modem73

---

## Equipment used:

![Diagram](https://raw.githubusercontent.com/RFnexus/reticulum-over-hf/main/Connection%20Diagram%20for%20ICOM%207300.png)

Reticulum supports most  data modems  through the `TCPClientInterface` with `KISS_FRAMING` enabled or through the serial interface
- https://reticulum.network/manual/interfaces.html#tcp-client-interface

For software modems like Direwolf or FreeDVTNC, they both use the TCPClientInterface with KISS_FRAMING enabled


## List of Radio Packet Modems supported by Reticulum
### Software: 
1. **FreeDVInterface** - A plug and play FreeDVInterface for Reticulum https://github.com/RFnexus/FreeDVInterface
2. **modem73** https://github.com/RFnexus/modem73
3. **fldigi**: https://github.com/w1hkj/fldigi (OFDM-500 and OFDM-750 have good performance over NVIS links)
4. **Direwolf TNC** https://github.com/wb2osz/direwolf
6. **freedvtnc2** https://github.com/xssfox/freedvtnc2
### Hardware:
 1. **OpenModem** https://unsigned.io/openmodem/ 
