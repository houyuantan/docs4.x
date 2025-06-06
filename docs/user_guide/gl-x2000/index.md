# Spitz Plus (GL-X2000) User Guide

All of GL.iNet's devices have a simple and almost identical setup process, [click here to learn about the first time setup](../../faq/first_time_setup.md/).

## How to set up Spitz Plus

To set up Spitz Plus, you will use one of the four supported internet connection methods: Cellular (SIM cards), ethernet, repeater, and tethering. Watch this setup video or follow the steps below. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/3dm0w5kjAlc?si=3YykOcaz_YK_vp28" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<small>(This video uses a different GL.iNet router to demonstrate the setup but the steps are the same for Spitz Plus and other router models.)</small>

!!! note "Before you start, follow these steps (if connecting via the cellular method):"

    To connect to the internet via the cellular method, you will need at least one nano SIM card. Once you have the nano SIM card(s) ready, follow these steps:
    
    1. Activate your SIM card(s), if required by the SIM card carrier.
    2. Make sure you router is powered off.
    3. Insert the SIM card(s) into the SIM card slots. (**Note:** Only one SIM card is active at each time. The other SIM card functions only as a backup.)

### 1. Power on the Spitz Plus

Put the two-piece power adapter together. Connect it to your router and plug it into a outlet. It will start up automatically.

### 2. Connect your device to the Spitz Plus

Connect your computer or mobile device to the router using Wi-Fi or ethernet.

=== "Ethernet"

    Connect your device to the router's LAN port using an ethernet cable. 

=== "Wi-Fi"

    On your device, locate your router's Wi-Fi network name in the list of available networks and enter the password. (You can find the default network name and password printed on your router's label.)

### 3. Connect the Spitz Plus to the internet 

