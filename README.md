# wp-theme-unit-test
Personal collection of WordPress Test Posts

## Contents:

| File         | Description                                                                                                  |
|--------------|--------------------------------------------------------------------------------------------------------------|
| uikit-v2.xml | Contains a page of all the components from UIKit Version 2. See here. https://getuikit.com/v2/docs/base.html |


## Importing via wp-cli

```
wp plugin install wordpress-importer --activate;
curl -fsSL https://rawgit.com/craigiswayne/wp-theme-unit-test/master/uikit-v2.xml -o uikit-v2.wxr;
wp import uikit-v2.wxr;
rm uikit-v2.wxr;
```

### Importing via wp-cli (Single Command)
```
wp plugin install wordpress-importer --activate && curl -fsSL https://rawgit.com/craigiswayne/wp-theme-unit-test/master/uikit-v2.xml -o uikit-v2.wxr && wp import uikit-v2.wxr && rm uikit-v2.wxr;
```
