# Concurrent Set Game

A multi-threaded Java implementation of the Set card game, developed as a team software engineering project.

## Overview

This project implements the core logic of the Set card game using Java concurrency concepts.  
The game includes multiple players, a dealer, shared table state, synchronization mechanisms, scoring, penalties, and automated testing.

## Technologies

- Java
- Maven
- JUnit
- Mockito
- Object-Oriented Programming
- Multithreading
- Synchronization
- Semaphores
- Blocking Queues

## Key Features

- Multi-threaded game flow
- Separate player threads
- Dealer thread responsible for game management
- Thread-safe card and token handling
- Synchronization over shared table resources
- Human and computer player support
- Scoring and penalty system
- Unit tests for core components

## Main Components

### Dealer
Manages the game flow, card dealing, set validation, timer handling, player submissions, and winner announcement.

### Player
Represents a player thread, handles key presses, token placement, penalties, scoring, and AI simulation for computer players.

### Table
Maintains the shared table state, including card-slot mapping, token placement, and synchronized access to table slots.

## Project Type

Team Project

## Skills Demonstrated

- Concurrent programming in Java
- Thread synchronization
- Shared resource management
- Object-oriented system design
- Unit testing
- Maven-based project structure
