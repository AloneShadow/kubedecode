# Kubedecode

Utility to extract and decode a kubernetes secret.

## Install
* run `wget https://raw.githubusercontent.com/AloneShadow/kubedecode/master/kubedecode`
* `sudo mv kubedecode /usr/local/bin`
* `sudo chmod +x /usr/local/bin/kubedecode`

## Run
* `kubedecode <kube_namespace>` lists all available secrets inside a given namespace
* `kubedecode <kube_namespace> [<kube_secret>]` return a secret value
