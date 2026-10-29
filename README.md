# 冒险行囊 · 电脑端 WowPocket

[English below](#adventurers-pouch--wowpocket-for-your-computer)

冒险行囊是《魔兽世界：无限》玩家自己做的手机伴侣 App：在手机上看你的角色面板、装备说明、天赋和副本掉落。它要配合电脑上的 **WowPocket** 用：WowPocket 找到你的游戏，装好记录角色的插件；你退出游戏后，它把角色传到你自己的 Google Drive 或坚果云（国内玩家用这个），手机再从那里取。

**非官方工具，与暴雪娱乐无关。** 《魔兽世界》是暴雪娱乐的商标。

手机上的冒险行囊不上 Google Play，安装包（APK）由作者直接发：国内玩家进 QQ 群 **1033497104**，海外玩家进 Discord 服务器 https://discord.gg/CPKjbhHGW4 。有问题、有想法也在这两处说。登录谷歌对所有谷歌账号开放。iPhone 上只有国内版：安装包（ipa）也在 QQ 群里，要用你自己的 Apple ID 签名后安装，步骤见 [iPhone 版安装教程](IPHONE.md)。

## 下载

在本页右边的 **Releases** 里下载最新的版本：

- Mac（Apple 芯片）：`WowPocket-版本号-macos-arm64.zip`
- Windows（64 位）：`WowPocket-版本号-windows-x64.zip`

安装包里附了 WowPocket 用到的开源软件的许可声明（`THIRD-PARTY-NOTICES.txt`）。

## 安装

**Mac**：解压，把 `WowPocket.app` 拖进“应用程序”文件夹。第一次打开时 macOS 会说“无法验证开发者”：在 WowPocket 上点右键选“打开”，或者到“系统设置 → 隐私与安全性”里点“仍要打开”。

**Windows**：解压到一个固定的文件夹（比如“文档”下面），双击 `WowPocket.exe`。第一次打开时 Windows 可能提示“Windows 已保护你的电脑”：点“更多信息”，再点“仍要运行”。

## 用法

1. 打开 WowPocket，它会找到游戏并装好插件。
2. 在 WowPocket 里登录谷歌账号，用和手机上一样的账号；国内玩家在“同步到”里选坚果云，填坚果云账号和应用密码。可以开“开机自动运行”，以后不用手动打开。
3. 进游戏玩一会儿再退出，WowPocket 会自己上传。
4. 在手机上打开冒险行囊，它会自己取；也可以在“切换”里点同步。

## 更新

0.14.0 起，在 WowPocket 窗口最下面的“关于”里点“检查更新”；有新版本就点“更新到 … 并重新打开”，WowPocket 会自己下载、核对、换上，再重新打开。Mac 上要先把 WowPocket 拖进“应用程序”、从那里打开：直接在“下载”里打开的那份，macOS 把它放在一个只读的临时位置运行，换不了。点了才会连 GitHub，GitHub 会看到你的 IP 地址和 WowPocket 的版本号。0.13.2 和更早的版本没有这个按钮，要像第一次那样从这里手动下载。

## 隐私

角色数据只存在你自己的 Google Drive 里只有这个应用能看的文件夹，或者你坚果云里的 WowPocket 文件夹，没有我们的服务器。详见[隐私政策](PRIVACY.md)。插件读游戏给插件的信息，不发消息、不替你操作；只有你在幻化师那里点它的“冒险行囊”按钮时，它才把手机上存的幻化方案写成一个叫“冒险行囊”的自定义套装、填进幻化窗口，生效（花金币）还是点游戏自己的保存按钮。

---

# Adventurer’s Pouch · WowPocket for your computer

Adventurer’s Pouch is a fan-made phone companion for World of Warcraft: Infinite: your character sheet, item descriptions, talents and dungeon drops on your phone. It works with **WowPocket** on your computer: WowPocket finds your game and installs the addon that records your characters; after you quit the game it uploads them to your own Google Drive or Jianguoyun (坚果云, for players in China), where the phone fetches them.

**Unofficial; not affiliated with Blizzard Entertainment.** World of Warcraft is a trademark of Blizzard Entertainment.

Adventurer’s Pouch is not on Google Play: its author hands out the APK directly, on the Discord server https://discord.gg/CPKjbhHGW4 (or in the QQ group **1033497104** for players in China). Ask questions and share ideas there too. Signing in to Google is open to every Google account. On the iPhone there is the version for China alone: its ipa is in the QQ group too, and you sign it with your own Apple ID to install it; see the [iPhone install guide](IPHONE.md) (in Chinese).

## Download

Get the latest version under **Releases** on the right of this page:

- Mac (Apple silicon): `WowPocket-version-macos-arm64.zip`
- Windows (64-bit): `WowPocket-version-windows-x64.zip`

Each package carries the licences and notices of the open-source software WowPocket uses (`THIRD-PARTY-NOTICES.txt`).

## Install

**Mac**: unzip and drag `WowPocket.app` into Applications. The first time, macOS says it cannot verify the developer: right-click WowPocket and choose Open, or click Open Anyway in System Settings → Privacy & Security.

**Windows**: unzip into a folder you keep (under Documents, say) and double-click `WowPocket.exe`. The first time, Windows may say it protected your PC: click More info, then Run anyway.

## Use

1. Open WowPocket: it finds the game and installs the addon.
2. Sign in to Google in WowPocket with the same account as on your phone (players in China pick Jianguoyun under Sync to and enter their Jianguoyun account and app password). Turn on starting at login so you never have to open it again.
3. Play a while and quit the game: WowPocket uploads by itself.
4. Open Adventurer’s Pouch on your phone: it fetches by itself, or sync under Switch.

## Updates

From 0.14.0, click Check for updates under About at the bottom of the WowPocket window; when there is a new version, click Update to … and reopen, and WowPocket downloads it, checks it, puts it in place and opens again. On a Mac, drag WowPocket into Applications first and open it from there: opened straight from Downloads, macOS runs it from a read-only temporary place where it cannot be replaced. GitHub is asked only when you click, and sees your IP address and the WowPocket version. Version 0.13.2 and earlier have no such button: download the new one here by hand, as the first time.

## Privacy

Your characters go only to a folder of your own Google Drive that only this app can see, or to the WowPocket folder of your Jianguoyun; there is no server of ours. See the [privacy policy](PRIVACY.md). The addon reads what the game gives addons, sends no messages and acts for you in nothing; only when you click its Adventurer's Pouch button at a transmogrifier does it write the outfit saved on your phone into a custom set named Adventurer's Pouch and fill it into the transmog window, and it is the game's own save button that applies it (for gold).
