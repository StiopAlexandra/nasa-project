# NASA Mission Control Project

This repository is part of the [Complete Node.js Developer: Zero to Mastery](https://academy.zerotomastery.io/a/aff_jqtq5631/external?affcode=441520_1jw4f2ay) course. 
The project simulates the core functions of a NASA mission control center, allowing users to schedule, manage, and track upcoming space missions using real NASA data. Users can plan missions by selecting target planets, setting launch dates, and tracking mission status, all while interacting with real-world data on habitable planets.

## Getting Started

1. Ensure you have Node.js installed.
2. Create a free [Mongo Atlas](https://www.mongodb.com/atlas/database) database online or start a local MongoDB database.
3. Create a `server/.env` file with a `MONGO_URL` property set to your MongoDB connection string.
4. In the terminal, run: `npm install`

## Running the Project

1. In the terminal, run: `npm run deploy`
2. Browse to the mission control frontend at [localhost:8000](http://localhost:8000) and schedule an interstellar launch!

## Docker

1. Ensure you have the latest version of Docker installed
2. Run `docker build -t nasa-project .`
3. Run `docker run -it -p 8000:8000 nasa-project`
