Opauth-AzureAD
==============
[Opauth][1] strategy for Azure Active Directory

Getting started
----------------
1. Install Opauth-AzureAD:
   ```bash
   cd path/to/app/root
   composer require opauth/azure-ad:dev-1.0
   ```

2. Create application at http://manage.windowsazure.com

3. Configure Opauth-AzureAD strategy with at least `ID` and `Secret`.

4. Direct user to `http://path_to_opauth/azure-ad` to authenticate

Strategy configuration
----------------------

Required parameters:

```php
<?php
'AzureAD' => array(
	'app_id' => 'YOUR ID',
	'app_secret' => 'YOUR SECRET'
)
```

License
---------
Opauth-AzureAD is MIT Licensed
Copyright © 2014 U-Zyn Chua (http://uzyn.com)

[1]: https://github.com/opauth/opauth