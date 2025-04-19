# Subscription Template for [Marzban Panel](https://github.com/Gozargah/Marzban)

<div align="center">
  <img width="666" alt="Screenshot" src="https://github.com/user-attachments/assets/392bc478-f7d3-4a11-bd8e-0360f97f2760" />
</div>

# Features
  * User info like data limit or time limit
  * Quick addition of subscription links to apps
  * Links for downloading required applications
  * Access to copy all configs by one click
  * Access to copy each config separately
  * ...

# Installation
1. Download the template file:
```
sudo wget -N -P /var/lib/marzban/templates/subscription/ https://raw.githubusercontent.com/FixTheDamnDOOR/SpideySub/main/index.html
```
2. Run this code:
```
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env
```
3. restart marzban:
```
marzban restart
```
