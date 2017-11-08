# wp-theme-unit-test
Personal collection of WordPress Test Posts

## Contents:

| File         | Description                                                                                                  |
|--------------|--------------------------------------------------------------------------------------------------------------|
| uikit-v2.xml | Contains a page of all the components from UIKit Version 2. See here. https://getuikit.com/v2/docs/base.html |



## Importing UIKIT Examples via wp-cli

```shell
wp plugin install wordpress-importer --activate;
curl -fsSL https://rawgit.com/craigiswayne/wp-theme-unit-test/master/uikit-v2.xml -o uikit-v2.wxr;
wp import uikit-v2.wxr --authors=create;
rm uikit-v2.wxr;
```

### Importing WordPress Theme Unit Test Examples via wp-cli (Single Command)
```shell
wp plugin install wordpress-importer --activate && curl -fsSL https://rawgit.com/craigiswayne/wp-theme-unit-test/master/themeunittestdata.wordpress.xml -o themeunittestdata.wordpress.wxr && wp import themeunittestdata.wordpress.wxr --authors=create && rm themeunittestdata.wordpress.wxr;
```

### Importing UIKIT Examples via wp-cli (Single Command)
```shell
wp plugin install wordpress-importer --activate && curl -fsSL https://rawgit.com/craigiswayne/wp-theme-unit-test/master/themeunittestdata.wordpress.xml -o themeunittestdata.wordpress.wxr && wp import themeunittestdata.wordpress.wxr --authors=create && rm themeunittestdata.wordpress.wxr;
```

### Importing All Examples via wp-cli (Single Command)
```shell
wp plugin install wordpress-importer --activate && curl -fsSL https://rawgit.com/craigiswayne/wp-theme-unit-test/master/uikit-v2.xml -o uikit-v2.xml && wp import uikit-v2.xml --authors=create && rm uikit-v2.xml && curl -fsSL https://rawgit.com/craigiswayne/wp-theme-unit-test/master/themeunittestdata.wordpress.xml -o themeunittestdata.wordpress.xml && wp import themeunittestdata.wordpress.xml --authors=create && rm themeunittestdata.wordpress.xml;
```


