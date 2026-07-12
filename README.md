# SSLCommerz Payment Gateway

> SSLCOMMERZ is the first payment gateway in Bangladesh opening doors for merchants to receive payments on the internet via their online stores. Their customers will be able to buy products online using their credit cards as well as bank accounts. If you are a merchant, you have come to the right place! WooCommerce plugin for SSLCommerz payment gateway with Dynamic IPN Support.

## Getting Started

### Also available at [Wordpress Plugin Store](https://wordpress.org/plugins/wc-sslcommerz-easycheckout/ "SSLCommerz Payment Gateway")

### Prerequisites

1. Wordpress 5.8 or later
2. WooCommerce 3.6 or later
3. cURL php extension enabled.
4. [Sandbox Credentials](https://developer.sslcommerz.com/registration/ "SSLCommerz Sandbox Registration") or [Live Credentials](https://signup.sslcommerz.com/register/ "Merchant Registration")

### Support
> If you face any technical issue and need support, please communicate **via email** at **integration@sslcommerz.com**.

### Installation

1. Download zip file or Clone the repository.
2. Go to `Plugins > Add New`.
3. Click on `Upload Plugin` button.
4. Go to `Choose File` and upload the Zip file of plugin.
5. Active the plugin.


> This plugin will automatically set the IPN url, there is no need to set IPN in merchant panel when using this.

### Configuration

1. Open Admin Panel.

![Payments Menu](images/screenshot-1.png)

2. Navigate to ```Woocommerce > Settings > Payments``` tab.

![Payments Menu](images/screenshot-2.png)
![Payments Menu](images/screenshot-3.png)

3. Click on SSLCommerz to edit the settings. If you do not see SSLCommerz in the list at the top of the screen make sure you have activated the plugin in the WordPress Plugin Manager.
4. Enable the Payment Method, give a proper title and description to show on the checkout page,  fill up stroe id and store passowrd fields carefully, select success and fail/cancel page.
5. You can enable or disable Hosted/Popup mode from `Hosted EasyCheckout` 
6. Setup is complete. Check if everything is working properly.


## FAQ

### I am getting error which says my store is de-active.
> check Testmode, Store ID and Store Password in the settings. If issue still persists, communicate with merchnat's Key Account Manager (**KAM**).
 
### How can I enable IPN?
> This plugin handled IPN with ZERO configuration. No action needed from your end. 

### I want to create order in woocommerce only if transaction is successful. Otherwise order will not be placed.
> This is NOT possible. Order gets created before going to payment page with "Pending" status. After transaction order status will be updated within a short time. 

### I want to enable EMI option, how it works?
> To enable EMI option first you have to make an agreement with us. To do that please communicate with the Business person, you have communicate at the time of Store registration. Besides this in live, you will have EMI configuration option after login to your Merchant report panel go to `My Stores>EMI Settings`.

### I want my customer will bear the gateway charges. How can I do that?
> Yes, We have solution for this, you can configure this from your merchant panel or mail to `operation@sslcommerz.com` .

## Contributors
> Prabal Mallick, Md. Rakibul Islam
> 
> Email: integration@sslcommerz.com
The WordPress plugin “SSLCommerz Payment Gateway – EasyCheckout” lets you integrate Bangladesh’s leading payment gateway directly into WooCommerce, supporting both sandbox and live credentials with minimal setup. It’s ideal for Dhaka‑based eCommerce sites that need fast, secure transactions with options like EMI and IPN handled automatically.🔑 Key FeaturesWooCommerce integration: Works with WooCommerce 3.6+ and WordPress 5.1+.Sandbox & live credentials: Test transactions safely before going live.Hosted & popup checkout: Choose between redirecting customers or embedding checkout.IPN support: Instant Payment Notification is auto‑configured, no manual setup required.EMI option: Available after merchant agreement; configurable via merchant panel.Gateway charges: Can be passed to customers if enabled in merchant settings.⚙️ Setup ProcessActivate plugin in WordPress Plugin Manager.Go to WooCommerce → Settings → Payments.Select SSLCommerz and enable the method.Enter Store ID and Store Password (from merchant panel).Configure success/fail/cancel pages.Choose Hosted or Popup mode.Save settings and test with sandbox credentials.📊 Comparison TableFeatureSSLCommerz EasyCheckout PluginManual API IntegrationEase of setupSimple WooCommerce settingsRequires codingSandbox testingBuilt‑inManual API callsIPN handlingAutomaticMust configure listenerEMI optionMerchant panel toggleRequires custom logicGateway chargesConfigurable in merchant panelManual surcharge setup⚠️ Risks & ConsiderationsOrder creation timing: Orders are created in WooCommerce before payment, marked “Pending.” Status updates after transaction success.Deactivation errors: If you see “store is de‑active,” check Testmode, Store ID, and Store Password. Contact your Key Account Manager if issues persist.Customer charges: Passing gateway fees to customers may affect conversion rates — use cautiously.Compliance: Ensure PCI DSS and SSL/TLS 1.3 are enforced for live transactions.📌 Why It Matters for Dhaka eCommerceLocal relevance: SSLCommerz is Bangladesh’s most widely used gateway, trusted by major retailers.Mobile‑first: Works seamlessly with bKash, Nagad, Rocket, and NexusPay integrations.Scalability: Supports EMI, multiple banks, and real‑time reporting via merchant panel.Would you like me to show you how to extend this plugin setup into a unified multi‑provider dashboard (SSLCommerz + bKash + Nagad + Rocket) with real‑time monitoring, or keep it focused on WooCommerce checkout only? You can explore multi‑provider dashboard or WooCommerce only.