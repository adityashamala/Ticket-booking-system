# 🎬 KMIT Theatre Booking System

A console-based theatre ticket booking system developed using **C programming**.

This project simulates a theatre reservation experience where users can view available seats, choose between regular and recliner seating, and book tickets through an interactive menu-driven interface.

## ✨ Features

- **Interactive Menu:** Simple and user-friendly console interface.
- **Seating Arrangement:** 10 × 10 theatre seating layout.
- **Two Seating Categories:**
  - Regular Seats (Rows 0–7)
  - Recliner Premium Seats (Rows 8–9)
- **Dynamic Seat Selection:** Users can select seats using row and column numbers.
- **Seat Availability:** Prevents users from booking seats that are already occupied.
- **Different Pricing:** Separate pricing for regular and recliner seats.
- **Booking Flow:** Collects customer details and simulates a payment process.
- **Multiple Bookings:** Allows users to make additional bookings during the same session.

## 🛠️ Technologies Used

- C Programming
- 2D Arrays
- Loops and Conditional Statements
- User Input/Output
- Basic Data Validation

## 🎟️ Seating Layout

The theatre consists of 100 seats arranged in a 10 × 10 grid.

| Seat Category | Rows | Price |
|---|---|---|
| Regular | 0–7 | 50 |
| Recliner Premium | 8–9 | 100 |

### Seat Symbols

| Symbol | Meaning |
|---|---|
| `_` | Available Regular Seat |
| `R` | Available Recliner Seat |
| `*` | Booked Seat |

## 🚀 How to Run

### Prerequisites

Install a C compiler such as GCC.

### Compilation

```bash
gcc main.c -o theatre
```

### Execution

**Windows:**
```bash
theatre.exe
```

**Linux/macOS:**
```bash
./theatre
```

## 📸 Sample Output

The application displays:
- Welcome screen
- Customer details input
- Theatre seating arrangement
- Ticket pricing
- Seat selection interface
- Booking confirmation

## 🔮 Future Improvements

- Persistent booking records using file handling.
- Customer account management.
- Improved seat availability tracking.
- Admin dashboard for managing bookings.
- Enhanced input validation.
- Modular implementation using functions.

## 👨‍💻 Author

**Aditya Shamala**

GitHub: [@adityashamala](https://github.com/adityashamala)

---

*Built as a beginner-level C programming project to practise programming fundamentals and application logic.*
