# Spec Sheet
*notice*: i did use Claude to generate some of the information here such as the ORG names and IP ranges for the RIRs

## RIRs

|RIR|IP Block|IP Range|AS Range|
|---|---|---|---|
|NA-RIR|32.0.0.0/3|32-63|1000-2000|
|EU-RIR|64.0.0.0/3|64-95|2000-3000|
|APAC-RIR|96.0.0.0/4|96-111|3000-4000|
|LATAM-RIR|128.0.0.0/4|128-143|4000-5000|
|AF-RIR|144.0.0.0/4|144-159|5000-6000|

## NA-RIR — 32.0.0.0/3 · AS1000–1999

| Org | Type | Region | ASN | Prefix | Upstreams |
|---|---|---|---|---|---|
| Liberty Backbone | Tier 1 | US | 1000 | 32.0.0.0/14 | — |
| Maple Transit | Tier 1 | Canada | 1001 | 32.4.0.0/14 | — |
| Tornado Electric | Regional ISP | US South | 1100 | 33.0.0.0/16 | 1000 |
| Great Lakes Fiber | Regional ISP | US North/Central | 1101 | 33.1.0.0/16 | 1000 |
| Pacific Crest Networks | Regional ISP | US West | 1102 | 33.2.0.0/16 | 1000 |
| Appalachian Telecom Co-op | Regional ISP | US East | 1103 | 33.3.0.0/16 | 1000 |
| Aurora Telecom | Regional ISP | Alaska | 1104 | 33.4.0.0/16 | 1000 |
| Kona Link | Regional ISP | Hawaii | 1105 | 33.5.0.0/16 | 1000 |
| Northern Lights Broadband | Regional ISP | Canada | 1106 | 33.6.0.0/16 | 1001 |
| Coral Reef Communications | Regional ISP | Caribbean (NA) | 1107 | 33.7.0.0/16 | 1000 |

## EU-RIR — 64.0.0.0/3 · AS2000–2999

| Org | Type | Region | ASN | Prefix | Upstreams |
|---|---|---|---|---|---|
| Continental Carrier Group | Tier 1 | EU | 2000 | 64.0.0.0/14 | — |
| Rhine Valley Networks | Regional ISP | Germany | 2100 | 65.0.0.0/16 | 2000 |
| Channel Fibre | Regional ISP | UK | 2101 | 65.1.0.0/16 | 2000 |
| FjordNet | Regional ISP | Nordics | 2102 | 65.2.0.0/16 | 2000 |
| Geysir Telecom | Regional ISP | Iceland | 2103 | 65.3.0.0/16 | 2000 |
| Polar Cap Telecom | Regional ISP | Greenland | 2104 | 65.4.0.0/16 | 2000 |
| Levant Gateway | Regional ISP | Middle East | 2105 | 65.5.0.0/16 | 2000 |

## APAC-RIR — 96.0.0.0/4 · AS3000–3999

| Org | Type | Region | ASN | Prefix | Upstreams |
|---|---|---|---|---|---|
| Pacific Rim Transit | Tier 1 | APAC | 3000 | 96.0.0.0/14 | — |
| Sakura Net | Regional ISP | Japan | 3100 | 97.0.0.0/16 | 3000 |
| Ganges Broadband | Regional ISP | India | 3101 | 97.1.0.0/16 | 3000 |
| Outback Fibre | Regional ISP | Australia | 3102 | 97.2.0.0/16 | 3000 |
| Straits Connect | Regional ISP | Southeast Asia | 3103 | 97.3.0.0/16 | 3000 |

## LATAM-RIR — 128.0.0.0/4 · AS4000–4999

| Org | Type | Region | ASN | Prefix | Upstreams |
|---|---|---|---|---|---|
| Andes Backbone | Tier 1 | LATAM | 4000 | 128.0.0.0/14 | — |
| Amazonia Telecom | Regional ISP | Brazil | 4100 | 129.0.0.0/16 | 4000 |
| Pampas Net | Regional ISP | Argentina | 4101 | 129.1.0.0/16 | 4000 |
| Istmo Connect | Regional ISP | Central America | 4102 | 129.2.0.0/16 | 4000 |
| Antilles Link | Regional ISP | Caribbean (LATAM) | 4103 | 129.3.0.0/16 | 4000 |

## AF-RIR — 144.0.0.0/4 · AS5000–5999

| Org | Type | Region | ASN | Prefix | Upstreams |
|---|---|---|---|---|---|
| Sahara Transit | Tier 1 | Africa | 5000 | 144.0.0.0/14 | — |
| Nile Delta Networks | Regional ISP | Egypt | 5100 | 145.0.0.0/16 | 5000 |
| Savanna Broadband | Regional ISP | Kenya | 5101 | 145.1.0.0/16 | 5000 |
| Gulf of Guinea Telecom | Regional ISP | Nigeria | 5102 | 145.2.0.0/16 | 5000 |
| Cape Fibre | Regional ISP | South Africa | 5103 | 145.3.0.0/16 | 5000 |