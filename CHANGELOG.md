# Changelog
This document provides an overview of changes between released versions of this specification. It is particularly important to consider this when implementing Registration and Query APIs which may support multiple releases simultaneously to ease upgrades in large facilities (see [Upgrade Path](docs/6.0.%20Upgrade%20Path.md)).

## Release v1.1
* Add multi-protocol support and version identification to Node API /self and hence Query API /nodes
* Add 'api\_proto' TXT records to DNS-SD advertisements
* Add 'api\_ver' TXT records to DNS-SD advertisements
* Add guidance on use of DNS SRV record priority and weight
* Add support for secure websockets to the Query API
* Add support for Upgrade headers when using websockets
* Add paging support to the Query API
* Add advanced query parameter support for the Query API
* Add 'device\_id' to Flow attributes covering cases where a Device is a content transformer only
* Permit Senders without attached Flows to model a Device before internal routing has been performed
* Add support for exposing control endpoints from Devices
* Add support for muxed Sources and Flows (TR-04 and 2022-6)
* Add attributes for Sources and Flows for TR-03 set of media streams (raw video, raw audio, anc data)
* Ensure all API resources consistently advertise a 'label', 'description' and 'tags'
* Add support for signalling clocks exposed by Nodes and used by Sources

## Release v1.0
* Initial release
