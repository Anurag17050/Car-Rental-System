# Car-Rental-System
# Car Rental System (Java)

This project is a simple **console-based Car Rental System** implemented in Java. It demonstrates Object-Oriented Programming (OOP) concepts such as classes, objects, encapsulation, lists, and user interaction using `Scanner`.

---

## 🚗 Features

* Add cars and customers to the system
* Rent available cars
* Return rented cars
* Auto-calculated rental price based on days
* Displays rental info before confirmation
* Menu-driven user interface

---

## 🧩 Project Structure

```
Main.java
├── Car               // Car details and availability
├── Customer          // Customer details
├── Rental            // Rental info (car + customer + days)
└── CarRentalSystem   // Core system logic + menu UI
```

---

## 📌 Classes Overview

### **Car**

* Stores car ID, brand, model, base price per day
* Calculates rental cost
* Tracks availability

### **Customer**

* Stores customer ID and name

### **Rental**

* Connects a car with a customer and rental duration

### **CarRentalSystem**

* Holds lists of cars, customers, rentals
* Handles renting/returning
* Menu-driven interface

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/car-rental-system.git
```

2. Navigate to the project folder:

```bash
cd car-rental-system
```

3. Compile the Java file:

```bash
javac Main.java
```

4. Run the program:

```bash
java Main
```

---

## 🖥️ Sample Output (Menu)

```
===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice:
```

---

## 🏗️ Future Enhancements (Ideas)

* Store data in files or database
* Add login for admin & customers
* Add car categories (SUV, Sedan, etc.)
* Track total income
* Maintain rental history

---

## 🤝 Contributing

Feel free to fork this project and submit pull requests.

---

## 📄 License

This project is licensed under the MIT License.
