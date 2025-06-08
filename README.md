[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8Wlm3hvS)

Wiktor Koncewicz

Instrukcja odpalenia projektu.

## Kroki wstępne
```
git clone https://github.com/konrad-ug/bezpiecze-stwo-aplikacji-webowych-wkoncewicz.git wkoncewicz-projekt
cd wkoncewicz-projekt
npm install
```

## Keycloak
```
docker run -p 8080:8080 -v "${PWD}/keycloak_data_backup:/opt/keycloak/data" -e KC_BOOTSTRAP_ADMIN_USERNAME=admin -e KC_BOOTSTRAP_ADMIN_PASSWORD=admin quay.io/keycloak/keycloak:26.1.4 start-dev
```

## Backend
```
node backend/index.js
```

## Frontend
```
npm start
```

## Użytkownicy
| Username     | Password | Czy Admin |
| rwaters      | user     | tak       |
| regular-user | user     | nie       |