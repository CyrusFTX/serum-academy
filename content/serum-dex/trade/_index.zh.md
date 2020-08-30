---
date: 2020-08-27T00:0:00+00:00
title: 交易
weight: 3
---

## 交易

当您成功连接您的SOL钱包后就可以进行交易。整个交易体验和在中央化交易所进行交易是一样的，用户介面也是相同。

举例说，我们要以3.1QUOTE价格购买88个BASE通证，确保输入正确数量和价格后，请在 [Sollet.io](https://sollet.io) 弹窗同意这笔交易请求。

![order form](/images/articles/serum-dex/trade/order-form.png?classes=shadow&width=30pc)

![approve-transaction](/images/articles/serum-dex/trade/approve-transaction.png?classes=shadow&width=40pc)

现在您可以在订单簿以及当前委托看到您的限价单。

![order](/images/articles/serum-dex/trade/order.png?classes=shadow&width=60pc)

请注意，取消当前委托单或成交订单不会更新您的钱包余额。这些资金会存放在Serum上的一个临时帐户中，您需要在余额页面点击结算来将这些资金转回到你的 [Sollet.io](https://sollet.io) 钱包。

- 在取消上述限价订单后您的余额

![balances](/images/articles/serum-dex/trade/balances.png?classes=shadow&width=60pc)

- 在完成上述交易后的余额

  - 在点击"结算"之前 ![before-settlement](/images/articles/serum-dex/trade/before-settlement.png?classes=shadow&width=60pc)
  - 在点击"结算"之后 ![after-settlement](/images/articles/serum-dex/trade/after-settlement.png?classes=shadow&width=60pc)

{{% notice tip %}}
请注意，您必须对所有交易进行结算，否则资金只会继续停留在临时帐户。
{{% /notice %}}
