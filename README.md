# 🍽️ Food Management and Menu Creation Application

> **Course:** Modeling and Design
> **Academic Year:** 2024/2025
> **Degree:** Bachelor in Informatics Engineering - ISEC

## 📋 About the Project

This repository contains the analysis and design artifacts for the development of an information system focused on optimizing family food management. The main goal of the application is to suggest recipes based on family preferences and assist in the efficient management of existing household food stock (pantry, fridge, and freezer), avoiding waste and facilitating the creation of shopping lists.

The project is developed in a team and divided into three phases: Vision and Scope, Problem Analysis, and Solution Design.

## ✨ Key Features

Based on the analyzed requirements, the solution was designed to support:

* **Stock Management:** Control of food items in the pantry, fridge, and freezer, including expiration dates, quantities, and location.
* **Meal Scheduling:** Planning menus in an agenda, defining the moment of consumption and the time block required for cooking.
* **Smart Recipe Suggestions:** Suggestions based on existing ingredients and dietary restrictions, with the ability to scale portions.
* **Shopping List Management:** Automatic addition of missing ingredients and suggestion of supermarkets with the best distance/price ratio.
* **External Integrations:** Exporting the meal agenda to external calendars (e.g., Google Calendar).
* **Reminder System:** Notifications for food defrosting and cooking start times.

## 🏗️ Architecture and Design (Phase 3)

The current phase of the project focuses on **Solution Design**, specifically detailing the planning and structure of the system.

### Focus Use Case: "Schedule Meal"
The detailed design focuses on the process of a family member planning future meals. The system checks stock availability, interacts with external services, and manages reminders.

**Involved Actors:**
* **Family Member:** Main user.
* **Recipe Service:** Suggests dishes and instructions.
* **Calendar Service:** Syncs the agenda.
* **Supermarket Service:** Suggests purchasing locations.

### Produced Artifacts
In this phase, the following UML diagrams and models were created:
1.  **Updated Domain Model:** Representation of entities such as `Meal`, `Recipe`, `Ingredient`, `Stock`, and `Meal Agenda`.
2.  **System Sequence Diagram (SSD):** Mapping of interactions for scheduling, including alternative scenarios (service failure or missing ingredients).
3.  **Class Diagram (Low Level):** Software class structure, including controllers (`ControladorRefeicoes`) and data management (`GestorIngrediente`, `AgendamentoReceita`).
4.  **Sequence Diagrams (Low Level):** Detail of internal message exchange, such as the `selectRecipe` and `checkAvailability` methods.

## 👥 Development Team

* **Duarte Xavier de Oliveira Santos** (2022149622)
* **Gustavo Trigo Costa** (2023145800)
* **Gonçalo Ferraz Bento** (2023137116)

---
*Note: This project is a fictional scenario for the purpose of developing software modeling and teamwork skills.*
