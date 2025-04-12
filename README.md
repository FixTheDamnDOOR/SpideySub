# Subscription Template for [Marzban Panel](https://github.com/Gozargah/Marzban)

<img width="738" alt="Screenshot 2025-04-12 at 23 10 56" src="https://github.com/user-attachments/assets/283c09f2-c636-46cf-999a-6d940dbabb62" />

# Features
  * User info like data limit or time limit
  * Quick addition of subscription links to apps
  * Links for downloading required applications
  * Access to copy all configs by one click
  * ...

# Installation
1. Download the template file:
```
sudo wget -N -P /var/lib/marzban/templates/subscription/ https://raw.githubusercontent.com/FixTheDamnDOOR/SpideySub/blob/main/index.html
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
