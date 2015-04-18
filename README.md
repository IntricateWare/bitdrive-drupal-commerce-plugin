# bitdrive-drupal-commerce-plugin
## BitDrive payment method plugin for Drupal Commerce

Accept bitcoin payments on Drupal Commerce using BitDrive Standard Checkout. Includes support for the BitDrive Instant Payment Notification (IPN) messages.

### Minimum Requirements
* PHP 5.2+
* Drupal 7
* Drupal Commerce module 1.0+ OR Commerce Kickstart 2.0+

### Quick Installation
1. Extract the files in the archive to the appropriate modules/ path in Drupal.
2. Log in to the Drupal admin area and navigate to **Site settings > Advanced settings > Modules**.
3. Activate the **BitDrive Bitcoin Payments** module and click the **Save configuration** button if required.
4. Navigate to **Store settings > Advanced store settings > Payment methods**.
5. Enable the **BitDrive Standard Checkout** payment method rule and click the **edit** link for the rule.
6. Click the **edit** button for the **Enable payment method: BitDrive Standard Checkout** action.
7. Specify your BitDrive **Merchant ID**.
8. If you have IPN enabled, specify your BitDrive **IPN Secret**.
9. Specify whether or not **IPN Debug** mode should be enabled.
10. Select the preferred order status for orders when the **Payment Completed** notification is processed.
11. Click the **Save** button.

For documentation on BitDrive merchant services, go to https://www.bitdrive.io/help/merchant-services/6-introduction
