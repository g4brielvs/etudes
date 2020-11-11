# MacOs

## Security & Privacy

### System Integrity Protection Temporarily

> https://developer.apple.com/documentation/security/disabling_and_enabling_system_integrity_protection

#### Disable System Integrity Protection Temporarily

To disable SIP, do the following:

1. Restart your computer in Recovery mode.
2. Launch Terminal from the Utilities menu.
3. Run the command `csrutil disable`.
4. Restart your computer.


#### Enable System Integrity Protection

To reenable SIP, do the following:

1. Restart your computer in Recovery mode.
2. Launch Terminal from the Utilities menu.
3. Run the command `csrutil enable`.
4. Restart your computer.

### Reset and Remove Applications in Location Services

```sh
sudo -s

plutil -convert xml1 /var/db/locationd/clients.plist
```

```sh
plutil -convert binary1 /var/db/locationd/clients.plist
```