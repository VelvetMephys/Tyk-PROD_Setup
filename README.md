# Environnemnent de production Tyk sur 4 machines

## Description de l'environnement
- Tyk\-Dashboard
- Tyk\-Gateway
- Tyk\-Pump
- Redis
- MongoDb
- HAProxy
- ELK

## Description de l'architecture :
- [Serveur_Dashboard] : Dashboard + MongoDB + Pump
- [Serveur_Gateway 1] : Gateway
- [Serveur_Gateway 2] : Gateway
- [Serveur_Redis] : Redis
- [Serveur_ELK] : ELK

## Adresse IP et DNS :
Environnement | IP | DNS
----------| -----------|----------------
Dashboard | 51.75.196.202 | tyk-dashboard 
Gateway | 51.77.108.198  | tyk-gateway1 
Gateway | 51.83.12.162  | tyk-gateway2
Redis | 51.68.40.126  | tyk-redis
Gateway | 51.77.108.198  | tyk-redis

## Documentation Officielle :
- https://tyk.io/docs/get-started/with-tyk-on-premise/installation/redhat-rhel-centos/

[serveur_Dashboard]: https://github.com/VelvetMephys/Tyk-PROD_Setup/blob/master/INSTALLATION_DASHBOARD.md "guide d'installation du serveur Dashboard"
[serveur_Gateway 1]: https://github.com/VelvetMephys/Tyk-PROD_Setup/blob/master/INSTALLATION_GATEWAY_1.md "Guide d'installation du serveur Gateway"
[serveur_Gateway 2]: https://github.com/VelvetMephys/Tyk-PROD_Setup/blob/master/INSTALLATION_GATEWAY_2.md "Guide d'installation du serveur Gateway"
[serveur_Redis]: https://github.com/VelvetMephys/Tyk-PROD_Setup/blob/master/INSTALLATION_REDIS.md "Guide d'installation du serveur Redis"
[serveur_ELK]: https://github.com/VelvetMephys/Tyk-PROD_Setup/blob/master/INSTALLATION_ELK.md "Guide d'installation du serveur pour ELK"
