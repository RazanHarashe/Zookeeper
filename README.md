# Zookeeper 

This project helps a zookeeper track the energy levels of her animals, focusing on mammals. It includes classes for general mammals, a specific gorilla, and a rare giant bat.

## Description

### Mammal Class
The `Mammal` class represents a generic mammal with:
- `energyLevel` (default 100)
- `displayEnergy()` method to print and return the current energy level

### Gorilla Class
The `Gorilla` class extends `Mammal` and includes:
- `throwSomething()`: Decreases energy by 5 and prints a message.
- `eatBananas()`: Increases energy by 10 and prints a message.
- `climb()`: Decreases energy by 10 and prints a message.

### Bat Class
The `Bat` class extends `Mammal` with:
- `energyLevel` (default 300)
- `fly()`: Decreases energy by 50 and prints a message.
- `eatHumans()`: Increases energy by 25 and prints a message.
- `attackTown()`: Decreases energy by 100 and prints a message.

## Usage

### GorillaTest
The `GorillaTest` class demonstrates the `Gorilla` class functionality:
- Throws three things
- Eats bananas twice
- Climbs once
- Displays the energy level

### BatTest
The `BatTest` class demonstrates the `Bat` class functionality:
- Attacks three towns
- Eats two humans
- Flies twice
- Displays the energy level
