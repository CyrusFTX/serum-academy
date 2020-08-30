---
date: 2020-08-27T00:0:00+00:00
title: SOL钱包
weight: 1
---

## 创建您的SOL钱包和入金

Serum是建基于 [Solana公链](https://solana.com), 需要在Serum上交易的话，第一步是创建一个SOL钱包。我们建议使用 [Sollet.io](https://sollet.io)。

如果您是首次进入 [Sollet.io](https://sollet.io) 页面时就能创建新钱包。 创建新钱包时，您会获得seed words。请注意，务必将seed words保存在一个安全不会遗失的地方，它只会出现在首次创建钱包的时候，找回密码亦需要seed words验证。

![creat-wallet](/images/articles/serum-dex/sol-wallet/create-new-wallet.png?classes=shadow&width=25pc)

您将seed words保存在一个安全的地方后，您可以为您的 [Sollet.io](https://sollet.io) 钱包配置一组密码。虽然密码不是必需的，但因为安全理由，我们还是议您使用密码。

![password](/images/articles/serum-dex/sol-wallet/password.png?classes=shadow&width=25pc)

不论您是否设定了密码，您已经成功创建了您的SOL钱包。下一步就是将SOL转入到您创建的钱包中。SOL可以在 [币安](https://binance.com) 或 [FTX](https://ftx.com) 等交易所买到。

![balance](/images/articles/serum-dex/sol-wallet/balance.png?classes=shadow&width=50pc)

我们现在转一些SOL通证到刚创建的钱包。点击 **接收（Receive）** 后会出现弹窗，上面有您专属的SOL地址。您可以从交易所转入SOL通证到这地址。**该地址仅能接受SOL通证，请不要将其他SPL制式通证（例如SRM）转入到该地址**

![deposit-sol](/images/articles/serum-dex/sol-wallet/deposit-sol.png?classes=shadow&width=50pc)

成功将SOL通证转入钱包后，您可以在钱包创建其他SPL制式通证地址。点击页面右上角的 **+** 图示后会出现个弹窗，在弹窗内您可以选择添加主要通证（Popular Tokens）例如: **SRM**, **MSRM**, **FTT**, **BTC**, **ETH**, **LINK** **XRP**, **USDT** 。成功添加以后请获取这些SPL制式通证的入金地址（Deposit Address）。
请将USDC, USDT, XRP, LINK, YFI, FTT, ETH, BTC原生通证存入您的FTX账户钱包，并从FTX将USDC, USDT, XRP, LINK, YFI, FTT, ETH, BTC提取到sollet的对应SPL制式通证的入金地址。FTX会自动将这些通证转化为SPL制式通证。
当您需要把这些SPL制式通证转化回原生通证仅需将他们提取到FTX地址即可。

![add-token-popular](/images/articles/serum-dex/sol-wallet/add-token-popular.png?classes=shadow&width=25pc)

假设您需要转入 **SRM** 通证到钱包。您需要点击 **添加 (Add)**, 这样您就将SRM地址添加到您的钱包了。以下您能看到您的SOL通证地址和SRM通证地址。您可以使用这些地址来存入资金到您的 [Sollet.io](https://sollet.io) 钱包，或提取款项。

![srm-balance](/images/articles/serum-dex/sol-wallet/srm-balance.png?classes=shadow&width=50pc)

如果您想要添加其他通证到钱包，您可以手动添加，只需要输入该通证的 **铸币地址（Mint Address）** 即可。

![add-token-manual](/images/articles/serum-dex/sol-wallet/add-token-manual.png?classes=shadow&width=25pc).

现在我们已经成功入金至 [Sollet.io](https://sollet.io) 钱包。您已经准备好在Serum交易了！

{{% notice warning %}}
通证地址（Token Address）或 **铸币地址（Mint Address）** 是通证的 **合约地址** ，可以理解为通证的 **识别码** 。
{{% /notice %}}

{{% notice warning %}}
**入金地址（Deposit Address）** 用来存入通证的地址。
{{% /notice %}}
