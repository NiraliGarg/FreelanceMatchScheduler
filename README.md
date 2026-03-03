# FreelanceMatchScheduler

A simple Java application developed as part of a data structures and algorithms course project. The program reads a list of freelance assignments from a CSV dataset and allocates them to suitable freelancers using basic matching logic. A graphical user interface (GUI) written with Swing allows users to load the data and view assignment results.

## 📌 Project Overview

The project consists of three main Java classes:

- **Project.java** – Represents a single freelance project with attributes such as title, required skills, budget, and duration.
- **FreelanceProjectAllocator.java** – Contains the core allocation logic. It parses the CSV dataset and assigns projects to available freelancers based on simple heuristic rules.
- **FreelanceMatchGUI.java** – Provides a basic GUI that lets the user choose the dataset file, trigger the allocation algorithm, and display the matched pairs.

The CSV file (`feelance_dataset.csv`) holds sample data used by the application.

## 🛠 Features

- Parses a comma‑separated file of project descriptions.
- Matches projects to freelancers using a first‑fit style algorithm.
- Displays assignments in a Swing window.
- Easy to extend with more advanced matching strategies or additional attributes.

## 🚀 Getting Started

Follow these steps to compile and run the application on a Windows machine with JDK installed:

1. Clone or download the repository:
   ```bash
   git clone https://github.com/NiraliGarg/FreelanceMatchScheduler.git
   cd FreelanceMatchScheduler
   ```
2. Make sure the dataset file `feelance_dataset.csv` is in the project root (it already is in this repo).
3. Compile the Java source files:
   ```powershell
   javac *.java
   ```
4. Run the GUI:
   ```powershell
   java FreelanceMatchGUI
   ```

The GUI will prompt you to select the CSV file and then allocate projects when you click the "Match Projects" button.

## 🎓 Notes for Students

- This project was created to demonstrate object‑oriented design, file I/O, and basic algorithm implementation in Java.
- You are encouraged to modify and experiment with the matching logic (e.g., try greedy, backtracking, or optimization techniques).
- The dataset can be replaced with your own test cases to see how the allocator behaves.

## 📁 Repository Structure

```
FreelanceMatchScheduler/
├─ README.md          (this file)
├─ feelance_dataset.csv
├─ FreelanceMatchGUI.java
├─ FreelanceProjectAllocator.java
└─ Project.java
```

## 📄 License

This repository is released for educational purposes. Feel free to use the code for learning and experimentation.

---

*Created by a student for a DAA (Design and Analysis of Algorithms) course project.*
