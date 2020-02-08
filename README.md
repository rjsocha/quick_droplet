# quick_droplet
Tool for quickly creating Digital Ocean's droplets (terraform frontend)


This tool is for my internal use.

It's terraform config generator for quick droplet creation for my lab.

DNS domain names are hardcoded in tool (this can be easly extended to parse some kind of config file)

This tool *will not* work for you without customisation!

Usage:
```
define Digital Ocean's access token in variable

export NAUKA_DIGITALOCEAN_TOKEN=xxxxxxxxxxxxxxxxxxxxxxx

./quick_droplet NAME.do.nauka.ga 
```

