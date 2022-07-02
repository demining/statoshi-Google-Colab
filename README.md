-------------------------
### Run statoshi-Google-Colab

https://colab.research.google.com/drive/1OShIMVcFZ_khsUIBOIV1lzrqAGo1gfm_?usp=sharing

-------------------------

Statoshi's objective is to protect Bitcoin by bringing transparency to the activity
occurring on the node network. By making this data available, Bitcoin developers can
learn more about node performance, gain operational insight about the network, and
the community can be informed about attacks and aberrant behavior in a timely fashion.

There is a live Grafana dashboard at [statoshi.info](https://statoshi.info)

License
-------

Statoshi is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see http://opensource.org/licenses/MIT.

Development Process
-------

Statoshi's changeset to Bitcoin Core is applied in the `master` branch and is
built and tested after each merge from upstream or from a pull request. However,
it not guaranteed to be completely stable. We do not recommend using Statoshi
as a Bitcoin wallet.

A guide for Statoshi developers is available [here](https://blog.lopp.net/statoshi-developer-s-guide/)

Other Notes
-------

A system metrics daemon is available [here](https://github.com/jlopp/bitcoin-utils/blob/master/systemMetricsDaemon.py)

Statoshi also supports running multiple nodes that emit metrics to a single graphite instance.
In order to facilitate this, you can add a line to bitcoin.conf that will partition each
metric by the name of the host: statshostname=yourNodeName

----

|  | Donation Address |
| --- | --- |
| ♥ __BTC__ | 1Lw2kh9WzCActXSGHxyypGLkqQZfxDpw8v |
| ♥ __ETH__ | 0xaBd66CF90898517573f19184b3297d651f7b90bf |
