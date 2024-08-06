# Breaking Access Control in Home Wireless Mesh Networks
Do you know your home mesh network can be hacked? Check out!

# Introduction
In the year of 2023, we discovered novel attacks for home wireless mesh networks. Simply speaking, the control protocols over backhaul wireless links can be tampered with. As a result, an attacker who has a (fronthaul) Wi-Fi passphrase can obtain root shells on access points, and/or steal fronthaul/backhaul Wi-Fi passphrases. Obtaining a root shell allows an attacker to capture/inject wireless packets, to change Wi-Fi passphrases to attacker-controlled values, among others. Stealing fronthaul/backhaul Wi-Fi passphrases allows an attacker to evade network access revocations. 

# Publication
Untangling the Knot: Breaking Access Control in Home Wireless Mesh Networks [[PDF]](https://www.cs.ucr.edu/%7Ezhiyunq/pub/ccs24_wireless_mesh.pdf) \
Xin’an Zhou, Qing Deng, Juefei Pu, Keyu Man, Zhiyun Qian, Srikanth V. Krishnamurthy \
Proceedings of the 2024 ACM SIGSAC Conference on Computer and Communications Security. 

Fallen Tower of Babel: Rooting Wireless Mesh Networks by Abusing Heterogeneous Control Protocols [[Link]](https://www.blackhat.com/us-24/briefings/schedule/index.html#fallen-tower-of-babel-rooting-wireless-mesh-networks-by-abusing-heterogeneous-control-protocols-39898) \
Xin’an Zhou, Zhiyun Qian, Juefei Pu, Qing Deng, Srikanth V. Krishnamurthy, Keyu Man \
Black Hat USA 2024

# Affected Vendors/Products
[Netgear Orbi](https://www.netgear.com/home/wifi/mesh/orbi/) \
[ASUS AiMesh](https://www.asus.com/microsite/aimesh/en/index.html) \
[TP-Link Deco](https://www.tp-link.com/us/deco-mesh-wifi/product-family/) \
[Linksys](https://store.linksys.com/shop/shop-home/whole-home-mesh-wifi/) \
[Wyze](https://www.wyze.com/products/wyze-mesh-router-pro) \
[AmpliFi](https://amplifi.com/) \
[Wi-Fi EasyMesh Standard](https://www.wi-fi.org/discover-wi-fi/wi-fi-easymesh)

Note that the two types of security flaws we found are general, impacting the whole Wi-Fi mesh industry. If you don't find your brand of choice above, it is still possible that your mesh network is vulnerable. 

# Open-source Timeline
The full exploitation code will be available before the ACM CCS 2024 publication date (10/2024). At this stage (08/2024), we still want to give vendors and users more time to deploy patches. 
