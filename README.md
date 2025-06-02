# SpaceX Dragon Rocket Repository

## Description
A simple, test-driven Java library to manage SpaceX missions and rockets. No frameworks, no APIs – just clean domain modeling and behavior.

## Features
- Add and assign rockets to missions
- Update rocket and mission status
- Get mission summary report, sorted by logic
- In-memory implementation
- TDD with JUnit5

## Instructions
1. Clone the repo
2. Run tests with `mvn test`
3. Use `SpaceXService` class in your app

## Assumptions
- A rocket can be assigned to only one mission at a time.
- Mission status updates automatically based on rocket status.
- Ended missions retain their rockets (unless needed otherwise).
