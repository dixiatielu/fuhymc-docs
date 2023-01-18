# 基岩版与Java版账号信息互通

## 先决条件
- Minecraft基岩版正版
- Minecraft Java版（PC版）正版
要实现账号信息互通，您需要事先从Google Play（适用于Android手机）或App Store（适用于iOS设备）购买国际版正版Minecraft。若您尚未获取正版基岩版Minecraft，请自行在网上查阅购买、获取方法。此外，您也需要获取一个适用于PC的Java版Minecraft的正版账户。（可以从minecraft.net购买）。
- 已注册LittleSkin账号
- 首次在PC上登入FuHyMC时使用LittleSkin账号登陆，而非直接通过正版账户登陆。

## 账号互通实现方法
### 在LittleSkin绑定您的Java版正版账户
登入LittleSkin官网，在登入后主页右下角的`正版绑定`板块按提示绑定您拥有Minecraft的微软账户。

### 基岩版账户与Java账户在Geyser统一验证服务器的链接
在您的PC上以任意启动器通过微软**正版账户**启动Mincraft Java版。选择`多人游戏`，然后进入Geyser Floodgate Java版统一验证服务器`link.geysermc.org:25565`

> Geyser是将Java版服务器数据包“翻译”为基岩版数据包的一个开源插件，其本身及其统一验证服务器均不由FuHyMC开发或运营，FuHyMC仅为其使用者之一。

同时，在您的移动设备（或其他使用Minecraft Bedrock版的设备）上启动Minecraft基岩版。并在`游戏->服务器`中选择`添加服务器`，在`服务器地址`处填写`link.geysermc.org`，`端口`处填写`19132`，`服务器名称`可任意填写。完成后点击`游戏`登入到服务器。

1. 通过在您的Java版游戏**或**基岩版游戏上键入 `/linkaccount` 来开始账户链接过程
2. 您将收到一条消息，其中包含一个随机数，您必须在未启动链接过程的帐户中输入该随机数。
3. 通过键入 `/linkaccount <code>` 在另一个帐户上输入随机数
4. 您应该会在您的 Bedrock 和 Java 帐户上被服务器踢出，并显示已成功链接您的帐户的消息。
5. 关闭游戏窗口
6. 大功告成，您可以继续进行下面的步骤。
7. 以后您如需取消链接您的全局链接帐户，请在 Java 或 Bedrock 上重新加入Geyser统一验证服务器（如上所述进行链接），并使用 /unlinkaccount 命令。

### 登入账号

回到您所使用的启动器，将使用正版账号登陆改为**使用LittleSkin登陆**。确保此LittleSkin账户是绑定了您正版账户的账户。

!> 在PC上登入账号时，请确保您通过LittleSkin登陆而非通过正版登陆直接登陆服务器，以免造成不必要的麻烦。

在多人游戏中登入FuHyMC服务器。

退出Java版游戏，在基岩版游戏上登陆FuHyMC基岩版地址：`entrance.fuhymc.cn`，端口`19132`。

您现在应该能在基岩版账户上与Java版共享您账号的背包、位置、皮肤等信息了，玩的开心！

!> 如果您遇到任何问题，请加入我们的QQ群：`1079084078`询问，群友们可为您提供力所能及的帮助。在提问之前请保证您完整、仔细阅读本文档。