---
date: 2020-08-27T00:0:00+00:00
title: Trade
weight: 3
---

## Trade

Now that you have successfully connected your SOL wallet it’s time to trade. The trading experience is the same as a centralized exchange, with the same interface.

Let’s buy 88 BASE tokens at a limit price of 3.1 QUOTE tokens each and make sure you approve this transaction on your [Sollet.io](https://sollet.io) popup.

![order form](/serum-dex/trade/images/order-form.png?classes=shadow&width=30pc)

![approve-transaction](/serum-dex/trade/images/approve-transaction.png?classes=shadow&width=40pc)

Now you can see your limit buy order on the Orderbook, also in the Open Orders.

![order](/serum-dex/trade/images/order.png?classes=shadow&width=60pc)

Note that cancelling your Open Orders or having the trade successfully matched and traded won’t update your wallet balance. These funds sit in an intermediary account and require you to settle them back to your own sollet wallet. You have to go to Balances to settle them back to your [Sollet.io](https://sollet.io) wallet.

- Your Balances after cancelling the limit buy order of “88 BASE tokens at limit price 3.1 QUOTE”

![balances](/serum-dex/trade/images/balances.png?classes=shadow&width=60pc)

- Your Balances after buying “11 BASE tokens at the price of 2.22 QUOTE”

  - Before settlement ![before-settlement](/serum-dex/trade/images/before-settlement.png?classes=shadow&width=60pc)
  - After settlement ![after-settlement](/serum-dex/trade/images/after-settlement.png?classes=shadow&width=60pc)

{{% notice tip %}}
Note that you need to settle your trades. Otherwise they will sit in an intermediary account.
{{% /notice %}}
