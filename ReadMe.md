# SameSite = None

WordPress Plugin `Version 1.0`

Owerwrites `wp_set_auth_cookie` to use `Secure = true` and `SameSite = 'None'` cookie attributes. Uses `setcookie` function with options array. Please note: an alternative signature supporting an options array has been added for `setcookie` function starting `PHP 7.3.0`.

How to install
- [Download plugin](https://github.com/peresyolkov/SameSiteNone/archive/master.zip) and save as `SameSiteNone.zip`
- Open your WordPress admin dashboard, navigate to Plugins, and then click on Add New.
- On the next screen, you can select Upload Plugin, which will let you choose a plugin file from your computer.
- Select the `SameSiteNone.zip` and click Install Now.
- The plugin will now be added to your site, and you can activate it as usual.