# bpbonworkers
这是一个拉取BPB面板代码并做混淆的代码，用于在Cloudflare workers中使用，该代码会自动拉取BPB官方面板代码，并进行混淆。

Introduction
This project is dedicated to developing a user panel for the Cloudflare-workers/pages proxy script created by yonggekkk. The panel offers two deployment options:

Worker deployment
Pages deployment

🌟 If you found BPB Panel valuable, Your donations make all the difference 🌟

USDT (BEP20): 0x111EFF917E7cf4b0BfC99Edffd8F1AbC2b23d158
Features
Free: No cost involved.
User-Friendly Panel: Designed for easy navigation, configuration and usage.
Protocols: Provides VLESS, Trojan and Wireguard (Warp) protocols.
Warp Pro configs: Optimized Warp for crucial circumstances.
Support Fragment: Supports Fragment functionality for crucial network situations.
Full routing rules: Bypassing Iran/China/Russia and LAN, Blocking QUIC, Porn, Ads, Malwares, Phishing...
Chain Proxy: Capable of adding a chain proxy to fix IP.
Supports Wide Range of Clients: Offers subscription links for Xray, Sing-box and Clash core clients.
Password-Protected Panel: Secure your panel with password protection.
Fully customizable: Ability to use online scanner and setting up clean IP-domains, Proxy IP, setting DNS servers, choosing ports and protocols, Warp endpoints...

How to use:
Installation (Pages - New recommended method)

Installation (Pages)

Installation (Worker)

How to use

FAQ


Supported Clients
Client	Version	Fragment	Warp Pro
v2rayNG	1.9.33 or higher	✔️	✔️
v2rayN	7.8.3 or higher	✔️	✔️
v2rayN-PRO	1.8 or higher	✔️	✔️
Husi		❌	❌
Sing-box	1.11.2 or higher	❌	❌
Streisand	1.6.48 or higher	✔️	✔️
V2Box		❌	❌
Shadowrocket		❌	❌
Nekoray		✔️	❌
Hiddify	2.5.7 or higher	✔️	✔️
NikaNG		✔️	✔️
Clash Meta		❌	❌
Clash Verge Rev		❌	❌
FLClash		❌	❌
Environment variables
Variable	Usage
UUID	VLESS UUID
TR_PASS	Trojan Password
PROXYIP	Proxy IP or domain (VLESS, Trojan)
SUB_PATH	Subscriptions' URI
FALLBACK	Fallback domain (VLESS, Trojan)
DOH_URL	Core DOH
