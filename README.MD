# Mini Booking Platform
## Descriere
Aplicație Spring Boot pentru gestionarea companiilor, utilizatorilor, deplasărilor și rezervărilor.
## Tehnologii
- Java 21
- Spring Boot 3
- PostgreSQL
- Docker
- JUnit + Mockito
## Pornire locală
```bash
mvn clean package
docker compose up --build
```
## API principal
- POST /api/companies
- GET /api/companies
- POST /api/users
- POST /api/trips
- PATCH /api/trips/{id}/approve
- POST /api/trips/{id}/bookings
- GET /api/trips/{id}/summary
## Testare
```bash
mvn test
```
## Autori
- Nume practicant