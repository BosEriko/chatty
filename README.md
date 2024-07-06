# Chatty (Chat Client)
Download [Scoop](https://github.com/BosEriko/scoop) as your package manager then install [Chatty](https://scoop.sh/#/apps?q=chatty).

## Install Chatty
```sh
scoop bucket add extras
scoop install extras/chatty
```

## Sync your settings
Go to the folder where your Chatty files are located and run the following script.
```sh
curl -fsSL https://raw.githubusercontent.com/BosEriko/chatty/HEAD/install.sh | sh
```

_Note: Chatty files are usually located at %userprofile%/scoop/apps/chatty/current._