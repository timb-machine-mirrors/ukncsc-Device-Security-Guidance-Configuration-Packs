## NCSC iOS configurations ##
|MDM settings||
|---|---|
||
|General||
|Security (Controls when the profile can be removed)|Never|
|Automatically Remove Profile (Settings for automatic profile removal)|Never|
||
|Restrictions - Functionality tab||
|Allow AirDrop (supervised devices only)|No|
|Allow Siri whilst device is locked|No|
|Allow iCloud backup|No|
|Allow iCloud documents & data|No|
|Allow iCloud Keychain|No|
|Allow managed apps to store data in iCloud|No|
|Force encrypted backups|Yes|
|Force limited ad tracking|Yes|
|Allow users to accept untrusted TLS certificates|No|
|Allow trusting new enterprise app authors|No|
|Allow installing configuration profiles (supervised only)|No|
|Allow adding VPN Configurations (supervised only)|No|
|Allow modifying account settings (supervised only)|No|
|Allow USB accessories while device is locked (supervised only)|No|
|Allow pairing with non-Configurator hosts (supervised only)|No|
|Allow documents from managed sources in unmanaged destinations|No|
|Allow documents from unmanaged sources in managed destinations|No|
|Treat AirDrop as unmanaged destination|Yes|
|Allow sending diagnostic and usage data to Apple|No|
|Force Apple Watch wrist detection|Yes|
|Show Control Centre in Lock screen|No|
|Show Notification Centre in Lock screen|No|
|Show Today view in Lock screen|No|
||
|Restrictions - Apps tab�||
|Restrict App Usage (supervised only)|Do not allow some apps: com.apple.shortcuts|
||
|VPN configuration - IPsec PRIME profile||
|Connection type|IKEv2|
|Always-on (supervised only)|Yes|
|Machine Authentication|Certificate|
|Enable perfect forward secrecy|Yes|
|Enable certificate revocation check|Yes|
|Encryption algorithm (IKE & Child SA)|AES-128-GCM|
|Diffie-Hellman Group (IKE & Child SA)|19|
|Allow traffic from captive web sheet outside the VPN tunnel|Yes|
||
|Passcode||
|Allow simple value|Configure to organisation policy|
|Require alphanumeric value|Configure to organisation policy|
|Minimum passcode length|Configure to organisation policy|
|Minimum number of complex characters|Configure to organisation policy|
|Maximum passcode age|Configure to organisation policy|
|Maximum Auto-Lock|Configure to organisation policy|
|Passcode history|Configure to organisation policy|
|Maximum grace period for device lock|Configure to organisation policy|
|Maximum number of failed attempts|Configure to organisation policy|
||
|On-device settings||
||
|Notifications||
|Show Previews|Never|
||