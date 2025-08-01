# Yasb & Komorebi

## Yasb

### Setup

```shell
winget install --id AmN.yasb
```

### Widgets Included

- [Weather](<https://github.com/amnweb/yasb/wiki/(Widget)-Weather#example-configuration>)
- [Cava](<https://github.com/amnweb/yasb/wiki/(Widget)-Cava#cava-widget-configuration>)
- [Wallpapers](<https://github.com/amnweb/yasb/wiki/(Widget)-Wallpapers#example-configuration>)
- [Disk](<https://github.com/amnweb/yasb/wiki/(Widget)-Disk#example-configuration>)
- Media
- Volume
- Wifi
- Battery
- Settings
- Notifications
- Power Menu

### Yasb Theme

- Fluent Design
- Aero Glass
- Acrylic
- Windows 11 Theme

### NOTE

```
Copy my config.yaml & styles.css
```

## Komorebi

### Setup

1. It is highly recommended that you enable support for long paths in Windows by running the following command in an Administrator Terminal before installing `komorebi`.

```shell
Set-ItemProperty 'HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem' -Name 'LongPathsEnabled' -Value 1
```

2. Install the `komorebi` and `whkd` packages using `winget install`.

```shell
winget install LGUG2Z.komorebi
winget install LGUG2Z.whkd
```

3. Run the following command to download example configuration files for `komorebi` and `whkd`. Pay attention to the output of the command to see where the example files have been downloaded. For most new users this will be in the `$Env:USERPROFILE` directory.

```shell
komorebic quickstart
```

With the example configurations downloaded, you can now start `komorebi` and `whkd`.

```shell
komorebic start --whkd
```

### NOTE

```
Copy my komorebi.json
```
