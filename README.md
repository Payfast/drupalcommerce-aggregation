# drupalcommerce-aggregation

## Payfast Aggregation module v1.5.0 for for Drupal Commerce 2.x

This is the Payfast module for Drupal Commerce 2.x. Please feel free
to [contact the Payfast support team](https://payfast.io/contact/) should you require any assistance.

## Installation

You will need Drupal 9 or 10 with the latest version of Drupal Commerce 2 installed.


1. In your composer.json add the following under **"repositories": [**

```
        {
            "type": "package",
            "package": {
                "name": "payfast/drupalcommerce-aggregation",
                "version": "1.5.0",
                "type": "drupal-module",
                "source": {
                    "url": "https://github.com/Payfast/drupalcommerce-aggregation.git",
                    "type": "git",
                    "reference": "master"
                }
            }
        }
```

2. In your composer.json add the following under **"extra": { "installer-paths": {**

```
            "modules/commerce/modules": [
                "payfast/drupalcommerce-aggregation"
            ]
```

3. Require the module using composer.

```
composer require 'payfast/drupalcommerce-aggregation:^1.5.0'
```

5. Log into the admin dashboard and install Commerce Payfast on the **Extend** page.
6. Navigate to **Commerce** -> **Configuration** -> **Payment gateways** and click on **Add payment gateway**.
7. Select **Payfast** and configure as required.
8. Click **Save**.

Please [click here](https://payfast.io/integration/plugins/drupal-commerce/) for more information concerning this
module.

## Collaboration

Please submit pull requests with any tweaks, features or fixes you would like to share.
