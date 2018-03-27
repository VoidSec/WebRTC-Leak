# WebRTC-Leak
Check if your VPN leaks your IP address via the WebRTC technology.

# 23% of tested VPNs leaks users' IPs

## WebRTC

Browsers have implemented WebRTC that allow requests to STUN servers be made that will return the local and public IP addresses for the user. These request results are available to javascript, so you can now obtain a users local and public IP addresses in javascript. This demo: https://ip.voidsec.com/ is an example implementation of that.

Additionally, these STUN requests are made outside of the normal XMLHttpRequest procedure, so they are not visible in the developer console and cannot be blocked by plugins such as AdBlockPlus or Ghostery. This makes these types of requests available for online tracking, de-anonymize and trace users behind common privacy protection services such as: VPN, SOCKS Proxy, HTTP Proxy and in the past (TOR users).

Read my research on: https://voidsec.com/vpn-leak
