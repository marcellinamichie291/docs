<img src="https://static.openfintech.io/payment_providers/ems/logo.svg?w=400" width="400px" >

# EMS

Follow the guidance for setting up a connection with EMS as a payment service provider.

## Set Up Account

### Step 1: Contact EMS support manager

Send a request, submit the required documents to verify your account and gain access.

### Step 2: Get credentials

Go to the *Security* settings in the Merchant Control Panel and copy credentials:

* Merchant ID
* Hash key

!!! important
    Be sure to check with the manager if you require to provide a white list of IPs, and if so, specify IP addresses from the [Corefy list](/integration/ips/).

## Connect H2H Merchant Account

### Step 1. Connect H2H account at the {{custom.company_name}} Dashboard

Press **Connect** at [*EMS Provider Overview*]({{custom.dashboard_base_url}}connect-directory/payment-providers/ems/general) page in *'New connection'* and choose **H2H Merchant account** option to open Connection form.

![Connect](images/h2h-merchant-account.png)

Enter credentials:

* Merchant ID
* Hash key

Select Test or Live mode according to the type of account to connect with EMS.

Choose Currencies and Features. You can set these parameters according to available currencies and features for your EMS account, but it's necessary to verify details of the connection with your {{custom.company_name}} account manager.

!!! success
    You have connected **EMS** H2H merchant account!

!!! question "Still looking for help connecting your EMS account?"
    <!--email_off-->[Please contact our support team!](mailto:{{custom.support_email}})<!--/email_off-->
