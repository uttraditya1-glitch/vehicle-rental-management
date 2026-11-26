# Vehicle Rental Management System

**Problem Statement No.:** 44  
**Course:** Bachelor of Technology in Computer Science and Engineering  
**Institution:** Rungta International Skills University – School of Computer Science and Engineering  
**Language:** Python 3  
**Core Concepts:** Object-Oriented Programming (OOP), Lists, Dictionaries, File Handling  

---

## Overview

A console-based **Vehicle Rental Management System** built in Python 3. The application allows users to add vehicles to an inventory, rent vehicles to customers for a specified number of days, process vehicle returns, and view currently available vehicles. Rental bills are calculated automatically—including a **10% discount** for rentals of 7 or more days—and all vehicle and rental states are persisted in a local `vehicles.txt` file.

---

## Features

* **Add Vehicles:** Dynamically registers new vehicles with sequential IDs (`V1`, `V2`, `V3`, etc.), vehicle type, model, and daily rental rate.
* **Rent Vehicles:** Validates vehicle availability and rental duration (minimum 1 day), blocks double-booking of already rented vehicles, and maps active rentals using a dictionary.
* **Automated Billing & Discounts:** Calculates `rate_per_day × days` and automatically applies a **10% discount** when renting for **7 or more days**.
* **Return Vehicles:** Updates the vehicle status back to `Available` and removes the completed entry from active rentals.
* **Persistent Storage:** Automatically saves and loads vehicle records and rental statuses using `vehicles.txt`.

---

## Project Structure

```text
├── rental_system.py   # Main Python 3 console application
├── vehicles.txt       # Auto-generated file storing vehicle inventory and rental status
└── README.md          # Project documentation


PROJECT MENTOR
Mentored by: Mr. Satyaprakash Sethy
GitHub: @SATYAPRAKASHSETHY
Role:   Python mentor/ Technical Guide
