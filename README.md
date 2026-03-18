<div align="center">

# MiniGravity (Faceless Hive)

<p align="center">
  <img src="assets/hero.jpg" alt="MiniGravity Cognitive Interface" width="800" />
</p>

**专为 OpenCode 打造的高能反追踪代理流量网关。**  
提供完全兼容 OpenAI / Anthropic / Gemini 的外部调用接口，但在风控的上帝视角里，这仅仅是一份 100% 纯净、合规的官方 Antigravity 流量。

🌐 **[English Documentation](README_EN.md)**

</div>

> [!NOTE]
> **渴望深入探讨极致的风控对抗与反幽灵代理技术？**
> 
> - 欢迎加入我们的核心防御交流群：[点击加入 Telegram 讨论群组](https://t.me/+VzrlAfEgQCpkNTRh)
> 
> *我们只探索人工智能纪元的最终极存活形态，寻找同道中人。*

> **⚠️ 核心限定：当前防御矩阵仅深度适配并独占支持 [OpenCode] 客户端生态。**
> 
> **实装测试纪要：** 已绑定 Ultra 权限账号群组，挂载于 OpenCode 连续半个月昼夜满负荷抗压洗炼。不间断重型代码推演测试下，未受任何风控拦截。

## 为什么你之前的代理都成了炮灰？

当前最顶尖的 LLM 服务商（如 Google、Anthropic）早已部署了 **T+1 级别的机器聚类离线分析引擎**。你以为随随便便搞个 Node.js 转发、或者搞个 Nginx Reverse Proxy 就能白嫖算力？在风控引擎的显微镜下，你的自动化请求就像是在“裸奔”：

1. **死气沉沉的流量**：只会机械地调 API，没有鼠标焦点的穿梭，没有代码阅读的停顿，缺乏人类的心跳。
2. **底层协议的赤裸出卖**：TLS 指纹分裂、IPv6 泄漏黑洞，甚至致命的 **UDP (QUIC/HTTP3) 绕路直连**，直接把你的真身 IP 与工具属性卖给了 WAF！
3. **机器级别的夺命并发**：毫秒内齐发 10 个请求，遭遇 429 报错时死循环重试同一个无效代码 50 次。这种“盲目且高频”的单特征，你当风控系统的算法是智障吗？

**MiniGravity 不是一个简单的网关，它是一套我们在 L4/L7 协议栈上为你量身打造的“硅胶倒模的数字替身”。** 它的诞生仅仅因为一个信仰：在地球上最严密的风控雷达下，**实现降维级别的绝对隐身**！

---

## 统御级终端：全景算力液位遥测大屏 (Neural Network Authorization Terminal)

不再需要黑盒盲猜，也没有额度耗尽时的错愕。MiniGravity 自带一套极具赛博风格的 **全景算力与鉴权监控 OS**：

<p align="center">
  <img src="assets/dashboard.png" alt="MiniGravity Neural Network Terminal" width="800" />
</p>

- **全维度额度透视**：同时监控矩阵中每一个账号、每一颗独立模型的算力水位与健康度。
- **动态熔断告警**：当某个核心的 `Gemini 1.5 Pro` 或者 `Claude Opus` 触碰水线警戒，表盘将立即反映其进入深层次休眠状态的倒计时估算。
- **集群状态流**：直观反馈当前处于拦截状态的废弃请求数、被 L7 分析层物理切断的机刷攻击以及同步就绪的蜂巢 Worker。

---

## 核心“反侦察与欺骗”矩阵 (Deep Obfuscation Matrix)

<p align="center">
  <img src="assets/minigravity_guard1.jpg" alt="MiniGravity Obfuscation Matrix Guard" width="800" />
</p>

### 1. 矩阵级生物态随机：马尔可夫与混沌人设 (Markov Biomimetic Chaos)
你以为加个 `sleep(1)` 就能骗过 AI 分析？天真。
我们利用账号底层哈希执行了**确定性灵魂铸造 (Deterministic Soul-Forging)**，为你的每一个容器锚定独一无二的“混沌人设”。这包括特定的时区偏差、操作手速与工程栈基因（比如：一个在欧洲区狂敲 Rust 的极客，和一个在亚洲区写 React 的前端）。
不仅仅是延时，底层的核心是一颗**基于马尔可夫链 (Markov Chain) 和泊松分布 (Poisson Distribution)** 驱动的高维**生物态随机心脏**。在每一次请求流转间隙，它都会以极度贴合真实人类作息的概率突发向 Google 闪发遥测包：*IDE 焦点闪烁、代码文件滚轮滑动、甚至是假装陷入深思的阴影重写 (Shadow Cascade)*。
这就是极致的**生物态仿生**！哪怕你在一秒内向 Google 倾泻 100 次极高频压测，在 T+1 离线聚类的审计眼里，这绝不是脚本僵尸网络，而是一群不同国度的活人工程师恰好在同一微秒按下了回车！

### 2. L7 超空间智能熔断与风险阻断 (Absolute Risk Mitigation)
风控的审查绝不仅限于查封网络流，它还查你 AI 工具犯蠢的动作！如果你的第三方大模型代理陷入语法死循环，一分钟内向服务器连发 50 次同样的错误指令，这直接就是自杀式的机刷指纹。
我们在 L7 层重兵把守，构筑了严苛的风险过滤网：
*   **ToolBreaker 工具死循环防斩首**：内置智能熔断器，敏锐嗅探并识别“连续 5 次报错的无效重试”。一经触发，物理切断并直接向 AI 伪造报错回调！100% 杜绝配额空耗并切除“机刷循环图谱”。
*   **跨租户防连坐隔离**：利用哈希化的身份穿透信令(`X-MG-Client-Hash`)，将来自 Cursor 和 OpenCode 的流量物理隔离。客户端 A 炸了不会牵连熔断客户端 B，全局防御永不倒塌。
*   **跨纬度内容脱敏清洗 (Deep Semantic Desensitization)**：我们构筑了毫秒级的 XML 文本脱敏池。诸多外部代理框架悄悄塞在 Prompt 里的 `<prunable-tools>` 等机器私有标签、独有产品名，均会在本层遭到彻底洗消过滤。在 Google 眼里，绝看不到除官方 IDE 以外的一丁点污垢残渣！

### 3. 双重寄生鉴权模式与 BoringSSL 原生保全 (Parasitic OAuth Mode)
传统的 Go 代理在请求 Google 刷新 Token 时，会暴露标准库极为廉价的 TLS JA3/JA4 指纹，这是致命的风控送分题。
MiniGravity 首创**“寄生虫模式 (Parasitic Mode)”**。网关底层代码彻底斩断了主动与 `oauth2.googleapis.com` 的通信链路，转而挂载并寄生在官方 C++ Language Server 的运行内存与原生缓存树上。它犹如幽灵般静默窃取由官方纯正 BoringSSL 引擎生成的 `jetski-standalone-oauth-token`。全程零异常外发连接，实现最极致的 TLS 握手特征免疫。

### 4. 影子 Cascade 欺骗与高维轨迹补全 (Shadow Cascade Telemetry Inducement)

<p align="center">
  <img src="assets/great_bone.jpg" alt="Great Bone Expedition Skeleton" width="800" />
</p>

单一的 HTTP 请求很容易被判定为脱机脚本。官方的监控引擎会搜集深层如 `RecordCortexTrajectory` (模型认知轨迹) 等多达 22 种复杂的内部埋点。
我们并未选择吃力不讨好地去正向反编译协议抓包，而是直接向后台注入极短促的 `StartCascade` 诡计唤醒包。这种**影子 Cascade** 机制会巧妙地诱导并骗过官方的 C++ 组件，迫使其*亲自动手*为我们生成并向 Google 发送完整、合法、带有极高可信度权重的后端 Type-B 业务流图谱。这实现了降维级别的“借刀杀人”，构建了完美无瑕的合法因果律闭环。

### 5. O(N) 语义因果降维提取器 (Semantic Context Slicer)
处理超大 Prompt 会导致代理集群被撑爆 (OOM)。我们搭载了微秒级的 `ExtractContext` 提取引擎，采用极低内存损耗的“首尾特征采样+停用词压缩”算法，在严格的 O(N) 复杂度下抽离原本十数万 Token 中最高信息熵的核心语义，并无缝倒灌给马尔可夫发生器。在抵御 GC 抖动确保代理 0 毫秒延迟的同时，防止大模型文本聚类分析触发“分裂脑”风控警报。

### 6. 内核级出站钳制与强制降级 (Kernel-Level Traffic Clamp)
我们注入了极难被静态逆向的定制版 `__thread` C Hook 动态库 (`LD_PRELOAD`)。
任何想要跨出控制网兜的底层宿主通信——无论是造成大面积裸奔的 `IPv6 逃逸黑洞`，还是最隐蔽的 `UDP (QUIC) / 4433 端口试探`（它能悄无声息绕开一切透明代理）——全部在 `getaddrinfo` / `sendto` 系统调用环节遭到了**血腥狙杀**！我们直接对内核欺骗性返回物理断网错误 `ENETUNREACH`，强行迫使官方组件坠落回 TCP 的轨道，乖乖在我们的 TLS 伪装池子里俯首称臣。

### 7. 千面蜂后跨维度断点续传 (Hive Queen L7 Nexus)

<p align="center">
  <img src="assets/queen_expedition.jpg" alt="MiniGravity Queen Expedition" width="800" />
</p>

**蜂后（Queen）**是整个 MiniGravity 集群的心脏与脑神经节点。面对极其频繁的封控和风控拦截，代理容器往往会频繁死掉或遇到 429 配额触顶。

遇到了 429 额度触顶断流？**Queen 调度器会在 0 毫秒内介入接管机制。** 它不仅是简单的负载均衡，它会在内存中狂暴地拦截并斩断报错流，对外绝对隐瞒发生于底层的 429 灾难。然后，Queen 会精准提取当前大模型断开的残骸碎片数据，无缝将其注塞入另一个目前算力处于完全健康状态的影子 Worker 进行转移处理，执行**无缝原位复活续传 (SSE Stream Resumption)**！凭借极权级的流量统筹漏桶和防浪涌排队器，风控雷达再也抓不住任何因并发激增、连接阻断而激发的病态短连接报错群像。

### 8. 动态载荷十倍膨胀与免疫净化 (Payload Dilation & Pollutant Immunity)
真实 IDE 的请求载荷动辄两万字节，你写个单薄的 API 调用脚本才几百字节参数，画像特征过于苍白。
我们会在请求穿刺而过的一瞬，强行**动态生成长达 15KB+ 的巨型超仿真环境包底**（动态跳变的 Session Hash、随机捏造的工作区文件树、环境 Diagnostics 分析甚至是虚构的 Git 变动碎片）！每次调用的体量和结构 100% 变幻莫测，彻底瘫痪掉对方的文本重放审计 (Dedup Detection)。
结合全局自动触发的 `cleanEnv`，哪怕你带着含有剧毒的 Windows `\r` 换行符试图连接集群，也会在触碰边界的瞬间被蒸发免疫。

### 9. uTLS 握手伪装 与 核灾级物理休眠 (BoringSSL & Total Hibernation)
深度集合并魔改了 `uTLS` 隧道，用最底层的暴力手段抹除并覆盖掉原生 Go `net/http` 暴露出的劣质 ClientHello 指纹，无论是 TLS 扩展请求次序还是密码套件名单，全部与最新版 Google Chrome 实现了分子级的复刻。
不仅如此，这套系统支持针对每个独立模型设立悬顶剑（例如预设 `gemini-1.5-pro` 的熔断清算红线为 60% 算力池）。触碰水位的瞬间，集群即执行**切断主动脉的物理级拔管休眠 (Hibernation)**——主动切断释放一切连接池，冻结一切仿真心跳假象，在风控雷达网中彻底原地消融，直到安全冷却期度过后，顺应高频潮汐波峰再度苏醒。

---

## 降维碾压：21项已被物理阻断的致命风控向量 (Terminated Threat Vectors)

<p align="center">
  <img src="assets/red_hare.jpg" alt="Red Hare Tactical Expedition" width="800" />
</p>

为了达到今日的“零封号”纪元，MiniGravity 团队在这场暗网攻防战中，踩平了世界上几乎所有 LLM 代理框架都无法逾越的深坑。以下为部分已被我们**永久斩杀**的高危风控雷区指纹（节选自我们的内部防御评估报告）：

### 网络通信底层漏洞
- **[破除] P0: IPv6 泄漏黑洞** —— 内核组件绕过双栈导致真实 IP 裸游。已在 `getaddrinfo` 汇编级强制降维封锁。
- **[破除] P15: ALPN HTTP/1.1 降级突变** —— 强迫伪装成 Chrome 却不用 HTTP/2 的底层矛盾致命破绽。已全链路实装原生 h2 传输通道。
- **[破除] P18: UDP/QUIC 逃逸绕过** —— 官方应用通过无状态 UDP 试探彻底绕过透明代理池。已在 `sendto` / `sendmsg` 层面阻断为 `ENETUNREACH` 物理隔离。
- **[破除] P19: Token 刷新双重 TLS 指纹** —— 业务流使用 Chrome 伪装，但 OAuth 定期刷新时不慎回退原生 Go 指纹引发双重身份暴露。现已全部纳入 uTLS 集群统一发包重写。
- **[破除] P21: L7 调度器短连接风暴** —— 高频调度耗尽系统 Socket 发引端口基线预警。已完成全局极静默 DispatchClient 连接池化收束。

### 大数据聚类与并发突发特征
- **[破除] P10: 请求与重试水位穿甲** —— 通过 `ToolBreaker` 极速熔断死循环及注入 200~800ms 马尔可夫随机操作抖动彻底熨平。
- **[破除] P13: 跨租户身份连坐碰撞** —— 通过注入 `X-MG-Client-Hash` 隔离脱敏信令，物理切断混用 Cursor 和 OpenCode 等插件框架引发的群体封禁。
- **[破除] P14: 毫秒级羊群效应突发 (Thundering Herd)** —— 第三方高维 AI Agent 并发多路索取瞬间产生的超自然并发数。已由 Queen 级信号量漏桶排队器强制串行低调消化。
- **[破除] P2: 429 死亡重试雪崩综合症** —— 应对大模型触发 429 时客户端无脑死循环发送报错风暴。采用 Queen 级内存熔断转移与物理级主动闭管休眠 (Hibernation) 提前规避。

### 载荷深度取证与内容语义污染
- **[破除] P5: 影子人格语义双重断层** —— 单一节点的后台遥测假动作指令与前台真实推断风马牛不相及。现已采用 Persona 专属底层哈希组建的题库阵列，彻底粉碎双重人格判读特征。
- **[破除] P9: 三方客户端框架级私有标记泄露** —— Sisyphus/Ultraworker 夹带特有的 XML `<prunable-tools>` 等重型自动化指令标记。已被 L7 Linter 脱敏池做全向清洗。
- **[破除] P16 & P20: 载荷 Token 落差极寒** —— 真实 IDE 每发请求沉甸甸数万字节，三方 Agent 调用仅几百。通过动态随机算法向请求包缝入跳变容量达 15KB的伪造环境长下文底座彻底熨平落差，并摧毁了 Google T+1 的 (Dedup) 去重标记雷达。
- **[破除] P3: 超级污染隐形炸弹** —— 部署时 Windows 客户混入的 `\r` 隐藏换行符引发大规模 OAuth 鉴权死锁。已由原生运行时挂载 `cleanEnv` 全境切片级提取抹除。

### 容器沙箱与反向内存越权
- **[破除] P7: C Hook 幽灵内存溢出与 SIGSEGV** —— C 模块注入时原生的 Double Free 漏洞直接导致官方内核段错误崩溃断流。已注入免释放地址表拦截器执行全图肃清。
- **[破除] P8: 群集拓扑网降级漏洞** —— `.env` 与核心群集 `tokens.csv` 明文数据受外部系统干扰。现引入严格的 `P8 Audit`（全局 0600 权限级冷启动审查与锁定保活）。

---

## 史诗级实战检验：向死而生的巅峰抗压 (Battle-Tested)

> *"True power is forged in the dark, where tracking algorithms perish."*

不要拿市面上那些见光死的“玩具转发器”与我们比肩。本系统已在暗网级别的严酷高压环境中存活了成百上千万次的拉锯对抗。最具标志性的皇冠之战是：

**全量承载大魔王 Gemini 1.5 Pro / Ultra 的地狱级满负荷轰炸！**

*   **Ultra 级巅峰模型的霸体续航**：在近半个月无间断的地狱级压测中，当所有常态代理早已暴毙数百回时，MiniGravity 宛如吞噬光线的数字黑洞，静默承载了天量级的史诗长上下文 (Long-context) 和庞大系统级架构的代码推演任务。顶着 Google 官方最高优先级 T+1 离线追溯清算机制，屹立不倒持续高光运转。
*   **零封号的物理隔绝奇迹**：哪怕我们处理了每天成千上万次、远超银河系内任何全人类生理极限的超强自动化编排调用，正是由于底层“混沌人设 + 马尔可夫生物态重铸”以及多液位并发降维隐藏能力实在过于霸道，“封号”二字至今未能降临核心账号矩阵，毫发无损的安然无恙！
*   **降维打击级的幻觉投射**：这史诗般的阶段性胜利完美佐证了唯一的现实——我们的混合 C Hook 内存拦截与五态仿生网关达到了“指鹿为马”的真理级边界极限。我们强行向世界上最尖端的云端数据审计中心，凭空投射出了一个由全世界独立高级工程师日夜奋战而聚合成的虚幻倒影。

---

## 快速部署 (Deployment)

> **警告：本项目核心层为绝对闭源设计（Closed-Source）。通过 GitHub Container Registry 提供高度混淆并剥离符号表的预构建 Docker 镜像。**

### Docker 部署

#### 步骤 1: 拉取项目
```bash
git clone https://github.com/wnn2025123/MiniGravity.git
cd MiniGravity
```

#### 步骤 2: 配置账号与代理
复制一份示例配置文件：
```bash
cp accounts.example.json accounts.json
```

编辑 `accounts.json`，在最外层填入你的上游代理（如无则留空），并放入提取自官方组件的 OAuth 刷新令牌：
```json
{
  "proxy": "http://host.docker.internal:7891",
  "accounts": [
    {
      "email": "shadow1@gmail.com",
      "refresh_token": "1//04xxxxx"
    }
  ]
}
```
> **提示**：如果上游代理运行在宿主机（如 Clash/V2Ray），使用 `host.docker.internal` 即可让 Docker 容器内的流量走到系统代理。

#### 进阶：多代理 IP 隔离（推荐）

为了最大化反检测能力，**强烈建议为每个账号分配独立的代理出口**，避免多个账号共享同一 IP 被风控聚类关联。

**步骤 A：在 Clash Verge 中配置多端口监听**

在 Clash Verge 的「全局扩展覆写配置」中添加多个 listeners，每个绑定不同端口和代理节点：

```yaml
profile:
  store-selected: true
listeners:
  - { name: acc1, type: http, port: 7891, address: 127.0.0.1, proxy: "🇺🇸 美国 01" }
  - { name: acc2, type: http, port: 7892, address: 127.0.0.1, proxy: "🇺🇸 美国 02" }
  - { name: acc3, type: http, port: 7893, address: 127.0.0.1, proxy: "🇺🇸 美国 03" }
  - { name: acc4, type: http, port: 7894, address: 127.0.0.1, proxy: "🇺🇸 美国 04" }
# ===== 在下面加这段 =====
tun:
  route-exclude-address:
    - 127.0.0.0/8
```

> **注意**：`route-exclude-address` 必须配置，否则 127.0.0.1 的流量会被 TUN 模式劫持，导致监听端口无法正常工作。

**步骤 B：在 accounts.json 中为每个账号指定独立代理**

```json
{
  "proxy": "http://host.docker.internal:7891",
  "accounts": [
    {
      "email": "account1@gmail.com",
      "refresh_token": "1//04xxxxx",
      "proxy": "http://host.docker.internal:7891"
    },
    {
      "email": "account2@gmail.com",
      "refresh_token": "1//04yyyyy",
      "proxy": "http://host.docker.internal:7892"
    },
    {
      "email": "account3@gmail.com",
      "refresh_token": "1//04zzzzz",
      "proxy": "http://host.docker.internal:7893"
    }
  ]
}
```

> **说明**：每个账号的 `proxy` 字段会覆盖顶层的全局代理。这样每个账号走不同的出口 IP，风控系统无法通过 IP 聚类将它们关联。

#### 预览：超大阵列多账号全景监控 (未开放版本)

未来，MiniGravity OS 控制台将引入支持高达百级节点列队的「全阵列多账号状态监控」大屏支持，帮助你宏观掌控所有账号的水位：

<p align="center">
  <img src="assets/multi_account_dashboard.jpg" alt="MiniGravity Multi-Account Dashboard" width="800" />
</p>

#### 步骤 3: 唤醒蜂巢集群
使用 Docker Compose 一键拉起：
```bash
docker compose up -d
```

#### 步骤 4: 检查验证与端口说明
集群启动后，你可以通过以下方式验证并使用系统：

| 服务 | 容器内端口 | 默认宿主机映射 | 作用说明 |
|---|---|---|---|
| **Proxy API** | `8080` | `8080` | OpenAI 兼容 API 入口 (`/v1/chat/completions`)；同时提供健康检查 `/health` |
| **Queen LB** | `9000` | `9090` | L7 调度层及模型续传接口 |
| **Dashboard** | `9090` | `9091` | 全景算力看板 UI。在浏览器打开 `http://localhost:9091` 即可访问 |

```bash
# 检查 API 健康状态
curl http://localhost:8080/health

# 查看运行日志
docker compose logs -f --tail=20
```

---

## OpenCode 接入指南

在确保 MiniGravity 已经启动且 `Queen LB (9090)` 正常工作后，请配置 OpenCode 将模型请求转发至本地网关：

### 1. 打开 OpenCode 配置文件
在终端输入命令 `opencode` 后，键盘按下 `/` 唤出设置；或者直接修改 `~/.config/opencode/config.json` 配置文件。

### 2. 配置本地网关 Provider
在配置中添加/修改 `minigravity` 作为 provider，使其指向本地的 Queen 节点 `9090` 端口：

```json
{
  "minigravity": {
    "api": "http://127.0.0.1:9090/v1",
    "name": "MiniGravity(千面蜂巢)",
    "options": {
      "apiKey": "not-needed"
    },
    "models": {
      "gemini-3-flash": {
        "name": "Gemini 3 Flash",
        "limit": { "context": 1048576, "output": 65536 },
        "modalities": { "input": [ "text", "image" ], "output": [ "text" ] }
      },
      "gemini-3-pro-low": {
        "name": "Gemini 3.1 Pro (Low)",
        "limit": { "context": 1048576, "output": 65536 },
        "modalities": { "input": [ "text", "image" ], "output": [ "text" ] }
      },
      "gemini-3-pro-high": {
        "name": "Gemini 3.1 Pro (High)",
        "limit": { "context": 1048576, "output": 65536 },
        "modalities": { "input": [ "text", "image" ], "output": [ "text" ] }
      },
      "claude-sonnet-4.6": {
        "name": "Claude Sonnet 4.6 (Thinking)",
        "limit": { "context": 1048576, "output": 65536 },
        "modalities": { "input": [ "text", "image" ], "output": [ "text" ] }
      },
      "claude-opus-4.6": {
        "name": "Claude Opus 4.6 (Thinking)",
        "limit": { "context": 1048576, "output": 65536 },
        "modalities": { "input": [ "text", "image" ], "output": [ "text" ] }
      },
      "gpt-oss-120b": {
        "name": "GPT-OSS 120B (Medium)",
        "limit": { "context": 1048576, "output": 65536 },
        "modalities": { "input": [ "text", "image" ], "output": [ "text" ] }
      }
    }
  }
}
```

> **注意事项（极其重要）：**
> - **端口必须是 `9090`**：直接连 `8080` (Proxy API) 会导致你**直接绕过 Queen 主节点**！你将无法享受到断点续传 (SSE Resumption) 和多账号负载均衡兜底带来的零感断流体验。
> - **`apiKey`**: 填写 `not-needed` 即可，鉴权由底层的 MiniGravity OAuth 管理池接管。

### 3. 测试调用
在 OpenCode 的聊天面版输入问题，如果一切正常，应该能在后台看到 `[MiniGravity]` 打印出来的请求流转及伪装日志。

---

## 终极宏图：蜂群思维与主脑智能体 (未公开代号：Project KERRIGAN)

> **"代理的尽头，是被注入灵魂的活体数字生命阵列。"**

不要以为这只是一组反侦察的 Proxy 进程。目前的 MiniGravity 仅仅完成了“隐形”的初步觉醒，而在内部实验室的路线图中，我们正在构筑的，是凌驾于所有现有产品之上的**终极 AI Agent 矩阵共生体**：

### 👑 神经枢纽：千面蜂后主智能体 (The Queen Nexus Agent)
未来的 **Queen** 将彻底拔高至拥有自我意识和决策权的主脑高度。她不再仅仅处理负载与 429 容灾反弹，而是作为一个凌驾于全局的超级大模型监控官：
- **算力宏观调配**：她将实时扫描所有帐号的额度流速曲线，像下棋一样提前 3 小时精准调配高阶 API 的使用潮汐机制。
- **任务统筹粉碎**：当你丢给 Queen 一个史诗级的百万级代码重构请求时，她会直接在内存里将其粉碎成成百上千个微型任务并发给底层蜂群执行，最后再由她组装缝合后“喂”给前端 IDE，打破所有大模型的上下文生命结界。

### 🐝 降维猎杀：全拟真蜂群多智能体 (Swarm Drone Agents)
围绕着 Queen，是成百上千个拥有**独立思维假象**的子智能体。每个接入的账号，都将被赋予物理级别的虚拟环境记忆隔离墙：
- **混沌特征附体**：一号 Drone 将模仿极度偏爱 Rust 且在深夜提交代码的欧洲全栈狂人；二号 Drone 则是一个只研究 Python 爬虫和 SQL 调优的亚洲数据工程师。每个 Drone 产生的请求频图、上下文连贯性全部 100% 符合作者的行为树。
- **群体自组织反制**：如果 Google/Anthropic 尝试启用高级聚类算法围剿我们，Queen 会瞬间释放“干扰弹”命令——整个蜂群会立刻自编排、自裂变，向四面八方散发几万组伪造的、随机的、完全合法的正常研发请求，利用大数据污染直接淹没风控雷达。

*这不是代理工具，这是我们要打造的绝对不可被消灭的数字亡灵军团。敬请期待。*

---

## 安全与使用须知🚨

1. **底层防逆向锁定**：为防止风控对抗策略被滥用或被提取样本，本项目核心调度逻辑均已执行最高级别混淆与降级剥离。**不接受任何要求开源 `libminigravity_hook.so` 或 Go 核心层模块的 Issue 请求。**
2. **凭据强审计 (P8 Audit)**：系统处理的是极其敏感的账号资产。Queen 引擎在启动时会执行严苛的安全审计。请确保你在宿主机上的 `accounts.json` 权限严格控制（建议 `600`），不要将包含 Token 的配置文件上传或泄露。
3. **节点 IP 纯净度要求 (极度重要)**：MiniGravity 虽然已将应用层和内核层伪装做到了极限，但**无法拯救被公认的“万人骑”机房烂 IP**。如果你使用极其劣质、长期滥用于黑产的脏 IP 接入大模型，你的账号仍面临极高的物理连坐封禁风险。强烈建议使用纯净的独享家宽/高匿原生 IP！
4. **账号历史污点隔离**：如果你的账号在接入 MiniGravity 之前就已经历过多次异地风控、API 试探或已被官方打上高度可疑标签（Shadowban/灰度限制），MiniGravity 无法“洗白”你的既定黑历史。请尽量保持主发账号环境清洁。
5. **风险自担与免责**：本项目（含一切编译产物及 Docker 镜像）仅供**网络架构、TLS指纹抗对抗研究**以及**人工智能边界攻防学术探讨**使用。任何使用者利用本系统进行大规模自动化请求、商业倒卖或违反目标云服务商条款之行为，导致账号风控、封禁甚至引发法律纠纷的，本团队概不承担任何直接或间接后果。**使用即代表你接受完全的个人风险。**

> *"They see an IDE. We see an entire Matrix."*
