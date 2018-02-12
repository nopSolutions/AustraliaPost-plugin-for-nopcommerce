nopCommerce Shipping.AustraliaPost plugin
===========
Shipping plugin for Australia Post


nopCommerce site: [https://www.nopcommerce.com](https://www.nopcommerce.com)

Listing on nopCommerce "extensions and themes" catalog: [https://www.nopcommerce.com/p/2982/shipping-plugin-for-australia-post-nopcommerce-team.aspx](https://www.nopcommerce.com/p/2982/shipping-plugin-for-australia-post-nopcommerce-team.aspx)

## Installation

### Build

'Copy local' property of the referenced assemblies are set to 'false'.
We know that they're referenced by the main web applications. So there's no need to deploy them.
It can dramatically reduce package size.

Set the project output path to `..\..\Presentation\Nop.Web\Plugins\{PluginName}\` (both 'Release' and 'Debug' configurations)

All views (cshtml files) and web.config file should have "Build action" set to **"Content"** and **"Copy to output directory"** set to **"Copy if newer"**

### Configuration

Within the NopCommerce Admin interface, open `Plugins\Local plugins` and Install the added plugin.
Then click the Configure button to further customize the plugin.
