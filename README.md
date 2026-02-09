# Cyber Security

## Owner 
- Phachara Piasai

## Email Owner
### 1.Google Mail 
- s6702041511063@email.kmutnb.ac.th
### 2.Outlook Mail
- s6702041511063@kmutnb.ac.th

## Enviroment
```sh
cp env.simple .env
```

## Running Services
```sh
------------------------   Database ---------------------
docker compose -f db.yaml up #monitoring
docker compose -f db.yaml up -d #background
------------------------   Admin ------------------------    
docker compose -f admin.yaml up #monitoring
docker compose -f admin.yaml up -d #background
------------------------   APP ---------------------------    
docker compose -f app.yaml up #monitoring
docker compose -f app.yaml up -d #background
```

## Last Changed
- 08/02/2569 | 20:40

