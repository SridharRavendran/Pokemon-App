# Pokemon-App

A full-stack Pokémon web application that allows users to view a list of Pokémon, filter and search them by various attributes, and view detailed information about individual Pokémon.

## Features

### Frontend:
- View a list of Pokémon with their ID, name, type, and image.
- Search for Pokémon by name.
- Filter Pokémon by type (e.g., Fire, Water, Grass).
- Pagination to navigate through the list (10 Pokémon per page).
- Detailed Pokémon page showing:
  - ID, name, type, height, weight, and image.
  - Stats: HP, Attack, Defense, Special Attack, Special Defense.
  - Similar Pokémon based on type.

### Backend:
- RESTful APIs built using Node.js and Express.js.
- Database designed with PostgreSQL to store Pokémon data.
- Dynamic seeding of Pokémon data from the [PokeAPI](https://pokeapi.co/).
- APIs for fetching Pokémon list, details, and similar Pokémon.

---

## Tech Stack

### Frontend:
- React.js: For building the user interface.
- Axios: For making HTTP requests.
- React Router DOM: For routing and navigation.

### Backend:
- Node.js: Backend runtime environment.
- Express.js: Web framework for building RESTful APIs.
- Sequelize: ORM for interacting with the database.
- PostgreSQL: Relational database for storing Pokémon data.

---

## Pre-requisites

### Software:
- Node.js (v18 or higher)
- PostgreSQL (v12 or higher)
