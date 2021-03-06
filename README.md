# Awesome anti-censorship

> A curated list of open source tools and readings for fighting Internet censorship.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.

## Categories
- [Network tunnels](#network-tunnels)
- [Firewall analysis](#firewall-analysis)
- [Decentralized systems](#decentralized-systems)
- [Steganography](#steganography)
- [Deniable encryption](#deniable-encryption)
- [Articles and research papers](#articles-and-research-papers)

### Network tunnels
- [obfsproxy](https://git.torproject.org/pluggable-transports/obfsproxy.git) Tor framework for implementing pluggable transports (anti-censorship network tunnels)
- [flashproxy](https://crypto.stanford.edu/flashproxy/) -  miniature proxy that runs in a web browser, and reflects traffic to a Tor relay.
- [meek](https://trac.torproject.org/projects/tor/wiki/doc/meek) - Tor pluggable transport that uses HTTP for carrying bytes and TLS for obfuscation.
- [lantern](https://github.com/getlantern/lantern) - Lantern is a free desktop application that delivers fast, reliable and secure access to the open Internet for users in censored regions
- [scramblesuit](http://www.cs.kau.se/philwint/scramblesuit/) - Tor pluggable transport that uses look-like-nothing traffic as a cover channel
- [FTE](https://github.com/kpdyer/fteproxy) - fteproxy provides transport-layer protection to resist keyword filtering, censorship and discriminatory routing policies
- [stegotorus](https://github.com/SRI-CSL/stegotorus) - A Camouflage Proxy for the Tor Anonymity System
- [telex](https://github.com/ewust/telex) - involves placing anticensorship technology into the Internet's core network infrastructure, through cooperation from large ISPs. 
- [uproxy](https://github.com/uProxy) - uProxy is a browser extension that lets friends route their connection to their Internet through each other's computers. It can help people with restricted or insecure access to the Internet get to the content they care about safely.
- [shadowsocks](https://github.com/shadowsocks) - a fast socks5 proxy that encrypts traffic
- [streisand](https://github.com/jlund/streisand) - single command set for a server running a wide variety of anti-censorship software
- [obfs4](https://github.com/Yawning/obfs4) - the newest version of the Tor obfsproxy obfuscation proxy. implements multiple pluggable transports.
- [bit-smuggler](https://github.com/danoctavian/bit-smuggler) - tunnel traffic through a bittorrent connection.
- [govpn](https://github.com/stargrave/govpn) - virtual private network daemon, aimed to be reviewable, secure, DPI/censorship-resistant
- [gohop](https://github.com/bigeagle/gohop) - A VPN implemention in golang, with crypto and obfuscation in nature.
- [Dust](https://github.com/blanu/Dust) - A Polymorphic Engine for Filtering-Resistant Transport Protocols
- [marionette](https://github.com/kpdyer/marionette/) - Marionette is a programmable client-server proxy that enables the user to control network traffic features with a lightweight domain-specific language.
- [facebook-tunnel](https://github.com/matiasinsaurralde/facebook-tunnel) Tunneling Internet traffic over FB chat.
- [chnroutes](https://github.com/fivesheep/chnroutes)- modifies the route table to route only censored ips through vpn
- [firefly-proxy](https://github.com/yinghuocho/firefly-proxy) - A proxy software to help circumventing the Great Firewall.
- [iodine](https://github.com/yarrick/iodine) - This is a piece of software that lets you tunnel IPv4 data through a DNS server. This can be usable in different situations where internet access is firewalled, but DNS queries are allowed.
- [obfuscated-openssh](https://github.com/brl/obfuscated-openssh) - Handshake obfuscation strengthens the initial SSH handshake against systems that identify or classify various network protocols by examining data in transit for static signatures.
- [infranet](http://sourceforge.net/projects/infranet/) - Infranet is a system that attempts to circumvent web censorship by allowing clients to surreptitiously request sensitive content via cooperating Web servers distributed across the global Internet.
- [goagent](https://github.com/phuslu/goagent) - code is missing now.
- [fwlite](https://github.com/v3aqb/fwlite) - A powerful HTTP proxy server designed to circumvent the Great Firewall (GFW)

### Decentralized systems
- [ipfs](https://github.com/ipfs/ipfs) - Ipfs is a global, versioned, peer-to-peer filesystem.
- [ZeroNet](https://github.com/HelloZeroNet/ZeroNet) - Decentralized websites using Bitcoin crypto and the BitTorrent network
- [twister](https://github.com/miguelfreitas/twister-core) - twister is an experimental peer-to-peer microblogging software.
- [freenet](https://github.com/freenet) - Freenet is a peer-to-peer platform for censorship-resistant communication.

### Firewall analysis
- [mongol](https://github.com/mothran/mongol) - A simple python tool to pinpoint the IP addresses of machines working for the Great Firewall of China.
- [ChinaDNS](https://github.com/shadowsocks/ChinaDNS) - Protect yourself against DNS poisoning in China.
- [gfw_whitelist](https://github.com/n0wa11/gfw_whitelist) - A Pac File of the Whitelisted Websites for the Great Firewall of China (GFW)

### Steganography
- [DissidentX](https://github.com/bramcohen/DissidentX) - DissidentX is encoding messages in files on the web.

### Deniable encryption
- [rubberhose](https://github.com/sporkexec/rubberhose) - Julian Assange's deniable-encryption filesystem.

### Articles and esearch papers
- [Learning more about the GFW's active probing system](https://blog.torproject.org/blog/learning-more-about-gfws-active-probing-system)
- [A closer look at the Great Firewall of China - Tor Blog](https://blog.torproject.org/blog/closer-look-great-firewall-china)
- [How the Great Firewall of China is Blocking Tor](https://www.usenix.org/system/files/conference/foci12/foci12-final2.pdf)
- [Towards a Censorship Analyser for Tor](http://www.cs.kau.se/philwint/pdf/foci2013.pdf)
- [stegotorus](http://freehaven.net/anonbib/cache/ccs2012-stegotorus.pdf)
- [Format-Transforming Encryption](https://kpdyer.com/publications/ccs2013-fte.pdf)
- [ScrambleSuit](http://arxiv.org/pdf/1305.3199.pdf )


