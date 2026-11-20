## Docker Compose - Sparta App

### Manual Seeding

1. Enter the folder:

`cd "manual seeding"`

2. Start containers:

`docker compose up -d`

3. Seed database:

`docker compose exec app node seeds/seed.js`

### Automatic Seeding

1. Start containers:

`docker compose up -d`
