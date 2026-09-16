---
layout: default
title: Castaway Cards — 隐私政策 / Privacy Policy
---

# Castaway Cards
## 隐私政策 / Privacy Policy

[中文](#zh) · [English](#en)

> **生效日期 / Effective date: 2026-09-16**

## 中文 {#zh}

### 1. 谁负责，以及适用范围

本政策说明 **Brooklyn**（下称“我们”）在 PC 游戏 **Castaway Cards** 中使用可选的 GameAnalytics 玩法与性能统计、基本错误上报，以及处理隐私联系时的数据实践。我们决定这项处理的目的与方式，在适用法律下作为数据控制者。

隐私联系邮箱：**[yuanotes@gmail.com](mailto:yuanotes@gmail.com)**。

Steam 自行处理的账户、购买、支付及平台服务数据由 [Valve 隐私政策](https://store.steampowered.com/privacy_agreement/)说明，不属于我们这项 GameAnalytics 接入。

### 2. 你的选择

这项统计与错误上报默认关闭。只有你在游戏内明确同意，并且该发行版本启用了采集功能后，才会初始化这项接入。拒绝或关闭首次提示不会被视为同意，不影响正常游玩。

你可以随时从游戏内设置重新打开数据收集选项并撤回同意。我们以你的同意作为这项可选处理的依据。撤回后，本游戏停止新增的玩法统计和日志上报，并关闭 SDK 事件提交；撤回不会使此前基于有效同意的处理失效，也不会自动删除已接收的数据或撤回已经发送的请求。

同意选择保存在你的设备上。你可以拒绝统计而继续游戏；无需提供邮箱或 SteamID 才能游玩。

### 3. 收集哪些数据

同意后，GameAnalytics 接入可能处理以下数据：

- **玩法事件**：一局开始；到达第 2、3、5、10、20、30、50、100 天；因饥饿、受伤、主动放弃或重新开局而结束，以及相应的游戏天数。游戏中途同意不会补传之前的玩法事件，玩法记录从下一局开始。
- **会话与技术信息**：SDK 为桌面端生成并在会话之间保留的随机用户标识、会话标识、事件时间、会话时长、游戏和 SDK 版本、操作系统、平台、设备及区域设置信息。服务端在接收网络请求时会处理 IP 地址，并可能据此判断大致国家或地区；这不等于 GPS 精确定位。
- **性能信息**：当前配置启用了平均 FPS 与低帧率统计，用于判断运行流畅度。
- **基本错误信息**：Unity 的错误、异常、警告及断言消息和可用的调用堆栈。当前设置为每次启动最多自动提交 10 条错误类事件，警告也占用该额度。这不是对所有错误或桌面原生崩溃的完整捕获。

我们的自定义事件不主动传送 SteamID、真实姓名、邮箱、截图、完整存档、卡牌实例编号或随机种子。SDK 的随机标识仍可能将多次活动关联到同一设备上的用户，因此这些数据**不能一概称为匿名数据**。错误文字和调用堆栈可能包含运行路径或其他上下文，不能保证其中没有个人信息。

本游戏当前未接入 Sentry。

### 4. 用途与接收方

我们使用这些信息了解玩法进度、难度和结束原因，分析流畅度，并定位错误、改善游戏稳定性；不通过这项接入提供定向广告，也不出售本政策说明的统计数据。

接收方是 **GameAnalytics** 及其履行服务所需的服务提供商。GameAnalytics 为我们提供分析服务时作为数据处理者。其数据处理条款也允许在适用法律许可的范围内进行服务改进、安全与反欺诈处理，以及使用不能合理用于识别个人的汇总或去标识信息。详见 [GameAnalytics 数据处理附录](https://www.gameanalytics.com/trust/eu-data-processing-addendum)和[开发者政策](https://www.gameanalytics.com/trust/privacy-faq)。

如果你给我们发送邮件，我们会处理你的邮箱地址、邮件内容及你主动提供的附件，用来回复和处理你的请求。这些邮件通过 Gmail/Google 的邮件服务处理；请勿发送密码、支付资料或不必要的敏感信息。

### 5. 数据存储、保留与跨境处理

GameAnalytics 可能在你的国家或地区之外处理数据。其公开数据处理附录列明美国 AWS `us-east-1` 为境外数据存储或访问地点，并说明适用时采用欧盟标准合同条款及英国相关传输机制。不同地区的数据保护规则可能不同。若你不希望发生这项传输，可以不启用或撤回统计同意。

GameAnalytics 公开的数据处理附录列出以下保留安排（为供应商数据类别，适用情况取决于所使用的服务）：

| 供应商数据类别 | 公布的保留期限 |
| --- | --- |
| 原始及注释数据（Raw and annotated data） | 1 个月 |
| 玩家数据仓库（Player Warehouse） | 1 年 |
| 用于计算留存的玩家索引（Player Lookups） | 18 个月 |

这些期限不代表所有数据都只保存一个月，也不等于后台报表可查看的时间窗口。依法必须继续保留的数据以及不再能合理识别个人的汇总结果，可能有不同的处理安排。我们会根据适用条款与法律处理删除请求，而不是将关闭统计等同于删除。

SDK 可以在设备上缓存标识、会话状态和未发送的事件。撤回同意不会由本游戏主动清空 SDK 数据库；如果以后重新同意，先前在同意期间产生的缓存可能继续提交。本游戏不保存未同意期间的自定义玩法事件以便日后补传。卸载游戏不一定清除全部本地 SDK 数据。

隐私联系邮件按处理请求及必要后续事项所需的期间保留；涉及争议或法律要求时按必要期间保留。

### 6. 你的权利与联系

根据所在地适用法律，你可能享有访问、更正、删除、限制处理、数据可携带、反对处理及向数据保护监管机关投诉等权利。你始终可以在游戏内撤回这项可选统计的同意。

请通过 **[yuanotes@gmail.com](mailto:yuanotes@gmail.com)** 提出请求。为核实请求并定位记录，我们可能请你提供必要的版本、平台或其他相关信息。由于统计使用随机标识，仅凭邮箱或 SteamID 可能无法定位记录；我们会说明需要的信息，并在适用法律范围内与 GameAnalytics 协作处理。请不要在公开 GitHub Issue 中提交个人数据。

如果你未达到所在地可独立同意这类处理的法定年龄，请不要自行启用统计。家长或监护人可联系我们处理有关儿童数据的疑问或删除请求。当前游戏没有年龄识别或监护人验证功能；一般同意按钮并不替代法律要求的额外授权手续。

### 7. 本政策网页

本网页由 GitHub Pages 托管。页面本身不嵌入 GameAnalytics、广告、第三方字体或统计脚本。访问页面时，GitHub 会处理提供网页所需的网络信息，例如 IP 地址；有关其处理方式，参见 [GitHub 隐私声明](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)。

### 8. 更新

游戏的数据实践改变时，我们会更新本政策，并标明生效日期。需要重新征得同意的变更会在相关采集开始前另行请求同意。中英文版本意在表达相同内容；如你发现差异，请通过上述邮箱联系我们。

---

## English {#en}

### 1. Who is responsible and what this notice covers

This notice describes how **Brooklyn** (“we”) uses optional GameAnalytics gameplay and performance analytics and basic error reporting in the PC game **Castaway Cards**, and handles privacy correspondence. We determine the purposes and means of this processing and act as the data controller where applicable law uses that term.

Privacy contact: **[yuanotes@gmail.com](mailto:yuanotes@gmail.com)**.

Steam’s own processing of accounts, purchases, payments, and platform services is described in the [Valve Privacy Policy](https://store.steampowered.com/privacy_agreement/), not by our GameAnalytics integration.

### 2. Your choice

Analytics and error reporting are off by default. This integration is initialized only after you expressly agree in the game and collection is enabled for that release. Declining or dismissing the initial prompt does not count as consent and does not prevent normal gameplay.

You can reopen the data collection options in the game settings and withdraw consent at any time. Consent is our basis for this optional processing. After withdrawal, the game stops generating new gameplay reports and forwarding logs, and disables SDK event submission. Withdrawal does not affect the lawfulness of processing based on valid consent before withdrawal, automatically delete data already received, or recall requests already sent.

Your choice is stored on your device. You may continue playing without analytics; you do not need to supply an email address or SteamID to play.

### 3. Data collected

After consent, the GameAnalytics integration may process:

- **Gameplay events:** starting a run; reaching days 2, 3, 5, 10, 20, 30, 50, and 100; ending through starvation, injury, giving up, or restarting; and the corresponding in-game day. Agreeing during a run does not backfill earlier gameplay events: gameplay tracking starts with the next run.
- **Session and technical information:** a random desktop user identifier generated by the SDK and retained across sessions, session identifiers, event times, session duration, game and SDK versions, operating system, platform, device, and regional settings. Receiving servers process the IP address associated with network requests and may use it to infer an approximate country or region. This is not precise GPS location.
- **Performance information:** the current configuration enables average FPS and low-frame-rate reporting to assess smoothness.
- **Basic error information:** Unity error, exception, warning, and assertion messages, together with available stack traces. The current setting automatically submits at most 10 error-class events per launch, with warnings counting toward that limit. This is not comprehensive capture of every error or native desktop crash.

Our custom events do not intentionally send SteamIDs, real names, email addresses, screenshots, full save files, card-instance identifiers, or random seeds. SDK random identifiers can still link activities across sessions to a user on a device, so this data **must not be described as entirely anonymous**. Error text and stack traces can contain runtime paths or other context; we cannot guarantee that they contain no personal information.

The game does not currently integrate Sentry.

### 4. Purposes and recipients

We use this information to understand progression, difficulty, and run-ending reasons, assess performance, diagnose errors, and improve stability. We do not use this integration to deliver targeted advertising or sell the analytics data described here.

Recipients are **GameAnalytics** and service providers needed to deliver its services. GameAnalytics acts as our processor when providing analytics. Its data processing terms also permit service improvement, security and fraud prevention where legally permitted, and use of aggregated or de-identified information that cannot reasonably identify a person. See the [GameAnalytics Data Processing Addendum](https://www.gameanalytics.com/trust/eu-data-processing-addendum) and [Developer Policy](https://www.gameanalytics.com/trust/privacy-faq).

If you email us, we process your email address, message, and any attachments you choose to send in order to respond and handle your request. Correspondence is processed through Gmail/Google’s email service. Please do not send passwords, payment details, or unnecessary sensitive information.

### 5. Storage, retention, and international processing

GameAnalytics may process data outside your country or region. Its published Data Processing Addendum identifies the United States, AWS `us-east-1`, as a location for transferred data storage or access, and describes EU Standard Contractual Clauses and relevant UK transfer mechanisms where applicable. Data protection rules vary between jurisdictions. If you do not want this transfer, you can decline or withdraw analytics consent.

The published GameAnalytics Data Processing Addendum lists the following retention schedule. These are the provider’s data categories; applicability depends on the services used:

| Provider data category | Published retention |
| --- | --- |
| Raw and annotated data | 1 month |
| Player Warehouse | 1 year |
| Player Lookups used to calculate retention | 18 months |

These periods do not mean that all data is kept for only one month, nor are they the same as dashboard reporting windows. Data that must be retained by law and aggregate results that can no longer reasonably identify a person may be subject to different arrangements. We handle deletion requests under applicable terms and law rather than treating an analytics opt-out as deletion.

The SDK may cache identifiers, session state, and unsent events on your device. The game does not actively erase the SDK database when you withdraw consent. If you later agree again, cached events created while consent was active may be submitted. The game does not retain custom gameplay events from periods without consent for later backfilling. Uninstalling the game may not remove all local SDK data.

Privacy correspondence is retained for as long as needed to handle the request and necessary follow-up, or as needed for disputes or legal obligations.

### 6. Your rights and contact

Depending on applicable law, you may have rights to access, correct, delete, restrict processing, obtain portable data, object to processing, and complain to a data protection authority. You can always withdraw consent for these optional analytics in the game.

Contact **[yuanotes@gmail.com](mailto:yuanotes@gmail.com)** to make a request. We may ask for necessary version, platform, or other relevant information to verify the request and locate records. Because analytics use random identifiers, an email address or SteamID alone may not identify those records. We will explain what information is needed and work with GameAnalytics as required by applicable law. Please do not post personal data in public GitHub issues.

If you have not reached the age at which you can independently consent to this processing under local law, do not enable analytics yourself. A parent or guardian can contact us with questions about children’s data or deletion requests. The game currently has no age-identification or parental-verification feature; its general consent button does not replace any additional authorization procedures required by law.

### 7. This policy website

GitHub Pages hosts this website. The page itself embeds no GameAnalytics, advertising, third-party fonts, or analytics scripts. GitHub processes network information needed to serve the page, such as IP addresses. See the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) for its practices.

### 8. Changes

We will update this notice and state its effective date when the game’s data practices change. Where renewed consent is required, we will request it before starting the relevant collection. The Chinese and English versions are intended to convey the same information. Please contact us if you notice a discrepancy.
