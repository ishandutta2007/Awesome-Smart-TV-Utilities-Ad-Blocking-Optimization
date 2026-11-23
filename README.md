# Awesome-Smart-TV-Utilities-Ad-Blocking-Optimization

# Top Smart TV Utilities & Ad Blocking Optimization Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Network-Wide DNS Ad Blocking, Android TV / Fire TV Debloating, Ad-Free Streaming Clients & Custom Launchers*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted DNS filtering platforms** and **open-source GitHub projects** for **Smart TV Utilities & Ad Blocking Optimization**. These tools eliminate telemetry, home-screen ads, tracking domains, and bloated vendor apps across Android TV, Google TV, Amazon Fire TV, Tizen, and webOS while delivering faster, cleaner, and privacy-respecting living-room media setups.

**Examples** include Gathin23/CleanYourTV, Pi-hole, AdGuard Home, SmartTube, Projectivy / FLauncher, ADB TV, Technitium DNS Server, Blocky, Unbound, Kodi, Jellyfin, AdGuard DNS, NextDNS, Control D, Cisco Umbrella, Cloudflare 1.1.1.1, Quad9, CleanBrowsing, Blokada Cloud, and AdLock.

**Open-source emphasis**: This list heavily expands on active open-source self-hosted DNS sinkholes, ADB TV debloaters, ad-free Smart TV media clients, custom launchers, and curated Smart TV blocklists — ideal for home-labbers, cord-cutters, and privacy-conscious users reclaiming full control over their Smart TVs.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[AdGuard DNS](https://adguard-dns.io)**  
  Cloud-hosted privacy-first DNS resolver offering customizable ad, tracker, and Smart TV telemetry blocklists with per-device profiles and encrypted DNS (DoH/DoT/DoQ).

- **[NextDNS](https://nextdns.io)**  
  Cloud DNS firewall and ad blocker featuring dedicated native tracking blocklists for Samsung, LG, Sony, Roku, and Xiaomi Smart TVs alongside real-time query analytics.

- **[Control D](https://controld.com)**  
  Customizable cloud DNS resolver combining ad/tracker blocking, Smart TV telemetry filtering, and global traffic routing without requiring VPN apps on TV hardware.

- **[Cloudflare 1.1.1.1 for Families](https://one.one)**  
  Free, fast public DNS service by Cloudflare offering malware blocking (`1.1.1.2`) and adult-content filtering (`1.1.1.3`) easily configured in any Smart TV or router network settings.

- **[Quad9](https://quad9.net)**  
  Non-profit, privacy-focused public DNS resolver (`9.9.9.9`) blocking malicious domains, phishing, and spyware endpoints with zero PII logging.

- **[CleanBrowsing](https://cleanbrowsing.org)**  
  Cloud-based DNS filtering service providing free and paid family-safe, security, and custom blocklist profiles for home routers and Smart TVs.

- **[Cisco Umbrella](https://cisco.com)**  
  Enterprise cloud-delivered DNS security and content filtering platform protecting connected devices from malicious domains and unauthorized callbacks.

- **[Blokada Cloud](https://blokada.org)**  
  Cloud-managed ad-blocking DNS and WireGuard VPN service engineered to strip ads and trackers across mobile and Smart TV devices.

- **[AdLock](https://adlock.com)**  
  Commercial cross-platform ad blocker offering system-wide filtering apps and cloud DNS blocking for Android TV and home networks.


## Open-Source GitHub Projects

- **[CleanYourTV (Gathin23/CleanYourTV)](https://github.com)**  
  Open-source ADB-based Android TV & Google TV optimization and debloating toolkit that safely removes pre-installed bloatware, disables telemetry/ads, optimizes animations, and streamlines system performance.

- **[Pi-hole (pi-hole/pi-hole)](https://github.com)**  
  The iconic Linux network-level advertisement and Internet tracker blocking application that acts as a DNS sinkhole to protect every Smart TV and IoT device on your LAN.

- **[AdGuard Home (AdguardTeam/AdGuardHome)](https://github.com)**  
  Network-wide, single-binary open-source software written in Go for blocking ads, Smart TV tracking servers, and phishing domains with built-in DNS-over-HTTPS/TLS support.

- **[SmartTube (yuliskov/SmartTube)](https://github.com)**  
  Open-source, ad-free YouTube client engineered specifically for Android TV, Google TV, and Fire TV sticks featuring built-in SponsorBlock, 4K/8K HDR playback, and zero Google Services dependency.

- **[FLauncher (etienn01/flauncher)](https://github.com)**  
  Open-source, lightweight, ad-free custom home screen launcher for Android TV built with Flutter to replace cluttered, ad-heavy stock interfaces.

- **[Technitium DNS Server (TechnitiumSoftware/DnsServer)](https://github.com)**  
  Cross-platform, open-source authoritative and recursive DNS server with native ad-blocking blocklists, DNSSEC, DoH/DoT, and a rich web admin console.

- **[Blocky (0xERR0R/blocky)](https://github.com)**  
  Fast, lightweight DNS proxy and ad-blocker written in Go designed for home labs and Kubernetes with per-client device groups and Prometheus metrics.

- **[Universal Android Debloater Next Generation (Universal-Debloater-Alliance/universal-android-debloater-next-generation)](https://github.com)**  
  Cross-platform Rust GUI utility using ADB to safely inspect and remove manufacturer bloatware and spyware packages on Android phones and Android TV boxes.

- **[Jellyfin (jellyfin/jellyfin)](https://github.com)** & **[Kodi (xbmc/xbmc)](https://github.com)**  
  Flagship open-source home theater and media center software delivering 100% ad-free, telemetry-free local and networked media streaming on Smart TVs.

- **[Hagezi Multi-Pro DNS Blocklists (hagezi/dns-blocklists)](https://github.com)**  
  Meticulously maintained open-source DNS blocklists including dedicated Native Tracker lists that block telemetry from Samsung, LG, Sony, Roku, Hisense, and Amazon Smart TVs.

- **[Blokada Libre (blokadaorg/blokada)](https://github.com)**  
  Open-source on-device DNS/VPN ad blocker for Android and Android TV that filters ads locally without routing traffic through external servers.

- **[RethinkDNS (celzero/rethink-app)](https://github.com)**  
  Open-source Android firewall, DNS-over-HTTPS client, and WireGuard manager allowing granular per-app internet blocking on Android TV devices.

- **[NewPipe (TeamNewPipe/NewPipe)](https://github.com)** & **[PipePipe (InfinityLoop1308/PipePipe)](https://github.com)**  
  Lightweight, open-source streaming frontends supporting Android TV playback, SponsorBlock integration, and background audio with zero ads or tracking.

### Additional Strong Open-Source Options

- **[Unbound (NLnetLabs/unbound)](https://github.com)** — Validating, recursive, caching DNS resolver often paired with Pi-hole or AdGuard Home for direct root-server queries without upstream DNS providers.
- **[dnscrypt-proxy (DNSCrypt/dnscrypt-proxy)](https://github.com)** — Flexible DNS proxy supporting encrypted DNS protocols, local blocklists, and cloaking rules.
- **[TizenTube (reisxd/TizenTube)](https://github.com)** & **[YouTube AdFree webOS (webosbrew/youtube-webos)](https://github.com)** — Open-source ad-free and SponsorBlock-enabled YouTube clients tailored for Samsung Tizen and LG webOS Smart TVs.
- **[Aerial Views (theothernt/AerialViews)](https://github.com)** — Open-source Apple TV-style 4K Dolby Vision/HDR screensaver for Android TV and Google TV.
- **[tvQuickActions / Button Mapper Alternatives (KeyMapper)](https://github.com)** — Open-source Android key-remapping utility for customizing Smart TV remote buttons and disabling hardcoded streaming app shortcuts.
- **[SponsorBlock (ajayyy/SponsorBlock)](https://github.com)** — Crowdsourced open-source API and database for automatically skipping in-video sponsor segments across Smart TV clients.

**Frameworks for building custom systems**: Combine **Pi-hole** or **AdGuard Home** + **Unbound** + **Hagezi Native Smart TV Blocklists** at the router level, then optimize your TV using **CleanYourTV** (via ADB), **FLauncher**, and **SmartTube** / **Jellyfin** for a completely ad-free, high-speed living-room setup.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- ADB debloating utilities (`CleanYourTV`, `UAD`) disable or uninstall system packages; removing critical OEM services (such as Play Services, DRM/Widevine, or system launchers without a fallback installed) can cause boot loops or break paid streaming apps. Always review package descriptions before disabling.
- Aggressive Smart TV DNS blocklists may occasionally block firmware updates, voice search, or legitimate streaming app authentication endpoints; whitelist required domains as needed.

---

**Made for home-lab enthusiasts, cord-cutters, privacy advocates, and open-source developers.**  
Let's make Smart TVs faster, cleaner, ad-free, and open to everyone.
