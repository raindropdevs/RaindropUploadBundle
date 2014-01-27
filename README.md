# WARNING: This bundle is under development and not ready for production use.

# Raindrop Upload Bundle

This bundle offers widgets and services to manage a centralized upload system using CKFinder


### **INSTALLATION**:

First add the dependency to your `composer.json` file:

    "require": {
        ...
        "raindrop/upload-bundle": "dev-feature/alpha-version",
    },

Then install the bundle with the command:

    php composer.phar update

Enable the bundle in your application kernel:

``` php
<?php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        // ...
        new Raindrop\PageBundle\RaindropUploadBundle(),
    );
}
```

Now the bundle is enabled.

### **CONFIGURATION**:

No configuration needed.

### **USAGE**:
