# Openvpn plugin

This plugin allows to connect Jeedom to an openvpn server. It is also used and therefore mandatory for the Jeedom DNS service which allows you to access your Jeedom from the internet.

# Plugin configuration

After downloading the plugin, you just need to activate and install the openvpn dependencies (click on the Install / Update button)

# Equipment configuration

Here you find all the configuration of your equipment :

-   **Name of the openvpn device** : name of your Openvpn device,
-   **Parent object** : indicates the parent object to which the equipment belongs,
-   **Category** : equipment categories (it can belong to several categories),
-   **Activer** : makes your equipment active,
-   **Visible** : makes your equipment visible on the dashboard,

> **Note**
>
> The other options will not be detailed here, for more information please refer to the [openvpn documentation](https://openvpn.net/index.php/open-source/documentation.html)

> **Note**
>
> For shell commands executed after startup you have the tag #interface# for the interface name automatically replaced

Below you find the list of orders :

-   **Nom** : the name displayed on the dashboard,
-   **Afficher** : allows to display the data on the dashboard,
-   **Tester** : Used to test the command

> **Note**
>
> Jeedom will check every 15 minutes if the VPN is started or stopped (if necessary) and act accordingly if it is not
