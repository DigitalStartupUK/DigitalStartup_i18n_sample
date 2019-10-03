# DigitalStartup_i18n_sample

## About
These files represent a sample of what i18n Language Packs should look like.

This one contains Language Packs for both **en_GB** and **fr_FR**. These can be tested by updating the appropriate Locale in the backend of Magento.

You should take the time to read the files and understand the structure in order to help you add your own languages.

## Installation
1. Upload the `i18n/DigitalStartup` folder to `<magento>/app/`. (resulting in `<magento>/app/i18n/DigitalStartup`)
2. Deploy Static Content for both languages: `bin/magento setup:static-content:deploy en_GB fr_FR -f`
3. Clean Cache: `bin/magento cache:clean`
4. Flush Cache: `bin/magento cache:flush`
5. Change your locale in **Stores > Configuration > General > General > Locale Options > Locale**
