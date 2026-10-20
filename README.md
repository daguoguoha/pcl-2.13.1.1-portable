# PCL 2.13.1.1 便携配置包

[下载便携配置包](./PCL-2.13.1.1-portable-no-auto-update.zip)



PCL 原作者为龙腾猫跃（[官方项目](https://github.com/Meloong-Git/PCL)，[赞助作者](https://meloong.com/afd/a/LTCat)）。

本包由第三方整理，包含未经修改的官方 2.13.1.1 主程序和关闭启动器自动更新的配置，不是官方新发布版本，也不是重新编译的修改版。

## 使用

1. 完整解压到单独文件夹，运行 `Plain Craft Launcher 2.exe`。
2. 在“版本选择”里添加已有 Minecraft 文件夹，或选择新目录。
3. 在“下载”页面选择 Minecraft、Forge / Fabric，或使用原有 CurseForge / Modrinth 模组下载。
4. 如需微软登录，请在官方微软页面自行完成。

`PCL/Setup.ini` 中的 `SystemSystemUpdate:3` 对应“关闭更新提示”，同时停止自动下载启动器更新。不要在设置里重新开启；手动检查更新功能未被删除。

若覆盖已有 PCL，请先退出启动器并备份主程序和 `PCL/Setup.ini`。已有设置应仅合并 `SystemSystemUpdate:3`，避免整份替换导致其他设置丢失。

## 来源与核验

- 官方来源：[2.14.0.0 标签内的“最新正式版.zip”](https://github.com/Meloong-Git/PCL/blob/2.14.0.0/最新正式版.zip)。该压缩包中的 EXE 文件版本为 2.13.1.1。
- 原压缩包 Git blob：`ece8652cc3c30a819db82e3c11ad0bf0a0264bfc`。
- EXE SHA-256：`30eb93c62fc51ede0898648e67455478a3d5a4f279938ae65aec77b84cb9703f`。
- 官方源代码：[Meloong-Git/PCL](https://github.com/Meloong-Git/PCL/tree/2.14.0.0)。原许可与使用指南见 `LICENCE`。

本包不含账号、令牌、注册表导出、个人路径、日志、游戏文件、存档或本机设置备份。关闭启动器自动更新不影响 Minecraft 版本列表的联网刷新。

已核验官方来源、EXE 哈希、主程序版本和关闭更新配置；尚未完成所有游戏版本及加载器的实际下载安装和启动测试。
