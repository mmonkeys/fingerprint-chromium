# fingerprint-chromium

*一个基于`Ungoogled Chromium`的指纹浏览器*

## 安装与使用

### 下载
请从以下链接下载适配您系统的版本，每个大版本的 Chromium 会编译一个对应的版本，选择适合的操作系统和版本进行下载：

| **版本**        | **源码**                                                                                   | **Windows**                                                                                   | **Linux**                                                                                   | **MacOS**     |
|------------------|--------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------| ---------------------------------------------------------------------------------------------|
| **Chrome 138**   | 跟随Chrome 139发布              | [安装包](https://github.com/adryfish/fingerprint-chromium/releases/download/138.0.7204.183/ungoogled-chromium_138.0.7204.183-1.1_installer_x64.exe) <br> [ZIP](https://github.com/adryfish/fingerprint-chromium/releases/download/138.0.7204.183/ungoogled-chromium_138.0.7204.183-1.1_windows_x64.zip) | [ 138.0.7204.183-1_linux.tar.xz ](https://github.com/adryfish/fingerprint-chromium/releases/download/138.0.7204.183/ungoogled-chromium_138.0.7204.183-1_linux.tar.xz) | [138.0.7204.183-1.1_macos.dmg](https://github.com/adryfish/fingerprint-chromium/releases/download/138.0.7204.183/ungoogled-chromium_138.0.7204.183-1.1_macos.dmg) |
| **Chrome 136**   | [136.0.7103.113](https://github.com/adryfish/fingerprint-chromium/tree/136.0.7103.113)              | [安装包](https://github.com/adryfish/fingerprint-chromium/releases/download/136.0.7103.113/ungoogled-chromium_136.0.7103.113-1.1_installer_x64.exe) <br> [ZIP](https://github.com/adryfish/fingerprint-chromium/releases/download/136.0.7103.113/ungoogled-chromium_136.0.7103.113-1.1_windows_x64.zip) | [ 136.0.7103.113-1_linux.tar.xz ](https://github.com/adryfish/fingerprint-chromium/releases/download/136.0.7103.113/ungoogled-chromium_136.0.7103.113-1_linux.tar.xz) | [136.0.7103.113-1.1_macos.dmg](https://github.com/adryfish/fingerprint-chromium/releases/download/136.0.7103.113/ungoogled-chromium_136.0.7103.113-1.1_macos.dmg) |
| **Chrome 135**   | [135.0.7049.95](https://github.com/adryfish/fingerprint-chromium/tree/135.0.7049.95)               | [安装包](https://github.com/adryfish/fingerprint-chromium/releases/download/135.0.7049.95/ungoogled-chromium_135.0.7049.95-1.1_installer_x64.exe) <br> [ZIP](https://github.com/adryfish/fingerprint-chromium/releases/download/135.0.7049.95/ungoogled-chromium_135.0.7049.95-1.1_windows_x64.zip) | [ 135.0.7049.95-1_linux.tar.xz ](https://github.com/adryfish/fingerprint-chromium/releases/download/135.0.7049.95/ungoogled-chromium_135.0.7049.95-1_linux.tar.xz) | [135.0.7049.95-1.1_macos.dmg](https://github.com/adryfish/fingerprint-chromium/releases/download/135.0.7049.95/ungoogled-chromium_135.0.7049.95-1.1_macos.dmg) |
| **Chrome 134**   | [134.0.6998.165](https://github.com/adryfish/fingerprint-chromium/tree/134.0.6998.165)               | [安装包](https://github.com/adryfish/fingerprint-chromium/releases/download/134.0.6998.165/ungoogled-chromium_134.0.6998.165-1.1_installer_x64.exe) <br> [ZIP](https://github.com/adryfish/fingerprint-chromium/releases/download/134.0.6998.165/ungoogled-chromium_134.0.6998.165-1.1_windows_x64.zip) | [ 134.0.6998.165-1_linux.tar.xz ](https://github.com/adryfish/fingerprint-chromium/releases/download/134.0.6998.165/ungoogled-chromium_134.0.6998.165-1_linux.tar.xz) |  |
| **Chrome 133**   | [133.0.6943.126](https://github.com/adryfish/fingerprint-chromium/tree/133.0.6943.126)               | [安装包](https://github.com/adryfish/fingerprint-chromium/releases/download/133.0.6943.126/ungoogled-chromium_133.0.6943.126-1.1_installer_x64.exe) <br> [ZIP](https://github.com/adryfish/fingerprint-chromium/releases/download/133.0.6943.126/ungoogled-chromium_133.0.6943.126-1.1_windows_x64.zip) | [ 133.0.6943.126-1_linux.tar.xz ](https://github.com/adryfish/fingerprint-chromium/releases/download/133.0.6943.126/ungoogled-chromium_133.0.6943.126-1_linux.tar.xz) |  |
| **Chrome 132**   | [132.0.6834.159](https://github.com/adryfish/fingerprint-chromium/tree/132.0.6834.159)               | [安装包](https://github.com/adryfish/fingerprint-chromium/releases/download/132.0.6834.159/ungoogled-chromium_132.0.6834.159-1.1_installer_x64.exe) <br> [ZIP](https://github.com/adryfish/fingerprint-chromium/releases/download/132.0.6834.159/ungoogled-chromium_132.0.6834.159-1.1_windows_x64.zip) | [ 132.0.6834.159-1_linux.tar.xz ](https://github.com/adryfish/fingerprint-chromium/releases/download/132.0.6834.159/ungoogled-chromium_132.0.6834.159-1_linux.tar.xz) | [132.0.6834.110-1.1_macos.dmg](https://github.com/adryfish/fingerprint-chromium/releases/download/132.0.6834.159/ungoogled-chromium_132.0.6834.110-1.1_macos.dmg) |

对于中国大陆用户，可以使用网盘下载

夸克网盘链接: https://pan.quark.cn/s/9bb65af874fb

---

在 GitHub Release 页面中，您可以找到每个大版本的 Chromium 对应的编译版本，选择合适的文件进行下载。

### 从源码构建

**源代码位于GitHub仓库的TAG中，而非main分支。**

为了维护这个免费开源项目的完整性，我们采用了延迟发布源代码的策略：

- **当前版本**：编译好的二进制文件立即向所有用户提供
- **源代码**：补丁文件将在下一个版本发布时公开（通常一个月后）

这种方法有助于防止不法分子打包出售牟利，同时保持开源。

一旦源代码发布，您可以参考[`ungoogled-chromium`](https://github.com/ungoogled-software/ungoogled-chromium/blob/master/docs/building.md)文档进行构建。只需将`ungoogled-chromium`子模块URL替换为`fingerprint-browser`仓库URL即可。


## 📢 广告

<div style="border: 2px solid #f39c12; padding: 15px; background-color: #fffbe6; border-radius: 10px;">

<details open>
<summary><b>🌟 推荐工具：EasyChat - Claude官网镜像</b></summary>

🔥 **EasyChat** 是一个无需注册和登录的 Claude 官网镜像，免费提供国内直登体验，1:1 还原官网功能，为你畅享高效的 AI 助手服务！

- 🚀 **免注册体验**：开箱即用，完整还原官网功能，点击即可开始使用。
- 🌐 **国内可访问**：无需科学上网，直连 Claude 官网服务。
- 🤝 **共享会员**：支持使用 Claude 会员账号，无需担心封号风险。

🔗 **访问网站**：[https://easychat.top](https://easychat.top)

</details>

</div>

<div style="border: 2px solid #3498db; padding: 15px; background-color: #e6f3ff; border-radius: 10px; margin-top: 15px;">

<details open>
<summary><b>🛠️ Flapcode</b></summary>

专为不便自建但需要使用 Claude Code 的用户打造的一站式解决方案。

**核心优势：**
- 🌐 **国内直连**：无需科学上网，即可极速访问 Claude Code 完整功能
- 🤝 **全站 Max 账号**：享受完整的模型体验，无需担心使用限制
- 💰 **计费简单透明**：采用与官方 API 相同的计费标准，每日更新使用额度
- 🔒 **安全可靠**：专业运维团队保障服务稳定性，让您专注于开发本身

🔗 **访问网站**：[https://flapcode.com](https://flapcode.com)

</details>

</div>


## 功能特性

### 指纹支持

可以使用 creepjs 和 browserleaks 来测试指纹修改效果。

* **User-Agent**：修改浏览器的 `navigator.userAgent`、`navigator.platform`、`navigator.userAgentData` 和 `Client Hints` 信息。
* **操作系统**
* **音频指纹**
* **插件**：133+版本去除后，浏览器会返回固定的插件列表。
* **CPU核心数**
* **内存**
* **WebGL 图像**
* **WebGL 元数据**：修改 GPU 供应商和显卡型号（暂时只支持 Linux）。
* **字体**
* **Canvas 图像**
* **Canvas 文本**
* **ClientRects**
* **WebRTC**
* **语言支持**
* **时区支持**

### 自动化支持
**优化了自动化使用场景，提供了以下特性：**

1. **封闭 Shadow DOM 的伪造支持**
  新增fakeShadowRoot属性，与shadowRoot属性相同，但是实现对Closed Shadow Root访问，方便自动化工具处理。

2. **避免 CDP 检测**
调用 Runtime.enable 时不会触发 CDP（Chrome DevTools Protocol）检测，进一步增强自动化的隐蔽性。

3. **Webdriver**
`navigator.webdriver`设定为false，避免自动化工具设置为true。

4. **Headless**
只是将`User-Agent`的`HeadlessChrome`的改成`Chrome`，其他Headless特征没有更改，谨慎使用。

### 启用指纹功能的命令行参数

在启动浏览器时，通过命令行参数启用或自定义指纹和隐私保护功能：

| **参数** | **描述** | **可用值/示例** |
|---------|---------|---------------|
| **`--fingerprint`** | 指定指纹种子(seed)，启用后大部分指纹功能生效 | 32位整数 |
| **`--fingerprint-platform`** | 指定操作系统类型 | `windows`, `linux`, `macos` |
| **`--fingerprint-platform-version`** | 指定操作系统版本 | 不填时使用默认版本 |
| **`--fingerprint-brand`** | 指定 `User-Agent` 和 `User-Agent Data` 中的浏览器品牌 | Chrome, Edge, Opera, Vivaldi (默认Chrome) |
| **`--fingerprint-brand-version`** | 指定品牌的版本号 | 不填时使用默认版本 |
| **`--fingerprint-hardware-concurrency`** | 指定 CPU 核心数 | 整数值（不提供时由指纹种子随机生成） |
| **`--disable-non-proxied-udp`** | 指定 WebRTC 策略，默认是禁用非代理 UDP 连接 | 建议保持默认设置 |
| **`--lang`** | 设置浏览器的语言 | 语言代码（如 `zh-CN`） |
| **`--accept-lang`** | 设置浏览器接受的语言 | 语言代码（如 `zh-CN,en-US`） |
| **`--timezone`** | 设置时区 | 时区（如`Asia/Shanghai`, `UTC`） |
| **`--proxy-server`** | 设置代理 | `http`, `socks`代理(不支持密码验证) |

### **新增的 User-Agent 自定义命令行参数**

Chrome 131 新增了两个用于进阶自定义 `User-Agent` 和 `User-Agent Data` 的命令行参数：

- **`--fingerprint-brand`**
  - 指定在 `User-Agent` 和 `User-Agent Data` 中使用的浏览器品牌。
  - 支持的值：`Chrome`，`Edge`，`Opera`，`Vivaldi`，或自定义品牌名称。

- **`--fingerprint-brand-version`**
  - 指定指定品牌的版本号。
  - 默认值：`Chrome`，`Edge`，`Opera`，`Vivaldi` 都提供默认版本，也可以传入自定义版本。

这些参数增强了浏览器环境模拟的能力，适合自动化和测试场景。如果没有指定 `--fingerprint-brand`，将使用默认品牌。

## 使用示例

以下是几个常见使用场景的命令行示例：

### 基本使用

```bash
./chrome --fingerprint=1000 --user-data-dir=/tmp/chromium/1000 --timezone="America/Los_Angeles" --proxy-server="你的代理服务器地址"
```

### 定制`User-Agent`

```bash
chrome.exe --fingerprint=2023 --fingerprint-platform=macos --fingerprint-platform-version="15.2.0" --fingerprint-brand="Edge"  --user-data-dir=%TEMP%\chromium
```

### 指纹测试

| 测试平台                                                                                            | 状态                                                      |
| -------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| [**CreepJS**](https://abrahamjuliot.github.io/creepjs/)                                            | ✔️ 51.5%。                          |
| [**BrowserScan**](https://browserscan.net/)                                                        | ✔️ 100%。通过所有检测。                 |
| [**BrowserLeaks**](https://browserleaks.com/)                                                      | ✔️ 支持多项指纹泄漏检测                                      |
| **Cloudflare**                                                                                     | ✔️                                                        |
| ‣ [Turnstile](https://nopecha.com/demo/turnstile)                                                  | ✔️                                                        |


## 用户交流

扫码加入QQ群与其他用户交流：

<img src="qqgroup.png" alt="QQ群二维码" width="300">

## Credits

 * [Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium)

 ## License

BSD-3-clause. See [LICENSE](LICENSE)