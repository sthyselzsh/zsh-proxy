# zsh-proxy

![](pics/slender.png)

zsh plugin to deal with corp proxies.

Set site specific proxy detail in ~/.proxy.conf

```
PROXY=http://${PROXY_USER}:${PROXY_PASSWORD@10.11.12.13:6666
NO_PROXY=localhost,.bulshitcorp.net,jira,complaints,whistleblowerblower
```

Provides 

| Command | Description |
| ------- | ----------- |
| proxy-on | Enables proxy | 
| proxy-off | Disables proxy | 

# Install



# Install using zplug

Using [zplug](https://github.com/zplug/zplug) in .zshrc 

```
zplug "sthysel/zsh-proxy"
```

