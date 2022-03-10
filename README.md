# sonarqube / windows

## pré-requis

WSL, Docker Desktop

## install

1. Dans une invite de commande :
```
wsl -d docker-desktop
sysctl -w vm.max_map_count=262144
```
2. Ensuite, lancer Docker Desktop

(a priori, la conf sysctl est à refaire à chaque reboot de windows)

## run

[http://localhost:9000](http://localhost:9000)

{admin, admin}

(admin1)