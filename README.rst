Anomalous-DNS
=============
A set of zeek scripts providing a module for tracking and correlating abnormal DNS behavior. Detection of tunneling and C&C through connection duration and volume, request and answer size, DNS request type, and unique queries per domain.

Requirements
____________

domain-tld: https://github.com/sethhall/domain-tld
(automatically installed with package)

Installation
____________

``zkg install sensorfleet/anomalous-dns``

Documentation
_____________

Current documentation consists of inline comments.

This version has the following changes over jbaggs version:
 - support for more aggressive whitelisting: you can whitelist IPs to fully disable all DNS anomaly tracking.
