<img src="https://static.openfintech.io/payment_providers/whitebit/logo.svg?w=400" width="400px" >

# WhiteBIT

Follow the guidance for setting up a connection with WhiteBIT as a payment service provider.

## Set Up Account

### Step 1: Contact WhiteBIT support manager

Send a request to WhiteBIT to create and set up your account. Then, submit the required documents to verify it and get full access.

### Step 2: Get credentials

Login to the WhiteBIT merchant dashboard and copy credentials:

* Account ID
* API key
* Private key

!!! important
    Be sure to check with the manager if you require to provide a white list of IPs, and if so, specify IP addresses from the [Corefy list](/integration/ips/).

## Connect Provider Account

### Step 1. Connect account at the {{custom.company_name}} Dashboard

Press **Connect** at [*WhiteBIT Provider Overview*]({{custom.dashboard_base_url}}connect-directory/payment-providers/whitebit/general) page in *'New connection'* and choose **Provider account** option to open Connection form.

![Connect](images/provider-account.png)

Enter credentials:

* Account ID
* API key
* Private key

Also, choose the Send metadata option if you want to use metadata in payment invoices.

!!! success
    You have connected **WhiteBIT** account!

## Connect H2H Merchant Account

### Step 1. Connect H2H account at the {{custom.company_name}} Dashboard

Press **Connect** at [*WhiteBIT Provider Overview*]({{custom.dashboard_base_url}}connect-directory/payment-providers/whitebit/general) page in *'New connection'* and choose **H2H Merchant account** option to open Connection form.

![Connect](images/h2h-merchant-account.png)

Enter credentials:

* Account ID
* API key
* Private key

Also, select Test or Live mode according to the type of account to connect with WhiteBIT.

Choose Currencies and Features. You can set these parameters according to available currencies and features for your WhiteBIT account, but it's necessary to verify details of the connection with your {{custom.company_name}} account manager.

!!! success
    You have connected **WhiteBIT** H2H merchant account!

!!! question "Still looking for help connecting your WhiteBIT account?"
    <!--email_off-->[Please contact our support team!](mailto:{{custom.support_email}})<!--/email_off-->
