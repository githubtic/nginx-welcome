# Projet Docker + Nginx + HTTPS prêt à l'emploi

## Étapes

1. Remplace `mon-domaine.com` dans `nginx/default.conf` par ton domaine réel.
2. Construis et démarre les conteneurs :
```bash
docker-compose up -d --build
```
3. Le site sera accessible sur HTTPS automatiquement.

Certbot s'occupe du renouvellement automatique des certificats.
