# xrevive

### [**English**](../README.md) · [**Deutsch**](README.de.md) · [**Français**](README.fr.md) · [**Español**](README.es.md) · [**Italiano**](README.it.md) · [**Português (Brasil)**](README.pt-BR.md) · [**Русский**](README.ru.md) · [**العربية**](README.ar.md) · [**日本語**](README.ja.md) · **简体中文**

一款用于运行经 [Xrecomp](https://github.com/Teraflopping/Xrecomp) 重编译的初代 Xbox 游戏的桌面启动器，并提供来自 Xbox Live 复兴项目 [xb.live](https://xb.live) 的在线服务。

## 下载

[下载 Windows x64 版](https://github.com/Teraflopping/xrevive/releases/latest) · [下载 Linux 版（AppImage）](https://github.com/Teraflopping/xrevive/releases/latest) · [所有安装包与更新说明](https://github.com/Teraflopping/xrevive/releases/latest)

目前托管的游戏可执行文件仅支持 **Windows x64**。在 Linux 上可通过 Wine 或 Proton 运行（实验性）。macOS 安装包尚无法游玩。

## 功能

- 添加你自己的 ISO 或已解压的游戏文件夹，然后下载对应的可执行文件。有 Release 版本时优先使用 Release；安装 Beta 或 Alpha 版本前会先询问。支持游戏的免区、媒体补丁、重命名或重新签名的镜像同样可以识别。从 Beta 或 Alpha 安装的游戏，在有适用于你这份游戏的 Release 版本后，会通过更新切换到 Release。
- 安装前即可浏览任意 Release、Beta 或 Alpha 游戏：动态、更新、排行榜、成就、附加内容以及实时玩家与大厅数量，页面上直接提供 **INSTALL** 按钮。
- 自动检查游戏与启动器更新。游戏更新会删除被替换的旧可执行文件；游戏从就近的服务器下载，断线后可续传。
- 使用 xb.live 登录（目前从 Midnight Club 3 在线开始），通过玩家代号添加好友，查看在线大厅、社区活动和 XB Online 公告。xb.live 无法连接时，游戏仍可离线启动。
- 管理已安装的游戏：启动、浏览本地文件、卸载，以及 DLC/Addons 页，每个模组都有开/关开关并显示作者署名。**▶ PLAY** 会以已开启的模组启动游戏，游戏更新后附加内容依然可用。
- 每个游戏页面上的 Saves 页支持备份、还原、导入、**移动…**到你选择的文件夹、PS2 存档转换（无需 Xbox 档案），以及 Midnight Club 3 和 NINJA GAIDEN Black 存档编辑器。
- 可从 xemu 导入存档，即使是其他主机签名的存档也可以：NINJA GAIDEN Black 等已知格式的存档会为这台电脑重新签名，并标记为未验证。
- 自定义音轨：在音乐页面创建音轨，并添加 MP3、FLAC、Ogg、WAV、M4A 或 AAC 歌曲，所有支持的游戏都会播放（Midnight Club 3 从 1.0.7 更新起）。
- 来自 XB Online 的标题更新和 DLC 会在游戏关闭时自动安装，每个游戏的 Add-ons 列表会显示其标题更新和开关。联机游戏需要标题更新：如果缺失或已关闭，点击 Play 时会询问是下载（或重新开启）它，还是这次离线游玩。
- 在 XB Online 商店中有 DLC 的游戏，会在 DLC/Addons 页列出并提供下载和移除，游戏下次启动时即可找到。
- 在游戏菜单中进行单独设置：全屏、分辨率、垂直同步、宽高比、亮度、对比度、饱和度、抗锯齿、FPS 上限，以及 DirectX 12、DirectX 11 或 Vulkan。Midnight Club 3 还有自己的语言列表，包括葡萄牙语、俄语和阿拉伯语翻译 addon。
- 记录每个游戏的游玩时间，游戏 EXE 在更新后保持同一名称，NVIDIA 控制面板的配置文件会继续生效。
- 可在设置中选择关闭窗口时让 xrevive 留在托盘中还是直接退出。重启进入标题更新的游戏仍会显示为正在游玩，游玩时间和在线会话也会延续。
- 设置 > 光盘检查器可读取光盘镜像的标题、标题 ID、版本和区域，并复制一份可直接粘贴到错误报告中的报告。
- 着色器缓存随游戏保留，只有首次启动时需要编译着色器。
- 清晰的错误提示，说明问题原因及解决方法；当“受控文件夹访问”阻止安装时，提供 **Allow xrevive in Windows Security** 按钮。
- 可在 设置 > 语言 中从 10 种语言中选择：英语、德语、法语、西班牙语、意大利语、巴西葡萄牙语、俄语、阿拉伯语、日语和简体中文。阿拉伯语下整个窗口从右到左显示。
- 将已安装游戏添加到 Steam（设置或库），支持封面与 Deck 上的 Steam Input。
- 自定义游戏外观：右键点击游戏并打开“管理”，即可选择自己的横幅和图标（PNG 或 JPEG）。不自定义时，游戏列表会显示每个游戏 default.xbe 中的存档图标，添加到 Steam 也会使用相同的图片。
- 系统检查：Windows 8.1+ 与 Direct3D 11，仍可选择继续游玩。
- 按下 Play 时，旧 `XBL-Hosted` 文件夹中的 XB Online 存档会复制到各游戏的常规存档文件夹。不会覆盖已有存档，也不会删除任何文件；确认存档无误后，可自行删除 `SaveData\XBL-Hosted`。

## 游戏需自备

xrevive 不包含任何游戏 ISO 或游戏资源，请使用你自己的游戏文件。此版本会下载已发布的可执行文件，而不是在本地编译游戏；暂无可执行文件的游戏可以先解压，以备日后使用。

Windows 启动器与安装程序已进行 Authenticode 签名。启动器更新使用 xrevive 更新密钥签名。macOS 安装包未经过公证，因此首次安装时可能会出现安全提示。

---

xrevive 是一个粉丝项目，与 Microsoft 无关联，也未获得其认可。
