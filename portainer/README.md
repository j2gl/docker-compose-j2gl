# REAdME

Password will be prompted the first time you go to http://localhost:9000

If you want to delete Portainer Data including password, you will need to delete the volume data.   Example:

```sh
$ docker volume ls
local               portainer_portainer_data

$ docker volume rm portainer_portainer_data
```