## 1. Language Package Process

This is status of Spanish Language Pack, you can see how many percentage of this project has been done.

![language pack](http://progressed.io/bar/90?title=translated)

It is not fully translated? Feel free to contribute:
- [On Crowdin](https://crowdin.com/project/magento-2): It takes time to approve your contribution by Magento team.
- [On Github](https://github.com/mageplaza/magento-2-spanish-language-pack/blob/master/HOW-TO-CONTRIBUTE.md): It's faster, our team will approve it after you send pull request.


Find other [language packs here](https://www.mageplaza.com/kb/magento-2-language-pack/)

## 2. How to Install Spanish Language Pack

```

wget https://raw.githubusercontent.com/yersoncp/magento-2-spanish-language-pack/master/es_PE.csv
sudo bin/magento-cli i18n:pack -m replace -d es_PE.csv es_PE
sudo bin/magento-cli setup:static-content:deploy es_PE -f
sudo bin/magento-cli cache:clean
sudo bin/magento-cli cache:flush

```

## 3. How to active Spanish language pack

Now time to active the Spanish language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Spanish language pack}}](https://cdn.mageplaza.com/media/general/aPSUA0l.png)


## 4. How to contribute

Contribute to this language at https://crowdin.com/project/magento-2/es-ES

## 5. Supported Magento versions

It supports all Magento 2 versions include [Magento 2 open-source](https://www.mageplaza.com/download-magento/), Magento 2 Commerce.


- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x

## 6. Note

- This project automatically updates weekly from Crowdin.
- Any question, issue please [create a new issue](https://github.com/mageplaza/magento-2-spanish-language-pack/issues/new)


