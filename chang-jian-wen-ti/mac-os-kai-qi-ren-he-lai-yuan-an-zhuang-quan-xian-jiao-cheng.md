# ⚙️ Mac OS 开启 「任何来源」 安装权限教程

{% hint style="success" %}
在 Mac OS 中，默认情况下仅允许从 **App Store** 或 **已认证开发者** 下载的应用安装。如果你需要安装来自第三方来源的应用（例如 Clash, 等），需要手动开启 **「任何来源」**。
{% endhint %}

### 1. 打开系统偏好设置

1. 点击屏幕左上角 **🍎 Apple 菜单**
2. 选择 **「系统偏好设置」**
3. 点击 **「安全性与隐私」**

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1).png" alt="" width="375"><figcaption></figcaption></figure>

### 2. 进入通用设置

1. 在「安全性与隐私」页面，切换到 **「通用」** 选项卡
2. 如果界面下方显示 **「任何来源」**，直接勾选即可

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1).png" alt="" width="375"><figcaption></figcaption></figure>

### 3. 如果未显示「任何来源」

在新版 Mac OS 中，「任何来源」选项可能被隐藏，需要通过终端命令开启。

<figure><img src="../.gitbook/assets/image (3) (1) (1).png" alt="" width="375"><figcaption></figcaption></figure>

#### 操作步骤

1. 打开 **终端（Terminal）**
2.  输入以下命令并按回车：

    ```bash
    sudo spctl --master-disable
    ```

<figure><img src="../.gitbook/assets/image (4) (1).png" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (5) (1).png" alt="" width="375"><figcaption></figcaption></figure>

{% hint style="danger" %}
如果不开启，可能无法正常安装
{% endhint %}
