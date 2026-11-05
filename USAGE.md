# Install only when intended

The core uses bash, NetworkManager/nmcli and standard Linux tools. The status UI
requires Python/Gtk (python3-gi, gir1.2-gtk-3.0). Configure WIFI_GUARD_IFACE for your
network device. Install bin files into ~/.local/bin only after reviewing them.
The optional notifier now uses WIFI_GUARD_TELEGRAM_TOKEN and
WIFI_GUARD_TELEGRAM_CHAT_ID from the environment, so it does not need the trading
repo or its .env. It never stores the Wi-Fi password. No service is auto-enabled.
