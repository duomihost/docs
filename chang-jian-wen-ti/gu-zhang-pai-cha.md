# ⚙️ 故障排查

## 目录

[#kuai-su-pai-cha-qing-dan-jian-yi-yi-xu-jin-xing](gu-zhang-pai-cha.md#kuai-su-pai-cha-qing-dan-jian-yi-yi-xu-jin-xing "mention")

[#shou-ci-pei-zhi-xian-lu-bu-ke-yong](gu-zhang-pai-cha.md#shou-ci-pei-zhi-xian-lu-bu-ke-yong "mention")

[#jin-bu-fen-liu-lan-qi-wu-fa-zou-dai-li](gu-zhang-pai-cha.md#jin-bu-fen-liu-lan-qi-wu-fa-zou-dai-li "mention")

[#bu-fen-wang-zhan-wu-fa-fang-wen](gu-zhang-pai-cha.md#bu-fen-wang-zhan-wu-fa-fang-wen "mention")

[#reng-wei-jie-jue-ru-he-gao-xiao-fan-kui](gu-zhang-pai-cha.md#reng-wei-jie-jue-ru-he-gao-xiao-fan-kui "mention")

[#chang-jian-su-jie-fang-an-hui-zong](gu-zhang-pai-cha.md#chang-jian-su-jie-fang-an-hui-zong "mention")

{% hint style="success" %}
点击上方目录即可跳转
{% endhint %}

本页介绍本服务常见问题的**标准化排查流程**。人工客服也会按照此流程核查，因此建议您**先自行按步骤排查**，大多数问题都能快速解决。

{% hint style="warning" %}
排查前请先确认：

* 已关闭并退出其它代理/VPN 软件（避免冲突）
* 已关闭 360 等安全软件（容易拦截代理流量）
* 代理客户端为**最新版本**，订阅已**成功导入**
{% endhint %}

***

### 快速排查清单（建议依序进行）

* 重启软件/设备
* 切换网络（Wi-Fi ↔ 移动热点）
* 切换至全局模式测试
* 关闭冲突软件（360/插件/其它 VPN）
* 刷新或重新导入订阅
* 尝试更换客户端

***

### 首次配置 → 线路不可用

1. 对照配置教程逐步核查：\
   参考文档（示例）： [..](../ "mention")
2. 如确认无操作失误：
   * 尝试更换客户端（部分环境会冲突）

***

### 非首次使用 → 突然不可用

**1) 部分线路不可用**

* 在节点列表查看是否标记故障
* 临时切换其他节点

**2) 全部线路不可用**

* 检查套餐是否过期/流量是否耗尽
* 查看维护日志是否有说明
* 确认节点信息是否需更新订阅
* 本地操作：重启 → 关闭 360 → 刷新/重导订阅 → 卸载重装/换客户端

***

### 仅**部分浏览器**无法走代理

通常与浏览器的**代理/隐私扩展插件**有关：

* 使用**无痕模式**测试（禁用大部分插件）
* 更换**另一款浏览器**对比
* 若确认为某个插件导致，**关闭或卸载**该插件

{% hint style="warning" %}
常见冲突：内置“智能代理/翻墙/加速器”类插件
{% endhint %}

***

### **部分网站**无法访问

* 先在网站的**审计系统**中查看是否触发审计
* 如未触发，切换为**全局模式**测试是否为**自定义策略**导致

{% hint style="warning" %}
关于个性化策略问题，官方不提供技术支持。我们始终建议用户在**无特殊需求**时使用**全局模式**；不使用时完全关闭代理软件即可。
{% endhint %}

***

### 仍未解决？如何高效反馈

为缩短排障时间，请一次性提供以下信息给客服：

* 设备系统（例：Windows 11 / iOS 17）
* 客户端与版本号
* 具体问题表现（页面/应用/报错/时间）
* 订阅状态（最后更新时间、是否已刷新）
* 节点情况（节点名称、对比结果）
* 已完成的排查步骤
* 截图或短视频

{% hint style="info" %}
这些信息能帮助我们快速定位是**账号/节点/本地环境/客户端**哪一侧的问题，从而更快给出处理方案。
{% endhint %}

***

### 常见“速解”方案汇总

* **刷新订阅** → 等 10–30 秒 → 重启客户端
* 切换 **全局模式** 测试 → 若可用，说明是**策略/分流**问题
* 更换到**非高峰时段**或更换**不同国家**节点测试
* 切换网络（运营商/宽带 → 热点/5G，或反向）
* 关闭 360、安全管家、去广告/网络管控类软件
* 仍无解 → **换客户端** + 重新导入订阅

***

{% hint style="success" %}
按照以上步骤，绝大多数故障都能在**3–10 分钟**内自助解决；剩余少数场景也能快速向客服提供关键信息并定位问题。
{% endhint %}
