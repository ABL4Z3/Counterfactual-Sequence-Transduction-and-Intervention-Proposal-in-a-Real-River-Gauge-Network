# Public Data Source — Anonymized River-Gauge Daily Flow Network

## What this dataset is

Daily mean streamflow series for 17 stream gauges on a single dendritic
river network, 2014-2025, anonymized (G01-G17, relative ticks, per-gauge
scale jitter), together with counterfactual outcome and intervention
labels defined by a hidden routing model fitted to those series. The
labels are synthetic and exist nowhere else; the underlying flow series
are real measurements.

## Source

- Flow data: U.S. Geological Survey National Water Information System
  (NWIS), daily mean stream discharge (parameter 00060, statistic 00003)
- Network topology: USGS Network Linked Data Index (NLDI)
  upstream/downstream navigation
- Access: public web-service retrieval (waterservices.usgs.gov,
  api.water.usgs.gov), retrieved 2026-09-13 for this dataset

Gauge identities, locations, and dates are not disclosed as part of the
task design; the network is presented only through anonymized,
scale-jittered flow windows.

## License

USGS data are works of the U.S. federal government and are in the public
domain under 17 U.S.C. § 105; NWIS/NLDI distribution carries no
restrictions on commercial or derivative use. The episode packaging, task
design, and labels are original work released under CC0 1.0 Universal
(public domain dedication).
