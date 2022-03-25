<img src="https://static.openfintech.io/payment_providers/payelata/logo.svg?w=400" width="400px" >

# Payelata

> Your first step to accept payments

**Website**: [payelata.com](https://payelata.com/)

**Login**: [dashboard.payelata.com](https://dashboard.payelata.com/login)

Follow the guidance for setting up a connection with Payelata as a payment service provider.

## Set Up Account

### Step 1: Contact Payelata support manager

Send a request on the [website](https://payelata.com/). Sign up to the [dashboard](https://dashboard.payelata.com/login) and set up created account. Then, submit all required documents to verify it and get full access.

### Step 2: Get credentials

Login to the Payelata merchant [dashboard](https://dashboard.payelata.com/login) and copy credentials:

* Account ID
* API key
* Private key

!!! important
    Be sure to check with the manager if you require to provide a white list of IPs, and if so, specify IP addresses from the [Corefy list](/integration/ips/).

## Connect provider account

### Step 1. Connect an account at the {{custom.company_name}} dashboard

Press **Connect** at [*Payelata Provider Overview*]({{custom.dashboard_base_url}}connect-directory/payment-providers/payelata/general) page in *'New connection'* and choose **Provider account** option to open Connection form.

![Connect](images/provider-account.png)

Enter credentials:

* Account ID
* API key
* Private key

Also, choose the Send metadata option if you want to use metadata in payment invoices.

!!! success
    You have connected **Payelata** account!

## Connect H2H Merchant Account

### Step 1. Connect an account at the {{custom.company_name}} Dashboard

Press **Connect** at [*Payelata Provider Overview*]({{custom.dashboard_base_url}}connect-directory/payment-providers/payelata/general) page in *'New connection'* and choose **H2H Merchant account** option to open Connection form.

![Connect](images/h2h-merchant-account.png)

Enter credentials:

* Account ID
* API key
* Private key

Select Test or Live mode according to the type of account to connect with Payelata. Also, choose the *Send metadata* option if you want to use metadata in payment invoices.

Choose Currencies and Features. You can set these parameters according to available currencies and features for your Payelata account, but it's necessary to verify details of the connection with your {{custom.company_name}} account manager.

!!! success
    You have connected **Payelata** H2H merchant account!

!!! question "Still looking for help connecting your Payelata account?"
    <!--email_off-->[Please contact our support team!](mailto:{{custom.support_email}})<!--/email_off-->
