![Preview](preview.png)

## Marzneshin [server]

1. **Download the template:**
   ```sh
   https://raw.githubusercontent.com/trbsami/ClockSub/main/marzban/index.html
   ``` 

2. **Run these commands:**
   ```bash
   echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
   echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env

3. **Restart Marzneshin:**
   ```sh
   marzban restart
   ```

## Marzban [host]

check and use:

```bash
sudo wget -N -P /var/lib/marzneshin/templates/subscription/ https://raw.githubusercontent.com/trbsami/ClockSub/main/marzban/marzban.php
```

**Our channel on Telegram :**  
trbSami   [![Telegram](https://img.shields.io/badge/Telegram-26A5E4?logo=telegram&logoColor=white)](https://t.me/trbsami)

