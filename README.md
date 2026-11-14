# Akile SGLite 怎么选：¥24.99 的 Mini 和 ¥87.49 的 Standard 差在哪？四档套餐、库存与超量限速一次说明白（附全套餐表）

AkileCloud 的 SGLite 是新加坡流量型 VPS，当前目录里有四档，月付 ¥24.99 到 ¥212.49。截至 2026 年 11 月上旬，四档里只有 SGLite-Standard（¥87.49/月，1 核 1 GB、6000 GB 流量）显示有货，SGLite-Mini、SGLite-Starter、SGLite-Pro 都是售罄状态。它主打的是新加坡出口、内部 DNS 解锁当地流媒体、1 个 IPv4 加 1 个 IPv6；流量用完后不会关机，而是降到共享 10 Mbps 继续跑。

下面把四档 SGLite 和同在新加坡的 SGBGP Base 四档放在一张表里，再算清楚几件事：哪档够用、超量重置划不划算、当前有没有必要等补货。

> 只想低成本解锁新加坡流媒体、每月 1 TB 以内，选 SGLite-Mini（¥24.99/月），但它当前售罄，要等补货；现在就要开通，SGLite-Standard（¥87.49/月）是四档里唯一有货的；完全不看流量，再看 SGBase-UNLIMITED-500M（¥235/月）。
>
> 👉 [打开 AkileCloud 查看 SGLite 套餐与库存](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)

## 新加坡八档套餐：SGLite 四档和 SGBGP Base 四档

下表是截至 2026 年 11 月上旬的目录快照，八档都是月付人民币计价，另有一档自定义高配需要联系客服。库存是实时变动的，下单前以页面为准。

