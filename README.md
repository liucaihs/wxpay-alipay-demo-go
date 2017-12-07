# wxpay-alipay-demo-go
微信App支付、支付宝App支付服务端Demo


https://docs.open.alipay.com/270/alipay.trade.page.pay

	bizContent := `{"product_code":"FAST_INSTANT_TRADE_PAY","qr_pay_mode":2,"total_amount":"` + total_amount + `","subject":"游戏充值","out_trade_no":"` + common.GetOutTradeNo() + `"}`
