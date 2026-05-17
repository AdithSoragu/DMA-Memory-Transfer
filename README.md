# DMA Memory Transfer Simulation Using Keil

<p align="center">
  <img src="https://img.shields.io/badge/Language-Embedded C-blue">
  <img src="https://img.shields.io/badge/Simulation-Keil-green">
  <img src="https://img.shields.io/badge/Status-Completed-success">
</p>

## Overview
This project demonstrates a simple DMA (Direct Memory Access) memory transfer simulation using Embedded C in Keil µVision. The program transfers data from a source array to a destination array and verifies the transferred data using the Watch Window in Keil.

This project is completely simulation-based and does not require any hardware.

---

# Software Used
- Keil µVision
- Embedded C

---

# Project Type
Simulation Only (No Hardware Required)

---


# How To Execute The Project In Keil

## Step 1: Open Keil µVision
Open the Keil µVision software.

---

## Step 2: Create New Project
- Go to:
  ```
  Project → New µVision Project
  ```
- Create a folder for the project.
- Save the project.

---

## Step 3: Select Device
- Select any generic device or default target.
- Click OK.

---

## Step 4: Create Source File
- Go to:
  ```
  File → New
  ```
- Paste the program code.
- Save the file as:
  ```
  adith.c
  ```

---

## Step 5: Add File To Project
- In Project Window:
  ```
  Source Group 1
  ```
- Right-click:
  ```
  Add Existing Files to Group
  ```
- Select:
  ```
  adith.c
  ```

---

## Step 6: Build The Project
Press:
```text
F7
```

OR

Go to:
```text
Project → Build Target
```

---

## Step 7: Start Debug Session
Press:
```text
Ctrl + F5
```

OR

Go to:
```text
Debug → Start/Stop Debug Session
```

---

## Step 8: Open Watch Window
Go to:
```text
View → Watch Windows → Watch 1
```

---

## Step 9: Add Variables
Add the following variables:

```text
destination[0]
destination[1]
destination[2]
destination[3]
destination[4]
```

---

## Step 10: Run Simulation
Press:
```text
F5
```

---

# Expected Output

## Before DMA Transfer

```text
destination[0] = 0
destination[1] = 0
destination[2] = 0
destination[3] = 0
destination[4] = 0
```

---

## After DMA Transfer

```text
destination[0] = 10
destination[1] = 20
destination[2] = 30
destination[3] = 40
destination[4] = 50
```

---

# Working Principle
The DMA transfer function copies data automatically from the source array to the destination array.

```text
Source Memory  →  Destination Memory
```

---

# Applications
- Embedded Systems
- DMA Concept Demonstration
- Memory Transfer Systems
- Educational Simulation Projects

---

# Advantages
- Simple and beginner friendly
- No hardware required
- Easy simulation in Keil
- Useful for understanding DMA concepts

---

# Conclusion
The project successfully demonstrates DMA memory transfer simulation using Embedded C in Keil µVision. The transferred data is verified using the Watch Window during simulation.

---

# Author
Adith Soragu