**Note:** The following instructions were written for those using the router admin panel to connect the router to the internet. If you want to use the GL.iNet app instead of the admin panel, [download the app](https://www.gl-inet.com/app/) and follow the on-screen instructions. 

#### 1. Sign in to the router admin panel 

In a web browser's address bar, enter `192.168.8.1`. Choose your language, then click **Next**. Set your admin password, then click **Apply**. 

#### 2. Set up your internet connection method(s)

=== "Cellular"

    ![cellular](https://static.gl-inet.com/docs/router/en/4/user_guide/gl-x2000/internet/x2000_cellular.jpg){class="glboxshadow"}

    If you already inserted the SIM card into your router, you should be connected to the internet automatically. (You should see the name of your SIM carrier and a light green dot appear next to it.) If not, click the **Auto Setup** option if it appears. 
    
    Please note that eSIM functionality is **only** available on [Beta Firmware v4.5.22](https://dl.gl-inet.com/router/x2000/beta). 
    Learn how to set up the eSIM physical card on your GL.iNet router with our step-by-step instructions here: [How to Set Up the eSIM Physical Card with the GL.iNet Routers?](https://docs.gl-inet.com/router/en/4/tutorials/how_to_set_up_esim/)

    For issues using the cellular method, refer to the [Cellular Network Troubleshooting Guide](https://docs.gl-inet.com/router/en/4/faq/gl-x3000_gl-xe3000_connection_optimization/). 

=== "Ethernet"

    ![ethernet](https://static.gl-inet.com/docs/router/en/4/user_guide/gl-x2000/internet/x2000_ethernet.jpg){class="glboxshadow"}
    
    Connect an ethernet cable to your router's WAN port and an upstream device, such as a modem. If you are connected to the internet successfully, a light green dot appears next to "Ethernet."

    Please refer to [Connect to the Internet via an Ethernet cable](../../interface_guide/internet_ethernet.md) for detailed instructions.

=== "Repeater"

    ![repeater](https://static.gl-inet.com/docs/router/en/4/user_guide/gl-x2000/internet/x2000_repeater.jpg){class="glboxshadow"}

    1. On the main screen of the admin panel, locate the "Repeater" section, then click **Connect**.
    2. Select a Wi-Fi network. 
    3. Enter the network password, then click **Apply**.
    
    If you are connected to the internet successfully, a light green dot appears next to the Wi-Fi network name.

    Please refer to [Connect to the Internet via an existing Wi-Fi network](../../interface_guide/internet_repeater.md) for detailed instructions.

=== "Tethering"

     ![tethering](https://static.gl-inet.com/docs/router/en/4/user_guide/gl-x2000/internet/x2000_tethering.jpg){class="glboxshadow"}

    1. Connect your mobile device to the router's USB port using a 3.0 USB data transfer cable. 
    2. In your mobile device's settings, enable tethering. 
    3. On the main screen of the admin panel, click **Connect** in the "Tethering" section. 
    
    If you are connected to the internet successfully, a light green dot appears next to "Tethering".

    Please refer to [Connect to the Internet via USB tethering](../../interface_guide/internet_tethering.md) for detailed instructions.

**Note:** If you want to use the multi-WAN feature, you will have to set up more than one internet connection methods. 

---

## How to set up a VPN 

A VPN (virtual private network) creates a secure, encrypted traffic between your device and the VPN server. It provides an added layer of privacy and security (VPN client) and allows you to access a remote network (VPN server). Spitz Plus (and other GL.iNet routers) support OpenVPN, WireGuard. 


=== "OpenVPN" 
    Spitz Plus (and other GL.iNet routers) support the OpenVPN protocol which offers strong security. To set up OpenVPN, follow these tutorials:

    * [How to set up an OpenVPN client](https://docs.gl-inet.com/router/en/4/interface_guide/openvpn_client/)
    * [How to set up an OpenVPN server](https://docs.gl-inet.com/router/en/4/interface_guide/openvpn_server/)

=== "WireGuard"
    Spitz Plus (and other GL.iNet routers) support the WireGuard protocol which offers great speeds and convenience. To set up WireGuard, follow these tutorials:

    * [How to set up a WireGuard client](https://docs.gl-inet.com/router/en/4/interface_guide/wireguard_client/)
    * [How to set up a WireGuard server](https://docs.gl-inet.com/router/en/4/interface_guide/wireguard_server/)

---

## More features and settings

=== "Port forwarding"

    Port forwarding allows remote servers and devices on the internet to access devices on a private network. To set up port forwarding, refer to [Port Forwards](https://docs.gl-inet.com/router/en/4/interface_guide/firewall/#port-forwards). 

=== "Multi-WAN"

    Multi-WAN is a networking feature that allows you to set up your router with multiple internet connections (e.g., cellular, repeater, and ethernet) at the same time. If your current internet connection fails, the router will automatically switch to another internet connection. This ensures smooth and uninterrupted internet access. 

    To set up multi-WAN, refer to [Multi-WAN](https://docs.gl-inet.com/router/en/4/interface_guide/multi-wan/). 

=== "AdGuard Home"

    AdGuard Home is a third-party tool that blocks ads and tracking to keep you safe. To learn how to enable AdGuard Home, refer to [AdGuard Home](https://docs.gl-inet.com/router/en/4/interface_guide/adguardhome/). 


=== "Drop-in gateway"

    Drop-in gateway extends the functionality of your main router with features it may not have, including AdGuard Home, encrypted DNS, and VPN. To set up drop-in gateway, refer to [How to set up drop-in gateway](https://docs.gl-inet.com/router/en/4/tutorials/how_to_set_up_drop_in_gateway/). 

---

=== "Parental controls"

    Parental controls are a group of settings designed to help you manage and control your children's devices. They include limiting their screen time and restricting their access to certain content. Spitz Plus offers two options for parental controls: the local version developed by GL.iNet and the integrated version from Bark, a parental controls app. 

    To set up parental controls, refer to [Parental controls](../../interface_guide/parental_control.md). 

=== "eSIM"

    This router supports eSIM functionality only on [Beta Firmware v4.5.22](https://dl.gl-inet.com/router/x2000/beta). 
    
    To learn how to set up and manage eSIM on your device, please refer to [this tutorial](../../tutorials/how_to_set_up_esim_physical_card_with_glinet_routers.md).

    <iframe width="560" height="315" src="https://www.youtube.com/embed/hyHh8pAxgVw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    
---

## System settings

* To reset the router's admin password, follow [these instructions](https://docs.gl-inet.com/router/en/4/interface_guide/admin_password/). 
* To reset the router's firmware, follow [these instructions](https://docs.gl-inet.com/router/en/4/faq/repair_network_or_reset_firmware/). 
* To reset the router's time zone, follow [these instructions](https://docs.gl-inet.com/router/en/4/interface_guide/time_zone/). 
* To set scheduled tasks, follow [these instructions](https://docs.gl-inet.com/router/en/4/interface_guide/scheduled_tasks/). 
* To set up custom DNS servers, follow [these instructions](https://docs.gl-inet.com/router/en/4/interface_guide/dns/). 
* To view system logs, follow [these instructions](https://docs.gl-inet.com/router/en/4/interface_guide/log/). 

--- 

## Product overview

### Product information

Spitz Plus (GL-X2000) is a dual-SIM 4G LTE Wi-Fi 6 cellular gateway designed to provide fast, reliable connections especially in remote areas and during road trips. Featuring 3-Carrier Aggregation, the router streams data on three carrier bands simultaneously, providing 3x available bandwidth to avoid congestion. It offers four internet access methods: Cellular (SIM cards), ethernet, repeater, and tethering. It supports multi-WAN (failover and load-balancing), VPN (OpenVPN and Wireguard), parental controls, AdGuard Home, port forwarding, Tailscale, and more. 

![gl-x2000 interface](https://static.gl-inet.com/docs/router/en/4/user_guide/gl-x2000/hardware_info/x2000_interface.jpg){class="glboxshadow"}


### Package contents

Please note that the adapter within the package depends on your shipping country.

Your router package includes:

- 1 x User manual
- 1 x Spitz Plus (GL-X2000)
- 4 x External antennas
- 1 x Thank you card
- 1 x Ethernet cable
- 1 x Wall mount kit
- 1 x Adhesive pad
- 4 x Screws
- 1 x Power adapter
- 1 x Converters (Base on your shipping countries, US/EU/UK/AU plugs)


![package contents](https://static.gl-inet.com/docs/router/en/4/user_guide/gl-x2000/first_time_setup/x2000_unboxing.jpg){class="glboxshadow"}

### LED indicators 

| Condition status                                                              | Power                                | Internet                    | 2.4GHz                      | 5GHz                        |Cellular | 
| ----------------------------------------------------------------------------- | ------------------------------------ | --------------------------- | --------------------------- | --------------------------- | ------- |
| Normal (connected to the internet)                                            | Green                                | Green                       | Green                       | Green                       | Green   |
| Not connected to the internet                                                 | Green                                | Off                         | Green                       | Green                       | Green   |
| Updating firmware                                                             | Green                                | Blinking green (every 0.5s) | Blinking green (every 0.5s) | Blinking green (every 0.5s) | Green   | 
| Resetting router (hold down "reset" button for > 3s)                          | Blinkng green (every 1s)             | Green                       | Green                       | Green                       | Green   |
| Restoring router to factory settings (hold down "reset" button for 10s)       | Fast blinking green (every 0.25s)    | Green                       | Green                       | Green                       | Green   | 

### Specifications

Refer to [Specifications](https://www.gl-inet.com/products/gl-x2000/#specs){target="_blank"}. 

