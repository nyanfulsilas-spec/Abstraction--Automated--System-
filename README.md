# Abstraction--Automated--System-
# ABSTRACTION-Automation-System

This repository contains a Python implementation of an automated management system for UMaT's new auditorium, demonstrating **Abstraction** and **Polymorphism**.

## Features

- **Abstract Base Class (`BuildingSystem`)**: Defines standard abstract methods (`start()`, `stop()`, `status()`) that all sub-systems must implement.
- **Polymorphic Execution**: Dynamically manages multiple subsystems (`AirConditioningSystem`, `LightingSystem`, `SecuritySystem`, and `FireAlarmSystem`) via a unified processing loop.
- **Extensibility**: Demonstrates the Open/Closed Principle by integrating a new `FireAlarmSystem` class without modifying the existing execution loop.

