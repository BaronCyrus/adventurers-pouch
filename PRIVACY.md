# 隐私政策 · 冒险行囊与 WowPocket

[English below](#privacy-policy--adventurers-pouch-and-wowpocket)

生效日期：2026-10-22

冒险行囊（Adventurer’s Pouch）是个人开发者 BaronCyrus 做的《魔兽世界：无限》非官方手机伴侣 App。它要配合电脑上的 WowPocket 和 WowPocket 装进游戏的插件一起用。这份政策写的是这三样东西会碰到哪些数据、数据放在哪里、怎么删掉。

冒险行囊不在 Google Play 上，安装包（APK）由作者直接发，有两个版本：海外版经你自己的 Google Drive 把角色数据传到手机，国内版经你自己的坚果云传。电脑上的 WowPocket 两种都能用，你选哪个就用哪个。

**简单说**：你的角色数据只存在四个地方：你自己的电脑、你自己的 Google Drive 或坚果云、你自己的手机。我们没有服务器，收不到也不保存你的任何数据。没有广告，也没有统计分析。

## 碰到哪些数据

**游戏角色的数据**：角色名、服务器名、等级、种族、职业、装备、属性、金币、天赋，以及装备的耐久和附魔。插件在游戏里读到这些，游戏把它们写进你电脑上的插件存档。WowPocket 把存档上传到你选的地方：
- Google Drive：放在一个隐藏的文件夹里。Google 叫它“应用数据文件夹”，只有这个应用能访问，你在云盘里看不到。
- 坚果云：放在 WowPocket 文件夹里，你在坚果云里看得见。

手机 App 再从那里下载到手机上，用来显示你的角色。插件只读游戏开放给插件的信息，游戏标成保密的数值不存也不传。

**谷歌账号的授权**（用 Google Drive 时）：你在谷歌自己的页面上登录、点同意，我们碰不到你的密码。申请的权限只有一项：读写上面说的那个隐藏文件夹。你云盘里的其他文件，冒险行囊和 WowPocket 都看不到。
- 电脑上：谷歌给的授权凭据和你登录的账号邮箱，存在你电脑上 WowPocket 的数据文件夹里，只有你本人的系统账号能读。存邮箱是为了在窗口里告诉你登录的是哪个账号。
- 手机上：授权由手机上的 Google Play 服务管理，App 自己不保存。

**坚果云的账号和应用密码**（用坚果云时）：应用密码是你在坚果云的“第三方应用管理”里自己生成的，不是你的登录密码。按坚果云的说法，应用密码能碰到你整个坚果云；WowPocket 只读写其中的 WowPocket 文件夹，手机 App 读它，只往里写幻化方案那一个文件，别的文件都不碰。
- 电脑上：坚果云账号和应用密码存在 WowPocket 数据文件夹里单独的一个文件里，只有你本人的系统账号能读。
- 手机上：存在 App 自己的存储里，别的 App 读不到；设置里只显示账号，不再显示应用密码。

**设置和天赋方案**：App 的语言、你在天赋模拟器里保存的方案，只存在手机上。

**幻化方案**：你在 App 幻化页保存的方案（哪个角色，每个部位换成哪种外观的编号，什么时候存的）存在手机上，同时写进你选的地方：Google Drive 里上面说的那个隐藏文件夹，或坚果云的 WowPocket 文件夹，文件叫 `wp-plans.json`。电脑上的 WowPocket 把它取下来，写进游戏里插件的文件夹；你在游戏的幻化师那里点插件的按钮，它才填进游戏的幻化窗口。

**打赏**：打不打赏，App 的功能都一样。
- 国内版：用微信或支付宝扫作者的码，付款在微信或支付宝里完成，冒险行囊不经手。微信、支付宝会按它们自己的规矩告诉作者谁付了多少（比如微信昵称）。
- 海外版：可以点“在 Ko-fi 上打赏”，用手机浏览器打开作者的 Ko-fi 页面，付款在 Ko-fi 那里完成；也可以扫作者的微信、支付宝码，同上。冒险行囊不经手。

## 不做的事

- 不把你的数据传到我们这里：我们没有服务器。
- 不出售、不出租、不分享你的数据。
- 不放广告，不做统计分析，不跟踪你在别的 App 或网站上的行为。
- 不拿你的数据训练任何人工智能模型。

## 从 Google API 拿到的数据

冒险行囊和 WowPocket 使用从 Google API 收到的信息、或把它转给其他应用时，遵守 [Google API 服务用户数据政策](https://developers.google.com/terms/api-services-user-data-policy)，包括其中的“有限使用”要求。我们只拿这些信息在你的设备上显示你自己的角色、把你在手机上存的幻化方案带到你电脑上的游戏里，不另作他用。

## 第三方

- **Google**：用 Google Drive 时，Google Drive 存你的角色数据，Google Play 服务负责授权。这些服务适用 [Google 隐私权政策](https://policies.google.com/privacy)。
- **坚果云**：用坚果云时，你的坚果云存你的角色数据，适用坚果云的隐私政策。
- **微信、支付宝**：国内版和海外版扫码的打赏在它们那里完成，适用它们各自的隐私政策。
- **Ko-fi**：海外版在 Ko-fi 上的打赏在那里完成，适用 Ko-fi 的隐私政策。
- **GitHub**：在 App 里点“在手机上打开下载页”或“隐私政策”，会用浏览器打开 GitHub 上的页面，那里适用 GitHub 的隐私声明。在 WowPocket 窗口里点“检查更新”，WowPocket 会连 GitHub（api.github.com 和它放下载文件的服务器）查最新的版本号，你点了更新才下载新版本的安装包；GitHub 会看到你的 IP 地址、WowPocket 的版本号和下载的是哪个系统的安装包，适用 GitHub 的隐私声明。不点就不连。
- **Discord**：在 App 设置里点“在 Discord 上反馈问题和建议”，或在 WowPocket 窗口里点“在 Discord 上反馈”，会用浏览器打开冒险行囊的 Discord 服务器（国内版没有）。冒险行囊和 WowPocket 自己不连 Discord。你在服务器里发的内容和你的 Discord 用户名由 Discord 保管，服务器里的人都看得到，适用 Discord 的隐私政策；我们只拿它来回答问题、改进 App。
- **QQ**：国内版的设置里和 WowPocket 窗口里写着冒险行囊的 QQ 群号，点了只是把群号复制到剪贴板，冒险行囊和 WowPocket 自己不连 QQ。你在群里发的内容和你的 QQ 资料由腾讯保管，群里的人都看得到，适用 QQ 的隐私政策；我们只拿它来回答问题、改进 App。

## 保留和删除

- **手机**：卸载 App，手机上的数据就全部删掉了。国内版还可以在设置的“坚果云”里点“不用坚果云了”，只删掉手机上的应用密码。
- **Google Drive**：打开网页版 Google Drive → 设置 → 管理应用 → 找到 WowPocket → 选项 → 删除隐藏的应用数据（角色数据和幻化方案都在里面）。
- **撤销谷歌授权**：在 [Google 账号的第三方关联](https://myaccount.google.com/connections) 里移除 WowPocket。撤销以后电脑和手机都取不到云盘里的数据了。
- **坚果云**：删掉坚果云里的 WowPocket 文件夹；只想删幻化方案的话，删其中的 `wp-plans.json`。要让应用密码失效，在坚果云的“第三方应用管理”里把它删掉。
- **电脑**：在 WowPocket 窗口里点“退出登录”或“断开坚果云”，保存的授权凭据或应用密码就删掉了。要删得一点不剩，删掉 WowPocket 的数据文件夹：Mac 上是 `~/Library/Application Support/WowPocket`，Windows 上是 `%APPDATA%\WowPocket`。
- **插件**：删掉游戏目录 `Interface/AddOns` 下的 `WowPocket` 文件夹。插件的存档是游戏 `WTF/Account/<你的账号>/SavedVariables` 下的 `WowPocket.lua`。

## 安全

和谷歌、坚果云之间的通信全部走加密连接（HTTPS）。谷歌那边申请的权限只够碰那一个隐藏文件夹；坚果云的应用密码按坚果云的说法能碰整个坚果云，所以我们只在你自己的设备上存它，用完可以随时作废。授权凭据和应用密码只存在你自己的设备上。

## 儿童

冒险行囊不面向 13 岁以下的儿童。

## 修改

这份政策改了的话，新版本会放在这个页面上，并更新顶部的生效日期。

## 联系

codiee.zane@gmail.com

## 与暴雪无关

冒险行囊和 WowPocket 是非官方工具，与暴雪娱乐无关，也没有得到暴雪娱乐的认可。《魔兽世界》是暴雪娱乐的商标。

---

# Privacy policy · Adventurer’s Pouch and WowPocket

Effective: 22 October 2026

Adventurer’s Pouch is an unofficial companion app for World of Warcraft: Infinite, made by an individual developer, BaronCyrus. It works with WowPocket on your computer and the addon WowPocket installs in the game. This policy says what data these three touch, where that data is kept and how to delete it.

Adventurer’s Pouch is not on Google Play: its author hands out the APK directly, in two versions. The international version carries your character data to the phone through your own Google Drive; the version for China carries it through your own Jianguoyun (坚果云). WowPocket on your computer works with either; you pick one.

**In short**: your character data is kept in only four places: your own computer, your own Google Drive or Jianguoyun, and your own phone. We have no server, so we neither receive nor keep any of your data. There are no ads and no analytics.

## What data they touch

**Your game characters**: character name, realm, level, race, class, equipment, stats, gold and talents, plus the durability and enchantments of your gear. The addon reads these in the game, and the game writes them to the addon’s saved file on your computer. WowPocket uploads that file to the place you picked:
- Google Drive: a hidden folder. Google calls it the app data folder: only this app can reach it, and it does not show in your Drive.
- Jianguoyun: the WowPocket folder, which you see among your files there.

The phone app then downloads the file to your phone to show you your characters. The addon reads only what the game gives addons, and it neither keeps nor sends values the game marks as secret.

**Your Google sign-in** (with Google Drive): you sign in and agree on Google’s own pages, so we never see your password. Only one permission is requested: to read and write that hidden folder. Adventurer’s Pouch and WowPocket cannot see any other file in your Drive.
- On your computer: Google’s sign-in token and your account’s email address are kept in WowPocket’s data folder on your computer, readable only by your own user account. The email address is kept so the window can show which account you are signed in with.
- On your phone: the sign-in is managed by Google Play services on the phone, and the app keeps none of it.

**Your Jianguoyun account and app password** (with Jianguoyun): the app password is one you make yourself under Third-party App Management in Jianguoyun; it is not your login password. As Jianguoyun puts it, an app password reaches your whole Jianguoyun; WowPocket reads and writes only its WowPocket folder there, and the phone app reads it and writes only the one file of transmog outfits into it.
- On your computer: the account and app password are kept in a file of their own in WowPocket’s data folder, readable only by your own user account.
- On your phone: they are kept in the app’s own storage, which other apps cannot read; the settings show the account but never the app password again.

**Settings and talent plans**: the app’s language and the plans you save in the talent simulator are kept only on your phone.

**Transmog outfits**: the outfits you save on the app’s Transmog page (which character, the appearance number for each slot, when it was saved) are kept on your phone and written to the place you picked as well: the hidden folder of your Google Drive described above, or the WowPocket folder of your Jianguoyun, in a file named `wp-plans.json`. WowPocket on your computer fetches it and writes it into the addon’s folder in the game; only when you press the addon’s button at a transmogrifier does it fill the outfit into the game’s transmog window.

**Tips**: the app works the same whether or not you tip.
- Version for China: you scan the author’s code with WeChat or Alipay, and the payment is made in WeChat or Alipay, never through the app. WeChat and Alipay tell the author who paid how much (a WeChat nickname, say) under their own rules.
- International version: you can tap “Tip on Ko-fi” to open the author’s Ko-fi page in your phone’s browser and pay there, or scan the author’s WeChat or Alipay code as above; the app never handles the payment.

## What they never do

- Send your data to us: we have no server.
- Sell, rent or share your data.
- Show ads, run analytics, or track what you do in other apps or on other websites.
- Use your data to train any AI model.

## Data from Google APIs

Adventurer’s Pouch’s and WowPocket’s use and transfer to any other app of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. That information is used only to show you your own characters on your own devices and to carry the transmog outfits you save on your phone to the game on your computer.

## Third parties

- **Google**: with Google Drive, Google Drive keeps your character data and Google Play services handles the sign-in. The [Google Privacy Policy](https://policies.google.com/privacy) applies to these services.
- **Jianguoyun**: with Jianguoyun, your Jianguoyun keeps your character data, and Jianguoyun’s privacy policy applies.
- **WeChat, Alipay**: tips scanned in the version for China or the international version are made in them, and their own privacy policies apply.
- **Ko-fi**: tips on Ko-fi from the international version are made there, and Ko-fi’s privacy policy applies.
- **GitHub**: “Open the download page” or “Privacy policy” in the app opens a page on GitHub in your browser, where GitHub’s privacy statement applies. “Check for updates” in the WowPocket window has WowPocket ask GitHub (api.github.com and the servers its downloads come from) for the latest version, and download the new version’s package only when you choose to update; GitHub sees your IP address, the WowPocket version and which system’s package is downloaded, and GitHub’s privacy statement applies. Nothing is asked unless you press it.
- **Discord**: “Send feedback on Discord” in the app’s settings, or “Feedback on Discord” in the WowPocket window, opens the Adventurer’s Pouch Discord server in your browser (not in the version for China). Adventurer’s Pouch and WowPocket do not connect to Discord themselves. What you post there and your Discord username are kept by Discord and seen by the people on the server, and Discord’s privacy policy applies; we use them only to answer you and improve the app.
- **QQ**: the settings of the version for China and the WowPocket window show the Adventurer’s Pouch QQ group’s number; tapping it only copies the number to your clipboard, and Adventurer’s Pouch and WowPocket do not connect to QQ themselves. What you post in the group and your QQ profile are kept by Tencent and seen by the people in the group, and QQ’s privacy policy applies; we use them only to answer you and improve the app.

## Keeping and deleting

- **Phone**: uninstalling the app deletes everything it kept on your phone. In the version for China, “Stop using Jianguoyun” under Jianguoyun in the settings deletes just the app password on the phone.
- **Google Drive**: in Google Drive on the web, open Settings → Manage apps → WowPocket → Options → Delete hidden app data (your character data and your transmog outfits are both in it).
- **Withdrawing Google access**: remove WowPocket under [your Google Account’s third-party connections](https://myaccount.google.com/connections). After that, neither your computer nor your phone can reach the data in your Drive.
- **Jianguoyun**: delete the WowPocket folder in your Jianguoyun; to delete just the transmog outfits, delete `wp-plans.json` in it. To make an app password stop working, delete it under Third-party App Management in Jianguoyun.
- **Computer**: Sign out or Disconnect Jianguoyun in the WowPocket window deletes the kept sign-in token or app password. To delete everything, delete WowPocket’s data folder: `~/Library/Application Support/WowPocket` on a Mac, `%APPDATA%\WowPocket` on Windows.
- **Addon**: delete the `WowPocket` folder under `Interface/AddOns` in your game folder. Its saved file is `WowPocket.lua` under `WTF/Account/<your account>/SavedVariables` in the game folder.

## Security

All traffic with Google and Jianguoyun goes over encrypted connections (HTTPS). The Google permission requested reaches that one hidden folder and nothing else; a Jianguoyun app password reaches your whole Jianguoyun, as Jianguoyun puts it, so it is kept only on your own devices and can be revoked at any time. Sign-in tokens and app passwords are kept only on your own devices.

## Children

Adventurer’s Pouch is not directed at children under 13.

## Changes

If this policy changes, the new version goes on this page with a new effective date at the top.

## Contact

codiee.zane@gmail.com

## Not affiliated with Blizzard

Adventurer’s Pouch and WowPocket are unofficial tools, not affiliated with or endorsed by Blizzard Entertainment. World of Warcraft is a trademark of Blizzard Entertainment.
