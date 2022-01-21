+++
category = ""

[[xeps]]
  resource = "https://xmpp.org/extensions/xep-0047.html"
  status   = "complete"
  version  = "2.0.1"
+++

Package **`ibb`** implements In-Band Bytestreams.

[IBB] provides a mechanism for transmitting data over the signaling channel.
It provides a useful fallback for other more efficient data transfer mechanisms
such as [SOCKS5 Bytestreams] when a connection cannot be negotiated
out-of-band.

[IBB]: https://xmpp.org/extensions/xep-0261.html
[SOCKS5 Bytestreams]: https://xmpp.org/extensions/xep-0260.html
