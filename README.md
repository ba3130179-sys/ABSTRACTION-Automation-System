# ABSTRACTION-Automation-System
Boateng Bruhaan
FOE.21.006.018.24
# Abstractio_Automation_system
# ABSTRACTION-Automation-System

## Project Overview
Building Automation System for UMaT's new auditorium. This project demonstrates abstraction and runtime polymorphism in Object-Oriented Programming. All automated systems share a common interface but implement unique behaviors.

## Task Requirements
1. Create an abstract class `BuildingSystem`
2. Define abstract methods: `start()`, `stop()`, `status()`
3. Implement child classes: `AirConditioningSystem`, `LightingSystem`, `SecuritySystem`
4. Store objects in a list and demonstrate polymorphic behavior by calling each method
5. Add a new class `FireAlarmSystem` without modifying the existing processing loop

## Implementation
- **Language**: Python 3
- **Core File**: `building_automation.py`
- **Abstract Base Class**: `BuildingSystem` uses `ABC` module to enforce method implementation
- **Child Classes**: Each system overrides `start()`, `stop()`, `status()` with specific logic
- **Polymorphism**: Main loop iterates through a list of systems and calls methods uniformly without type checking
