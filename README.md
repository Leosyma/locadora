# 🚗 Car Rental CLI App

A simple command-line application built with Python that simulates a car rental service. Users can view available cars, rent a car for a number of days, and return rented cars. The program manages a portfolio of cars and updates the availability based on user interactions.

---

## 📌 Features

### 1. View Available Cars
- Users can display a list of available vehicles for rent.
- Each vehicle is shown with a daily rental price and an index code for selection.

### 2. Rent a Car
- Users can select a car to rent by entering its corresponding code.
- The system asks for the rental duration and calculates the total price.
- Upon confirmation, the car is marked as rented and removed from the available list.

### 3. Return a Car
- Users can return a previously rented vehicle.
- A list of rented cars is displayed to choose from.
- Upon return, the car is added back to the list of available cars.

---

## ⚙️ Technologies Used
- **Python 3**
- **os** module for terminal control

---

## ▶️ How to Run

```bash
python locadora.py
```

---

## 📦 Project Structure

```
locadora.py      # Main script with rental logic
```

---