| 套餐 | 配置（CPU / 内存 / 硬盘） | 带宽 / 月流量 | 月付价格 | 库存 | 购买 |
| --- | --- | --- | --- | --- | --- |
| SGLite-Mini | 1 核 / 1 GB / 5 GB | 1 Gbps / 1000 GB | ¥24.99 | 售罄 | [ 查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGLite-Starter | 1 核 / 1 GB / 10 GB | 1 Gbps / 3000 GB | ¥43.74 | 售罄 | [ 查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGLite-Standard | 1 核 / 1 GB / 10 GB | 1.5 Gbps / 6000 GB | ¥87.49 | 有货 | [ 查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGLite-Pro | 2 核 / 2 GB / 20 GB | 2 Gbps / 12000 GB | ¥212.49 | 售罄 | [ 查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGBase-Lite | 1 核 / 1 GB / 10 GB | 2 Gbps / 3000 GB | ¥35.00 | 售罄 | [ 查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGBase-Standard | 1 核 / 2 GB / 10 GB | 2 Gbps / 6000 GB | ¥70.00 | 售罄 | [ 查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGBase-UNLIMITED-500M | 1 核 / 2 GB / 10 GB | 500 Mbps / 不限量 | ¥235.00 | 有货 | [ 查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGBase-UNLIMITED-1000M | 1 核 / 3 GB / 20 GB | 1 Gbps / 不限量 | ¥360.00 | 有货 | [ 查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| Custom Higher Config | 自定 | 自定 | 联系客服 / 工单 | 需咨询 | [ 咨询](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |

SGLite 四档都给 1 个 IPv4 和 1 个 IPv6；系统模板有 Debian 11/12、Ubuntu 18/20/22、RockyLinux 8/9。购买页先选类型 Traffic-Based Cloud Server，再选 Singapore，最后选节点。SGLite 和 SGBGP Base 是两条产品线，选错节点会买到另一条线。

SGLite-Pro 在 2026 年 3 月的记录里还有 6 台，11 月已标售罄。SGLite-Mini 在 2026 年 5 月有过补货消息，现在又显示无货。库存不是静态的，但也不能按“随时会补”来安排项目。

## SGLite 和 SGBGP Base 差在哪

SGLite 的节点说明写的是内部 DNS 解锁新加坡流媒体，IPv6 移动直连。SGBGP Base 走私有 DNS 解锁 Netflix 等，产品说明明确不保证中国直连。两条线都没有中国大陆优化线路的承诺，第三方套餐对比也只按硬件和价格打分，不含路由测试。

流量计费也不同。SGLite 四档全是限量流量，超量后限速共享 10 Mbps，可以付费重置。SGBGP Base 有 SGBase-Lite、SGBase-Standard 两档限量，还有 500M、1000M 两档不限量。

价格上，SGBase-Lite 是 1 核 1 GB、10 GB 硬盘、2 Gbps 端口、3000 GB 流量，¥35/月。SGLite-Starter 同样是 1 核 1 GB、10 GB 硬盘、3000 GB 流量，¥43.74/月，端口 1 Gbps。SGBase-Lite 便宜 ¥8.74，差别在解锁方式，SGBase-Lite 用私有 DNS，SGLite-Starter 用内部 DNS，线路说明也不一样。两档当前都售罄。

## 哪一档够用：按每月流量和用途选

按用途分，五类需求对应五档，前四档是 SGLite，最后一档是 SGBGP Base 不限量。

- 单人看新加坡区流媒体、每月 1 TB 以内：SGLite-Mini，¥24.99，1 核 1 GB，1000 GB。当前售罄，不急可以等；急用就看 SGLite-Standard。
- 多设备、每月 3 TB 以内：SGLite-Starter，¥43.74，3000 GB，比 SGLite-Mini 多 5 GB 硬盘。当前售罄。
- 每月 6 TB 以内：SGLite-Standard，¥87.49，6000 GB，1.5 Gbps。四档里唯一有货，也是 2026 年 11 月上旬能直接开通的 SGLite。
- 每月 12 TB 左右、需要 2 核 2 GB：SGLite-Pro，¥212.49，12000 GB，2 Gbps。当前售罄，此前有货。
- 完全不看流量：SGBase-UNLIMITED-500M，¥235，1 核 2 GB、500 Mbps、不限量。要 1 Gbps 和 3 GB 内存，再上 SGBase-UNLIMITED-1000M，¥360。两档都有货。

SGLite 的重置流量单独收费，价格按档位递增。

| 套餐 | 重置流量价格 | 占月费 |
| --- | --- | --- |
| SGLite-Mini | ¥19.99 | 80% |
| SGLite-Starter | ¥36.00 | 82% |
| SGLite-Standard | ¥70.00 | 80% |
| SGLite-Pro | ¥144.00 | 68% |

SGLite-Mini 超 1000 GB 后，买一次重置 ¥19.99，总支出 ¥44.98，拿到 2000 GB。直接升到 SGLite-Starter 是 ¥43.74，给 3000 GB，还多 5 GB 硬盘。入门档超量，升档比重置划算。从 SGLite-Starter 往上，重置一次的价格是月费的七八成，只补流量，不改变配置。偶尔超一次，重置比升一档便宜；每个月都超，说明这档流量不适合你，应该直接上一档。

👉 [查看 SGLite 各档当前价格与库存](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)

## 真实成本：年支出、端口速率和充值手续费

按月付价乘 12：SGLite-Mini ¥299.88/年，SGLite-Starter ¥524.88/年，SGLite-Standard ¥1049.88/年，SGLite-Pro ¥2549.88/年。这是按当前月付价推算的支出，不含任何折扣，也没有把重置流量算进去。

带宽数字要会读。1 Gbps 是端口上限，不是一个月都能跑满。SGLite-Mini 的 1000 GB 按 1 Gbps 全速跑，大约两个多小时就没了。这类套餐买的是月流量额度，端口速率只决定峰值。

如果你打算先充值余额再下单，官方在 2023 年 6 月说明过，充值最低 50 元，Stripe 收单手续费 3.3% + 0.25 EUR，直接下单买产品没有这个最低限制。这条口径距今三年多，结账页可能已经调整，付款前看实际金额。

## SGLite-One 的低价记录，和现在的四档不是一回事

搜索里经常能看到 SGLite-One 的低价记录，需要和现在的四档分开看。2024 年 11 月的一篇第三方测评里，SGLite-One 是 1 核 1 GB、5 GB 硬盘、500 Mbps、1000 GB 流量，月付 ¥12.99。2026 年 10 月还有第三方目录收录它的年付 ¥124.99，折合每月约 ¥10.4，但该页明确注明价格和库存没有和官方确认。

当前 SGLite 目录的入门款是 SGLite-Mini，配置同样是 1 核 1 GB、5 GB、1000 GB，带宽 1 Gbps，月付 ¥24.99。SGLite-One 不在当前四档里。拿 ¥12.99 或年付 ¥124.99 当现价去下单，会对不上。

## 和 Bandwagon Host 新加坡 CN2 GIA 比，差的是线路钱

同为新加坡节点，Bandwagon Host 的 CN2 GIA 产品线是另一种定价。最低档 2 核 2 GB、40 GB 硬盘、1.5 Gbps、500 GB 流量，49.99 USD/月，按目录汇率折算约 ¥333。4 核 4 GB、80 GB、1000 GB 那档 86.99 USD/月，约 ¥580。

AkileCloud 的 SGLite-Standard 是 1 核 1 GB、10 GB、6000 GB，¥87.49/月。两者不是同一类商品。Bandwagon Host 卖的是标了 CN2 GIA 的线路，AkileCloud 的 SGLite 定位是流量型加 DNS 解锁，公开说明里没有中国直连或线路优化保证。要线路保障，预算按 Bandwagon Host 那档算。只要新加坡出口和大流量，SGLite 的价格结构轻得多。

## 几个下单前常问的问题

### 现在有优惠码吗？

现有公开信息里没有可用的折扣码。2026 年 3 月的产品页明确写着没有可用折扣码。2023 年 6 月官方通知里出现过一批折扣码，时间过去三年多，不能当作现在还能用。预算按页面实价算。

👉 [按当前实价查看 SGLite 套餐](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)

### SGLite-Mini 什么时候补货？

公开记录里，2026 年 5 月有过一次 SGLite-Mini 补货的消息，当前又显示售罄。从现有记录看不出固定补货周期，不要按具体日期等。项目急用，直接选有货的 SGLite-Standard，或者看 SGBGP Base 两档不限量。

### 能解锁哪些流媒体？

节点说明只提到新加坡本地流媒体。SGBGP Base 那条线另外写了私有 DNS 解锁 Netflix 等。没有一份可核验的完整解锁清单，具体平台以开通后的实际结果为准。

### 中国访问快不快？

没有可核验的中国大陆路由测试数据。SGBGP Base 的产品说明明确不保证中国直连，SGLite 也没有中国直连承诺。要稳定回国线路，应该去看标了 CN2 GIA 这类线路的产品，预算会高不少。

### 支持哪些系统？

Debian 11、Debian 12、Ubuntu 18、Ubuntu 20、Ubuntu 22、RockyLinux 8、RockyLinux 9。购买页可以直接选这些模板。

### 能自定义更高配置吗？

目录里有 Custom Higher Config 一档，配置和价格都要联系客服或提交工单，公开页没有标价。

## 最后怎么选

1. 每月 1 TB 以内、只为新加坡流媒体解锁：SGLite-Mini，¥24.99。当前售罄，急用就换 SGLite-Standard。
2. 每月 6 TB 以内、现在就要开通：SGLite-Standard，¥87.49，年支出 ¥1049.88，是当前唯一有货的 SGLite。
3. 完全不看流量：SGBase-UNLIMITED-500M，¥235。要 1 Gbps 和 3 GB 内存，再上 SGBase-UNLIMITED-1000M，¥360。

下单前确认两件事：库存是不是实时有货，计费周期是不是月付。SGLite-Pro 目前售罄，SGBGP Base 两档不限量有货，不要把这份快照当永久状态。

👉 [进入 AkileCloud 核对 SGLite 当前库存与价格](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)
