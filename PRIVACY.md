# 隐私政策 · 冒险行囊与 WowPocket

[English below](#privacy-policy--adventurers-pouch-and-wowpocket)

生效日期：2026-10-18

冒险行囊（Adventurer’s Pouch）是个人开发者 BaronCyrus 做的《魔兽世界：无限》非官方手机伴侣 App。它要配合电脑上的 WowPocket 和 WowPocket 装进游戏的插件一起用。这份政策写的是这三样东西会碰到哪些数据、数据放在哪里、怎么删掉。

**简单说**：你的角色数据只存在三个地方：你自己的电脑、你自己的 Google Drive、你自己的手机。我们没有服务器，收不到也不保存你的任何数据。没有广告，也没有统计分析。

## 碰到哪些数据

**游戏角色的数据**：角色名、服务器名、等级、种族、职业、装备、属性、金币、天赋，以及装备的耐久和附魔。插件在游戏里读到这些，游戏把它们写进你电脑上的插件存档。WowPocket 把存档上传到你 Google Drive 里一个隐藏的文件夹（Google 叫它“应用数据文件夹”，只有这个应用能访问，你在云盘里看不到）。手机 App 再从那里下载到手机上，用来显示你的角色。插件只读游戏开放给插件的信息，游戏标成保密的数值不存也不传。

**谷歌账号的授权**：你在谷歌自己的页面上登录、点同意，我们碰不到你的密码。申请的权限只有一项：读写上面说的那个隐藏文件夹。你云盘里的其他文件，冒险行囊和 WowPocket 都看不到。
- 电脑上：谷歌给的授权凭据和你登录的账号邮箱，存在你电脑上 WowPocket 的数据文件夹里，只有你本人的系统账号能读。存邮箱是为了在窗口里告诉你登录的是哪个账号。
- 手机上：授权由手机上的 Google Play 服务管理，App 自己不保存。

**设置和天赋方案**：App 的语言、你在天赋模拟器里保存的方案，只存在手机上。

**打赏**：打赏走 Google Play 的结算，付款由谷歌处理，我们拿不到你的银行卡之类的付款信息。谷歌会在开发者后台给我们看订单记录，我们只拿它来对账、处理退款、回答你的问题。打不打赏，App 的功能都一样。

**崩溃统计**：如果你在手机上允许过把使用情况和诊断信息发给谷歌，Google Play 会把 App 的崩溃和卡顿统计汇总后给开发者看。我们只拿它来修问题。

## 不做的事

- 不把你的数据传到我们这里：我们没有服务器。
- 不出售、不出租、不分享你的数据。
- 不放广告，不做统计分析，不跟踪你在别的 App 或网站上的行为。
- 不拿你的数据训练任何人工智能模型。

## 从 Google API 拿到的数据

冒险行囊和 WowPocket 使用从 Google API 收到的信息、或把它转给其他应用时，遵守 [Google API 服务用户数据政策](https://developers.google.com/terms/api-services-user-data-policy)，包括其中的“有限使用”要求。我们只拿这些信息在你的设备上显示你自己的角色，不另作他用。

## 第三方

- **Google**：Google Drive 存你的角色数据，Google Play 服务负责授权，Google Play 负责结算。这些服务适用 [Google 隐私权政策](https://policies.google.com/privacy)。
- **GitHub**：在 App 里点“在手机上打开下载页”，会用浏览器打开 GitHub 上的电脑端下载页，那里适用 GitHub 的隐私声明。

## 保留和删除

- **手机**：卸载 App，手机上的数据就全部删掉了。
- **Google Drive**：打开网页版 Google Drive → 设置 → 管理应用 → 找到 WowPocket → 选项 → 删除隐藏的应用数据。
- **撤销授权**：在 [Google 账号的第三方关联](https://myaccount.google.com/connections) 里移除 WowPocket。撤销以后电脑和手机都取不到云盘里的数据了。
- **电脑**：在 WowPocket 窗口里点“退出登录”，授权凭据就删掉了。要删得一点不剩，删掉 WowPocket 的数据文件夹：Mac 上是 `~/Library/Application Support/WowPocket`，Windows 上是 `%APPDATA%\WowPocket`。
- **插件**：删掉游戏目录 `Interface/AddOns` 下的 `WowPocket` 文件夹。插件的存档是游戏 `WTF/Account/<你的账号>/SavedVariables` 下的 `WowPocket.lua`。

## 安全

和谷歌之间的通信全部走加密连接（HTTPS）。申请的权限只够碰那一个隐藏文件夹。授权凭据只存在你自己的设备上。

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

Effective: 18 October 2026

Adventurer’s Pouch is an unofficial companion app for World of Warcraft: Infinite, made by an individual developer, BaronCyrus. It works with WowPocket on your computer and the addon WowPocket installs in the game. This policy says what data these three touch, where that data is kept and how to delete it.

**In short**: your character data is kept in only three places: your own computer, your own Google Drive and your own phone. We have no server, so we neither receive nor keep any of your data. There are no ads and no analytics.

## What data they touch

**Your game characters**: character name, realm, level, race, class, equipment, stats, gold and talents, plus the durability and enchantments of your gear. The addon reads these in the game, and the game writes them to the addon’s saved file on your computer. WowPocket uploads that file to a hidden folder in your Google Drive. Google calls it the app data folder: only this app can reach it, and it does not show in your Drive. The phone app then downloads the file to your phone to show you your characters. The addon reads only what the game gives addons, and it neither keeps nor sends values the game marks as secret.

**Your Google sign-in**: you sign in and agree on Google’s own pages, so we never see your password. Only one permission is requested: to read and write that hidden folder. Adventurer’s Pouch and WowPocket cannot see any other file in your Drive.
- On your computer: Google’s sign-in token and your account’s email address are kept in WowPocket’s data folder on your computer, readable only by your own user account. The email address is kept so the window can show which account you are signed in with.
- On your phone: the sign-in is managed by Google Play services on the phone, and the app keeps none of it.

**Settings and talent plans**: the app’s language and the plans you save in the talent simulator are kept only on your phone.

**Tips**: tips go through Google Play billing. Google handles the payment, so we never see your card or other payment details. Google shows us order records in its developer console, and we use them only to balance accounts, handle refunds and answer your questions. The app works the same whether or not you tip.

**Crash reports**: if you have allowed your phone to share usage and diagnostics data with Google, Google Play shows developers combined statistics about app crashes and freezes. We use them only to fix problems.

## What they never do

- Send your data to us: we have no server.
- Sell, rent or share your data.
- Show ads, run analytics, or track what you do in other apps or on other websites.
- Use your data to train any AI model.

## Data from Google APIs

Adventurer’s Pouch’s and WowPocket’s use and transfer to any other app of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. That information is used only to show you your own characters on your own devices.

## Third parties

- **Google**: Google Drive keeps your character data, Google Play services handles the sign-in, and Google Play handles billing. The [Google Privacy Policy](https://policies.google.com/privacy) applies to these services.
- **GitHub**: “Open the download page” in the app opens the download page for the computer app on GitHub in your browser, where GitHub’s privacy statement applies.

## Keeping and deleting

- **Phone**: uninstalling the app deletes everything it kept on your phone.
- **Google Drive**: in Google Drive on the web, open Settings → Manage apps → WowPocket → Options → Delete hidden app data.
- **Withdrawing access**: remove WowPocket under [your Google Account’s third-party connections](https://myaccount.google.com/connections). After that, neither your computer nor your phone can reach the data in your Drive.
- **Computer**: Sign out in the WowPocket window deletes the sign-in token. To delete everything, delete WowPocket’s data folder: `~/Library/Application Support/WowPocket` on a Mac, `%APPDATA%\WowPocket` on Windows.
- **Addon**: delete the `WowPocket` folder under `Interface/AddOns` in your game folder. Its saved file is `WowPocket.lua` under `WTF/Account/<your account>/SavedVariables` in the game folder.

## Security

All traffic with Google goes over encrypted connections (HTTPS). The only permission requested reaches that one hidden folder and nothing else. The sign-in token is kept only on your own devices.

## Children

Adventurer’s Pouch is not directed at children under 13.

## Changes

If this policy changes, the new version goes on this page with a new effective date at the top.

## Contact

codiee.zane@gmail.com

## Not affiliated with Blizzard

Adventurer’s Pouch and WowPocket are unofficial tools, not affiliated with or endorsed by Blizzard Entertainment. World of Warcraft is a trademark of Blizzard Entertainment.
