=== Myanmar States, Cities, and Places for WooCommerce ===\
Main Source: [States, Cities, and Places for WooCommerce](https://github.com/chitezh/woocommerce_states_places)\
Contributors: chitezh, yordansoares, luisurrutiaf, nobnob, joseayram\
Re-Contributor: h2kyaw\
Tags: woocommerce, locations, states, cities, provinces, regions, departments, municipalities, districs, governorates, counties, cantons\
Stable tag: 1.3.2\
Requires at least: 4.0\
Tested up to: 5.6\
Requires PHP: 7.0\
WC requires at least: 3.0.x\
WC tested up to: 4.8\
License: GPLv2 or later\
License URI: [GPL-3.0 License](https://www.gnu.org/licenses/gpl-3.0.html)

WordPress plugin that shows dropdowns for Myanmar States and Cities Select for WooCommerce.

== Description ==

This plugin adds locations of **available countries** (see list below) to the **State** and **City** fields of the **WooCommerce** address forms, making the fields filterable to enhance the **user experience**.

Additionally it adds the States to the **Shipping Zones** (Cities are not compatible with this area).

== Supported Countries ==
* MM Myanmar
* [Main Source for Other Country](https://github.com/chitezh/woocommerce_states_places)

== Plugin Demo Site ==

If you want to see the plugin in action, follow the steps below:

1. Visit the **plugin demo site**: https://thecoolcreatures.com
2. Select a **sample product** from the list.
3. Go to the **Checkout** to interact with available country locations.

== Available languages ==

* English (US, Australia, Canada, UK, New Zealand, and South Africa)
* Spanish (Argentina, Chile, Colombia, Costa Rica, Dominican Republic, Ecuador, Guatemala, Honduras, Mexico, Peru, Puerto Rico, Spain, Uruguay, and Venezuela)

== Installation ==

= Automatic installation =

1. Go to your **Dashboard » Plugins » Add new**
2. In the search form write **"Myanmar States, Cities, and Places for WooCommerce"**
3. When the search return the result, click on the **Install Now** button
4. Finally, click on the **Activate** button
5. Enjoy the plugin!

= Manual Installation = 
1. Download the plugin from this page clicking on the **Download** button
2. Go to your **Dashboard » Plugins » Add new**
3. Now select **Upload Plugin** button
4. Click on **Select file** button and select the file you just download
5. Click on **Install Now** button and the **Activate Plugin**
6. Enjoy the plugin!

= FTP Installation =
1. Download the plugin from this page clicking on the **Download** button
2. Decompress the file in your desktop
3. Run your FTP client software and conect to your WordPress installation
4. Copy to [root folder]/wp-content/plugins/ the plugin directory you just descompress
5. Go to your Dashboard » Plugins » Find the plugin and click on **Activate** option
6. Enjoy the plugin!

== Screenshots ==
1. In this screenshot you can see the plugin in action.
![Screenshot](https://github.com/h2kyaw/myanmar-states-and-cities-for-woocommerce/blob/main/assets/screenshot.gif?raw=true)

== Additional Setting ==
1. Go to Woocommerce Dashboard > Settings > In General options
2. **Change Selling location(s)** > Sell to specific countries > Select **Myanmar**.
3. **Shipping location(s)** > Ship to specific countries only > Select **Myanmar**.
4. Click **Save**.
5. Go to Wordpress Dashboard > Apperance > Theme Editor > In Style.css Add below codes

```css
#shipping_country_field,
#billing_country_field,
#calc_shipping_country_field,
#calc_shipping_postcode_field {
    display: none !important;
}
```

== Frequently Asked Questions ==

= How do I report bugs? =
Kindly create an issue stating the bug and how you caught it: [Create new issue](https://github.com/chitezh/woocommerce_states_places/issues/new).

= Can I suggest a new place or location? =
Yes, you can always suggest or request new locations by creating an issue in the [plugin repository](https://github.com/chitezh/woocommerce_states_places/issues/new) in GitHub. Please refer to the [Adding a new country](https://github.com/chitezh/woocommerce_states_places/tree/master/templates) instructions to get more details.

== Changelog ==

**9.0 - February  9, 2021**
* First release.
