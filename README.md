# ntfy-message-plugin-pwnagotchi
Unofficial plugin for pwnagotchi -- Sends message to a ntfy service when a handshake is captured

## How to install and configure:

### 1. Copy the ntfy_msg.py into your customplugins folder
### 2. Add following lines in your config.toml, set the ntfy_msg.serverlink to your ntfy topic url.
```
main.plugins.ntfy_msg.enabled = true
main.plugins.ntfy_msg.serverlink = "URL to ntfytopic"
```
### 3. Restart the pwnagotchi service or reboot the Pi


### And that's it, now you should get a ntfy notification when a handshake is captured. Important!! your pwnagotchi needs Internet connection for this so activate Bluetooth Tethering. 
