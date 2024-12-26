# JuniperDanteNDI 
Built on jorblad's config, this is a config for Juniper EX switch, with a single VLAN that holds Dante and NDI video data.

Additionally, this config allocates NDI 5/6 (RUDP) traffic to the assured-forwarding queue, and re-marks it as DSCP 26 (in-line with many other AVoIP video formats) to help create QoS rules on downstream switches.
