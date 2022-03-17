+++
category = ""
summary = "Package compress implements XML level stream compression."

[[xeps]]
  resource = "https://xmpp.org/extensions/xep-0138.html"
  status   = "complete"
  version  = "2.0"
[[xeps]]
  resource = "https://xmpp.org/extensions/xep-0229.html"
  status   = "complete"
  version  = "1.0"
+++

Package **`compress`** implements XML level stream compression.

Be advised: stream compression has many of the same security considerations as
TLS compression (see [RFC 3749 §6]) and may be difficult to implement safely
without special expertise.

[RFC 3749 §6]: https://datatracker.ietf.org/doc/html/rfc3749#section-6
