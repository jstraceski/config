# config

## How to clone

```bash
git init
git config core.sparseCheckout true
git remote add -f origin git@github.com:jstraceski/config.git
```

Set the restricted directories.
```bash
git sparse-checkout set ./README.md ... # Add the directories here.
echo "*" > .gitignore
echo "/..." >> .gitignore # And here.
```

Checkout the main branch and pull the files.
```bash
git checkout main
git pull
```

## TP-Link setup info
* Enable WDS bridging on 2.4G network.
* Set the local LAN IP to be something other than the default.
* Disable DHCP.

