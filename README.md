
# Cardano Ninja

### Demo
https://cardano.ninja

## How to run your own server

### Requirements

- Docker and docker-compose installed

### Instructions

- Download the code.
- Go to the folder docker-compose.
- Edit the file .env with your own blockfrost project api key (get one for free in https://blockfrost.io)
- Run: docker-compose up

## How it works

### Components

Cardano ninja is divided in several components:

- WebApp/Website (react app)
- Api (provides data from the database to the website)
- Database (MongoDb)
- Data Gatherer (retrieves the data from the blockchain and populates the database, constantly polls the blockchain for new data)
