# GL-XE300 (Puli) User Guide

## Hardware info

GL-XE300 (Puli) is a portable 4G smart router that is perfect for home, business and IoT solution. With its OpenWrt supported feature and large storage compatibility, it is designed for you to develop DIY IoT project. It also comes with a rechargeable battery, so you can bring it anywhere with you!

![gl-xe300 interface](https://static.gl-inet.com/docs/router/en/4/user_guide/gl-xe300/hardware_info/gl-xe300_interface.jpg){class="glboxshadow"}

[GL-XE300 specification](https://www.gl-inet.com/products/gl-xe300/#specs){target="_blank"}

### PCB Pinout

<div class="gl-lightbox" itemscope itemtype="http://schema.org/ImageGallery">
  <figure itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
    <a href="https://static.gl-inet.com/docs/router/en/4/user_guide/gl-xe300/hardware_info/gl-xe300_pinout.jpg" itemprop="contentUrl" data-size="3167x2480">
      <img src="https://static.gl-inet.com/docs/router/en/4/user_guide/gl-xe300/hardware_info/gl-xe300_pinout.jpg" itemprop="thumbnail" alt="gl-xe300 pinout" loading="lazy" />
    </a>
  </figure>
</div>

---

## First time setup

All of GL.iNet's devices have a simple and almost identical setup process, [click here to learn about the first time setup](../../faq/first_time_setup.md/).

Please note that the adapter within the package depends on your shipping country.

What's inside the package?

![gl-xe300 unboxing](https://static.gl-inet.com/docs/router/en/4/user_guide/gl-xe300/first_time_setup/xe300_unboxing.jpg){class="glboxshadow"}

Package Contents:

- 1 x User manual
- 1 x Puli (GL-XE300)
- 1 x Ethernet cable
- 1 x Thank you card
- 1 x Warranty card
- 1 x Power adapter (Selected plug type)

Check out Puli's [unboxing video](../../video_library/unboxing_first_set_up.md#puligl-xe300).

---

## INTERNET

The internet configuration interface lets users choose to establish the type of internet connection supported by the router.

Configure the internet network by selecting **INTERNET** in the side menu within the router's web Admin Panel. 

It supports four ways to connect to the internet as listed below:

### Ethernet

Transmit data over an Ethernet cable using an Ethernet cable to connect the router to an active modem or an active network device. This method usually provides the fastest and most reliable Internet connection. 

[Click here to learn how to connect to the internet via an ethernet cable](../../interface_guide/internet_ethernet.md)

![Ethernet Connection](https://static.gl-inet.com/docs/router/en/4/user_guide/gl-xe300/internet/xe300_ethernet.png){class="glboxshadow"}

### Repeater

Extend the Wi-Fi coverage area of an existing Wi-Fi network by using a router to receive wireless signals within range and forwarding the signals to a further distance. This method is most useful when a single router does not have enough range to cover the entire usage area.

[Click here to learn how to connect to the internet via an existing Wi-Fi](../../interface_guide/internet_repeater.md)

![Repeater Connection](https://static.gl-inet.com/docs/router/en/4/user_guide/gl-xe300/internet/xe300_repeater.png){class="glboxshadow"}

### Tethering

Establish internet access with connected devices by sharing a smartphone's mobile data to the router via cable. This method is most useful when users wants to use the phone's data to access the internet.

[Click here to learn how to connect to the internet via usb tethering](../../interface_guide/internet_tethering.md)

![Tethering Connection](https://static.gl-inet.com/docs/router/en/4/user_guide/gl-xe300/internet/xe300_tethering.png){class="glboxshadow"}

### Cellular
 
Connect the router to the internet by inserting a cellular enabled USB modem into the router's USB port. This method is most useful for sharing internet access from a USB modem to all connected devices.

[Click here to learn how to connect to the internet via cellular or usb modem](../../interface_guide/internet_cellular.md)

![Cellular Connection](https://static.gl-inet.com/docs/router/en/4/user_guide/gl-xe300/internet/xe300_cellular.png){class="glboxshadow"}

### Priority and load balance

Go to [Multi-WAN](../../interface_guide/multi-wan.md) to set the priority of each Internet access method or the load balance when multiple Internet access methods are used at the same time.

---

## WIRELESS

The wireless settings lets users manage network security of the primary Wi-Fi and the Guest Wi-Fi, it is accessible by going to **WIRELESS** on the side menu.

[Click here to learn more about the wireless configuration](../../interface_guide/wireless.md)

---

## CLIENTS

Clients are devices connected to the router, you can block clients or limit its network speed. The interface is accessible by clicking **CLIENTS** in the side menu of the router's Admin Panel.

[Click here to learn more about managing your device clients.](../../interface_guide/clients.md)

---

## VPN

GL.iNet routers are pre-installed with OpenVPN and WireGuard® supporting 30+ VPN services. It automatically encrypts all network traffic within the connected network, including guest devices and client devices that are not capable of running VPN encryption. Our routers can also act as VPN servers, redirecting traffic from client devices in remote locations to the VPN server via a VPN tunnel before accessing the public internet.

### VPN Dashboard

- [**VPN Dashboard**](../../interface_guide/vpn_dashboard.md)

### OpenVPN

Please refer to the following links for a step to step setup guide:

- [**Setup OpenVPN Client**](../../interface_guide/openvpn_client.md)
- [**Setup OpenVPN Server**](../../interface_guide/openvpn_server.md)

### WireGuard

Please refer to the following links for a step to step setup guide:

- [**Setup WireGuard Client**](../../interface_guide/wireguard_client.md)
- [**Setup WireGuard Server**](../../interface_guide/wireguard_server.md)

### Tor

- [**Tor**](../../interface_guide/tor.md)

---

## APPLICATIONS

GL.iNet routers include a wide range of add-on features that simplifies device management, improves user's internet experience, automates firmware update, and more.

### Plug-ins

Please visit the [**Plug-ins**](../../interface_guide/plugins.md) tutorial.

### Dynamic DNS

Please visit the [**Dynamic DNS**](../../interface_guide/ddns.md) tutorial.

### GoodCloud

Please visit the  [**GoodCloud**](../../interface_guide/cloud.md) tutorial.

### Network Storage

Please visit the [**Network Storage**](../../interface_guide/network_storage.md) tutorial.

### AdGuard Home

Please visit the [**AdGuard Home**](../../interface_guide/adguardhome.md) tutorial.

### Parental Control

Please visit the [**Parental Control**](../../interface_guide/parental_control.md) tutorial.

### ZeroTier

Please visit the [**ZeroTier**](../../interface_guide/zerotier.md) tutorial.

---

## NETWORK

### Firewall

GL.iNet's routers include multiple firewall features to ensure a secure connection and complete oversight by users. It lets users configure firewall rules including Port Forwarding, Open Ports, and DMZ.

[Click here to learn more about GL.iNet routers' firewall](../../interface_guide/firewall.md)

### Multi-WAN

Please visit the [**Multi-WAN**](../../interface_guide/multi-wan.md) tutorial.

### LAN

Please visit the [**LAN**](../../interface_guide/lan.md) tutorial.

### DNS

Please visit the [**DNS**](../../interface_guide/dns.md) tutorial.

### Network Mode

Please visit the [**Network Mode**](../../interface_guide/network_mode.md) tutorial.

### IPv6

Please visit the [**IPv6**](../../interface_guide/ipv6.md) tutorial.

### MAC Address

The Mac Address page was previously called Mac Clone and has been changed to Mac Address since v4.2.

Please visit the [**MAC Address**](../../interface_guide/mac_address.md) tutorial.

### Drop-in Gateway

Please visit the [**Drop-in Gateway**](../../interface_guide/drop-in_gateway.md) tutorial.

### IGMP Snooping

Please visit the [**IGMP Snooping**](../../interface_guide/igmp_snooping.md) tutorial.

---

## SYSTEM

### Overview

Please visit the [**System Overview**](../../interface_guide/system_overview.md) tutorial.

### Upgrade

GL.iNet provides regular updates on our routers' firmware to improve performance, resolving bugs and fix vulnerabilities.

Please visit the [**Upgrade**](../../interface_guide/upgrade.md) tutorial.

### Scheduled Tasks

Please visit the [**Scheduled Tasks**](../../interface_guide/scheduled_tasks.md) tutorial.

### Admin Password

This feature has been moved to [**Security**](../../interface_guide/security.md) since v4.5.

Please visit the [**Admin Password**](../../interface_guide/admin_password.md) tutorial.

### Time Zone

Please visit the  [**Time Zone**](../../interface_guide/time_zone.md) tutorial.

### Log

Please visit the [**Log**](../../interface_guide/log.md) tutorial.

### Security

This feature is available since v4.5.

Please visit the [**Security**](../../interface_guide/security.md) tutorial.

### Reset Firmware

Please visit the [**Reset Firmware**](../../interface_guide/reset_firmware.md) tutorial.

### Advanced Settings

Please visit the [**Advanced Settings**](../../interface_guide/advanced_settings.md) tutorial.

