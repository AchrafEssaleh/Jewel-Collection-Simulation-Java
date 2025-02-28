# Jewel Collection Simulation (Java)

This project simulates a grid-based environment where players collect various jewels while navigating obstacles and interacting with guardians. It demonstrates advanced Object-Oriented Programming (OOP) in Java, effective game mechanics implementation, and clean code design.

## Features
- Grid-based simulation environment
- Multiple jewel types and interactive obstacles
- Dynamic gameplay with guardians (including teleportable guardians)
- Robust exception handling for invalid moves and coordinates

## Folder Structure
- **/src**: Contains all Java source files:
  - `TestSimulation.java`: Main test class that runs the simulation.
  - `Teleportable.java`: Interface for teleportable entities.
  - `Agent.java`: Class representing the simulation agent.
  - `CaseNonPleineException.java`: Exception for handling non-full cases.
  - `CoordonneesIncorrectesException.java`: Exception for incorrect coordinates.
  - `DeplacementIncorrectException.java`: Exception for invalid movements.
  - `Gardien.java`: Class representing a guardian.
  - `GardienTeleportable.java`: Subclass of Gardien with teleportation capability.
  - `Joyaux.java`: Class representing jewels.
  - `Simulation.java`: Class that manages and runs the simulation.

## How to Compile and Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/YourUsername/Jewel-Collection-Simulation-Java.git
