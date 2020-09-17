# Desktop App QA Builds

This repo holds QA builds.

### Documentation

* [Public-facing README](https://github.com/tigerconnect/desktop-app)

### Download QA Releases

QA releases of the TigerConnect Desktop App may be downloaded at the following locations:

* [Windows - Single-click installer](https://github.com/tigertext/web-desktop-app-qa/releases/latest/download/TigerConnect-Setup.exe)
* [Mac OS](https://github.com/tigertext/web-desktop-app-qa/releases/latest/download/TigerConnect.dmg)
* [Debian-compatible GNU/Linux](https://github.com/tigertext/web-desktop-app-qa/releases/latest/download/TigerConnect-latest.deb)

Other installation options:

* [Windows - Admin installer](https://github.com/tigertext/web-desktop-app-qa/releases/latest/download/TigerConnect-Admin-Setup.exe)

### Configuration

Locate the [user-specific config.yaml file](https://github.com/tigerconnect/desktop-app)#user-configuration-file).

Example of using the QA auto-update channel:

```yaml
autoUpdateOptions:
  provider: "github"
  repo: "web-desktop-app-qa"
  owner: "tigertext"
```

Example of using Messenger from the UAT environment:

```yaml
targetUrl: "https://login.tigerconnect.com/uat/app/messenger/?apiEnv=prod"
```
