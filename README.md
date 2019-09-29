# Airbnb-clone

A Fullstack GraphQL Airbnb Clone with React and React Native

### Road Map

---

1. Website register / login
2. Deploy backend and frontend
3. App regiter / login
4. Website and App forgot password
5. Website and App create listing
6. Website and App view listings
7. Website and App chat
8. Feature requests

### Notes

---

- Typescript
- Ant Design

### Prerequisite

1. Postgres

```bash
# Pull postgreSQL Image
$ docker pull postgres

# Run PostgreSQL Container
$ docker run -d -p 5432:5432 --name pgsql -it --rm -v pgdata:/var/lib/postgresql/data postgres

# Run pgsql Container
$ docker exec -it pgsql bash

# Connect PostgreSQL in the Container
$ psql -U postgres
```

```sql
-- Create Database in PostgreSQL
$ CREATE DATABASE airbnbclone_dev;
$ CREATE DATABASE airbnbclone_test;

-- Check Databases
$ \list
```

2. Redis

```bash
# Pull postgreSQL Image
$ docker pull redis

# Run Redis Container
$ docker run -d -p 6379:6379 redis
```

3. Create React App in /packages/web

```bash
# Change the name of package.json to another name in root folder to avoid conflict & After install, Change back the name of package.json in root folder
$ npx create-react-app web --typescript
```
