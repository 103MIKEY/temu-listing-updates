# 上品工作台 · Windows 安装与更新

这是上品工作台的程序发布仓库，用于下载安装和自动更新。无需 GitHub 账号即可下载已发布附件。

## 首次安装

下载 [Windows 安装程序](https://github.com/103MIKEY/temu-listing-updates/releases/download/v5.2.1/TemuListing-5.2.1-Setup.exe)，运行后选择一个新目录。安装完成后配置自己的站斧浏览器和 API。

也可使用 [完整便携包](https://github.com/103MIKEY/temu-listing-updates/releases/download/v5.2.1/TemuListing-5.2.1-Windows.zip)，完整解压后运行其中的工作台 EXE。不要只移动主 EXE。

## 已有旧版

旧 v5 / 5.1.0 用户首次接入在线更新，可使用 [一次性升级包](https://github.com/103MIKEY/temu-listing-updates/releases/download/v5.2.1/TemuListing-5.2.1-Upgrade.zip)。先关闭工作台，在升级包里打开独立更新器，选择原来的完整工作台根目录和其中的 `5.2.1.tlu`，再安装。

未知旧版本或已修改的程序文件会停止升级，请向发布者核对，不要清空个人资料解决。

## 以后更新

工作台会检查新版本。点击左侧 **版本更新 → 下载并安装**，下载与签名校验通过后，程序会正常退出、安装更新并重新启动。

安装前结束上品任务、保存编辑内容并关闭 AI 标题窗口。网络失败时原程序可继续使用。升级只替换受管程序文件，商品资料、账号配置、API 设置、成功记录和断点保持原样；修改过的个人模板保留，官方新版另存更新历史目录。

发生中断时，打开安装目录中的 **更新器/上品工作台更新器.exe**，按提示恢复。恢复程序不会撤销已经发布的商品。

[查看所有发行版本](https://github.com/103MIKEY/temu-listing-updates/releases)。后续发行可能只提供更新包；首次安装器安装后可继续检查最新版本。

本仓库不存放发布者的账号、私钥或个人商品资料。分发包包含运行所需脚本和内置模板；公开下载不表示授予额外的源代码许可。更新包采用发布者签名校验，Windows 安装程序暂未使用 Authenticode 代码签名。

5.2.1 新增统一的工作台图标，已安装 5.2.0 的用户可直接在线更新。
