# ABSTRACTION-Automation-System

## Overview
This repository contains a Python solution to the OOP case study activity 
titled **"Building Automation System"**, developed as part of coursework 
at the University of Mines and Technology (UMaT).

## Task Summary
UMaT's new auditorium uses several automated systems that each perform 
different tasks but must share a common interface. This project models 
that scenario using **abstraction** and **polymorphism**:

- An abstract class `BuildingSystem` defines the common interface with 
  abstract methods `start()`, `stop()`, and `status()`.
- Three concrete child classes — `AirConditioningSystem`, `LightingSystem`, 
  and `SecuritySystem` — implement these methods according to their own 
  behaviour.
- All system objects are stored in a single list and processed uniformly 
  in a loop, demonstrating polymorphic behaviour.
- A new class, `FireAlarmSystem`, was added afterward and integrated into 
  the same list **without modifying the existing processing loop**, 
  showing how abstraction supports extensibility.

## Concepts Demonstrated
- Abstraction (via Python's `ABC` module)
- Inheritance
- Polymorphism
- Open/Closed Principle (extending behaviour without modifying existing code)

## How to Run
1. Clone the repository.
2. Open the notebook or script file.
3. Run all cells / execute the script to see each system's start, status, 
   and stop behaviour printed to the console.

## Author
Matthew Cobbinah (GitHub: MatthewCobbinah)
