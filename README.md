# ✈️ Python Flight Booking System

## 📌 Project Overview

This is a **console-based Flight Booking System** developed using **Python**. The project simulates real-world airline booking operations such as checking flights, booking seats, making payments via UPI simulation, viewing bookings, and canceling bookings.

It is designed for **learning Python concepts** including:

* Dictionaries & nested data structures
* Functions & lambda expressions
* Loops and conditionals
* Random module
* Date & time handling
* Menu-driven programs

---

## 🛠 Technologies Used

* **Language:** Python 3
* **Modules:**

  * `random`
  * `datetime`

---

## 🧩 Features

### ✅ Check Available Flights

* View airlines
* View flights by selected airline
* Displays route, price, and available seats

### ✅ Flight Booking

* Passenger details input
* Seat availability check
* 10% discount applied automatically
* Random seat allocation
* Booking ID generation

### ✅ UPI Payment Simulation

* UPI ID verification
* PIN authentication
* Balance check
* Payment confirmation

### ✅ Booking Management

* View booking details using Booking ID
* View all bookings
* Cancel booking and restore seat count

---

## 💸 Discount Logic

A flat **10% discount** is applied on the total ticket price using a lambda function:

```
discount = lambda price: price - (price * 0.10)
```

---

## 🧾 Sample Airlines Included

* SkyJet
* AirNova
* FlyHigh
* Indigo

Each airline contains multiple flights with:

* Route
* Price
* Random seat availability

---

## 📋 Menu Options

1. Check Flights
2. Book Flight
3. Check Booking
4. Cancel Booking
5. View All Bookings
6. Exit

```
python flight_booking_system.py
```

---

## 🔐 Sample UPI Details (For Testing)

* **UPI ID:** `vinit@upi`
* **UPI PIN:** `8999`
* **Initial Balance:** `500000`

---

## 🎯 Learning Outcomes

* Understand real-world problem solving using Python
* Practice dictionary-based data modeling
* Learn menu-driven application design
* Implement basic payment logic

---

## 👨‍💻 Author

**Vinit Raparti**

---



