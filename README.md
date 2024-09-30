# WIFI-password
 Wifi_Password_Master

People ask you for the Wi-Fi password. Answer quickly. **macOS only**.
[Windows version](https://github.com/4lph4shell/WIFI-password).

![](https://i.cloudup.com/uUo8iSbKXRh/km6iJT.gif)

## How to use

**1. Install it**
with `curl`:

```
curl -L https://github.com/4lph4shell/WIFI-password.git & cd WIFI-password  -o ~/bin/wifi-password && chmod +x ~/bin/wifi-password
```

If you don't have `~/bin` in your `$PATH`, replace it with `/usr/local/bin` or
similar.

**2. Use it:**

To get the password for the WiFi you're currently logged onto:

```
$ wifi-password
```

To get it for a specific SSID:

```
$ wifi-password <ssid>
```

To put it straight in your clipboard for pasting elsewhere (OS X only):

```
$ wifi-password | pbcopy
```

## License

MIT
