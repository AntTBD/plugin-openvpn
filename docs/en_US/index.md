This plugin allows to connect Jeedom to an openvpn server. It is also
used and therefore mandatory for the Jeedom DNS service which allows you
to access your Jeedom from the internet

Plugin configuration 
=======================

After downloading the plugin, you just need to activate and
install openvpn dependencies (click on the Install / Update button
up to date)

Equipment configuration 
=============================

Here you find all the configuration of your equipment :

-   **Name of the openvpn device** : name of your Openvpn device,

-   **Parent object** : indicates the parent object to which belongs
    equipment,

-   **Category** : equipment categories (it may belong to
    multiple categories),

-   **Activate** : makes your equipment active,

-   **Visible** : makes your equipment visible on the dashboard,

> **NOTE**
>
> The other options will not be detailed here, to have more
> further information please refer to the [documention
> openvpn] (https:

> **NOTE**
>
> For shell commands executed after startup you have the tag # interface # for the name of the interface automatically replaced

Below you find the list of orders :

-   **Name** : the name displayed on the dashboard,

-   **Pin up** : allows to display the data on the dashboard,

-   **Test** : Used to test the command

> **NOTE**
>
> Jeedom will check every 15 minutes if the VPN is started or
> arrested (if necessary) and act accordingly if this is not the case
