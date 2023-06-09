**English**

# OpenWrt-Actions

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/qxzzwh/OpenWrt-Actions/blob/main/LICENSE.txt)
![GitHub Stars](https://img.shields.io/github/stars/qxzzwh/OpenWrt-Actions.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/qxzzwh/OpenWrt-Actions.svg?style=flat-square&label=Forks&logo=github)

Build OpenWrt with GitHub Actions. The original code is from [P3TERX](https://github.com/P3TERX/Actions-OpenWrt). This code is for compiling OpenWrt and for my personal usage.
:warning:The sample configuration file included in this code is only for gateway service (bypass router mode) and has only one LAN port.

[OpenWrt Compilation Step-by-Step Command Explanation Tutorial](https://blog.ironegg.xyz/archives/openwrt-compilation-step-by-step-command-explanation-tutorial)

## Usage

- Fork this repository.
- Generate `.config` files using [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) source code. ( You can change it through environment variables in the workflow file. )
- Push `.config` file to the GitHub repository.
- Select `Build OpenWrt` on the Actions page.
- Click the `Run workflow` button.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.

## Tips

- It may take a long time to create a `.config` file and build the OpenWrt firmware. Thus, before create repository to build your own firmware, you may check out if others have already built it which meet your needs by simply [search `Actions-Openwrt` in GitHub](https://github.com/search?q=Actions-openwrt).
- Add some meta info of your built firmware (such as firmware architecture and installed packages) to your repository introduction, this will save others' time.

## Credits

- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [ActionsRML/delete-workflow-runs](https://github.com/ActionsRML/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)

## License

[MIT](https://github.com/qxzzwh/OpenWrt-Actions/blob/main/LICENSE.txt) © [**Coin**](https://blog.ironegg.xyz/)
