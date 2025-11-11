# Example config provider for the docker snap

> [!CAUTION] 
> The Docker snap with nvidia support writes to the config directory and modifies the daemon.json file. 
Changes made to daemon.json may be overwritten.

Build and install.

Connect:
```
sudo snap connect config-provider:docker docker:config-rw
```
