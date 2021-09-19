**English** | [中文](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

# Actions-OpenWrt

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/jackmoo1/Lean-BY-X86/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/jackmoo1/Lean-BY-X86.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/jackmoo1/Lean-BY-X86.svg?style=flat-square&label=Forks&logo=github)

## 此仓库来自于[**P3TERX**](https://p3terx.com)大佬


## 注意：开启ssh连接会出现错误，所以请提前本地make menuconfig，把生成的.config文件上传到仓库的根目录后，再进行运行自动话脚本，在run workflow时ssh连接选项选择false



## 用法

- 单击 `Use this template`按钮以创建新存储库
-  `.config` 文件是使用 [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) 的源代码创建的. ( 您可以通过工作流'workflow'文件中的环境变量进行更改 )
- 将 '.config' 文件推送到 GitHub 存储库根目录。
- 在Action页面上选择选择 `Build OpenWrt` 。
- 单击 `Run workflow` 按钮。ssh连接选择false
- 构建完成后，单击Artifacts操作页面右上角的按钮下载二进制文件。

## 提示

- 创建.config文件和构建 OpenWrt 固件可能需要很长时间。
- 在创建存储库以构建您自己的固件之前，您可以通过简单地在 GitHub 中搜索Actions-Openwrt来查看其他人是否已经构建了满足您需求的.config文件

## 内容

- 软件源为lean默认外加[**kenzok**](https://github.com/kenzok8/openwrt-packages)大佬的软件库和依赖
- openwrt 固件包含以下主要软件
- luci-app-vssr            ------------------vssr老竭力
- luci-app-dnsfilter       ------------------基于DNS的广告过滤
- luci-app-openclash       ------------------openclash图形         
- luci-app-adguardhome     ------------------去广告 
- luci-app-passwall        ------------------Lienol大神 
- luci-theme-argon_new     ------------------二合蓝 紫主题
- luci-app-ssr-plus        ------------------Lean大神 


## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © [**P3TERX**](https://p3terx.com)
