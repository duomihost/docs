# 🌐 Clash For Android 设置全局代理教程

### 1. 什么是分流/规则模式？

Clash for Windows 默认使用 **分流/规则模式**。\
分流模式的含义是：

* 大陆常见网站或应用 → 使用本地网络直连
* 国外网站或应用 → 使用代理服务器网络

{% hint style="success" %}
分流模式可以减少延迟、节省代理流量，但在某些情况下可能会导致部分应用或网页无法代理。
{% endhint %}

***

### 2. 什么是全局模式？

**全局模式** 表示：

* 所有流量均通过代理服务器转发

优点：

* 可以保持 **更高的匿名性**
* 确保所有应用均能正常代理

缺点：

* 访问大陆网站或应用时，可能会 **变慢**
* 占用更多代理带宽

{% hint style="warning" %}
建议：仅在需要高匿名性或遇到分流模式下无法访问的问题时，开启全局模式。
{% endhint %}

***

### 3. 开启全局代理模式

1. 打开 Clash for Android 主界面
2. 点击左侧菜单中的 **「代理（Proxy）」**

<figure><img src="../.gitbook/assets/{48680C17-0AB7-40AE-B074-088F8A4B4516}.png" alt=""><figcaption></figcaption></figure>

3. 在模式切换栏中选择 **「全局（Global）」**

<figure><img src="../.gitbook/assets/{025876D6-3848-4DD3-894E-B5728B756065}.png" alt=""><figcaption></figcaption></figure>

4. 从节点列表中选择你需要的代理节点

<figure><img src="../.gitbook/assets/{F75488C2-0F18-4BE4-8E1C-3233CB4A0809}.png" alt=""><figcaption></figcaption></figure>

5. 返回主页，确认连接成功后，即可实现全局代理

<figure><img src="../.gitbook/assets/{2A8DECBC-3F34-41E7-AB8E-DF49D3017464}.png" alt=""><figcaption></figcaption></figure>

***

### 4. 使用建议

* 建议日常使用 **分流/规则模式**，在需要时切换至 **全局模式**
* 如果全局模式下访问国内网站速度较慢，可以临时切回分流模式
* 切换模式后如遇异常，尝试重新连接或更新订阅

***

{% hint style="success" %}
现在，你已经成功学会如何在 **Clash for Android** 中设置全局代理模式。
{% endhint %}
