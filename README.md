# MageGuide PlaceOrder

Tested on: 2.2+, 2.3+

## Description

Magento 2 default checkout places the Place Order buttons under Payment Methods which is not the best place to put such a button. Order Summary is way too nicer place for such a button to exist. PlaceOrder module is gonna help you with that issue and after installing it your Place Order button is gonna appear under Checkout Order Summary!


### Functionalities

  - Adds Place Order button under Checkout Order Summary
  - Hides Place Order buttons under Payment Methods

### Installation

  Add the app folder with all the subfolders into the root folder of your Magento Application.

  Perform the following commands:

  * __Developer Mode__

```sh

    $ php bin/magento set:upg && php bin/magento c:c

```

  * __Production Mode__

```sh

    $ php bin/magento maintenance:enable
    $ php bin/magento setup:upgrade
    $ php bin/magento setup:di:compile
    $ php bin/magento setup:upgrade
    $ php bin/magento setup:static-content:deploy el_GR en_US #or any other space seperated language you need for your project
    $ php bin/magento maintenance:disable

```

### Usage

  Just go to Checkout Page and enjoy!

### Screenshots

#### Checkout Page
![Checkout Page](/screenshots/checkout_page.png)