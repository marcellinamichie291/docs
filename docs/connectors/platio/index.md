<img src="https://static.openfintech.io/payment_providers/platio/logo.svg?w=400" width="400px" >

# Platio

> Transfers between cards made easy

**Website**: [Platio](https://platio.com/)
**Login**: [Platio](https://w.platio.com/sign-in)

Follow the guidance for setting up a connection with Platio payment service provider.

## Set Up Account

### Step 1: Register your account

Register on the [website](https://w.platio.com/sign-up), verify your account, and gain access.

### Step 2: Create a new outlet

![New Outlet](images/platio-ui.png)

### Step 3: Get credentials

Credentials that have to be issued:

* Outlet ID
* Secret Key
* Secret Key for Result URL

For the H2H connection, you also should know an API type to interact with Platio.

## Connect Provider Account

### Step 1. Connect account at the {{custom.company_name}} Dashboard

Press **Connect** at [*Platio Provider Overview*]({{custom.dashboard_base_url}}connect-directory/payment-providers/platio/general) page in *'New connection'* and choose **Provider account** option to open Connection form.

![Connect](images/provider-account.png)

Enter credentials:

* Outlet ID as Account ID
* Secret Key
* Secret Key for Result URL as Secret Key Return URL

Also, select Test or Live mode according to the type of account to connect.

!!! success
    You have connected **Platio** account!

## Connect H2H Merchant Account

### Step 1. Connect H2H account at the {{custom.company_name}} Dashboard

Press **Connect** at [*Platio Provider Overview*]({{custom.dashboard_base_url}}connect-directory/payment-providers/platio/general) page in *'New connection'* and choose **H2H Merchant account** option to open Connection form.

![Connect](images/h2h-merchant-account.png)

Enter credentials:

* Outlet ID as Account ID
* Secret Key
* Secret Key for Result URL as Secret Key Return URL

Select Test or Live mode according to the type of account to connect. Choose your API type.

Enable *Send Merchant URL* option for sending the Merchant's shop URL to Platio.

Enable *Save Instant Token* if you plan on using payments by token with the connected Outlet ID.

Also, choose Currency and Features. You can set these parameters according to available currencies and features for your Platio account, but it's necessary to check details of the connection with your {{custom.company_name}} account manager.

!!! success
    You have connected **Platio** H2H merchant account!

!!! question "Still looking for help connecting your Platio account?"
    [Please contact our support team!](mailto:{{custom.support_email}}ompany_name}})
