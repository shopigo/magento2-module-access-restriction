[![Shopigo](https://www.shopigo.ch/wp-content/uploads/2018/08/github-shopigo-logo.png)](https://www.shopigo.ch)

# Magento 2 Access Restriction extension by [Shopigo](https://www.shopigo.ch)

This extension adds a feature which allow to deny access to certain pages by displaying a 404 error page.

More information available at [Shopigo Blog](https://www.shopigo.ch/blog/extension-magento-2-restreindre-acces-pages) (in french).

![](https://www.shopigo.ch/wp-content/uploads/2018/08/github-extension-access-restriction-settings.jpg)

## Requirements

Magento Open Source Edition 2.2.x.

## Installation

## Method 1 - Installing via composer

- Switch to your Magento project root
- Run `composer require shopigo/magento2-extension-access-restriction=dev-master`

## Method 2 - Installing using archive

- Download [ZIP Archive](https://github.com/shopigo/magento2-extension-access-restriction/archive/master.zip)
- Switch to your Magento project root
- Create folder `app/code/Shopigo/AccessRestriction`
- Extract zip into path

### Enable extension

- Switch to your Magento project root
- Run the following commands to enable the module and clear static contents generated by Magento:
```
php bin/magento module:enable Shopigo_AccessRestriction
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
```

## How to use it

- Log into your Magento back-office
- Go to the menu "Stores > Configuration > Shopigo Extensions > Access Restrictions"
- Configure your rules in the field "Restriction Rules"
- Set the parameter "Enabled" to "Yes"
- Flush Magento caches from the menu "System > Tools > Cache Management"

## Support

If you have any issues, open a bug report in GitHub's [issue tracker](https://github.com/shopigo/magento2-extension-access-restriction/issues).

## Need more features?

Please contact us to get a quote https://www.shopigo.ch/contact

## License

The code is licensed under [Open Software License ("OSL") v. 3.0](http://opensource.org/licenses/osl-3.0.php).

Enjoy!<br/>
[Shopigo](https://www.shopigo.ch)