# Forked from webrtc.io-demo
==============

You can have a look at the demo on http://multiwebrtc.nodejitsu.com

webrtc.io-deom is developed by:
    [@dennismatensson](https://github.com/dennismartensson)
    [@cavedweller](https://github.com/cavedweller)
    [@sarenji](https://github.com/sarenji)

##Use in peets
[peets](https://github.com/zhenkai/peets) is an effort to run WebRTC multi-user conference over [Named Data Networking](http://www.named-data.net/) (NDN).
webrtc.io-demo fits nicely as the frontend part of peets, which provides a clean UI and convenient WebRTC manipulation javascripts. Instead of communicating with a server.js running with node.js, webrtc.io-demo frontend would, in peets, communicate with a peets python backend, which would behaves like a proxy between the NDN world and IP world. In short, peets backend would fake peer connections to web browser, intercept the UDP traffic (RTP & RTCP) and distribute them over NDN.

