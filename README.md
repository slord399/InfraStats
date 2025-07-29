# InfraStats
Tracking networking outage be super hard task for most of DevOps for Networking.
I'm service provider and end-user myself but still it find it difficult where root of cause exist while supporting client.
Downdetector be not enough for those task so I collect list of major core networking provider so I can track what's going on over upstream provider and peering partner by now.

## Usage
 A. Join off [discord](https://discord.gg/8tdcHxzmBT)  
 B. Use URL on discord RSS Bot like [MonitoRSS](https://monitorss.xyz/)  
 C. Self-host RSS workflow/bot yourself

## Feed Provider
- [Media and Press](#media)
- [Data Centre](#data-centre-and-hosting)
- [Transit and ISP](#transit-and-isp)
- [Service as a Service (SaaS](#saas)

### Media
| Provider | Feed URLs |
| :-------------: | :-------------: |
| [ISPreview](https://www.ispreview.co.uk/) | https://www.ispreview.co.uk/index.php/feed/ |
| [SubTel Forum](https://subtelforum.com/) | https://subtelforum.com/rss |
| [Hurricane Electric](http://he.net/) | X to IFTTT:[henet](https://x.com/henet) |
| [Akamai](https://www.akamai.com/) and [Linode](https://www.linode.com/) | X to IFTTT:[Akamai](https://x.com/Akamai) or [linode](https://x.com/linode) |
| [Colt Technology Service](https://www.colt.net/) | https://www.colt.net/feed/ |

### Data Centre and Hosting
| Provider | Feed URLs |
| :-------------: | :-------------: |
| [Amazon Web Service](https://aws.amazon.com/) | https://status.aws.amazon.com/rss/all.rss |
| [Google Cloud Platform](https://cloud.google.com/) | https://status.cloud.google.com/en/feed.atom |
| [Microsoft Azure](https://azure.microsoft/) | https://rssfeed.azure.status.microsoft/en-gb/status/feed/ |
|  |  |
| [Equinix Metal](https://equinix.com/) | https://status.equinixmetal.com/history.atom |
|  |  |
| [Akamai](https://www.akamai.com/) | https://www.akamaistatus.com/history.atom |
| [Linode](https://www.linode.com/) | https://status.linode.com/history.atom |
| [Digital Ocean](https://digitalocean.com/) | https://status.digitalocean.com/history.atom |
| [Oracle](https://www.oracle.com/) | https://ocistatus.oraclecloud.com/api/v2/incident-summary.rss |
| [Hetzner](https://www.hetzner.com/) | https://status.hetzner.com/en.atom |
| [Sparked Host](https://sparkedhost.com/) | https://status.sparkedhost.com/history.rss |
| [GCORE](https://gcore.com/) | https://status.gcore.com/history.rss
|  |  |
| [GitHub](https://www.github.com/) | https://www.githubstatus.com/history.atom |
| [Redis](https://redis.com/) | https://status.redis.com/history.atom |


### Transit and ISP
**Global**
| Provider | Feed URLs |
| :-------------: | :-------------: |
| [RIPE NCC](https://ripe.net/) | https://status.ripe.net/history.atom |
| [Cloufflare](https://www.cloudflare.com/) | https://www.cloudflarestatus.com/feed |
| [Global Secure Layer](https://globalsecurelayer.com/) | https://www.gslstatus.com/history.atom |
| [Sucui Monitoring](https://sucuri.net/) | https://status.sucuri.net/history.atom |
| [Core-Backbone](https://core-backbone.com/) | https://status.core-backbone.com/rss.php?mode=all |


**Japan**
| Provider | Feed URLs |
| :-------------: | :-------------: |
| [NTT Smart Data Platform (JP)](https://sdpf.ntt.com/) | https://status.sdpf.ntt.com/rss/ja/ |
| [NTT Smart Data Platform (EN)](https://sdpf.ntt.com/) | https://status.sdpf.ntt.com/rss/en/ |
| [NTT docomo Business Biz (JP)](https://www.ntt.com) | https://support.ntt.com/vpn-besteffort/maintenance/list/rss |
|  |  |
| [OCN (Flet's)](https://ocn.ne.jp/) | https://support.ocn.ne.jp/hikari-w-flets/maintenance/list/rss |
| [OCN (Hikari)](https://ocn.ne.jp/) | https://support.ocn.ne.jp/hikari/maintenance/list/rss |
| [OCN (Direct)](https://ocn.ne.jp/) | https://support.ocn.ne.jp/ocn-internet/maintenance/list/rss |
|  |  |
| [au one net](https://www.au.com/) | https://www.notice.kddi.com/news/mainte/content/info/k/auonenet.xml |
| [au Hikari](https://www.au.com/) | https://www.notice.kddi.com/news/mainte/content/info/k/hikarione.xml |
|  |  |
| [JCOM](https://www.jcom.co.jp/) | X to IFTTT:[jcom_support](https://x.com/jcom_support) |


### SaaS
| Provider | Feed URLs |
| :-------------: | :-------------: |
| [IFTTT](https://ifttt.com/) | https://status.ifttt.com/feed |
| [ReadMe](https://readme.com/) | https://www.readmestatus.com/history.atom |
|  |  |
| [Unity Gaming Service](https://unity.com/) | https://status.unity.com/history.atom |
| [Epic Gaming Service](https://epicgames.com/) | https://status.epicgames.com/history.atom |
|  |  |
| [discord](https://discord.com/) | https://discordstatus.com/history.atom |
|  |  |
| [Slack](https://slack.com/) | https://slack-status.com/feed/rss |
| | |
| [OpenAI](https://openai.com/) | https://status.openai.com/history.atom |
|  |  |
| [Patreon](https://patreon.com/) | https://status.patreon.com/history.atom |
|  |  |
| [Let's Encrypt](https://letsencrypt.org/) | https://letsencrypt.status.io/pages/55957a99e800baa4470002da/rss |
|  |  |
| [Steam](https://store.steampowered.com/) by [Valve](https://www.valvesoftware.com/) | X to IFTTT:[SteamStatus](https://x.com/SteamStatus) (3rd party provider) |
|  |  |
| [Misskey.io](https://misskey.io/) | X to IFTTT:[misskey_dev](https://x.com/misskey_dev) |
|  |  |
| [Dyno](https://dyno.gg/) | From official discord |
|  |  |
| [VRChat](https://dyno.gg/) | X to IFTTT:[VRChat_Status](https://x.com/VRChat_Status) |
|  |  |
| [小説家になろう](https://syosetu.com/) | https://blog.syosetu.com/api/article/rss2/ |
| | |
| [Slack](https://slack.com/) | https://slack-status.com/feed/rss |
| | |
| [ニコニコ動画インフォ](https://www.nicovideo.jp/) | https://blog.nicovideo.jp/niconews/feed/topics/index.xml |
| | |
| [Ticket Bot v2](https://ticketsbot.cloud/) | https://ticketsv21.statuspage.io/history.atom |
| | |
| [Notion](https://www.notion.com/) | https://www.notion-status.com/history.rss |
| | |
| [LINE](https://www.line.me/) | https://api.line-status.info/history.rss |

### Other
| Provider | Feed URLs |
| :-------------: | :-------------: |
| [Downrightnow](http://downrightnow.com/) | http://feeds.downrightnow.com/downrightnow/ |
