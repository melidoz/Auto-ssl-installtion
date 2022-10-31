# Auto ssl installtion
This page guides you through the process of obtaining an HTTPS certificate for your site. This is a real certificate, not a self-signed certificate, and works in all major browsers.
The CA which we'll use is auto ssl installation. They provide basic certificates for free, although they will charge for other types, such as wildcard certificates.

# Support
> All of linux versions

# Prerequisites
- linux server
- domain
- curl

# Curl
> If you don't have curl, you can install curl with the command 
```
apt install curl
```
# Domain
> You can use this website to get domain and activate [free domain](https://www.freenom.com/)

# Install & Upgrade
```
bash <(curl -Ls https://raw.githubusercontent.com/melidoz/Auto-ssl-installtion/main/ssl.sh)
```
# Remove & Uninstall .acme ssl
```
acme.sh --uninstall
rm -r  ~/.acme.sh
```
