---
title: 'HowtheInternetWorks'
author: [Ghost]
tags: []
image: img/marvin-meyer-794521-unsplash.jpg
date: '2020-11-04T10:00:00.000Z'
draft: false
---


# **Internet ಹೇಗೆ ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತದೆ?**

[![Hemalatharao](https://miro.medium.com/fit/c/96/96/0*_LxkLpCb93uoJDAA)](https://medium.com/@hemalatharao936?source=post_page-----91f4d3698651--------------------------------)

[Hemalatharao](https://medium.com/@hemalatharao936?source=post_page-----91f4d3698651--------------------------------)

Following

[Nov 4](https://medium.com/microdegree/internet-%E0%B2%B9%E0%B3%87%E0%B2%97%E0%B3%86-%E0%B2%95%E0%B2%BE%E0%B2%B0%E0%B3%8D%E0%B2%AF%E0%B2%A8%E0%B2%BF%E0%B2%B0%E0%B3%8D%E0%B2%B5%E0%B2%B9%E0%B2%BF%E0%B2%B8%E0%B3%81%E0%B2%A4%E0%B3%8D%E0%B2%A4%E0%B2%A6%E0%B3%86-91f4d3698651?source=post_page-----91f4d3698651--------------------------------)  ·  9  min read

**TLDR: ವಿವಿಧ ಪ್ರೋಟೋಕಾಲ್‌ಗಳ ಪ್ರಕಾರ routerಗಳು ಚಲಿಸುವ ಪ್ಯಾಕೆಟ್‌ಗಳು**

![Image for post](https://miro.medium.com/max/60/0*L6l0jfik_zElSCon?q=20)

![Image for post](https://miro.medium.com/max/1000/0*L6l0jfik_zElSCon)

Visualization of the Internet. Photo by [Umberto](https://unsplash.com/@umby?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)  on [Unsplash](https://unsplash.com/s/photos/internet?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

**Internet ಹೇಗೆ ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತದೆ?**

ಇಂಟರ್ನೆಟ್ ಪ್ರೊಟೊಕಾಲ್(Internet Protocol) (IP),  _Transport Control Protocol_(TCP) ಮತ್ತು ಇತರ ಪ್ರೋಟೋಕಾಲ್‌(Protocol)ಗಳಿಗೆ ಅನುಸಾರವಾಗಿ packet routing network ಮೂಲಕ Internet ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತದೆ.

**ಪ್ರೋಟೋಕಾಲ್(Protocol) ಎಂದರೇನು?**

ಪ್ರೋಟೋಕಾಲ್ ಎನ್ನುವುದು ಕಂಪ್ಯೂಟರ್‌ಗಳು ಪರಸ್ಪರ networkನೊಂದಿಗೆ ಹೇಗೆ communication ನಡೆಸಬೇಕು ಎಂಬುದನ್ನು ಸೂಚಿಸುವ rulesಗಳ ಒಂದು ಗುಂಪಾಗಿದೆ. ಉದಾಹರಣೆಗೆ,  _Transport Control Protocol_  ಒಂದು ಕಂಪ್ಯೂಟರ್ ನಿಂದ ಮತ್ತೊಂದು ಕಂಪ್ಯೂಟರ್‌ಗೆ data ವನ್ನು ಕಳುಹಿಸಿದಾಗ, ಯಾವುದೇ data ಕಾಣೆಯಾಗಿದ್ದರೆ destination ಕಂಪ್ಯೂಟರ್, source ಕಂಪ್ಯೂಟರ್‌ಗೆ ತಿಳಿಸಬೇಕು ಆಗ source ಕಂಪ್ಯೂಟರ್ data ವನ್ನು ಮರು ಕಳುಹಿಸಬಹುದು. ಅಥವಾ ಕಂಪ್ಯೂಟರ್‌ಗಳು ಕಳುಹಿಸುವ ಡೇಟಾಗೆ ವಿಳಾಸಗಳನ್ನು ಲಗತ್ತಿಸುವ(attach) ಮೂಲಕ ಇತರ ಕಂಪ್ಯೂಟರ್‌ಗಳಿಗೆ ಮಾಹಿತಿಯನ್ನು ಹೇಗೆ ಸಾಗಿಸಬೇಕು ಎಂಬುದನ್ನು Internet Protocol ನಿರ್ದಿಷ್ಟಪಡಿಸುತ್ತದೆ.

**ಪ್ಯಾಕೆಟ್(Packet) ಎಂದರೇನು?**

Internet ಮೂಲಕ ಕಳುಹಿಸಲಾದ ಡೇಟಾವನ್ನು message ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ. messageನ್ನು ಕಳುಹಿಸುವ ಮೊದಲು, ಅನೇಕ fragmentsಗಳಲ್ಲಿ split ಮಾಡಲಾಗುತ್ತದೆ, ಅದನ್ನು ಪ್ಯಾಕೆಟ್‌ಗಳು ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ. ಈ ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು independent ಆಗಿ ಕಳುಹಿಸಲಾಗುತ್ತದೆ. ವಿಶಿಷ್ಟ maximum packet size 1000 ಮತ್ತು 3000 ಅಕ್ಷರಗಳ ನಡುವೆ ಇರುತ್ತದೆ. messageಗಳನ್ನು ಹೇಗೆ packetize ಮಾಡಬೇಕೆಂದು Internet Protocol ಸೂಚಿಸುತ್ತದೆ.

**ಪ್ಯಾಕೆಟ್ ರೂಟಿಂಗ್ ನೆಟ್‌ವರ್ಕ್(packet routing network) ಯಾವುದು?**

ಇದು, ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು source ಕಂಪ್ಯೂಟರ್‌ನಿಂದ destination ಕಂಪ್ಯೂಟರ್‌ಗೆ ಸಾಗಿಸುವ ನೆಟ್‌ವರ್ಕ್ ಆಗಿದೆ. ಇಂಟರ್ನೆಟ್,  **_routers_**  ಎಂಬ ವಿಶೇಷ ಕಂಪ್ಯೂಟರ್‌ಗಳ ಬೃಹತ್ ನೆಟ್‌ವರ್ಕ್‌ನಿಂದ ಮಾಡಲ್ಪಟ್ಟಿದೆ. ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು ಅವುಗಳ source ನಿಂದ ತಮ್ಮ destination ಗೆ ಹೇಗೆ move ಮಾಡಬೇಕೆಂದು ತಿಳಿಯುವುದು ಪ್ರತಿ routerನ ಕೆಲಸವಾಗಿದೆ. ಒಂದು ಪ್ಯಾಕೆಟ್ ತನ್ನ ಪ್ರಯಾಣದ ಸಮಯದಲ್ಲಿ ಅನೇಕ routersಗಳ ಮೂಲಕ ಚಲಿಸುತ್ತದೆ.

ಒಂದು ಪ್ಯಾಕೆಟ್ ಒಂದು routerನಿಂದ ಮತ್ತೊಂದಕ್ಕೆ ಚಲಿಸಿದಾಗ, ಅದನ್ನು ಹಾಪ್(hop) ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ. ನಿಮ್ಮ ಮತ್ತು ಹೋಸ್ಟ್(host) ನಡುವೆ ಹಾಪ್ಸ್(hops) ಪ್ಯಾಕೆಟ್‌ಗಳ ಪಟ್ಟಿಯನ್ನು ನೋಡಲು ನೀವು command line tool  **_traceroute_**  ಅನ್ನು ಬಳಸಬಹುದು.

![Image for post](https://miro.medium.com/max/60/0*wxLR1ffmUl_XT6aY?q=20)

![Image for post](https://miro.medium.com/max/1000/0*wxLR1ffmUl_XT6aY)

ನನ್ನ ಕಂಪ್ಯೂಟರ್ ಮತ್ತು ಗೂಗಲ್ ಸರ್ವರ್‌ಗಳ ನಡುವಿನ ಎಲ್ಲಾ ಹಾಪ್‌ಗಳನ್ನು ತೋರಿಸುವ Command-line utility traceroute

ಪ್ಯಾಕೆಟ್ನ header ಗೆ network addressಗಳನ್ನು ಹೇಗೆ attach ಮಾಡಬೇಕು ಎಂಬುದನ್ನು, ಅದರ meta-dataವನ್ನು ಹೊಂದಿರುವ ಪ್ಯಾಕೆಟ್ನಲ್ಲಿ ಗೊತ್ತುಪಡಿಸಿದ ಸ್ಥಳವನ್ನು Internet Protocol ಸೂಚಿಸುತ್ತದೆ. Internet Protocol, headerಲ್ಲಿನ addressನ್ನು ಆಧರಿಸಿ routerಗಳು ಪ್ಯಾಕೆಟ್ಗಳನ್ನು ಹೇಗೆ forward ಮಾಡಬೇಕು ಎಂಬುದನ್ನು ಸಹ ಸೂಚಿಸುತ್ತದೆ.

**ಈ Internet routerಗಳು ಎಲ್ಲಿಂದ ಬಂದವು? ಅವುಗಳನ್ನು ಯಾರು ಹೊಂದಿದ್ದಾರೆ?**

ಈ routersಗಳು 1960 ರ ದಶಕದಲ್ಲಿ ARPANET ಎಂಬ ಮಿಲಿಟರಿ ಯೋಜನೆಯಾಗಿ ಹುಟ್ಟಿಕೊಂಡಿವೆ, ಇದರ ಗುರಿ ಕಂಪ್ಯೂಟರ್ ನೆಟ್‌ವರ್ಕ್ ಆಗಿದ್ದು ಅದು decentralized ಆಗಿದೆ, ಆದ್ದರಿಂದ ದುರಂತದ ಸಂದರ್ಭದಲ್ಲಿ ಸರ್ಕಾರವು ಮಾಹಿತಿಯನ್ನು access ಮತ್ತು ವಿತರಿಸಬಹುದು(distribute). ಮಾಡಬಹುದಾಗಿದೆ. ಅಂದಿನಿಂದ, ಹಲವಾರು ಇಂಟರ್ನೆಟ್ ಸೇವಾ ಪೂರೈಕೆದಾರರು (ISP-Internet Service Providers) corporationsಗಳು ಈ ARPANET routerಗಳಲ್ಲಿ routerಗಳನ್ನು ಸೇರಿಸಿದೆ.

ಈ ಇಂಟರ್ನೆಟ್ routerಗಳಿಗೆ ಒಂದು ಮಾಲೀಕರು ಎಂದು ಇಲ್ಲ, ಬದಲಿಗೆ ಬಹು ಮಾಲೀಕರು ಇರುವುದು: ಆರಂಭಿಕ ದಿನಗಳಲ್ಲಿ ARPANET ಗೆ ಸಂಬಂಧಿಸಿದ ಸರ್ಕಾರಿ ಸಂಸ್ಥೆಗಳು ಮತ್ತು ವಿಶ್ವವಿದ್ಯಾಲಯಗಳು ಮತ್ತು ನಂತರ AT&T ಮತ್ತು Verizon ನಂತಹ ISP ನಿಗಮಗಳು(corporations).

ಇಂಟರ್ನೆಟ್ ಅನ್ನು ಯಾರು ಹೊಂದಿದ್ದಾರೆ ಎಂದು ಕೇಳುವುದು, ಎಲ್ಲಾ ದೂರವಾಣಿ ಮಾರ್ಗಗಳನ್ನು ಯಾರು ಹೊಂದಿದ್ದಾರೆ ಎಂದು ಕೇಳುವಂತಿದೆ. ಯಾವುದೇ ಅಸ್ತಿತ್ವವು ಅವೆಲ್ಲವನ್ನೂ ಹೊಂದಿಲ್ಲ; ಅನೇಕ ವಿಭಿನ್ನ ಘಟಕಗಳು ಅವುಗಳಲ್ಲಿ ಕೆಲವು ಭಾಗಗಳನ್ನು ಹೊಂದಿವೆ.

**ಪ್ಯಾಕೆಟ್‌ಗಳು ಯಾವಾಗಲೂ ಕ್ರಮವಾಗಿ ಬರುತ್ತವೆಯೇ? ಇಲ್ಲದಿದ್ದರೆ, ಸಂದೇಶವನ್ನು ಮತ್ತೆ ಜೋಡಿಸುವುದು ಹೇಗೆ?**

ಪ್ಯಾಕೆಟ್‌ಗಳು ತಮ್ಮ destinationನ್ನು ಕ್ರಮಬದ್ಧವಾಗಿ ತಲುಪಬಹುದು. ನಂತರದ ಪ್ಯಾಕೆಟ್ ಹಿಂದಿನದಕ್ಕಿಂತ destinationಗೆ quicker path ಕಂಡುಕೊಂಡಾಗ ಇದು ಸಂಭವಿಸುತ್ತದೆ. ಆದರೆ ಪ್ಯಾಕೆಟ್‌ನ header ಸಂಪೂರ್ಣ ಸಂದೇಶಕ್ಕೆ ಸಂಬಂಧಿಸಿದಂತೆ ಪ್ಯಾಕೆಟ್‌ನ ಆದೇಶದ ಮಾಹಿತಿಯನ್ನು ಒಳಗೊಂಡಿದೆ. Transport Control Protocol(TCP) ಈ ಮಾಹಿತಿಯನ್ನು destinationಲ್ಲಿ ಸಂದೇಶವನ್ನು ಪುನರ್ನಿರ್ಮಿಸಲು ಬಳಸುತ್ತದೆ.

**ಪ್ಯಾಕೆಟ್‌ಗಳು ಯಾವಾಗಲೂ ಅದನ್ನು ತಮ್ಮ destinationಗೆ ತಲುಪಿಸುತ್ತವೆಯೇ?**

ಪ್ಯಾಕೆಟ್‌ಗಳು ಯಾವಾಗಲೂ ತಮ್ಮ destinationಗಳಿಗೆ ಬರುತ್ತವೆ ಎಂಬುದಕ್ಕೆ Internet protocol ಯಾವುದೇ ಭರವಸೆ ನೀಡುವುದಿಲ್ಲ. ಅದು ಸಂಭವಿಸಿದಾಗ, ಅದನ್ನು  **_packet loss_**  ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ. router ಪ್ರಕ್ರಿಯೆಗೊಳಿಸಬಹುದಾದ ಹೆಚ್ಚಿನ ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು ಪಡೆದಾಗ ಇದು ಸಾಮಾನ್ಯವಾಗಿ ಸಂಭವಿಸುತ್ತದೆ. ಕೆಲವು ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು ಬಿಡುವುದನ್ನು ಬಿಟ್ಟು ಬೇರೆ ದಾರಿಯಿಲ್ಲ.

ಆದಾಗ್ಯೂ, Transport Control Protocol re-transmissions ಮಾಡುವ ಮೂಲಕ packet lossನ್ನು ನಿಭಾಯಿಸುತ್ತದೆ. destination ಕಂಪ್ಯೂಟರ್ periodically acknowledgement  _packets_ಗಳನ್ನು source ಕಂಪ್ಯೂಟರ್‌ಗೆ ಕಳುಹಿಸುವ ಮೂಲಕ ಎಷ್ಟು messageನ್ನು recieve ಮಾಡಿದೆ ಮತ್ತು reconstruct ಮಾಡಿದೆ ಎಂಬುದನ್ನು ಸೂಚಿಸುತ್ತದೆ. destination ಕಂಪ್ಯೂಟರ್ ಕಾಣೆಯಾದ ಪ್ಯಾಕೆಟ್‌(missing packet)ಗಳನ್ನು ಕಂಡುಕೊಂಡರೆ, ಅದು ಕಾಣೆಯಾದ ಪ್ಯಾಕೆಟ್‌(missing packet)ಗಳನ್ನು ಮತ್ತೆ ಕಳುಹಿಸಲು source ಕಂಪ್ಯೂಟರ್‌ಗೆ requestನ್ನು ಕಳುಹಿಸುತ್ತದೆ.

Transport Control Protocol ಮೂಲಕ ಎರಡು ಕಂಪ್ಯೂಟರ್‌ಗಳು ಸಂವಹನ (communication) ನಡೆಸುತ್ತಿರುವಾಗ, ಅವುಗಳ ನಡುವೆ TCP ಸಂಪರ್ಕವಿದೆ ಎಂದು ನಾವು ಹೇಳುತ್ತೇವೆ.

**ಈ ಇಂಟರ್ನೆಟ್ ವಿಳಾಸ(Internet Address)(IP) ಗಳು ಹೇಗೆ ಕಾಣುತ್ತವೆ?**

ಈ addressಗಳನ್ನು  _IP addresses_  ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ ಮತ್ತು ಇಲ್ಲಿ ಎರಡು standardsಗಳಿವೆ.

ಮೊದಲ address standard-  **ಐಪಿವಿ 4(IPV4)**  ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ ಮತ್ತು ಇದು 212.78.1.25 ನಂತೆ ಕಾಣುತ್ತದೆ. ಆದರೆ ಐಪಿವಿ 4(IPV4) ಕೇವಲ ²³² (ಸುಮಾರು 4 ಬಿಲಿಯನ್) ಸಂಭಾವ್ಯ ವಿಳಾಸಗಳನ್ನು ಮಾತ್ರ ಬೆಂಬಲಿಸುತ್ತಿರುವುದರಿಂದ, ಇಂಟರ್ನೆಟ್ ಟಾಸ್ಕ್ ಫೋರ್ಸ್([_Internet Task Force_](https://en.wikipedia.org/wiki/Internet_Engineering_Task_Force)) ಐಪಿವಿ 6(IPV6) ಎಂಬ ಹೊಸ address standardನ್ನು ಪ್ರಸ್ತಾಪಿಸಿತು, ಅದು ಈ ರೀತಿ ಕಾಣುತ್ತದೆ- 3ffe:1893:3452:4:345:f345:f345:42fc  _IPV6_  ²¹²⁸ possible addressesಗಳನ್ನು ಬೆಂಬಲಿಸುತ್ತದೆ, ಇದು ಹೆಚ್ಚು ನೆಟ್‌ವರ್ಕ್ ಮಾಡಲಾದ ಸಾಧನಗಳಿಗೆ ಅನುವು ಮಾಡಿಕೊಡುತ್ತದೆ, ಇದು ಅಂತರ್ಜಾಲದಲ್ಲಿ 2017 ರ ಪ್ರಸ್ತುತ 8+ ಬಿಲಿಯನ್ ನೆಟ್‌ವರ್ಕ್ ಸಾಧನಗಳಿಗಿಂತ ಸಾಕಷ್ಟು ಹೆಚ್ಚು.

ಹಾಗೆಯೇ, IPV 4 ಮತ್ತು IPV 6 addressಗಳ ನಡುವೆ ಒಂದರಿಂದ ಒಂದಕ್ಕೆ Mapping ಇದೆ. IPV 4 ರಿಂದ IPV 6 ಗೆ ಸ್ವಿಚ್ ಇನ್ನೂ ಪ್ರಗತಿಯಲ್ಲಿದೆ ಮತ್ತು ಬಹಳ ಸಮಯ ತೆಗೆದುಕೊಳ್ಳುತ್ತದೆ. 2014 ರ ಹೊತ್ತಿಗೆ, ಗೂಗಲ್, ತಮ್ಮ IPV 6 trafficನ್ನು ಕೇವಲ 3% ಎಂದು ಬಹಿರಂಗಪಡಿಸಿದೆ.

**ಕೇವಲ 4 ಬಿಲಿಯನ್ IPV 4 addressಗಳು ಇದ್ದಲ್ಲಿ ಅಂತರ್ಜಾಲದಲ್ಲಿ 8 ಬಿಲಿಯನ್ ನೆಟ್‌ವರ್ಕ್ ಸಾಧನಗಳು ಹೇಗೆ ಇರಲು ಸಾಧ್ಯ?**

ಏಕೆಂದರೆ public ಮತ್ತು private IP addressಗಳಿವೆ. ಇಂಟರ್ನೆಟ್‌ಗೆ ಸಂಪರ್ಕಗೊಂಡಿರುವ local ನೆಟ್‌ವರ್ಕ್‌ನಲ್ಲಿನ ಬಹು ಸಾಧನಗಳು ಒಂದೇ public IP addressನ್ನು ಹಂಚಿಕೊಳ್ಳುತ್ತವೆ. local ನೆಟ್‌ವರ್ಕ್‌ನಲ್ಲಿ, ಈ ಸಾಧನಗಳನ್ನು private IP addressಗಳಿಂದ ಪರಸ್ಪರ ಬೇರ್ಪಡಿಸಲಾಗುತ್ತದೆ, ಸಾಮಾನ್ಯವಾಗಿ 192.168.xx ಅಥವಾ 172.16.x.x ಅಥವಾ 10.x.x.x ಇಲ್ಲಿ x ಅನ್ನುವುದು 1 ಮತ್ತು 255 ರ ನಡುವಿನ ಸಂಖ್ಯೆಯಾಗಿದೆ. ಈ private IP addressಗಳನ್ನು Dynamic host configuration protocol (DHCP) ನಿಂದ ನಿಯೋಜಿಸುತ್ತದೆ.

ಉದಾಹರಣೆಗೆ, ಒಂದೇ ಸ್ಥಳೀಯ ನೆಟ್‌ವರ್ಕ್‌(local network)ನಲ್ಲಿ ಲ್ಯಾಪ್‌ಟಾಪ್ ಮತ್ತು ಸ್ಮಾರ್ಟ್ ಫೋನ್ ಎರಡೂ  [www.google.com](http://www.google.com/)  ಗೆ ವಿನಂತಿಯನ್ನು ಮಾಡಿದರೆ, ಪ್ಯಾಕೆಟ್‌ಗಳು ಮೋಡೆಮ್‌(modem)ನಿಂದ ಹೊರಡುವ ಮೊದಲು, ಅದು ಪ್ಯಾಕೆಟ್ headerಗಳನ್ನು ಮಾರ್ಪಡಿಸುತ್ತದೆ ಮತ್ತು ಅದರ ಒಂದು port ಅನ್ನು ಆ ಪ್ಯಾಕೆಟ್‌ಗೆ ನಿಯೋಜಿಸುತ್ತದೆ. ಗೂಗಲ್ ಸರ್ವರ್ requestಗಳಿಗೆ ಪ್ರತಿಕ್ರಿಯಿಸಿದಾಗ, ಅದು ಈ ನಿರ್ದಿಷ್ಟ ಬಂದರಿನಲ್ಲಿ ಡೇಟಾವನ್ನು ಮೋಡೆಮ್‌ಗೆ ಕಳುಹಿಸುತ್ತದೆ, ಆದ್ದರಿಂದ ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು ಲ್ಯಾಪ್‌ಟಾಪ್ ಅಥವಾ ಸ್ಮಾರ್ಟ್ ಫೋನ್‌ಗೆ ರವಾನಿಸಬೇಕೆ ಎಂದು ಮೋಡೆಮ್‌ಗೆ ತಿಳಿಯುತ್ತದೆ.

ಈ ಅರ್ಥದಲ್ಲಿ, IP addressಗಳು ಕಂಪ್ಯೂಟರ್‌ಗೆ ನಿರ್ದಿಷ್ಟವಾಗಿಲ್ಲ, ಆದರೆ ಕಂಪ್ಯೂಟರ್ ಇಂಟರ್ನೆಟ್‌ಗೆ ಸಂಪರ್ಕ ಸಾಧಿಸುವ connection. ನಿಮ್ಮ ಕಂಪ್ಯೂಟರ್‌ಗೆ ವಿಶಿಷ್ಟವಾದ address ಎಂದರೆ MAC Address, ಅದು ಕಂಪ್ಯೂಟರ್‌ನ ಜೀವನದುದ್ದಕ್ಕೂ ಎಂದಿಗೂ ಬದಲಾಗುವುದಿಲ್ಲ.

Private IP Addressಗಳನ್ನು public IP addressಗಳಿಗೆ ಮ್ಯಾಪಿಂಗ್(mapping) ಮಾಡುವ ಈ protocol ಅನ್ನು NAT-_Network Address Translation_  Protocol ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ. ಇದು ಕೇವಲ 4 ಬಿಲಿಯನ್ possible IPV 4 ವಿಳಾಸಗಳೊಂದಿಗೆ 8+ ಬಿಲಿಯನ್ ನೆಟ್‌ವರ್ಕ್ ಸಾಧನಗಳನ್ನು ಬೆಂಬಲಿಸಲು ಸಾಧ್ಯವಾಗಿಸುತ್ತದೆ.

**packet ಅನ್ನು ಎಲ್ಲಿ ಕಳುಹಿಸಬೇಕೆಂದು Routerಗೆ ಹೇಗೆ ಗೊತ್ತು? ಇಂಟರ್ನೆಟ್ನಲ್ಲಿ ಎಲ್ಲಾ IP Addressಗಳು ಎಲ್ಲಿವೆ ಎಂದು ತಿಳಿಯಬೇಕೇ?**

ಪ್ರತಿ IP Address ಎಲ್ಲಿದೆ ಎಂದು ಪ್ರತಿ routerಗೆ ತಿಳಿಯಬೇಕಾಗಿಲ್ಲ. ಪ್ರತಿ ಪ್ಯಾಕೆಟ್‌ಗೆ ಮಾರ್ಗ ಮಾಡಲು ಅದರ ನೆರೆಹೊರೆಯವರು ಯಾರು ಎಂದು ತಿಳಿದುಕೊಳ್ಳಬೇಕು, ಇದನ್ನು  **_outbound link_** ಎಂದು ಕರೆಯುತ್ತಾರೆ. IP addressಗಳನ್ನು ಎರಡು ಭಾಗಗಳಾಗಿ ವಿಂಗಡಿಸಬಹುದು,  **n_etwork prefix_  ಮತ್ತು  _host identifier_**. ಉದಾಹರಣೆಗೆ, 129.42.13.69 ಅನ್ನು ಈ ರೀತಿ ವಿಂಗಡಿಸಬಹುದು.

Network Prefix: 129.42

Host Identifier: 13.69

ಒಂದೇ ಸಂಪರ್ಕದ ಮೂಲಕ ಇಂಟರ್ನೆಟ್‌ಗೆ ಸಂಪರ್ಕಿಸುವ ಎಲ್ಲಾ ನೆಟ್‌ವರ್ಕ್ ಸಾಧನಗಳು (ಅಂದರೆ ಕಾಲೇಜು ಕ್ಯಾಂಪಸ್, ವ್ಯವಹಾರ, ಅಥವಾ ಮೆಟ್ರೋ ಪ್ರದೇಶದಲ್ಲಿನ ISP) ಎಲ್ಲವೂ ಒಂದೇ  **n_etwork prefix_**  ನ್ನು ಹಂಚಿಕೊಳ್ಳುತ್ತವೆ.

Routerಗಳು 129.42.*.* form ನ ಎಲ್ಲಾ ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು ಒಂದೇ ಸ್ಥಳಕ್ಕೆ ಕಳುಹಿಸುತ್ತಾರೆ. ಆದ್ದರಿಂದ ಶತಕೋಟಿ IP addressಗಳನ್ನು ಟ್ರ್ಯಾಕ್ ಮಾಡುವ ಬದಲು, routerಗಳು ಕೇವಲ ಒಂದು ಮಿಲಿಯನ್  **n_etwork prefix_**  ಬಗ್ಗೆ ನಿಗಾ ಇಡಬೇಕು.

**ಆದರೆ Router ಇನ್ನೂ ಸಾಕಷ್ಟು n_etwork prefix_  ಗಳನ್ನು ತಿಳಿದುಕೊಳ್ಳಬೇಕು. ಹೊಸ ರೂಟರ್ ಅನ್ನು ಇಂಟರ್ನೆಟ್‌ಗೆ ಸೇರಿಸಿದರೆ ಈ ಎಲ್ಲಾ n_etwork prefix_**  **ಗಳಿಗೆ ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು ಹೇಗೆ ನಿರ್ವಹಿಸುವುದು ಎಂದು ಹೇಗೆ ತಿಳಿಯುತ್ತದೆ?**

ಹೊಸ router ಮೊದಲೇ ಕಾನ್ಫಿಗರ್ ಮಾಡಿದ routeಗಳೊಂದಿಗೆ ಬರಬಹುದು. ಆದರೆ ಅದು ಪ್ಯಾಕೆಟ್ ಅನ್ನು ಎದುರಿಸಿದರೆ ಅದು ಹೇಗೆ route ಮಾಡಬೇಕೆಂದು ತಿಳಿದಿಲ್ಲ, ಅದು ತನ್ನ ನೆರೆಯ routerಗಳಲ್ಲಿ ಒಂದನ್ನು ಪ್ರಶ್ನಿಸುತ್ತದೆ. ನೆರೆಹೊರೆಯವರಿಗೆ ಪ್ಯಾಕೆಟ್ ಅನ್ನು ಹೇಗೆ route ಮಾಡಬೇಕೆಂದು ತಿಳಿದಿದ್ದರೆ, ಅದು ಆ ಮಾಹಿತಿಯನ್ನು request routerಗೆ ಕಳುಹಿಸುತ್ತದೆ. request router ಭವಿಷ್ಯದ ಬಳಕೆಗಾಗಿ ಈ ಮಾಹಿತಿಯನ್ನು save ಮಾಡುತ್ತದೆ. ಈ ರೀತಿಯಾಗಿ, ಹೊಸ router ತನ್ನದೇ ಆದ routing ಟೇಬಲ್ ಅನ್ನು,  **n_etwork prefix_**  ಗಳ database ನಿಂದ outbound linkಗಳಿಗೆ ನಿರ್ಮಿಸುತ್ತದೆ. ನೆರೆಯ router ತಿಳಿದಿಲ್ಲದಿದ್ದರೆ, ಅದು ತನ್ನ ನೆರೆಹೊರೆಯವರನ್ನು ಪ್ರಶ್ನಿಸುತ್ತದೆ.

**ಡೊಮೇನ್(Domain) ಹೆಸರುಗಳ ಆಧಾರದ ಮೇಲೆ ನೆಟ್‌ವರ್ಕ್ ಮಾಡಲಾದ ಕಂಪ್ಯೂಟರ್‌ಗಳು IP addressಗಳನ್ನು ಹೇಗೆ ಕಂಡುಹಿಡಿಯುತ್ತವೆ?**

[www.google.com](http://www.google.com/)  ನಂತಹ human-readable domain ಹೆಸರಿನ ಐಪಿ addressನ್ನು  **“resolving the IP address”**  ಎಂದು ನಾವು ಕರೆಯುತ್ತೇವೆ. domain Name Server (DNS), ಡೊಮೇನ್ ಹೆಸರುಗಳಿಂದ IP addressಗಳಿಗೆ ಮ್ಯಾಪಿಂಗ್‌ಗಳ ವಿಕೇಂದ್ರೀಕೃತ(decentralized) ಡೇಟಾಬೇಸ್ ಮೂಲಕ ಕಂಪ್ಯೂಟರ್‌ಗಳು IP addressಗಳನ್ನು ಪರಿಹರಿಸುತ್ತವೆ .

IP Addressನ್ನು ಪರಿಹರಿಸಲು, ಕಂಪ್ಯೂಟರ್ ಮೊದಲು ತನ್ನ local DNS cacheನ್ನು ಪರಿಶೀಲಿಸುತ್ತದೆ, ಅದು ಇತ್ತೀಚೆಗೆ ಭೇಟಿ ನೀಡಿದ ವೆಬ್‌ಸೈಟ್‌ಗಳ IP addressನ್ನು ಸಂಗ್ರಹಿಸುತ್ತದೆ. ಅಲ್ಲಿ IP addressನ್ನು ಕಂಡುಹಿಡಿಯಲಾಗದಿದ್ದರೆ ಅಥವಾ IP addressನ ದಾಖಲೆ ಅವಧಿ ಮೀರಿದ್ದರೆ, ಅದು ISP DNS Serverಗಳನ್ನು ಪ್ರಶ್ನಿಸುತ್ತದೆ, ಅದು IP addressಗಳನ್ನು ಪರಿಹರಿಸಲು ಮೀಸಲಾಗಿರುತ್ತದೆ. ISP ಯ DNS serverಗಳು IP addressನ್ನು ಪರಿಹರಿಸಲು ಸಾಧ್ಯವಾಗದಿದ್ದರೆ, ಅವರು root name serversಗಳನ್ನು ಪ್ರಶ್ನಿಸುತ್ತಾರೆ, ಇದು ನಿರ್ದಿಷ್ಟ  [_top-level domain_](https://www.iana.org/domains/root/db)  ಗಾಗಿ ಪ್ರತಿ ಡೊಮೇನ್ ಹೆಸರನ್ನು ಪರಿಹರಿಸಬಹುದು.  [_top-level domain_](https://www.iana.org/domains/root/db)ಗಳು ಡೊಮೇನ್ ಹೆಸರಿನಲ್ಲಿ ಹೆಚ್ಚಿನ ಅವಧಿಯ ಪದಗಳಾಗಿವೆ. .com .net .org ಇವು top-level domain ಗೆ ಕೆಲವು ಉದಾಹರಣೆಗಳಾಗಿವೆ.

**ಅಪ್ಲಿಕೇಶನ್‌ಗಳು ಇಂಟರ್ನೆಟ್ ಮೂಲಕ ಹೇಗೆ ಸಂವಹನ ನಡೆಸುತ್ತವೆ?**

ಅನೇಕ complex ಎಂಜಿನಿಯರಿಂಗ್ projectಗಳಂತೆ, ಇಂಟರ್ನೆಟ್ ಅನ್ನು independent componentಗಳಾಗಿ ವಿಂಗಡಿಸಲಾಗಿದೆ, ಇದು ಉತ್ತಮವಾಗಿ define ಮಾಡಲಾದ interfaceಗಳ ಮೂಲಕ ಒಟ್ಟಾಗಿ ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತದೆ. ಈ componentಗಳನ್ನು Internet Network Layerಗಳು ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ ಮತ್ತು ಅವು ಲಿಂಕ್ ಲೇಯರ್(Link layer), ಇಂಟರ್ನೆಟ್ ಲೇಯರ್(Internet layer), ಟ್ರಾನ್ಸ್‌ಪೋರ್ಟ್ ಲೇಯರ್(Transport layer) ಮತ್ತು ಅಪ್ಲಿಕೇಷನ್ ಲೇಯರ್(Application Layer) ಅನ್ನು ಒಳಗೊಂಡಿರುತ್ತವೆ. ಇವುಗಳನ್ನು ಒಂದರ ಮೇಲೊಂದು ನಿರ್ಮಿಸಲಾಗಿರುವುದರಿಂದ ಅವುಗಳನ್ನು Layerಗಳು ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ; ಪ್ರತಿಯೊಂದು layer ಅದರ implimentation detailsಗಳ ಬಗ್ಗೆ ಚಿಂತಿಸದೆ ಅದರ ಕೆಳಗಿರುವ layerಗಳ ಸಾಮರ್ಥ್ಯಗಳನ್ನು ಬಳಸುತ್ತದೆ.

![Image for post](https://miro.medium.com/max/60/0*W7GnvJCtZ1Zwljdz?q=20)

![Image for post](https://miro.medium.com/max/470/0*W7GnvJCtZ1Zwljdz)

ಇಂಟರ್ನೆಟ್ ಅಪ್ಲಿಕೇಶನ್‌ಗಳು ಅಪ್ಲಿಕೇಶನ್ ಲೇಯರ್‌ನಲ್ಲಿ ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತವೆ ಮತ್ತು ಆಧಾರವಾಗಿರುವ ಲೇಯರ್‌ಗಳಲ್ಲಿನ ವಿವರಗಳ ಬಗ್ಗೆ ಚಿಂತಿಸಬೇಕಾಗಿಲ್ಲ. ಉದಾಹರಣೆಗೆ, ಒಂದು application socket ಎಂದು ಕರೆಯಲ್ಪಡುವ ಒಂದು ರಚನೆಯನ್ನು ಬಳಸಿಕೊಂಡು TCP ಮೂಲಕ ನೆಟ್‌ವರ್ಕ್‌ನಲ್ಲಿರುವ ಮತ್ತೊಂದು ಅಪ್ಲಿಕೇಶನ್‌ಗೆ ಸಂಪರ್ಕಿಸುತ್ತದೆ, ಇದು routing ಪ್ಯಾಕೆಟ್‌ಗಳ ಸಮಗ್ರ ವಿವರಗಳನ್ನು ಮತ್ತು ಸಂದೇಶಗಳನ್ನು ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು ಮರು ಜೋಡಿಸುವುದು.

**ಈ ಪ್ರತಿಯೊಂದು ಇಂಟರ್ನೆಟ್ ಲೇಯರ್‌ಗಳು ಏನು ಮಾಡುತ್ತವೆ?**

Lowest levelಲ್ಲಿ ಲಿಂಕ್ ಲೇಯರ್ ಇದ್ದು,ಇದು ಇಂಟರ್ನೆಟ್‌ನ  **“physical layer”** ಆಗಿದೆ. ಫೈಬರ್-ಆಪ್ಟಿಕ್ ಕೇಬಲ್‌ಗಳು(fiber optic cable) ಅಥವಾ ವೈಫೈ(wifi) ರೇಡಿಯೊ ಸಿಗ್ನಲ್‌ಗಳಂತಹ ಕೆಲವು physical ಮಾಧ್ಯಮದ ಮೂಲಕ ಡೇಟಾ bitsಗಳನ್ನು ರವಾನಿಸುವುದರೊಂದಿಗೆ ಲಿಂಕ್ ಲೇಯರ್ ಸಂಬಂಧಿಸಿದೆ.

ಲಿಂಕ್ ಲೇಯರ್ನ ಮೇಲ್ಭಾಗದಲ್ಲಿ ಇಂಟರ್ನೆಟ್ ಲೇಯರ್ ಇದೆ. ಇಂಟರ್ನೆಟ್ ಲೇಯರ್ ತಮ್ಮ destinationಗಳಿಗೆ ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು routing ಮಾಡಲು ಸಂಬಂಧಿಸಿದೆ. ಇಂಟರ್ನೆಟ್ ಪ್ರೊಟೊಕಾಲ್ ಈ layerಲ್ಲಿ earlier livesನ್ನು ಉಲ್ಲೇಖಿಸಿದೆ. ಇಂಟರ್ನೆಟ್ ಪ್ರೋಟೋಕಾಲ್, ನೆಟ್‌ವರ್ಕ್ ಲೋಡ್ ಅಥವಾ outagesಗಳ ಆಧಾರದ ಮೇಲೆ ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು ಕ್ರಿಯಾತ್ಮಕವಾಗಿ adjust ಮತ್ತು reroute ಮಾಡುತ್ತದೆ. ಪ್ಯಾಕೆಟ್‌ಗಳು ಅದನ್ನು ಯಾವಾಗಲೂ ತಮ್ಮ destinationಗೆ ತಲುಪಿಸುತ್ತದೆ ಎಂದು ಖಾತರಿಪಡಿಸುವುದಿಲ್ಲ, ಅದು ಸಾಧ್ಯವಾದಷ್ಟು ಉತ್ತಮವಾಗಿ ಪ್ರಯತ್ನಿಸುತ್ತದೆ.

ಇಂಟರ್ನೆಟ್ ಲೇಯರ್ನ ಮೇಲ್ಭಾಗದಲ್ಲಿ Transport layer ಇದೆ. ಈ ಪದರವು ಇಂಟರ್ನೆಟ್ ಮತ್ತು ಕೆಳಗಿನ ಲಿಂಕ್ ಲೇಯರ್‌ಗಳಲ್ಲಿdataವು loss ಆಗಬಹುದು ಎಂಬ ಅಂಶವನ್ನು ಸರಿದೂಗಿಸುತ್ತದೆ. Transport layer protocol ಈ layerದಲ್ಲಿ earlier livesಗಳನ್ನು ಉಲ್ಲೇಖಿಸಿದೆ, ಮತ್ತು ಇದು ಪ್ರಾಥಮಿಕವಾಗಿ ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು ಅವುಗಳ ಮೂಲ ಸಂದೇಶಗಳಲ್ಲಿ ಮರು ಜೋಡಿಸಲು ಮತ್ತು ನಷ್ಟವಾದ ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು ಮರು-ರವಾನಿಸಲು ಕೆಲಸ ಮಾಡುತ್ತದೆ.

ಅಪ್ಲಿಕೇಶನ್ ಲೇಯರ್ top ಅಲ್ಲಿ ಇರುತ್ತದೆ. ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು ಇಂಟರ್ನೆಟ್‌ನಾದ್ಯಂತ ಚಲಿಸುವ ಸಂಕೀರ್ಣ ವಿವರಗಳನ್ನು ನಿರ್ವಹಿಸಲು ಈ ಪದರವು ಕೆಳಗಿನ ಎಲ್ಲಾ ಲೇಯರ್‌ಗಳನ್ನು ಬಳಸುತ್ತದೆ. ಸಾಕೆಟ್‌(socket)ಗಳಂತಹ ಸರಳ abstractions ಇಂಟರ್ನೆಟ್ ಮೂಲಕ ಇತರ ಅಪ್ಲಿಕೇಶನ್‌ಗಳೊಂದಿಗೆ ಸುಲಭವಾಗಿ ಸಂಪರ್ಕವನ್ನು ಮಾಡಲು ಇದು ಅನುಮತಿಸುತ್ತದೆ. ಅಪ್ಲಿಕೇಶನ್ ಲೇಯರ್‌ನಲ್ಲಿ ವೆಬ್ ಬ್ರೌಸರ್‌ಗಳು ಮತ್ತು ವೆಬ್ ಸರ್ವರ್‌ಗಳು ಹೇಗೆ interact ನಡೆಸಬೇಕು ಎಂಬುದನ್ನು HTTP ಪ್ರೊಟೊಕಾಲ್ ನಿರ್ದಿಷ್ಟಪಡಿಸುತ್ತದೆ. ಅಪ್ಲಿಕೇಶನ್ ಲೇಯರ್‌ನಲ್ಲಿ ಇಮೇಲ್ ಕ್ಲೈಂಟ್‌ಗಳು ಇಮೇಲ್ ಜೀವನವನ್ನು ಹೇಗೆ ಪಡೆದುಕೊಳ್ಳಬೇಕು ಎಂಬುದನ್ನು IMAP ಪ್ರೋಟೋಕಾಲ್ ನಿರ್ದಿಷ್ಟಪಡಿಸುತ್ತದೆ. ಫೈಲ್-ಡೌನ್‌ಲೋಡ್ ಮಾಡುವ ಕ್ಲೈಂಟ್‌ಗಳು ಮತ್ತು ಫೈಲ್-ಹೋಸ್ಟಿಂಗ್ ಸರ್ವರ್‌ಗಳ ನಡುವೆ File Transfer Protocol ಅನ್ನು ನಿರ್ದಿಷ್ಟಪಡಿಸುವ FTP ಪ್ರೋಟೋಕಾಲ್ ಅಪ್ಲಿಕೇಶನ್ ಲೇಯರ್‌ನಲ್ಲಿ ಇದೆ.

**ಸರ್ವರ್ ವಿರುದ್ಧ ಕ್ಲೈಂಟ್ ಎಂದರೇನು?**

ಕ್ಲೈಂಟ್‌ಗಳು(Client) ಮತ್ತು ಸರ್ವರ್‌ಗಳು(server) internetಲ್ಲಿ communicate ಮಾಡುವ ಎರಡೂ ಅಪ್ಲಿಕೇಶನ್‌ಗಳಾಗಿದ್ದರೂ, ಕ್ಲೈಂಟ್‌ಗಳು “ಬಳಕೆದಾರರಿಗೆ ಹತ್ತಿರವಾಗಿದ್ದಾರೆ(closer to the user)” ಏಕೆಂದರೆ ಅವು ವೆಬ್ ಬ್ರೌಸರ್‌ಗಳು, ಇಮೇಲ್ ಕ್ಲೈಂಟ್‌ಗಳು ಅಥವಾ ಸ್ಮಾರ್ಟ್ ಫೋನ್ ಅಪ್ಲಿಕೇಶನ್‌ಗಳಂತಹ ಹೆಚ್ಚು user-facing ಅಪ್ಲಿಕೇಶನ್‌ಗಳಾಗಿವೆ. ಸರ್ವರ್‌ಗಳು ದೂರಸ್ಥ ಕಂಪ್ಯೂಟರ್‌ನಲ್ಲಿ ಚಾಲನೆಯಲ್ಲಿರುವ ಅಪ್ಲಿಕೇಶನ್‌ಗಳಾಗಿವೆ, ಅದು ಕ್ಲೈಂಟ್‌ಗೆ ಅಗತ್ಯವಿರುವಾಗ ಇಂಟರ್ನೆಟ್ ಮೂಲಕ communicate ಮಾಡುತ್ತದೆ.

ಹೆಚ್ಚು formal definition ಎಂದರೆ ಸಂಪರ್ಕವನ್ನು ಪ್ರಾರಂಭಿಸುವ ಅಪ್ಲಿಕೇಶನ್ client TCP ಆಗಿದೆ, ಆದರೆ TCP ಸಂಪರ್ಕವನ್ನು ಸ್ವೀಕರಿಸುವ ಅಪ್ಲಿಕೇಶನ್ server ಆಗಿದೆ.

**ಕ್ರೆಡಿಟ್ ಕಾರ್ಡ್‌ಗಳಂತಹ ಸೂಕ್ಷ್ಮ ಡೇಟಾವನ್ನು ಇಂಟರ್ನೆಟ್ ಮೂಲಕ ಸುರಕ್ಷಿತವಾಗಿ ರವಾನಿಸುವುದು ಹೇಗೆ?**

ಇಂಟರ್ನೆಟ್‌ನ ಆರಂಭಿಕ ದಿನಗಳಲ್ಲಿ, ನೆಟ್‌ವರ್ಕ್ routerಗಳು ಮತ್ತು ಲಿಂಕ್‌ಗಳು physical ಆಗಿ ಸುರಕ್ಷಿತ ಸ್ಥಳಗಳಲ್ಲಿವೆ ಎಂದು ಖಚಿತಪಡಿಸಿಕೊಂಡಿತ್ತು. ಆದರೆ ಇಂಟರ್ನೆಟ್ sizeಲ್ಲಿ ಬೆಳೆದಂತೆ, ಹೆಚ್ಚಿನ routerಗಳು ಹೆಚ್ಚು ದುರ್ಬಲತೆಯ ಅಂಶಗಳನ್ನು ಸೂಚಿಸುತ್ತವೆ. ಇದಲ್ಲದೆ, ವೈಫೈನಂತಹ ವೈರ್‌ಲೆಸ್(wireless) ತಂತ್ರಜ್ಞಾನಗಳ ಆಗಮನದೊಂದಿಗೆ, ಹ್ಯಾಕರ್‌ಗಳು ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು ತಡೆಯಬಹುದು; ನೆಟ್‌ವರ್ಕ್ hardware ದೈಹಿಕವಾಗಿ ಸುರಕ್ಷಿತವಾಗಿದೆ ಎಂದು ಖಚಿತಪಡಿಸಿಕೊಳ್ಳಲು ಅದು ಸಾಕಾಗಲಿಲ್ಲ. ಇದಕ್ಕೆ ಎಸ್‌ಎಸ್‌ಎಲ್ / ಟಿಎಲ್‌ಎಸ್ (SSL/TLS) ಮೂಲಕ ಎನ್‌ಕ್ರಿಪ್ಶನ್(encryption) ಮತ್ತು ದೃಢೀಕರಣ(authentication) ಪರಿಹಾರವಾಗಿದೆ.

**ಎಸ್‌ಎಸ್‌ಎಲ್ / ಟಿಎಲ್‌ಎಸ್ ಎಂದರೇನು?**

ಎಸ್‌ಎಸ್‌ಎಲ್ ಎಂದರೆ  **_Secured Sockets Layer_**. ಟಿಎಲ್ಎಸ್ ಎಂದರೆ  **T_ransport Layer Security_**. ಎಸ್‌ಎಸ್‌ಎಲ್ ಅನ್ನು ಮೊದಲು ನೆಟ್‌ಸ್ಕೇಪ್ 1994 ರಲ್ಲಿ ಅಭಿವೃದ್ಧಿಪಡಿಸಿತು ಆದರೆ ನಂತರದ ಹೆಚ್ಚು ಸುರಕ್ಷಿತ ಆವೃತ್ತಿಯನ್ನು ರೂಪಿಸಲಾಯಿತು ಮತ್ತು ಟಿಎಲ್‌ಎಸ್ ಎಂದು ಮರುನಾಮಕರಣ ಮಾಡಲಾಯಿತು. ನಾವು ಅವರನ್ನು ಒಟ್ಟಿಗೆ ಎಸ್‌ಎಸ್‌ಎಲ್ / ಟಿಎಲ್‌ಎಸ್ ಎಂದು ಉಲ್ಲೇಖಿಸುತ್ತೇವೆ.

ಎಸ್‌ಎಸ್‌ಎಲ್ / ಟಿಎಲ್‌ಎಸ್ ಒಂದು ಐಚ್ಛಿಕ ಪದರವಾಗಿದ್ದು(optiona layer) ಅದು Transport layer ಮತ್ತು ಅಪ್ಲಿಕೇಶನ್ ಲೇಯರ್ ನಡುವೆ ಇರುತ್ತದೆ. ಎನ್‌ಕ್ರಿಪ್ಶನ್(encryption) ಮತ್ತು ದೃಢೀಕರಣ(authentication)ದ ಮೂಲಕ ಸೂಕ್ಷ್ಮ ಮಾಹಿತಿಯ ಸುರಕ್ಷಿತ ಇಂಟರ್ನೆಟ್ ಸಂವಹನವನ್ನು ಇದು ಅನುಮತಿಸುತ್ತದೆ.

ಎನ್‌ಕ್ರಿಪ್ಶನ್(encryption) ಎಂದರೆ ಸರ್ವರ್‌ಗೆ TCP ಸಂಪರ್ಕವನ್ನು ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಲು ಕ್ಲೈಂಟ್ ವಿನಂತಿಸಬಹುದು. ಇದರರ್ಥ ಕ್ಲೈಂಟ್ ಮತ್ತು ಸರ್ವರ್ ನಡುವೆ ಕಳುಹಿಸಲಾದ ಎಲ್ಲಾ ಸಂದೇಶಗಳನ್ನು ಪ್ಯಾಕೆಟ್‌ಗಳಾಗಿ ವಿಭಜಿಸುವ ಮೊದಲು ಅದನ್ನು ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಲಾಗುತ್ತದೆ. ಈ ಪ್ಯಾಕೆಟ್‌ಗಳನ್ನು ಹ್ಯಾಕರ್‌ಗಳು ತಡೆದರೆ, ಅವರಿಗೆ ಮೂಲ ಸಂದೇಶವನ್ನು ಪುನರ್ನಿರ್ಮಿಸಲು ಸಾಧ್ಯವಾಗುವುದಿಲ್ಲ.

ದೃಢೀಕರಣ(authentication) ಎಂದರೆ ಕ್ಲೈಂಟ್ ಸರ್ವರ್ ಎಂದು ಹೇಳಿಕೊಳ್ಳುವವರು ಎಂದು ನಂಬಬಹುದು. ಇದು  [man-in-the-middle attacks](https://en.wikipedia.org/wiki/Man-in-the-middle_attack)  ಯಿಂದ ರಕ್ಷಿಸುತ್ತದೆ, ಇದು ದುರುದ್ದೇಶಪೂರಿತ ಪಕ್ಷವು ಕ್ಲೈಂಟ್ ಮತ್ತು ಸರ್ವರ್ ನಡುವಿನ ಸಂಪರ್ಕವನ್ನು ಕದ್ದಾಲಿಕೆ ಮತ್ತು ಅವರ communicationನ್ನು ಹಾಳುಮಾಡದಂತೆ ತಡೆಯುತ್ತದೆ.

ನಾವು ಆಧುನಿಕ ಬ್ರೌಸರ್‌ಗಳಲ್ಲಿ ಎಸ್‌ಎಸ್‌ಎಲ್-ಶಕ್ತಗೊಂಡ ವೆಬ್‌ಸೈಟ್‌ಗಳಿಗೆ ಭೇಟಿ ನೀಡಿದಾಗಲೆಲ್ಲಾ ನಾವು ಎಸ್‌ಎಸ್‌ಎಲ್ ಅನ್ನು ಕಾರ್ಯರೂಪದಲ್ಲಿ ನೋಡುತ್ತೇವೆ. Http ಬದಲಿಗೆ https ಪ್ರೊಟೊಕಾಲ್ ಬಳಸಿ ಬ್ರೌಸರ್ ವೆಬ್ ಸೈಟ್ ಅನ್ನು ವಿನಂತಿಸಿದಾಗ, ಅದು ವೆಬ್ ಸರ್ವರ್‌ಗೆ ಅದು SSL ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಿದ ಸಂಪರ್ಕವನ್ನು ಬಯಸುತ್ತದೆ ಎಂದು ಹೇಳುತ್ತದೆ. ವೆಬ್ ಸರ್ವರ್ ಎಸ್‌ಎಸ್‌ಎಲ್ ಅನ್ನು ಬೆಂಬಲಿಸಿದರೆ, ಸುರಕ್ಷಿತ ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಿದ ಸಂಪರ್ಕವನ್ನು ಮಾಡಲಾಗಿದೆ ಮತ್ತು ಬ್ರೌಸರ್‌ನಲ್ಲಿ address barಲ್ಲಿ ನಾವು ಲಾಕ್ ಐಕಾನ್ ಅನ್ನು ನೋಡುತ್ತೇವೆ.

![Image for post](https://miro.medium.com/max/60/0*XECbHsnjYdod1IHY?q=20)

![Image for post](https://miro.medium.com/max/361/0*XECbHsnjYdod1IHY)

amazon.com ವೆಬ್ ಸರ್ವರ್ ಎಸ್‌ಎಸ್‌ಎಲ್-ಶಕ್ತಗೊಂಡಿದೆ. ಸಂವಹನವನ್ನು ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಲಾಗಿದೆಯೆ ಎಂದು ಖಚಿತಪಡಿಸಿಕೊಳ್ಳಲು ಬ್ರೌಸರ್ https ಮೂಲಕ ಅದನ್ನು ಸಂಪರ್ಕಿಸಬಹುದು. ಬ್ರೌಸರ್ ಇದು ನಿಜವಾದ amazon.com ಸರ್ವರ್‌ನೊಂದಿಗೆ ಸಂವಹನ ನಡೆಸುತ್ತಿದೆ ಎಂಬ ವಿಶ್ವಾಸದಲ್ಲಿದೆ, ಮತ್ತು ಮಧ್ಯದಲ್ಲಿ ಮನುಷ್ಯನಲ್ಲ.

**ಎಸ್‌ಎಸ್‌ಎಲ್ ಸರ್ವರ್‌ನ ಗುರುತನ್ನು ಹೇಗೆ ದೃಢೀಕರಿಸುತ್ತದೆ ಮತ್ತು ಅವರ ಸಂವಹನವನ್ನು ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡುತ್ತದೆ?**

ಇದು  _asymmetric encryption_  ಮತ್ತು ಎಸ್‌ಎಸ್‌ಎಲ್ ಪ್ರಮಾಣಪತ್ರಗಳನ್ನು ಬಳಸುತ್ತದೆ.

_asymmetric encryption_, (encryption) ಲಿಪೀಕರಣ ಯೋಜನೆ(scheme)ಯಾಗಿದ್ದು ಅದು public key ಮತ್ತು private key ಬಳಸುತ್ತದೆ. ಈ keyಗಳು ಮೂಲತಃ ದೊಡ್ಡ ಅವಿಭಾಜ್ಯಗಳಿಂದ ಪಡೆದ ಸಂಖ್ಯೆಗಳು. ಡೇಟಾವನ್ನು ಡೀಕ್ರಿಪ್ಟ್(decrypt) ಮಾಡಲು ಮತ್ತು ದಾಖಲೆಗಳಿಗೆ ಸಹಿ ಮಾಡಲು private keyಯನ್ನು ಬಳಸಲಾಗುತ್ತದೆ. ಡೇಟಾವನ್ನು ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಲು ಮತ್ತು ಸಹಿ ಮಾಡಿದ ದಾಖಲೆಗಳನ್ನು ಪರಿಶೀಲಿಸಲು public keyನ್ನು ಬಳಸಲಾಗುತ್ತದೆ.  _asymmetric encryption, symmetric_ ಲಿಪೀಕರಣಕ್ಕಿಂತ ಭಿನ್ನವಾಗಿದೆ,  _asymmetric encryption_ ಎಂದರೆ ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡುವ ಸಾಮರ್ಥ್ಯವು ಡೀಕ್ರಿಪ್ಟ್ ಮಾಡುವ ಸಾಮರ್ಥ್ಯವನ್ನು ಸ್ವಯಂಚಾಲಿತವಾಗಿ ನೀಡುವುದಿಲ್ಲ. ಸಂಖ್ಯೆ ಸಿದ್ಧಾಂತ ಎಂಬ ಗಣಿತ ಶಾಖೆಯಲ್ಲಿ ತತ್ವಗಳನ್ನು ಬಳಸುವ ಮೂಲಕ ಇದು ಮಾಡುತ್ತದೆ([a mathematical branch called number theory](https://medium.com/@User3141592/notes-on-computational-cryptography-98db5f2908f1)).

ಎಸ್‌ಎಸ್‌ಎಲ್ ಪ್ರಮಾಣಪತ್ರವು ವೆಬ್ ಡಾಕ್ಯುಮೆಂಟ್‌ಗೆ ನಿಯೋಜಿಸಲಾದ public keyಯನ್ನು ಒಳಗೊಂಡಿರುವ ಡಿಜಿಟಲ್ ಡಾಕ್ಯುಮೆಂಟ್ ಆಗಿದೆ. ಈ ಎಸ್‌ಎಸ್‌ಎಲ್ certificateಗಳನ್ನು ಸರ್ವರ್‌ಗೆ certificate authorities ನೀಡುತ್ತಾರೆ. ಆಪರೇಟಿಂಗ್ ಸಿಸ್ಟಂಗಳು, ಮೊಬೈಲ್ ಸಾಧನಗಳು ಮತ್ತು ಬ್ರೌಸರ್‌ಗಳು ಕೆಲವು ಪ್ರಮಾಣಪತ್ರ ಅಧಿಕಾರಿಗಳ ಡೇಟಾಬೇಸ್‌ನೊಂದಿಗೆ ಬರುತ್ತವೆ ಆದ್ದರಿಂದ ಅದು ಎಸ್‌ಎಸ್‌ಎಲ್ ಪ್ರಮಾಣಪತ್ರಗಳನ್ನು ಪರಿಶೀಲಿಸಬಹುದು.

ಕ್ಲೈಂಟ್ ಸರ್ವರ್‌ನೊಂದಿಗೆ ಎಸ್‌ಎಸ್‌ಎಲ್-ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಿದ ಸಂಪರ್ಕವನ್ನು ಕೋರಿದಾಗ, ಸರ್ವರ್ ತನ್ನ ಎಸ್‌ಎಸ್‌ಎಲ್ ಪ್ರಮಾಣಪತ್ರವನ್ನು ಹಿಂದಕ್ಕೆ ಕಳುಹಿಸುತ್ತದೆ. ಕ್ಲೈಂಟ್ SSL ಪ್ರಮಾಣಪತ್ರವನ್ನು ಪರಿಶೀಲಿಸುತ್ತದೆ.

-   ಈ ಸರ್ವರ್‌ಗೆ ನೀಡಲಾಗುತ್ತದೆ
-   ವಿಶ್ವಾಸಾರ್ಹ ಪ್ರಮಾಣಪತ್ರ ಪ್ರಾಧಿಕಾರದಿಂದ ಸಹಿ ಮಾಡಲಾಗಿದೆ
-   ಅವಧಿ ಮುಗಿದಿಲ್ಲ.

ಕ್ಲೈಂಟ್ ನಂತರ randomಗಿ ರಚಿಸಲಾದ ತಾತ್ಕಾಲಿಕ secret key ಯನ್ನುಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಲು ಮತ್ತು ಅದನ್ನು ಸರ್ವರ್‌ಗೆ ಕಳುಹಿಸಲು ಎಸ್‌ಎಸ್‌ಎಲ್ ಪ್ರಮಾಣಪತ್ರದ public keyಯನ್ನು ಬಳಸುತ್ತದೆ. ಸರ್ವರ್ ಅನುಗುಣವಾದ privateಯನ್ನು ಹೊಂದಿರುವುದರಿಂದ, ಅದು ಕ್ಲೈಂಟ್‌ನ ತಾತ್ಕಾಲಿಕ secret keyಯನ್ನು ಡೀಕ್ರಿಪ್ಟ್ ಮಾಡಬಹುದು. ಈಗ ಕ್ಲೈಂಟ್ ಮತ್ತು ಸರ್ವರ್ ಇಬ್ಬರಿಗೂ ಈ ತಾತ್ಕಾಲಿಕ secret keyಯನ್ನು ತಿಳಿದಿದೆ, ಆದ್ದರಿಂದ ಇಬ್ಬರೂ ಪರಸ್ಪರ ಕಳುಹಿಸುವ ಸಂದೇಶಗಳನ್ನು ಸಮ್ಮಿತೀಯವಾಗಿ ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಲು ಇದನ್ನು ಬಳಸಬಹುದು. ಅವರ ಅಧಿವೇಶನ ಮುಗಿದ ನಂತರ ಅವರು ಈ temporary secret keyಯನ್ನು ತ್ಯಜಿಸುತ್ತಾರೆ.

**ಎಸ್‌ಎಸ್‌ಎಲ್-ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಿದ ಅಧಿವೇಶನವನ್ನು ಹ್ಯಾಕರ್ ತಡೆದರೆ ಏನಾಗುತ್ತದೆ?**

ಕ್ಲೈಂಟ್ ಮತ್ತು ಸರ್ವರ್ ನಡುವೆ ಕಳುಹಿಸಿದ ಪ್ರತಿಯೊಂದು ಸಂದೇಶವನ್ನು ಹ್ಯಾಕರ್ ತಡೆದಿದ್ದಾನೆಂದು ಭಾವಿಸೋಣ. ಸರ್ವರ್ ಕಳುಹಿಸುವ ಎಸ್‌ಎಸ್‌ಎಲ್ ಪ್ರಮಾಣಪತ್ರ ಮತ್ತು ಕ್ಲೈಂಟ್‌ನ ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಿದ ತಾತ್ಕಾಲಿಕ secret keyಯನ್ನು ಹ್ಯಾಕರ್ ನೋಡುತ್ತಾನೆ. ಆದರೆ ಹ್ಯಾಕರ್ private keyಯನ್ನು ಹೊಂದಿರದ ಕಾರಣ ಅದು ತಾತ್ಕಾಲಿಕವಾಗಿ secret keyಯನ್ನು ಡೀಕ್ರಿಪ್ಟ್ ಮಾಡಲು ಸಾಧ್ಯವಿಲ್ಲ. ಮತ್ತು ಇದು ತಾತ್ಕಾಲಿಕ secret keyಯನ್ನು ಹೊಂದಿರದ ಕಾರಣ, ಕ್ಲೈಂಟ್ ಮತ್ತು ಸರ್ವರ್ ನಡುವಿನ ಯಾವುದೇ ಸಂದೇಶಗಳನ್ನು ಡೀಕ್ರಿಪ್ಟ್ ಮಾಡಲು ಸಾಧ್ಯವಿಲ್ಲ.

**ಸಾರಾಂಶ(Summary)**

-   ವಿಕೇಂದ್ರೀಕೃತ(decentralized) ಕಂಪ್ಯೂಟರ್ ನೆಟ್‌ವರ್ಕ್ ಗುರಿಯೊಂದಿಗೆ ಇಂಟರ್ನೆಟ್ 1960 ರ ದಶಕದಲ್ಲಿ ARPANET ಆಗಿ ಪ್ರಾರಂಭವಾಯಿತು.
-   ಭೌತಿಕವಾಗಿ, ಇಂಟರ್ನೆಟ್ ಎನ್ನುವುದು wireಗಳು, ಕೇಬಲ್‌ಗಳು ಮತ್ತು ರೇಡಿಯೊ ಸಿಗ್ನಲ್‌ಗಳ ಮೂಲಕ ಬಿಟ್‌ಗಳನ್ನು ಪರಸ್ಪರ ಚಲಿಸುವ ಕಂಪ್ಯೂಟರ್‌ಗಳ ಸಂಗ್ರಹವಾಗಿದೆ.
-   ಅನೇಕ ಸಂಕೀರ್ಣ ಎಂಜಿನಿಯರಿಂಗ್ ಯೋಜನೆಗಳಂತೆ, ಇಂಟರ್ನೆಟ್ ಅನ್ನು ವಿವಿಧ ಪದರಗಳಾಗಿ ವಿಭಜಿಸಲಾಗಿದೆ, ಪ್ರತಿಯೊಂದೂ ಸಣ್ಣ ಸಮಸ್ಯೆಯನ್ನು ಪರಿಹರಿಸುವಲ್ಲಿ ಸಂಬಂಧಿಸಿದೆ. ಈ ಪದರಗಳು ಉತ್ತಮವಾಗಿ ವ್ಯಾಖ್ಯಾನಿಸಲಾದ ಇಂಟರ್ಫೇಸ್‌ಗಳಲ್ಲಿ ಪರಸ್ಪರ ಸಂಪರ್ಕಗೊಳ್ಳುತ್ತವೆ.
-   ಇಂಟರ್ನೆಟ್ ಮತ್ತು ಅದರ ಅಪ್ಲಿಕೇಶನ್‌ಗಳು ವಿಭಿನ್ನ ಸ್ತರಗಳಲ್ಲಿ ಹೇಗೆ ಕಾರ್ಯನಿರ್ವಹಿಸಬೇಕು ಎಂಬುದನ್ನು ವ್ಯಾಖ್ಯಾನಿಸುವ ಹಲವು ಪ್ರೋಟೋಕಾಲ್‌ಗಳಿವೆ: HTTP, IMAP, SSH, TCP, UDP, IP, ಇತ್ಯಾದಿ. ಈ ಅರ್ಥದಲ್ಲಿ, ಇಂಟರ್‌ನೆಟ್ ಕಂಪ್ಯೂಟರ್‌ಗಳ ಭೌತಿಕ ನೆಟ್‌ವರ್ಕ್ ಆಗಿರುವುದರಿಂದ ಕಂಪ್ಯೂಟರ್‌ಗಳು ಮತ್ತು ಪ್ರೋಗ್ರಾಂಗಳು ಹೇಗೆ ವರ್ತಿಸಬೇಕು ಎನ್ನುವ ನಿಯಮಗಳ ಸಂಗ್ರಹವಾಗಿದೆ.
-   ಅಂತರ್ಜಾಲದ ಬೆಳವಣಿಗೆ, ವೈಫೈ ಆಗಮನ ಮತ್ತು ಇ-ಕಾಮರ್ಸ್ ಅಗತ್ಯತೆಗಳೊಂದಿಗೆ, ಭದ್ರತಾ ಕಾಳಜಿಗಳನ್ನು ಪರಿಹರಿಸಲು ಎಸ್‌ಎಸ್‌ಎಲ್ / ಟಿಎಲ್‌ಎಸ್ ಅನ್ನು ಅಭಿವೃದ್ಧಿಪಡಿಸಲಾಗಿದೆ.

**Article By: Hemalatha**

Credits:  [https://medium.com/@User3141592/how-does-the-internet-work-edc2e22e7eb8](https://medium.com/@User3141592/how-does-the-internet-work-edc2e22e7eb8)

MicroDegree is an edtech platform for learning Emerging Technologies such as Full-Stack Development, Data Science, Machine Learning using vernacular at an affordable price. For more details reach out to hello@microdegree.work

🚀 For Course Certification : [https://bit.ly/3gt2nY7](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqblAzcGQxZlRtSmdYZlppbDNUd2t0MFNSanV1QXxBQ3Jtc0tuS2VjaXpMd1hFS1I5NEFuMkxkYThlZE9MZkVzNGFmTXYxTTRtZjBsX0lkSTU3MEpEdnpCTnI3MUp2QVpNdWc0LXBjNEpVWEVhMTBuajBEeXRiMnZSWnpFVDJHMTlCRk91bkNpR24ySGxUSzJUblNfUQ%3D%3D&q=https%3A%2F%2Fbit.ly%2F3gt2nY7)

👍 Youtube:: [https://bit.ly/3ajK4Cz](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqbDlUVFVtUVN1Wnl0Z3lpZ19aUVV5ZVU1SWQyQXxBQ3Jtc0tuamNVOWJCVkdsNmwzcEF2VG1XS0cwYmZWekJVbFp2enBldkg1WUEzUm1iSkZuV0ZzbGduSG8tSXlRM1N1bzRtR1BCMGN2cTJMekJSS0xzVE9pdFBrd2hpNUV5SDQ5dl9sSFFYbERzQ1NNdU5CWWU4WQ%3D%3D&q=https%3A%2F%2Fbit.ly%2F3ajK4Cz)

Website : [https://microdegree.work](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqbjR2M3JJekdSZTZlTVFCNkt5RFBTc1JNMlhpUXxBQ3Jtc0tuZHhRdjZtQW9ubmliWXAxSVNfMm5UemNrS2RMd1hDMmtIdEdGcmlFZmpkTDRkV1JFbkl3Wng1b2NRSXZJeWVlMjFGWmRpWmJSUU5jTGZmMFA0NTMxRUJtTnBlVlNESUdDYlA1QU4tcUdzZ1gwZHFUWQ%3D%3D&q=https%3A%2F%2Fmicrodegree.work)

LinkedIn : [https://www.linkedin.com/company/micr](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqa1Z1SEw5M182a2I3ZC1BN25WeFdYYVNaRWkzQXxBQ3Jtc0tsTmlGQkN5RExFekhvWWFjVHJEZUZadVZVNW5NTURjYkxaSWlVTzFJaVU0aUJ3Q1Y1QXZaRU5sbEJFaVpiOUp6a3V4a3dZczVlSVA4SzVvYU1Jc3A3SEVUMkROUEpNeFFSNkxrbldZOVhTQTBUQWdFbw%3D%3D&q=https%3A%2F%2Fwww.linkedin.com%2Fcompany%2Fmicr)...

Facebook : [https://www.facebook.com/microdegree](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqa3BNeV9oRnNsVmdiMW1malJ4M3M2REVXUVItUXxBQ3Jtc0tsN0V6MXIxOXRCSU9DMDVBQm0wemEyMnFWMWRNQVRNNlNxX2ZwOHdQLWRUWVQ1SnBSR3JFLUFnLV9VS2FYdk9QQ0x5MjZZOEMyV2JkV2o2emNVMHhZVEZUbDRKdTBoVnBXS3FGNERiZkN3aFNXOF9Xbw%3D%3D&q=https%3A%2F%2Fwww.facebook.com%2Fmicrodegree)

Instagram : [https://www.instagram.com/micro.degree](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqbU82YjFKOFBrMXZ4QkRrWWtlbTlzV1VvU1g1QXxBQ3Jtc0trYndfRGt1cUtVS3ZUaFRkVEJtSUd4M1VJTndfR2s1WDQ0Y3Axd0dXdzN1eVRNZHF2VEo5MFhyZkkxRmVXcXJZMUN0X1dXYTZsY1RyNS11OVJWWG0zd0ZKX1EzcXJMSFU4Tnd2QzF6dUJYLTdrZW0zaw%3D%3D&q=https%3A%2F%2Fwww.instagram.com%2Fmicro.degree)