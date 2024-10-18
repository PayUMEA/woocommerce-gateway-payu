# WooCommerce PayU Gateway
* Contributors:  PayU Technical & Integration Support 
* Requires at least: 6.5
* Tested up to: WordPress 6.6 | WooCommerce 9.3
* Plugin version: 1.0.0
* License: GPLv2 or later
* License URI: http://www.gnu.org/licenses/gpl-2.0.html

Enables WooCommerce customers to do payments using PayU MEA (Middle East and Africa) as a payment gateway.

## Installation

1. Upload `woocommerce-gateway-payu` directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Navigate to the WooCommerce Payment gateway settings and configure with PayU MEA API details

## Adding payment methods in WooCommerce plugin

1. Payment methods names must be provided in capital letters
2. Payment methods names must be provided as comma separated list
Example
![image](https://github.com/user-attachments/assets/21ae601b-050c-4a41-b6bf-05222ae50533)

Payment methods names can be found on https://payusahelp.atlassian.net/wiki/spaces/developers/pages/426054/setTransaction+RPP in field "SupportedPaymentMethods"

## Configuration for Discovery Miles

If you have separate credentials for Discovery Miles, then:
1. Fill the credentials for "Discovery Miles Store" (all three)
2. put DISCOVERYMILES as *last (required!)* of methods in "Payment method" field (comma separated list)
3. Check the checkbox "Discovery Miles"
4. Set Discovery Miles "Transaction Type" to payment option title
