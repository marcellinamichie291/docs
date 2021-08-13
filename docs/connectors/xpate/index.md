<img src="https://static.openfintech.io/payment_providers/xpate/logo.svg?w=400" width="400px" >

# xpate

> The first genuine drag-and-drop payment experience in the world

**Website**: [xpate.com](https://www.xpate.com/)
**Login**: [beta early access](https://app.xpate.com/login)

Follow the guidance for setting up a connection with xpate payment service provider.

## Set Up Account

### Step 1: Contact xpate support manager

Send a request on the [website](https://www.xpate.com/). Submit the required documents to verify your account and gain access to the [application](https://app.xpate.com/).

### Step 2: Get credentials

Credentials that have to be issued to connect the provider account:

* Brand ID
* `Bearer` API Key

Find it in the *API* section of the UI.

![xpate UI](images/api-xpate-ui.png)

If you’re going to set up a H2H connection, you require:

* Control key (`merchant_control`)
* Endpoint ID (`endpointid`) related to the currency that you plan to use

!!! important
    Be sure to check with the manager if you require to provide a white list of IPs, and if so, specify IP addresses from the [Corefy list](/integration/ips/).

## Connect Provider Account

### Step 1. Connect account at the {{custom.company_name}} Dashboard

Press **Connect** at [*xpate Provider Overview*]({{custom.dashboard_base_url}}connect-directory/payment-providers/xpate/general) page in *'New connection'* and choose **Provider account** option to open Connection form.

![Connect](images/provider-account.png)

Enter credentials:

* Brand ID
* API Key as Secret Key

Also, select Test or Live mode according to the type of account to connect with xpate.

!!! success
    You have connected **xpate** account!

## Connect H2H Merchant Account

### Step 1. Connect H2H account at the {{custom.company_name}} Dashboard

Press **Connect** at [*xpate Provider Overview*]({{custom.dashboard_base_url}}connect-directory/payment-providers/xpate/general) page in *'New connection'* and choose **H2H Merchant account** option to open Connection form.

![Connect](images/h2h-merchant-account.png)

Enter credentials:

* Login
* Password
* Control key
* Endpoint ID

Select Test or Live mode according to the type of account to connect with xpate.

Choose Currency and Features. You can set these parameters according to available currencies and features for your xpate account, but it's necessary to check details of the connection with your {{custom.company_name}} account manager.

!!! success
    You have connected **xpate** H2H merchant account!

!!! question "Still looking for help connecting your xpate account?"
    <!--email_off-->[Please contact our support team!](mailto:{{custom.support_email}})<!--/email_off-->
