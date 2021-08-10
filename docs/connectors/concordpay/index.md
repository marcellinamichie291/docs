<img src="https://static.openfintech.io/payment_providers/concordpay/logo.png?w=400" width="400px" >

# ConcordPay

!!! quote ""
    ConcordPay internet acquiring

**Website**: [pay.concord.ua](https://pay.concord.ua/)

**Login**: [pay.concord.ua](https://pay.concord.ua/cabinet/default/login)

Follow the guidance for setting up a connection with ConcordPay as a payment service provider.

## Set Up Account

### Step 1: Register at ConcordPay

### Step 2: Get credentials

After registration, you obtain a unique client code name and also generate on your side a pair of RSA keys: public and private in the PEM (pkcs8) format. Contact your ConcordPay support manager if you have any complications with obtaining credentials.

For the H2H connection, you also should know an API type and decide how the ConcordPay and {{custom.company_name}} will calculate the payment fee.

!!! important
    Be sure to check with the manager if you require to provide a white list of IPs, and if so, specify IP addresses from the [Corefy list](/integration/ips/).## Connect Provider Account

## Connect Provider Account

### Step 1. Connect account at the {{custom.company_name}} Dashboard

Press **Connect** at [*ConcordPay Provider Overview*]({{custom.dashboard_base_url}}connect-directory/payment-providers/concordpay/general) page in *'New connection'* and choose **Provider account** option to open Connection form.

![Connect](images/provider-account.png)

Enter credentials:

* Client code name
* Private Key
* Public key (optionally)

Select Test or Live mode according to the type of account to connect with ConcordPay.

!!! success
    You have connected **ConcordPay** account!

## Connect H2H Merchant Account

### Step 1. Connect H2H account at the {{custom.company_name}} Dashboard

Press **Connect** at [*ConcordPay Provider Overview*]({{custom.dashboard_base_url}}connect-directory/payment-providers/concordpay/general) page in *'New connection'* and choose **H2H Merchant account** option to open Connection form.

![Connect](images/h2h-merchant-account.png)

Enter credentials:

* Client code name
* Private Key
* Public key (optionally)

Choose your API type and Fee calculation type.

Select Test or Live mode according to the type of account to connect with ConcordPay.

Choose Currency and Features. You can set these parameters according to available currencies and features for your Concord account, but it's necessary to check details of the connection with your {{custom.company_name}} account manager.

!!! success
    You have connected **ConcordPay** H2H merchant account!

!!! question "Still looking for help connecting your ConcordPay account?"
    <!--email_off-->[Please contact our support team!](mailto:{{custom.support_email}})<!--/email_off-->
