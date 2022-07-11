+++
title    = "legacy"
date     = "2022-03-17T09:00:00-04:00"
repo     = "https://mellium.im/repo/legacy"
todo     = "https://mellium.im/issue"
category = "Other"
summary  = "The legacy module contains outdated XMPP functionality."
+++

The **`legacy`** module contains outdated XMPP functionality.

Its contains packages that were either removed from the main [`mellium.im/xmpp`]
module before 1.0 or packages that implement functionality that is not
recommended for use by the XMPP Standards Foundation but is still used in the
wild and may be required on occasion.

Generally speaking, new uses of the `legacy` module are discouraged if at all
possible.

[`mellium.im/xmpp`]: /xmpp
