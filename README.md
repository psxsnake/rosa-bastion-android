# ROSA CLI Mobile

Android app to manage OpenShift ROSA cluster via SSH tunnel + VPN.

## Quick Start

1. Clone repo
2. Open in Android Studio
3. Copy `local.properties.example` → `local.properties` and fill your data
4. Build → Make Project
5. Install APK on phone

## local.properties template

bastion.host=10.99.0.10
bastion.port=22
bastion.user=middleware
bastion.key=-----BEGIN OPENSSH PRIVATE KEY-----\nYOUR_KEY\n-----END OPENSSH PRIVATE KEY-----\nvpn.config=client\ndev tun\nremote your-bastion.com 1194\n...cert/key...
