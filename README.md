# Hi, I'm Nicholas Nicolaou 👋

**Software Engineering with Electronics student** @ University of Westminster · Year 2  
Building things that live at the intersection of code and hardware.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nicholas-nicolaou-072a961b7)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Nicolaou2002@gmail.com)

---

## About Me

I'm a second-year Software Engineering with Electronics student with a passion for embedded systems, mobile development, and projects that bridge the physical and digital worlds.

- 🔭 Currently working on: **Custom Robot Arm (Co-Creators paid project) · SCC Robot Arm**
- 🌱 Learning: **Fusion 360 CAD · Robot kinematics · 3D printing & fabrication**
- 💼 Open to: **Summer internships & placements (2026)**
- 🎓 Expected graduation: **2027**

---

## 🛠️ Skills & Tech Stack

### Languages
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![PIC Assembly](https://img.shields.io/badge/PIC_Assembly-555555?style=flat-square&logoColor=white)
![KSH](https://img.shields.io/badge/Shell_Scripting-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

### Hardware & Embedded
![MBED](https://img.shields.io/badge/MBED-0091BD?style=flat-square&logoColor=white)
![PIC Microcontroller](https://img.shields.io/badge/PIC_Microcontroller-EE3124?style=flat-square&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)

### Tools & Platforms
![MPLABX](https://img.shields.io/badge/MPLABX-EE3124?style=flat-square&logoColor=white)
![Eagle](https://img.shields.io/badge/Eagle_PCB-0079C1?style=flat-square&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion_360-FF6D00?style=flat-square&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat-square&logo=android-studio&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

---

## 💻 Software Projects

### [Directed Graph Acyclicity Checker](https://github.com/N-Nicolaou/graph-acyclicity-checker)
**Tech:** C++ · Data Structures · Algorithm Design  
**Grade: 100%** — C++ program that determines whether a directed graph is acyclic or cyclic. Implemented a custom adjacency list with a reverse adjacency list optimisation, enabling O(deg⁻¹) sink removal rather than the O(E) naive alternative. The acyclicity test uses sink elimination; when a cycle is detected, DFS reconstructs the exact cycle path. Benchmarked against 90 test graphs ranging from 40 to 10,240 vertices, confirming O(V²+E) theoretical performance in practice.

### [OS File Processing Tools — Shell & C](https://github.com/N-Nicolaou/os-file-tools)
**Tech:** C · KSH Shell Scripting · Linux  
Two Unix system programming projects from an Operating Systems module. First: a KSH shell script that validates an input file (existence, permissions, emptiness), evaluates arithmetic expressions and writes results to an output file. Second: a C program that opens two text files and displays their contents side-by-side in configurable column widths, using `fgets` for line reading and proper error status codes throughout.

### [Outpatient Age Statistics — C++ CLI Tool](https://github.com/N-Nicolaou/outpatient-age-stats)
**Tech:** C++  
Command-line tool that takes hospital outpatient ages as input and produces statistical analysis and ASCII visualisations. Built across three progressively complex tasks: a basic age-group histogram, extended statistics (oldest/youngest patient, totals, under-40 count), and a vertical bar chart rendered entirely in the terminal using control flow logic.

### [FoodTable — Meal Search Android App](https://github.com/N-Nicolaou/food-table)
**Tech:** Kotlin · Jetpack Compose · MVVM · Room Database · REST API  
Android meal search app built with a clean MVVM architecture. Integrates with the MealDB REST API to search for meals by name or ingredient, with results stored locally using a Room database for offline access. Uses StateFlow for reactive UI that automatically survives screen rotation, async coroutines for non-blocking API calls, and a ViewModel layer to cleanly separate business logic from the UI. Features multiple screens including ingredient search, name search, and local database browsing.

### [CrossPuzzle — Maths Crossword Android App](https://github.com/N-Nicolaou/cross-puzzle)
**Tech:** Kotlin · Jetpack Compose · Android Studio  
Android puzzle game that generates a crossword-style grid filled with arithmetic equations instead of words. Randomly generates equations (addition, subtraction, multiplication, division) and places them across and down a dynamically sized grid, leaving one value blank per equation for the player to solve. Built entirely with Jetpack Compose and includes difficulty settings and equation validation logic.

### [Car Hire Management System](https://github.com/N-Nicolaou/car-hire-manager)
**Tech:** C++ · OOP · Inheritance · Polymorphism  
Object-oriented C++ system for managing a car hire business across multiple branches. Built a full class hierarchy with `Vehicle` as an abstract base class (pure virtual methods), extended by `Car` and `ElectricCar` subclasses. Additional classes handle `Inventory`, `BranchManager`, `Manager`, and `Location`, demonstrating encapsulation, inheritance, and polymorphism throughout. Features vehicle availability tracking, hire and return logic, and branch-level inventory management.

---

## ⚡ Electronics & Hardware Projects

### [Micro-Mouse Maze-Solving Robot](https://github.com/N-Nicolaou/micro-mouse)
**Hardware:** MBED · Stepper Motors · IR Sensors · Custom PCB  
**Software:** C++ · State Machine · Lee's Algorithm · Dijkstra's Algorithm  
Group project to design and build an autonomous maze-solving robot capable of navigating an 8×8 maze with no prior knowledge of its layout. Implemented wall detection using IR sensors, a state machine for navigation logic, and Lee's algorithm for maze mapping with Dijkstra's algorithm for optimal path analysis. Engineered motor driver circuits for precise stepper motor control, designed sensor circuits for reliable wall detection, and wrote the full firmware in C++ on the MBED platform. Validated through hardware unit testing and full maze runs. Videos of the robot navigating available on request.

### [PIC16F877A Temperature Data Acquisition System](https://github.com/N-Nicolaou/pic-daq-system)
**Hardware:** PIC16F877A · Custom PCB · NTC Thermistors · Op-Amps · LCD Display  
**Software:** PIC Assembly · MPLABX · MATLAB/Simscape · Fusion 360 · PicSim  
Group project to design and build a fully custom data acquisition system from scratch. Designed the analogue front end (AFE) with op-amp signal conditioning and low-pass filtering, a voltage regulation circuit (LM7805), and a PIC microcontroller circuit — all laid out on a custom PCB designed in Fusion 360. Wrote PIC assembly firmware for ADC interfacing, LCD driving with precise timing, BCD conversion for temperature display, and a debounced button input for toggling between two thermistor sources.

### [Custom Robot Arm — Co-Creators Project](https://github.com/N-Nicolaou/robot-arm-cocreators)
**Hardware:** 3D Printed · Fusion 360 · [Electronics TBD]  
Paid collaborative project (£250 co-creators grant) with a team of 4, designing and building a custom robot arm entirely from scratch. Currently in the design phase using Fusion 360 for CAD modelling ahead of 3D printing. The goal is to produce a fully functional robot arm while learning new skills outside of the university curriculum — combining mechanical design, electronics, and software control.

<!-- Keep adding projects here as you build them. -->

---

## 🎓 Academic Highlights

- 📘 **Year 2 GPA / Average:** [Add if you'd like to include it]
- 🏆 **Co-Creators Grant** — Awarded £250 to design and build a custom robot arm with a team of 4
- 🏆 **Empowerability Programme** — £250 paid role advocating for disabled students at the University of Westminster
- 🏆 **Lead Developer Award** — Recognised for problem-solving and reworking broken code in a team environment
- 📝 **Key modules:** Programming Methodology · Electronics Fundamentals · Computer Organisation & Digital Systems · Applied Mathematics · Algorithms & Data Structures · Operating Systems · Object Oriented Programming · Mobile Applications · Embedded Systems · Microcontroller Design · Sensors & Signals
- 🤝 **Incoming Year 3 Student Representative** — Elected to represent the Year 3 cohort to faculty

---

## 📊 GitHub Stats

![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=N-Nicolaou&show_icons=true&theme=default&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=N-Nicolaou&layout=compact&theme=default&hide_border=true)

---

## 📫 Get in Touch

I'm actively looking for **summer 2026 opportunities** in software engineering, embedded systems, or electronics — feel free to reach out!

- 💼 [LinkedIn](https://linkedin.com/in/nicholas-nicolaou-072a961b7)
- 📧 [Nicolaou2002@gmail.com](mailto:Nicolaou2002@gmail.com)

---

*Last updated: May 2026*

