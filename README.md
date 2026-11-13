# justhost 1美元vps 有吗：最低多少钱、512MB 够不够用、IPv6 版省的钱会不会被 IPv4 价格吃掉？（附全套餐年付价对照表）

JustHost 没有 1 美元的 VPS。它的四个官方站点（justhost.asia、justhost.ru、just.hosting、just-host.cn）VPS 页面标题统一写着 “VPS from $1.99”，页面里找不到任何 $1 套餐。目前能查到的最低门槛是 **IPv6-only 的 HDD VPS：1 核 / 512 MB / 5 GB HDD，年付折后 $1.60/月**，折合每年 $19.20；如果你需要 IPv4 地址，最便宜的入门选择是 **VPS Promo $1.99/月**（512 MB / 5 GB NVMe）或 **New Star $3.05/月**（1 GB / 10 GB NVMe，年付折后）。

下面把三件事写清楚：每个价位实际买到什么配置、IPv6 版省下的钱会不会被单独购买 IPv4 的费用抵消，以及页面上没写、但会影响你每月实际支出的附加费用。

> **选购速览**
> 只想花最少的钱跑个 IPv6 测试环境：HDD VPS IPv6，$1.60/月（年付）。
> 需要 IPv4、只要能跑脚本和小服务：VPS Promo $1.99/月，或 New Star $3.05/月（1 GB 内存，端口从 10 Mbps 提到 100 Mbps）。
> 要建站、跑 2 核 4 GB：Vega $10.75/月；再往上按内存和硬盘线性加价，Procyon（12 核 / 32 GB / 1 TB）$131.65/月封顶。
> 👉 [查看 JustHost 全部 VPS 套餐与年付价](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)

## “1 美元 VPS”在官网上对应什么

搜索结果里出现 1 美元的说法，实际能对上的只有两档价格，而且都有前提条件。

**$1.60/月**：HDD VPS IPv6，1 核 / 512 MB 内存 / 5 GB HDD，标价 $2，按 12 个月付款打 20% 后为 $1.60/月。这台机器只有 IPv6 地址，没有 IPv4。同系列还有 SSD 版 $2.12/月、NVMe 版 $2.38/月，配置一样，只换存储介质。

**$1.99/月**：VPS Promo，1 核 / 512 MB / 5 GB NVMe，10 Mbps fair-share 端口（官方换算约 4+ TB/月），含 IPv4 + IPv6。这张卡片标价 $1.99，但页面上 12 个月付款对应的价格显示为 “$-”，也就是说年付折后价没有正常显示，只能确认月付标价是 $1.99。

**$3.05/月**：New Star，1 核 / 1 GB / 10 GB NVMe，100 Mbps 端口（约 31+ TB/月），年付折后价，标价 $3.81。这款要求订购 3 个月及以上才能享受折扣。

三档之间的差别不只是 40 美分。$1.60 那档是纯 IPv6 + 机械硬盘 + 512 MB 内存；$1.99 那档同样是 512 MB，但换成 NVMe 并带 IPv4，端口只有 10 Mbps；$3.05 那档内存翻倍、端口翻十倍、硬盘翻倍。**多花 $1.45/月买 New Star，换来的是 1 GB 内存和 100 Mbps 端口**，这是本文最推荐的一档加钱。

品牌方自己公布的数据是约 38.6 万客户、41 个国家、80 个机房位置、经营 21 年（官网首页自述，仅作背景）。价格页面显示，该品牌有多个区域站点，各站标价并不完全一致；本文所有价格取自 justhost.asia 的套餐价格页，并用 justhost.ru、just-host.cn 交叉核对，三处一致。

## 全套餐对照表（年付折后价，美元/月）

JustHost 的折扣规则很统一：绝大多数套餐标 “-20%”，条件是按 12 个月付款；New Star、Double Star、Bright Star 三款额外要求订购 3 个月以上。下表按官方价格页顺序列出，价格一列括号内为月付标价。

**入门与主流配置**

