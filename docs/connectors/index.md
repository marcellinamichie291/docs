# Payment providers

??? info "What we include under the term "Payment Service Provider (PSP)""

    **Payment Service Provider (PSP)** is a third party that helps [merchants](/getting-started/glossary/#merchant) accept and facilitate payments.

    PSPs partner with [acquiring banks](/getting-started/glossary/#acquiring-bank) to offer merchants the capability to accept payments. They often offer services in addition to processing transactions. These services include [Payment Card Industry Data Security Standard (PCI)](/getting-started/glossary/#payment-card-industry-data-security-standard-pci) compliance, fraud protection, and the ability to process different currencies and translate different languages.

## Connectors

This section explains how to connect your payment providers' accounts and the {{custom.company_name}} platform. It describes setup processes and helps you to put in place new services that can relay requests to the payment or payout gateways.

Click on the name of the desired connector and follow the link to the step-by-step guide.

## List of ready-made connections

<!-- 16/11/2021: 141 connectors + test, external, manual, cardgate -->

| Name | Payments | Payouts | Supported currencies[^1] | Featured&nbsp;methods |
|:--:|:----:|:----:|:----|:----|
| <img src="https://static.openfintech.io/payment_providers/cardgate/logo.svg?w=70" width="70px"><br>[Direct card payments](cardgate/) | ✅ |  ✅ | AMD, AUD, AZN, BGN, BRL, BYN, CAD, CHF, CNY, CZK, DKK, EUR, GBP, GEL, GIP, HKD, IDR, INR, JPY, KGS, KZT, MDL, MXN, NGN, NOK, NZD, PHP, PLN, RUB, SEK, SGD, TJS, TMT, TRY, TZS, UAH, USD, UZS, VND, ZAR | |
| <img src="https://static.openfintech.io/payment_providers/externalprovider/logo.svg?w=35" width="35px"><br>[External&nbsp;provider protocol](externalprovider/) | | ✅ | [according to the protocol settings] | |
| <img src="https://static.openfintech.io/payment_providers/manual/logo.svg?w=25" width="25px"><br>[Manual](manual/) | ✅ | ✅ | [according to the transfer parameters] | Swift, cash, bank transfers |
| <img src="https://static.openfintech.io/payment_providers/4bill/logo.svg?w=70" width="70px"><br>[4bill](4bill/) | ✅ |  ✅  |  AUD, CAD, EUR, GBP, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/accentpay/logo.png?w=70" width="70px"><br>[Accentpay](accentpay/) | ✅ |  ✅  | EUR, PLN, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/adgroup/logo.svg?w=50" width="50px"><br>[ADgroup](adgroup/)  |  ✅ |  ✅  | EUR, RUB, USD | |
| <img src="https://static.openfintech.io/payment_providers/advcash/logo.svg?w=70" width="70px"><br>[AdvCash](advcash/) |  ✅ |   ✅  | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/alfabank/logo.svg?w=60" width="60px"><br>[Alfa Bank](alfabank/) | ✅  |  ✅  | UAH | |
| <img src="https://static.openfintech.io/payment_providers/alikassa/logo.svg?w=70" width="70px"><br>[AliKassa](alikassa/) |  ✅  |  ✅  | EUR, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/amlnode/logo.svg?w=70" width="70px"><br>[AML Node](amlnode/) | ✅ | | BCH, BTC, LTC, USDT | |
| <img src="https://static.openfintech.io/payment_providers/anycash/logo.svg?w=70" width="100px"><br>[any.cash](anycash/) | ✅ | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/anymoney/logo.svg?w=80" width="80px"><br>[Any.Money](anymoney/) | ✅ | ✅ | BCH, BTC, ETH, LTC, USDT, | |
| <img src="https://static.openfintech.io/payment_providers/appexmoney/logo.svg?w=80" width="80px"><br>[appexmoney](appexmoney/) | | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/axcessmerchantservices/logo.png?w=60" width="60px"><br>[Axcess Merchant Services](axcessmerchantservices/) | ✅ | | EUR, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/bankonego/logo.png?w=60" width="60px"><br>[Bank Onego](bankonego/) | ✅ | ✅ | RUB | |
| <img src="https://static.openfintech.io/payment_providers/betatransfer/logo.svg?w=80" width="80px"><br>[BetaTransfer](betatransfer/) | ✅ | | EUR, RUB, USD | |
| <img src="https://static.openfintech.io/payment_providers/billline/logo.svg?w=70" width="70px"><br>[BillLine](billline/) | ✅ | ✅ | RUB, UAH | |
| <img src="https://static.openfintech.io/payment_providers/blackrabbit/logo.png?w=70" width="70px"><br>[BlackRabbit](blackrabbit/) | ✅ | ✅ | EUR, KZT, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/cardpay/logo.svg?w=70" width="70px"><br>[Unlimint](cardpay/)<br>*(ex: CardPay)* | ✅ | ✅ | AUD, CAD, CZK, EUR, GBP, INR, MXN, NZD, PHP, PLN, RUB, SGD, UAH, USD, VND | |
| <img src="https://static.openfintech.io/payment_providers/cashfree/logo.png?w=80" width="80px"><br>[Cashfree](cashfree/) | | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/cauri/logo.png?w=35" width="35px"><br>[Cauri](cauri/) | ✅ | | EUR, RUB, USD | |
| <img src="https://static.openfintech.io/payment_providers/certusfinance/logo.png?w=120" width="120px"><br>[Certus Finance](certusfinance/) | | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/changcoinspay/logo.png?w=120" width="120px"><br>[ChangeCoins](changcoinspay/) | ✅ | | BNB, BTC, DOGE, ETH, USDT | |
| <img src="https://static.openfintech.io/payment_providers/cib/logo.svg?w=120" width="120px"><br>[Commercial Industrial Bank](cib/) | ✅ | ✅ | UAH | |
| <img src="https://static.openfintech.io/payment_providers/coingate/logo.svg?w=70" width="70px"><br>[CoinGate](coingate/) |  ✅ | |  BCH, BTC, ETH, EUR, LTC, USD | |
| <img src="https://static.openfintech.io/payment_providers/coinspaid/logo.svg?w=70" width="70px"><br>[CoinsPaid](coinspaid/) | ✅ | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/concord/logo.svg?w=120" width="120px"><br>[Concord Bank](concord/) | ✅ | ✅ | UAH | ApplePay, GooglePay, Masterpass |
| <img src="https://static.openfintech.io/payment_providers/concordpay/logo.png?w=80" width="80px"><br>[Concordpay](concordpay/) | ✅ | ✅ | RUB, UAH | |
| <img src="https://static.openfintech.io/payment_providers/connectum/logo.svg?w=70" width="70px"><br>[Connectum](connectum/) | ✅ | ✅ | AUD, CAD, EUR, GBP, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/crosspay/logo.png?w=80" width="80px"><br>[CrossPay](crosspay/) | ✅ | ✅ | UAH | |
| <img src="https://static.openfintech.io/payment_providers/cypix/logo.svg?w=70" width="70px"><br>[Cypix](cypix/) | ✅ | ✅ | EUR, KZT, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/decard/logo.svg?w=70" width="70px"><br>[Decard](decard/) | ✅ | |  RUB | |
| <img src="https://static.openfintech.io/payment_providers/decta/logo.svg?w=70" width="70px"><br>[Decta](decta/) | ✅ | | AUD, CAD, CHF, EUR, GBP, PLN, USD | |
| <img src="https://static.openfintech.io/payment_providers/dialup/logo.svg?w=10" width="10px"><br>[Dialup](dialup/) | | ✅ | | [according to the provider account settings] |
| <img src="https://static.openfintech.io/payment_providers/dixonpay/logo.svg?w=10" width="10px"><br>[DixonPay](dixonpay/) | ✅ | | AED, AUD, CAD, CHF, DKK, EUR, GBP, HKD, ILS, INR, JPY, KRW, MYR, NOK, NZD, PHP, RUB, SEK, SGD, THB, TRY, TWD, USD, ZAR | |
| <img src="https://static.openfintech.io/payment_providers/dlocal/logo.svg?w=70" width="70px"><br>[dLocal](dlocal/) | | ✅ | ARS, BOB, BRL, CLP, COP, INR, MXN, PEN, PYG || |
| <img src="https://static.openfintech.io/payment_providers/dotpay/logo.svg?w=70" width="70px"><br>[dotpay](dotpay/) | | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/easybits/logo.svg?w=100" width="100px"><br>[EasyBits.io](easybits/) | ✅ | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/easypayru/logo.png?w=10" width="10px"><br>[EasyPayRU](easypayru/) | ✅ | ✅ | RUB | |
| <img src="https://static.openfintech.io/payment_providers/easytransfer/logo.svg?w=100" width="100px"><br>[EasyTransfer](easytransfer/) | ✅ | ✅ | RUB, UAH | |
| <img src="https://static.openfintech.io/payment_providers/ecobanq/logo.png?w=70" width="70px"><br>[Ecobanq](ecobanq/) | ✅ | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/ecommpay/logo.svg?w=100" width="100px"><br>[ECommPay](ecommpay/) | | ✅ | [according to the provider account settings] | |
|  <img src="https://static.openfintech.io/payment_providers/ecopayz/logo.svg?w=70" width="70px"><br>[ecoPayz](ecopayz/) | ✅ | ✅ | AUD, BRL, CAD, EUR, GBP, IDR, INR, MDL, MXN, MYR, NGN, PLN, RUB, THB, UAH, USD, UZS, VND | |
| <img src="https://static.openfintech.io/payment_providers/emerald24/logo.svg?w=40" width="40px"><br>[Emerald24](emerald24/) | ✅ | |  EUR, USD | |
| <img src="https://static.openfintech.io/payment_providers/epay/logo.png?w=60" width="60px"><br>[ePay](epay/) | ✅ | ✅ | UAH | |
| <img src="https://static.openfintech.io/payment_providers/exactly/logo.svg?w=70" width="70px"><br>[exactly.](exactly/) | ✅ | ✅ | EUR, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/flashpay/logo.png?w=80" width="80px"><br>[FlashPay](flashpay/) | | ✅ | [according to the provider account settings] | |
|  <img src="https://static.openfintech.io/payment_providers/fondy/logo.svg?w=70" width="70px"><br>[Fondy](fondy/) | ✅ | ✅ | AUD, CAD, CZK, EUR, GBP, PLN, RUB, UAH, USD | ApplePay |
| <img src="https://static.openfintech.io/payment_providers/forta/logo.png?w=35" width="35px"><br>[Forta](forta/) | ✅ | ✅ | RUB | |
| <img src="https://static.openfintech.io/payment_providers/forwardbank/logo.svg?w=70" width="70px"><br>[Forward Bank](forwardbank/) | ✅ | ✅ | UAH | |
| <img src="https://static.openfintech.io/payment_providers/genome/logo.svg?w=70" width="70px"><br>[Genome](genome/) | ✅ | ✅ | AUD, CAD, EUR, GBP, UAH, USD | |
|  <img src="https://static.openfintech.io/payment_providers/geopaynet/logo.svg?w=70" width="70px"><br>[GEO pay](geopaynet/) | ✅ | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/getapay/logo.svg?w=70" width="70px"><br>[Getapay](getapay/) | ✅ | | EUR, RUB, UAH | |
| <img src="https://static.openfintech.io/payment_providers/globalmoney/logo.svg?w=50" width="50px"><br>[Global Money](globalmoney/) | | ✅ | [according to the provider account settings] | |
|  <img src="https://static.openfintech.io/payment_providers/gumballpay/logo.svg?w=70" width="70px"><br>[GumBallPay](gumballpay/) |  ✅ | | CAD, EUR, NOK, NZD, ZAR | |
| <img src="https://static.openfintech.io/payment_providers/hashconnect/logo.png?w=100" width="100px"><br>[Hashconnect](hashconnect/) | ✅ | ✅ | RUB | |
| <img src="https://static.openfintech.io/payment_providers/iboxbank/logo.png?w=50" width="50px"><br>[Ibox Bank](iboxbank/) | ✅ | ✅ | EUR, RUB, UAH, USD | ApplePay, GooglePay |
| <img src="https://static.openfintech.io/payment_providers/ikajo/logo.svg?w=70" width="70px"><br>[Ikajo](ikajo/) | ✅ | | RUB, EUR, USD | |
| <img src="https://static.openfintech.io/payment_providers/ingbankpl/logo.svg?w=70" width="70px"><br>[ING Bank Poland](ingbankpl/) | ✅ | | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/interkassa/logo.svg?w=80" width="80px"><br>[Interkassa](interkassa/) | ✅ | ✅ | EUR, INR, KZT, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/kassa/logo.svg?w=70" width="70px"><br>[Kassa](/connectors/kassa/) | ✅ | ✅ | BYN, EUR, KZT, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/klarna/logo.svg?w=90" width="90px"><br>[Klarna](klarna/) | ✅ | | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/kuna/logo.svg?w=70" width="70px"><br>[Kuna](kuna/) | ✅ | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/kunapay/logo.svg?w=70" width="70px"><br>[Kuna Pay](kunapay/) | ✅ | ✅ | EUR, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/leogaming/logo.svg?w=80" width="80px"><br>[LeoGaming](leogaming/) | | ✅ | RUB, UAH | |
| <img src="https://static.openfintech.io/payment_providers/liqpay/logo.svg?w=70" width="70px"><br>[LiqPay](liqpay/) | ✅ | ✅ | EUR, RUB, UAH, USD | Masterpass |
| <img src="https://static.openfintech.io/payment_providers/maxpay/logo.svg?w=90" width="90px"><br>[Maxpay](maxpay/) | ✅ | ✅ | EUR, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/mercuryo/logo.svg?w=90" width="90px"><br>[mercuryo](mercuryo/) | ✅ | | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/mineexchange/logo.png?w=90" width="90px"><br>[Mine.Exchange](mineexchange/) | ✅ | ✅ | [according to the provider account settings] | |  
| <img src="https://static.openfintech.io/payment_providers/moneypay/logo.png?w=90" width="90px"><br>[MoneyPay](moneypay/) | ✅ | | AUD, CNY, EUR, JPY, USD | |
| <img src="https://static.openfintech.io/payment_providers/muchbetter/logo.svg?w=90" width="90px"><br>[MuchBetter](muchbetter/) | ✅ | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/neteller/logo.svg?w=75" width="75px"><br>[Neteller](neteller/) | | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/nixmoney/logo.png?w=75" width="75px"><br>[NixMoney](nixmoney/) | | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/octopayz/logo.png?w=90" width="90px"><br>[Octopayz](octopayz/) | | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/odysseq/logo.svg?w=90" width="90px"><br>[Odysseq](odysseq/) | ✅ | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/offsetpay/logo.png?w=75" width="75px"><br>[OffsetPay](offsetpay/) | ✅ | | EUR, RUB, USD | |
| <img src="https://static.openfintech.io/payment_providers/opay/logo.svg?w=75" width="75px"><br>[OPay](opay/) | ✅ | | EUR, GBP, USD | |
| <img src="https://static.openfintech.io/payment_providers/parimatch/logo.svg?w=70" width="70px"><br>[Parimatch](parimatch/) | | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/pay2kassa/logo.svg?w=10" width="10px"><br>[pay2kassa](pay2kassa/) | ✅ | ✅ | [according to the account settings] | |
| <img src="https://static.openfintech.io/payment_providers/paybox/logo.svg?w=70" width="70px"><br>[Paybox](paybox/) | ✅ | ✅ | KZT | |
| <img src="https://static.openfintech.io/payment_providers/paydoo/logo.png?w=50" width="50px"><br>[Paydoo](paydoo/) | ✅ | | CHF, EUR, GBP, PLN, RUB, USD | |
| <img src="https://static.openfintech.io/payment_providers/payeer/logo.svg?w=70" width="70px"><br>[Payeer](payeer/) | ✅ | ✅ | BCH, BTC, DASH, ETH, EUR, LTC, RUB, USD | |
| <img src="https://static.openfintech.io/payment_providers/paylink/logo.png?w=70" width="70px"><br>[Paylink](paylink/) | ✅ | ✅ | UAH | Masterpass |
| <img src="https://static.openfintech.io/payment_providers/paylogic/logo.png?w=70" width="70px"><br>[Pay-logic](paylogic/) | | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/paymega/logo.svg?w=90" width="90px"><br>[Paymega.io](paymegaio/) | ✅ | ✅ | EUR, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/paymentcenter/logo.png?w=70" width="70px"><br>[Payment Center](paymentcenter/) | ✅ | ✅ | EUR, RUB, USD | |
| <img src="https://static.openfintech.io/payment_providers/paymentstrust/logo.svg?w=90" width="90px"><br>[Payments Trust](paymentstrust/) | ✅ | ✅ | EUR, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/paymentwall/logo.svg?w=110" width="110px"><br>[Paymentwall](paymentwall/) | ✅ | | USD | |
| <img src="https://static.openfintech.io/payment_providers/paypal/logo.svg?w=70" width="70px"><br>[PayPal](paypal/) | ✅ | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/paypound/logo.png?w=90" width="90px"><br>[PayPound](paypound/) | ✅ | | EUR, GBP, INR, JPY, RUB, USD | |
| <img src="https://static.openfintech.io/payment_providers/paysafe/logo.svg?w=90" width="90px"><br>[Paysafe](paysafe/) | ✅ | ✅ | AZN, BRL, EUR, INR, NGN, PKR, USD, UZS | |
| <img src="https://static.openfintech.io/payment_providers/paysafecard/logo.svg?w=90" width="90px"><br>[paysafecard](paysafecard/) | ✅ | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/paysage/logo.png?w=90" width="90px"><br>[PaySage.io](paysage/) | ✅ | ✅ | EUR, RUB | |
| <img src="https://static.openfintech.io/payment_providers/paysoft/logo.png?w=35" width="35px"><br>[PaySoft Inc.](paysoft/) | | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/perfectmoney/logo.png?w=70" width="70px"><br>[Perfect Money](perfectmoney/) | ✅ | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/piastrix/logo.svg?w=70" width="70px"><br>[Piastrix](piastrix/) | ✅ | ✅ | BCH, ETH, EUR, KZT, RUB, UAH, USD | ApplePay |
| <img src="https://static.openfintech.io/payment_providers/pivdennybank/logo.svg?w=100" width="100px"><br>[Pivdenny Bank](pivdennybank/) | ✅ | ✅ | UAH | |
| <img src="https://static.openfintech.io/payment_providers/platio/logo.svg?w=70" width="70px"><br>[Platio](platio/) | ✅ | ✅ | RUB | 
| <img src="https://static.openfintech.io/payment_providers/pmsolutions/logo.png?w=35" width="35px"><br>[PMSolutions](pmsolutions/) | ✅ | ✅ | EUR, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/portmone/logo.svg?w=70" width="70px"><br>[Portmone.com](portmone/) | ✅ | | UAH | GooglePay |
| <img src="https://static.openfintech.io/payment_providers/procard/logo.png?w=70" width="70px"><br>[Procard](procard/) | ✅ | | EUR, UAH | |
| <img src="https://static.openfintech.io/payment_providers/pspgate/logo.png?w=70" width="70px"><br>[PSPGate](pspgate/) | ✅ | | CNY, EUR, GBP, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/pumb/logo.svg?w=35" width="35px"><br>[PUMB (FUIB)](pumb/) | ✅ | ✅ | UAH | |
|  <img src="https://static.openfintech.io/payment_providers/qiwi/logo.svg?w=70" width="70px"><br>[Qiwi](qiwi/) | ✅ | | EUR, RUB, USD | |
| <img src="https://static.openfintech.io/payment_providers/raiffeisenbank/logo.svg?w=100" width="100px"><br>[Raiffeisen Bank](raiffeisenbank/) | ✅ | ✅ | UAH | |
| <img src="https://static.openfintech.io/payment_providers/rapyd/logo.svg?w=70" width="70px"><br>[Rapyd.net](rapyd/) | | ✅ | [according to the provider account settings] | |
 <img src="https://static.openfintech.io/payment_providers/rbkmoney/logo.png?w=70" width="70px"><br>[RBK Money](rbkmoney/) | ✅ | ✅ | EUR, RUB, USD | |
| <img src="https://static.openfintech.io/payment_providers/reel/logo.png?w=70" width="70px"><br>[REEL](reel/) | | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/royalpay/logo.svg?w=90" width="90px"><br>[Royal Pay](royalpay/) | ✅ | ✅ | RUB | |
| <img src="https://static.openfintech.io/payment_providers/rubikonsoft/logo.png?w=90" width="90px"><br>[Rubikon Soft](rubikonsoft/) | | ✅ | [according to the provider account settings] | |
|  <img src="https://static.openfintech.io/payment_providers/russianstandardbank/logo.png?w=70" width="70px"><br>[Russian Standard Bank](russianstandardbank/) | ✅ | |
| <img src="https://static.openfintech.io/payment_providers/safecharge/logo.svg?w=90" width="90px"><br>[Nuvei](safecharge/)<br>*(ex: SafeCharge)* | ✅ | ✅ | AUD, CAD, CHF, EUR, GBP, PLN, USD |
| <img src="https://static.openfintech.io/payment_providers/satchelpay/logo.svg?w=90" width="90px"><br>[SatchelPay](satchelpay/) | | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/selcom/logo.png?w=70" width="70px"><br>[Selcom](selcom/) | ✅ | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/skrill/logo.svg?w=50" width="50px"><br>[Skrill](skrill/) | ✅ | ✅ | AUD, BDT, BGN, CHF, CZK, DKK, EUR, GBP, HRK, HUF, LKR, MDL, MYR, NOK, NPR, PLN, RON, SEK, THB, USD | |
| <img src="https://static.openfintech.io/payment_providers/solidgate/logo.svg?w=70" width="70px"><br>[Solid](solidgate/) | ✅ | | AUD, CAD, EUR, GBP, NZD, SGD, USD | |
| <img src="https://static.openfintech.io/payment_providers/spoynt/logo.svg?w=70" width="70px"><br>[Spoynt](spoynt/) | ✅ | ✅ | EUR, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/square/logo.svg?w=70" width="70px"><br>[Square](square/) | ✅ | | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/stripe/logo.svg?w=70" width="70px"><br>[Stripe](stripe/) | ✅ | | AUD, CAD, EUR, GBP, USD | | ApplePay |
| <img src="https://static.openfintech.io/payment_providers/tinkoff/logo.svg?w=40" width="40px"><br>[Tinkoff](tinkoff/) | ✅ | | EUR, RUB, USD | |
| <img src="https://static.openfintech.io/payment_providers/tkbpay/logo.svg?w=70" width="70px"><br>[TKB Pay](tkbpay/) | ✅ | ✅ | RUB | |
|  <img src="https://static.openfintech.io/payment_providers/tome/logo.svg?w=70" width="70px"><br>[tome](tome/) | ✅ | ✅ | BYN, EUR, KZT, RUB, UAH, USD | |
|  <img src="https://static.openfintech.io/payment_providers/transactworld/logo.png?w=90" width="90px"><br>[Transact World](transactworld/) | ✅ | ✅ | GBP, EUR, USD | |
| <img src="https://static.openfintech.io/payment_providers/tranzzo/logo.svg?w=90" width="90px"><br>[Tranzzo](tranzzo/) | ✅ | | [according to the provider account settings] | | 
| <img src="https://static.openfintech.io/payment_providers/trustpay/logo.svg?w=90" width="90px"><br>[TrustPay](trustpay/) | ✅ | | AZN, CAD, IDR, KGS, KZT, MDL, MYR, PLN, PLN, RUB, THB, TJS, TMT, UZS, VND | |
| <img src="https://static.openfintech.io/payment_providers/trustpayments/logo.svg?w=70" width="70px"><br>[Trust Payments](trustpayments/) | ✅ | | AUD, CAD, EUR, NZD, SEK, SGD | |
| <img src="https://static.openfintech.io/payment_providers/twoclick/logo.png?w=50" width="50px"><br>[2click](twoclick/) | | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/uapay/logo.svg?w=50" width="50px"><br>[UAPay](uapay/) | ✅ | ✅ | UAH | |
| <img src="https://static.openfintech.io/payment_providers/ukrgasbank/logo.png?w=90" width="90px"><br>[UKRGASBANK](ukrgasbank/) | ✅ | ✅ | UAH | |  
| <img src="https://static.openfintech.io/payment_providers/unlimco/logo.svg?w=90" width="90px"><br>[Unlimco](unlimco/) | ✅ |  | CNY, RUB, USD | |
| <img src="https://static.openfintech.io/payment_providers/vcreditos/logo.svg?w=70" width="70px"><br>[VCreditos](vcreditos/) | ✅ | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/volt/logo.svg?w=40" width="40px"><br>[VOLT](volt/) | ✅ | | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/whitebit/logo.svg?w=90" width="90px"><br>[WhiteBIT](whitebit/) | ✅ | ✅ | EUR, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/winpay/logo.png?w=70" width="70px"><br>[Globalfin](winpay/)<br>(ex: WinPay)* | ✅ | ✅ | EUR, GBP, KZT, RUB, UAH, USD | |
| <img src="https://static.openfintech.io/payment_providers/wirecapital/logo.svg?w=110" width="110px"><br>[Wirecapital](wirecapital/) | ✅ | ✅ | AZN, EUR, INR, KGS, MDL, PLN, RUB, TJS, UAH, USD, UZS | |
| <img src="https://static.openfintech.io/payment_providers/wirecard/logo.svg?w=70" width="70px"><br>[wirecard](wirecard/) | ✅ | ✅ | AZN, BYN, EUR, KGS, KZT, MDL, RUB, TJS, TMT, UAH, USD, UZS | |
| <img src="https://static.openfintech.io/payment_providers/wlandpay/logo.png?w=90" width="90px"><br>[WlandPay](wlandpay/) | ✅ | | AED, AUD, CAD, CHF, DKK, EUR, GBP, HKD, ILS, INR, KRW, MYR, NOK, NZD, PHP, RUB, SEK, SGD, THB, TRL, TWD, USD, ZAR | |
| <img src="https://static.openfintech.io/payment_providers/wpayments/logo.png?w=90" width="90px"><br>[WPayments](wpayments/) | ✅ | ✅ | EUR, RUB | |
| <img src="https://static.openfintech.io/payment_providers/xpate/logo.svg?w=70" width="70px"><br>[xpate](xpate/) | ✅ | ✅ | EUR, KZT, PLN, RUB, USD | |
| <img src="https://static.openfintech.io/payment_providers/xpayua/logo.svg?w=70" width="70px"><br>[XPAY](xpayua/) | ✅ | ✅ | [according to the provider account settings] | |
| <img src="https://static.openfintech.io/payment_providers/zotapay/logo.png?w=70" width="70px"><br>[Zotapay](zotapay/) | ✅ | ✅ | EUR, GHS, IDR, KES, MYR, NGN, THB, TZS, USD, VND, ZAR | |

You can also send a request about a new connection by clicking the appropriate button on the [dashboard]({{custom.dashboard_base_url}}connect-directory/payment-providers) or <!--email_off-->[emailing our support team](mailto:{{custom.support_email}}).<!--/email_off-->

## How to Connect to the Payment Provider

![Step-by-Step](images/connection.png)

Usually, the connection algorithm includes the following steps:

1. Create an account on the side of the payment provider
2. Set up your provider or merchant account and get credentials for the further connection
3. Connect the account in the [{{custom.company_name}} Dashboard]({{custom.dashboard_base_url}})

!!! attention "Please note"
    - Sub-steps can be different, since methods of data storage, delivery and organisation are unique for each provider.

    - The credential parameters format must be appropriate to the connection form's requirements.

!!! question "Contact us"
    If you have any questions, feature suggestions or ideas, feel free to contact our support team via <!--email_off-->[email](mailto:{{custom.support_email}})<!--/email_off--> or [Jira service desk]({{custom.support_url}}).

[^1]: You can find the complete list of currencies {{custom.company_name}} support [here](/products/currency-rates/supported-currencies/).

--8<-- "includes/abbr.md"
