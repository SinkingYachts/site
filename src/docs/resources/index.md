# Resources

This page contains a list of notable anti-phishing and anti-malware resources for Discord moderation.


### Our Projects

Don't forget to check out the SinkingYachts [anti-phishing services](/projects)!


## The Vaccinator

The Vaccinator is a specialized malware analysis tool designed to combat Discord token grabbers.

**Link:** <br>
[sketchy.tel](https://sketchy.tel/)

**How it works:** <br>
Since most of this class of malware uses Discord webhooks to send the victim's data to the scammer, one is able to extract the webhook URL from the malware file. Then, the webhook can be deleted to prevent the scammer from getting other users' data (from that webhook). <br>
The Vaccinator operates off this principle, and is able to extract useful information from most common Discord token grabbers.

**Help:** <br>
You can contact `nwunder#4003` (me!) on Discord with questions or feedback about The Vaccinator.


## General Security

- **VirusTotal** ([virustotal.com](https://virustotal.com)) <br>
  Site for analyzing suspicious files and URLs. Very solid tool, the one everyone's heard of.
- **Hybrid Analysis** ([hybrid-analysis.com](https://www.hybrid-analysis.com)) <br>
  Site for analyzing suspicious files and URLs. Very powerful tool, has sandboxing in addition to VirusTotal-esque scanning.
- **Open Threat Exchange** ([otx.alienvault.com](https://otx.alienvault.com)) <br>
  Site for analyzing and sharing malware and other cyber threats. Offers useful tools for creating and sharing collections of known malware.
- **UrlScan** ([urlscan.io](https://urlscan.io)) <br>
  Site for analyzing suspicious URLs.
- **Abuse.ch** ([abuse.ch](https://abuse.ch)) <br>
  A nonprofit cybersecurity project run out of the Bern University of Applied Sciences in Switzerland.
  Provides lots of great cybersecurity resources, notably [URLhaus](https://urlhaus.abuse.ch) and [MalwareBazaar](https://bazaar.abuse.ch).


## APIs

- **Anti-Fish** ([anti-fish.bitflow.dev](https://anti-fish.bitflow.dev)): <br>
  API to provide easy checking for messages against phishing domains.

- **Phisherman** ([phisherman.gg](https://phisherman.gg)): <br>
  Phisherman is a centralised database of phishing and scam links. It is designed for use with Discord bots, allowing them to utilise the Phisherman API to cross-check urls against our known phishing links.

- **Hyperphish** ([hyperphish.com](https://api.hyperphish.com/docs)): <br>
  API providing acess to domains detected by the Fish Project.


## Bots

- **CrossLink** ([crss.link](https://crss.link)): <br>
  Crosslink is a smart link detection and reputation service built to make link filtering convenient for moderators and community managers.

- **SafeLink** ([safelink.gg](https://safelink.gg/)): <br>
  SafeLink protects your server from scam/phishing links, invites, explicit content, and more using our in-house deep scanning algorithm.

- **Fish** ([Benricheson101/anti-phishing-bot](https://github.com/Benricheson101/anti-phishing-bot/)): <br>
  Discord bot for deleting Steam/Discord phishing links.

- **GiselleBot** ([gisellebot.com](https://gisellebot.com/)): <br>
  A multipurpose Discord bot with anti-phishing features.

- **Dyno** ([dyno.gg](https://dyno.gg/bot)): <br>
  A multipurpose Discord bot with anti-phishing features.