| 套餐 | CPU · 内存 | 存储 | 端口（fair-share） | 年付月价 | 购买 |
| --- | --- | --- | --- | --- | --- |
| VPS Promo | 1 核 · 512 MB | 5 GB NVMe | 10 Mbps（≈4+ TB/月） | $1.99（12 个月价未显示） | [选购](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 核 · 1024 MB | 10 GB NVMe | 100 Mbps（≈31+ TB/月） | $3.05（$3.81） | [选购](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Double Star | 2 核 · 2048 MB | 20 GB NVMe | 200 Mbps（≈62+ TB/月） | $5.67（$7.08） | [选购](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Bright Star | 4 核 · 4096 MB | 30 GB NVMe | 300 Mbps（≈93+ TB/月） | $7.84（$9.80） | [选购](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Sirius | 1 核 · 1024 MB | 20 GB NVMe | 300 Mbps（≈93+ TB/月） | $3.88（$4.85） | [选购](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 核 · 2048 MB | 30 GB NVMe | 300 Mbps | $5.53（$6.92） | [选购](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Alpha Centauri | 2 核 · 2048 MB | 40 GB NVMe | 400 Mbps（≈124+ TB/月） | $7.19（$8.99） | [选购](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Vega | 2 核 · 4096 MB | 80 GB NVMe | 500 Mbps（≈155+ TB/月） | $10.75（$13.44） | [选购](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |

**大配置段**

| 套餐 | CPU · 内存 | 存储 | 端口 | 年付月价 | 购买 |
| --- | --- | --- | --- | --- | --- |
| Capella | 4 核 · 4096 MB | 120 GB NVMe | 750 Mbps（≈232+ TB/月） | $14.64（$18.30） | [选购](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |
| Rigel | 4 核 · 8192 MB | 200 GB NVMe | 750 Mbps | $22.35（$27.94） | [选购](https://justhost.asia/en/services/vps/tariffs/rigel?ref=196392) |
| Antares | 5 核 · 8192 MB | 300 GB NVMe | 750 Mbps | $26.49（$33.12） | [选购](https://justhost.asia/en/services/vps/tariffs/antares?ref=196392) |
| Betelgeuse | 6 核 · 12288 MB | 400 GB NVMe | 750 Mbps | $36.43（$45.54） | [选购](https://justhost.asia/en/services/vps/tariffs/betelgeuse?ref=196392) |
| Spica | 8 核 · 16384 MB | 500 GB NVMe | 750 Mbps | $48.85（$61.06） | [选购](https://justhost.asia/en/services/vps/tariffs/spica?ref=196392) |
| Altair | 8 核 · 24576 MB | 600 GB NVMe | 750 Mbps | $65.41（$81.76） | [选购](https://justhost.asia/en/services/vps/tariffs/altair?ref=196392) |
| Aldebaran | 8 核 · 32768 MB | 700 GB NVMe | 750 Mbps | $98.53（$123.16） | [选购](https://justhost.asia/en/services/vps/tariffs/aldebaran?ref=196392) |
| Procyon | 12 核 · 32768 MB | 1000 GB NVMe | 1000 Mbps（≈309+ TB/月） | $131.65（$164.56） | [选购](https://justhost.asia/en/services/vps/tariffs/procyon?ref=196392) |

全系 KVM 虚拟化，含 IPv4 + IPv6、DDoS 防护、SSH 访问、免费迁移、客户区内可随时更换 IP、随时升降配置。

## IPv6 版便宜的那一美元，够不够你加一个 IPv4

这是很多比价文章没算的一笔账。同一个配置，IPv6-only 版本比双栈版便宜，但便宜得不多，而补一个 IPv4 很贵。

以 Sirius 为例：双栈版年付 $3.88/月，IPv6 版 $2.88/月，每月省 $1.00。官方附加服务里，单独买一个 IPv4 地址是 **$3.31/月**。$2.88 + $3.31 = **$6.19/月**，比直接买双栈版贵 $2.31，一年多花 $27.72。

配置越大，这个差价越明显：

| IPv6-only 套餐 | 配置 | 年付月价 | 比同配置双栈版省 |
| --- | --- | --- | --- |
| Sirius IPv6 | 1 核 · 1024 MB · 20 GB | $2.88 | $1.00 |
| Arcturus IPv6 | 1 核 · 2048 MB · 30 GB | $3.88 | $1.65 |
| Alpha Centauri IPv6 | 2 核 · 2048 MB · 40 GB | $5.53 | $1.66 |
| Vega IPv6 | 2 核 · 4096 MB · 80 GB | $8.27 | $2.48 |
| Capella IPv6 | 4 核 · 4096 MB · 120 GB | $10.75 | $3.89 |
| Rigel IPv6 | 4 核 · 8192 MB · 200 GB | $16.55 | $5.80 |
| Antares IPv6 | 5 核 · 8192 MB · 300 GB | $19.60 | $6.89 |
| Betelgeuse IPv6 | 6 核 · 12288 MB · 400 GB | $26.95 | $9.48 |
| Spica IPv6 | 8 核 · 16384 MB · 500 GB | $41.39 | $7.46 |
| Altair IPv6 | 8 核 · 24576 MB · 600 GB | $57.13 | $8.28 |
| Aldebaran IPv6 | 8 核 · 32768 MB · 700 GB | $82.79 | $15.74 |
| Procyon IPv6 | 12 核 · 32768 MB · 1000 GB | $107.63 | $24.02 |

差价随配置放大，Procyon 那一档每月省 $24，已经接近一个独立 IPv4 的七倍价格。即便如此，规则没变：**确定只通过 IPv6 访问，才买 IPv6 版；需要 IPv4，直接买双栈套餐更便宜**。IPv6 版适合的场景很具体：纯 IPv6 网络内的测试、给已有 IPv6 环境做节点、跑不需要对外用 IPv4 访问的脚本。

👉 [直接开通带 IPv4 的 Sirius，年付 $3.88/月](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392)

## “不限流量”到底给多少带宽

官方写的是 unmetered port（fair-share），意思是流量不计量，但带宽与其他用户公平共享，不是独享。页面同时给了每个端口的等效月流量换算：10 Mbps ≈ 4+ TB/月，100 Mbps ≈ 31+ TB/月，300 Mbps ≈ 93+ TB/月，500 Mbps ≈ 155+ TB/月，750 Mbps ≈ 232+ TB/月，1000 Mbps ≈ 309+ TB/月。

拿 VPS Promo 的 10 Mbps 端口来说，跑定时脚本、做监控探针、挂个小代理、放个低流量静态页都够；跑下载站、视频转码、需要持续大并发的服务会顶到端口上限，那时你可以按月加 $2.50 加 10 Mbit 带宽，或者直接换高一档套餐。

想要“保证 1 Gbps”的选项在附加服务里，价格是 **$333.33/月**，是给对带宽有硬性要求的业务准备的，与入门价位不在一个量级。

## 每月 $1.60 之外还可能多花什么

除了 IPv4 地址 $3.31/月、加 10 Mbit 带宽 $2.50/月，还有两项容易被忽略：

**自动备份不提供。** 官方 FAQ 的原话是：“No, we don't offer automatic backups. Instead, set up your own backup server and keep copies on a separate server for extra reliability.” 官方建议是自建备份服务器、把副本放在另一台机器上。也就是说，备份成本要你自己承担，可能意味着再开一台最便宜的 VPS 专门存快照。如果你对数据有要求，把这笔钱提前算进去。

**系统管理服务按小时计。** 附加服务里列的是 $9.16/小时，适合临时让人处理一次环境问题，不适合当作长期运维方案。

👉 [在配置器里按需加上 IPv4 地址和带宽](https://justhost.asia/en/vps?ref=196392)

## 同样的配置，换存储介质差多少钱

JustHost 的配置器页面另有一条按存储类型分类的产品线，1 核 / 512 MB / 5 GB 这个规格有三种介质可选，都是年付价：HDD $2.60/月，SSD $3.12/月，NVMe $3.38/月。**从 HDD 换到 NVMe，每月多 $0.78。**

官方对三种介质的定位是“自行选择存储类型”，NVMe 用于更快的数据访问。$0.78/月换更好的随机读写，对数据库、编译、容器镜像这类 I/O 敏感的任务值得；纯粹当跳板机或跑轻量脚本，HDD 版的 $2.60 已经够。此外，2 核 4 GB 这一档，HDD 版 $17.60、SSD 版 $21.12、NVMe 版 $22.88，介质差价随配置升到每月 $5 上下。

需要注意，这条配置器产品线与前面的“星系”套餐是两条独立产品线，同名配置的价格不同。比如配置器里有个 Sirius Special，1 核 / 1 GB / 20 GB NVMe，年付 $2.25/月；而价格页上的 Sirius 是 $3.88/月。两者不是同一个商品，下单前看清你点的是哪条产品线。

👉 [在配置器里对比 HDD、SSD、NVMe 三种版本](https://justhost.asia/en/vps?ref=196392)

## 按你的用途直接定档

只做 IPv6 环境测试、不需要对外用 IPv4 访问：HDD VPS IPv6，$1.60/月，这是全站最低价。
需要 IPv4，预算压到最低：VPS Promo $1.99/月，但注意端口只有 10 Mbps、年付折后价页面没正常显示。
需要 IPv4 且想少踩坑：New Star $3.05/月，1 GB 内存、100 Mbps 端口，比 Promo 多 $1.06 换来双倍内存和十倍端口。
要一台正经能建站的双栈机：Sirius $3.88/月（1 核 / 1 GB / 20 GB NVMe / 300 Mbps）。
2 核 4 GB 跑中等流量站点：Vega $10.75/月；要更大硬盘和 750 Mbps 端口，就从 Capella $14.64/月往上挑。
12 核 32 GB 这一档的 Procyon $131.65/月，已经是独立服务器级别的配置需求才会用到的价格。

下单前确认两件事：第一，你是否需要 IPv4，需要就别买 IPv6-only 版本再补地址；第二，你是否能接受没有自动备份，不能接受就先把备份方案和第二台机器的钱算进预算。

👉 [从 $1.60/月的 IPv6 套餐或 $3.05/月的 New Star 开始](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)
