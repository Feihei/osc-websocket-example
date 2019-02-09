Max example about receiving OSC data through WebSocket.

There have been already some Max to web browser showcases:

- [xebra.js from MiraWeb](https://github.com/Cycling74/miraweb/tree/master/packages/xebra.js)

- [wsserver](https://github.com/olilarkin/wsserver)

Now Max 8 has a wonderful feature `Node for Max`. So the WebSocket and OSC functions in this example are actually implemented through NodeJS.

Use library [osc.js](https://github.com/colinbdclark/osc.js) to pack and parse OSC data.   
And osc.js itself supports WebSocket (and UDP, Serial port,  TCP), so that's all.

Cycling74 also has a WebSocket (no OSC) example: [max_socket](https://github.com/Cycling74/n4m-examples/tree/master/sockets). 


-----
Welcome PR! 👏

Cheers~

Contra

- patreon (**buy me a coffee** XD): [avantcontra](https://www.patreon.com/avantcontra)
- website: [floatbug.com/contra](https://www.floatbug.com/contra)
- facebook: [avantcontra](https://facebook.com/avantcontra)
- twitter: [avantcontra](https://twitter.com/avantcontra)
- 微信公众号/知乎专栏：[浮生开方](https://zhuanlan.zhihu.com/floatlab)