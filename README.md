# 🚗 OOP Vehicle Practice

## 📘 Practice Overview

This practice helps you understand and apply **Object-Oriented Programming (OOP)** concepts in Java such as:

* **Inheritance**
* **Polymorphism**
* **Encapsulation**
* **Abstraction**

You will build a small program where multiple types of vehicles behave differently when accelerating, and drivers can operate them.

---

## 🎯 Acceptance Criteria (AC)

### ✅ AC1: Car acceleration

* A **Car** named `"Cool Car"` has a base speed of `25 km/h`.
* When it speeds up, it accelerates `5 km/h`.
* The car should display:
  🖨️ `Cool Car: speed up to 30 km/h`

### ✅ AC2: Truck acceleration

* A **Truck** named `"Big Truck"` has a base speed of `20 km/h`.
* When it speeds up, it accelerates `2 km/h`.
* The truck should display:
  🖨️ `Big Truck: speed up to 22 km/h`

### ✅ AC3: Driver abstraction

* A **Driver** can operate **any vehicle** (Car, Truck, etc).
* The driver should invoke the vehicle’s acceleration and print its result.
* For example:

    * When driving `Cool Car` → 🖨️ `Cool Car: speed up to 30 km/h`
    * When driving `Big Truck` → 🖨️ `Big Truck: speed up to 22 km/h`

### ✅ AC4: Car engine affects acceleration

* A **Car** uses an **Engine** to determine its acceleration.
* There are two types of engines:

    * `GasolineEngine` → provides `5 km/h` acceleration.
    * `ElectricEngine` → provides `10 km/h` acceleration.
* Example:

    * A car with `ElectricEngine` at `25 km/h` → 🖨️ `Cool Car: speed up to 35 km/h`

---

## 🛠️ Task Instructions

* Create the necessary classes and interfaces.
* Follow the OOP best practices.
* Use method overriding where necessary.
* Make sure the `Driver` class can accept any `Vehicle`.
* Implement `toString()` or custom display logic for printing output.

---

## 📦 Sample Output

```
Cool Car: speed up to 30 km/h
Big Truck: speed up to 22 km/h
Cool Car: speed up to 35 km/h
```

---

Happy coding! 🎉
