# systemd-services
Systemd services for Eupnea

### eupnea-postinstall
One-shot service, executes postinstall.py in /usr/local/bin. Is disabled by the postinstall script after running

### eupnea-update
Two units, a timer which triggers every 24h and executes the service file, which updates the depthboot/eupneaos system.
