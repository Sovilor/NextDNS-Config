***
# Guidelines
1) Must pass the "[girlfriend test](https://www.urbandictionary.com/define.php?term=Grandma%20Test)"
2) Minimal allowlisting

***

# Security
### Threat Intelligence Feeds
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Use Threat Intelligence Feeds
### AI-Driven Threat Detection
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Enable AI-Driven Threat Detection
### Google Safe Browsing
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Enable Google Safe Browsing
### Cryptojacking Protection
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Enable Cryptojacking Protection → :radioactive: *Enabling may cause breakage (unlikely)*
### DNS Rebinding Protection
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg)  Enable DNS Rebinding Protection → :radioactive: *Enabling may cause breakage (unlikely)*
### IDN Homograph Attacks Protection
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Enable Homograph Attacks Protection
### Typosquatting Protection
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Enable Typosquatting Protection
### Domain Generation Algorithms (DGAs) Protection
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Enable DGA Protection
### Block Newly Registered Domains (NRDs)
![Disabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/disabled.svg) Block Newly Registered Domains (NRDs) → :radioactive: *Enabling may cause breakage*
<br>
<br> While there are legitimate NRDs, many are nefarious. Here's a recent (June 2022) incident of a scam NRD ([example](https://old.reddit.com/r/GaySoundsShitposts/comments/vr4fjf/be_gay_do_crime/) | commentary [1](https://old.reddit.com/r/gaybros/comments/vqb2q9/comment/iepjd69/) [2](https://old.reddit.com/r/gaybros/comments/vqb2q9/comment/ieoyygw/)). Another example is social media hacks where users click on links in there messages. Those are usually rogue NRDs.

This is marked as disabled because it will cause false positives. However, if you are comfortable allowlisting occasionally, **it is strongly encouraged that you enable this**. Selectively add NRDs to your allowlist; and if you add certain ones to your allowlist, **NEVER give sensitive information to a NRD!**

### Block Dynamic DNS Hostnames
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Enable Block Dynamic DNS Hostnames
### Block Parked Domains
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Block Parked Domains

### Block Top-Level Domains (TLDs)
```
.work
.fit
.surf
.asia
.tokyo
.info
.online
```

### Block Child Sexual Abuse Material
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Block Child Sexual Abuse Material

***

# Privacy
### Blocklists
	NextDNS Ads & Trackers Blocklist
	AdGuard DNS filter
	oisd
	1Hosts (Lite)
### Native Tracking Protection
:radioactive: *Enabling may cause breakage (unlikely)*

Add these brands according to what devices you use. There's no advantage in adding brands you don't own; however, there’s not a strong reason to omit unused brands either.

	Xiaomi
	Huawei
	Samsung
	Amazon Alexa
	Windows
	Apple
	Roku
	Sonos
### Block Disguised Third-Party Trackers
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Block Disguised Third-Party Trackers
### Allow Affiliate & Tracking Links
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Allow Affiliate & Tracking Links

***

# Parental Control
### YouTube Restricted Mode
![Disabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/disabled.svg) Enforce YouTube Restricted Mode → :radioactive: *Enabling may cause breakage*

### Block Bypass Methods
![Disabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/disabled.svg) Block Bypass Methods → :radioactive: *Enabling may cause breakage*

***

# Denylist
(optional) Most of these are blocked under [Block Dynamic DNS Hostnames](https://github.com/yokoffing/NextDNS-Config/edit/main/README.md#block-dynamic-dns-hostnames) (see [here](https://github.com/nextdns/metadata/blob/master/security/ddns/suffixes)).

	pubnub.com
	ddns.net
	duckdns.org
	hopto.org
	linkpc.net
	myddns.me
	myftp.biz
	myftp.org
	ngrok.io
	no-ip.biz
	no-ip.org
	portmap.host
	portmap.io
	publicvm.com
	sytes.net
	zapto.org

***

# Allowlist
if using Facebook and Instagram:

	graph.facebook.com
	graph.instagram.com

breaks CBS News (NextDNS Ads & Trackers Blocklist):

	production-cmp.isgprivacy.cbsi.com
***

# Settings
### Block Page
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Enable Block Page → :radioactive: *Enabling may cause breakage if the NextDNS Root CA is not on your devices*
### Anonymized EDNS Client Subnet
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Enable Anonymized EDNS Client Subnet
### Cache Boost
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Enable Cache Boost
### CNAME Flattening
![Enabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/enabled.svg) Enable CNAME Flattening
### Web3 (optional)
![Disabled](https://raw.githubusercontent.com/crssi/NextDNS-Config/main/icons/disabled.svg) Enable Web3

***

# Credit
Forked from the [crssi](https://github.com/crssi/NextDNS-Config#readme) config. Some inputs came from the [scafroglia93](https://github.com/scafroglia93/nextdns-setting]) config while other changes are my own.

***
