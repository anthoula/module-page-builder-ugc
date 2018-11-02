# Magento Page Builder - User Generated Content
This example module demonstrates how to add a custom content type within the Page Builder framework that pulls user generated content from Instagram.

## Installation

#### Prerequisite
* Install Magento 2
* Install Page Builder

#### Clone this repo into your Magento root directory
```
cd magento2ce
git clone git@github.com:anthoula/module-page-builder-ugc.git
```

#### Link module to Magento
Since we downloaded and installed the module-page-builder-ugc git repo at the root level of our Magento directory, we need to link it into app/code/Magento with all the other Magento modules.
```
cd magento2ce/app/code
ln -s ../../module-page-builder-ugc/app/code/Example
```
#### Install/Setup UGC Module

Navigate to the magento2ce root directory and install/setup the Page Builder UGC module by running setup:upgrade.
```
cd magento2ce
bin/magento setup:upgrade
```
