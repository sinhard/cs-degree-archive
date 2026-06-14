# Dev Notebook

A comprehensive portfolio showcasing both coursework from my Computer Science degree and practical development projects. This repository demonstrates my progression from foundational programming concepts to full-stack web applications, geographic information systems, and modern web technologies.

## 📚 Portfolio Domains

This repository is organized by development domain and specialty area:

- **[CS Coursework & Fundamentals](#-cs-coursework--fundamentals)** - Computer Science fundamentals (C Programming)
- **[Data Structures & Algorithms](#-data-structures--algorithms)** - Core algorithmic concepts and data structure implementations
- **[Embedded Systems](#-embedded-systems)** - Low-level programming and hardware-focused development
- **[Web Development](#-web-development)** - Full-stack web applications, UI/UX, and frameworks
- **[Geospatial Analysis & Mapping](#️-geospatial-analysis--mapping)** - GIS projects and geographic visualization
- **[Automation Scripts](#-automation-scripts)** - Utility scripts and automation tools

## 🎓 CS Coursework & Fundamentals

### C Programming

C is the foundational language taught at the beginning of most Computer Science programs. This folder contains structured university coursework covering fundamental computer science concepts and programming principles.

**Location:** [cs-coursework-fundamentals/c/](cs-coursework-fundamentals/c/)

#### Coursework Topics Covered

The exercises cover essential C programming concepts:

1. Introduction to the Language
2. Program Structure & Basic Syntax
3. Data Types & Variables
4. Constants & Storage Classes
5. Operators & Decision Making
6. Loops & Functions
7. Scope Rules & Arrays
8. Pointers & Strings
9. Structures, Unions & Bit Fields
10. TypeDef & Input/Output
11. File I/O & Preprocessors
12. Header Files & Type Casting
13. Error Handling & Recursion
14. Variable Arguments & Memory Management
15. Command Line Arguments

#### Exercises

| File | Description |
|------|-------------|
| **Ex1.c** | Volume of Sphere Calculator (fixed radius) - Computes the volume of a sphere with a 10-meter radius using the formula v = 4/3πr³ |
| **Ex2.c** | Volume of Sphere Calculator (user input) - Accepts radius value from user and calculates volume |
| **Ex3.c** | Dollar-and-Cents Calculator - Asks user to enter a dollars-and-cents amount and displays the amount with 5% tax added |
| **Ex4.c** | Polynomial Function Evaluator - Substitutes user input x value into the equation 3x⁵ - 2x⁴ - 5x³ - x² + 7x - 6 |
| **Ex5.c** | US Dollar Bill Denominator - Breaks down a dollar amount (0-20) using the smallest number of $20, $10, $5, and $1 bills |
| **Ex6.c** | Date Formatter - Accepts a date from user and formats it as yyyymmdd |
| **Ex7.c** | Tabbed View Exercise - Demonstrates text formatting with tabs |
| **Ex8.c** | Additional Exercise - Further practice with C concepts |

#### Main Program

| File | Description |
|------|-------------|
| **Game.c** | Interactive menu program that runs all exercises above - Provides a unified interface to execute any exercise |

#### Getting Started with C

**Prerequisites:**
- GCC compiler or any C compiler (e.g., `gcc`, `clang`)
- Terminal/Command prompt

**Compiling and Running:**

To compile a single exercise:
```bash
gcc -o Ex1 cs-coursework-fundamentals/c/Ex1.c
./Ex1
```

Or on Windows:
```bash
gcc -o Ex1 cs-coursework-fundamentals\c\Ex1.c
Ex1.exe
```

To compile and run the menu-based Game program:
```bash
gcc -o Game cs-coursework-fundamentals/c/Game.c
./Game
```

**Learning Resources:**
- [TutorialsPoint - C Programming](https://www.tutorialspoint.com/cprogramming/index.htm)
- [cs-coursework-fundamentals/c/README.md](cs-coursework-fundamentals/c/README.md) - Detailed exercise documentation

---

## 💻 Web Development

This domain encompasses full-stack web applications, interactive user interfaces, and web frameworks. Projects demonstrate responsive design, form handling, and modern web technologies.

**Location:** [web-development/](web-development/)

### Frontend Development

#### Interactive Applications
| Project | Location | Technologies | Description |
|---------|----------|---------------|-------------|
| **Tips Calculator** | [web-development/frontend-dev/tips-calculator/](web-development/frontend-dev/tips-calculator/) | JavaScript, CSS | Interactive tip calculation tool with real-time computation |
| **To-Do List** | [web-development/frontend-dev/to-do-List/](web-development/frontend-dev/to-do-List/) | JavaScript, CSS | Task management application with add/complete/delete functionality |

### UI Components & Design Systems

#### Responsive Forms & Components
| Project | Location | Technologies | Description |
|---------|----------|---------------|-------------|
| **Checkout Form** | [web-development/ui-components-design-systems/checkout-form/](web-development/ui-components-design-systems/checkout-form/) | HTML, CSS | Responsive checkout form with validation and styling |
| **Master Signup Form** | [web-development/ui-components-design-systems/master-signup-form/](web-development/ui-components-design-systems/master-signup-form/) | HTML, CSS | Comprehensive user authentication forms (signup, login, password recovery) |
| **Mini CSS Library** | [web-development/ui-components-design-systems/mini-css-library/](web-development/ui-components-design-systems/mini-css-library/) | HTML, CSS | Custom CSS utilities and reusable component library |
| **Navigation Bars** | [web-development/ui-components-design-systems/navbar/](web-development/ui-components-design-systems/navbar/) | HTML, CSS | Multiple navbar implementations showcasing responsive design patterns |
| **Navbar with Dropdown** | [web-development/ui-components-design-systems/navbar-with-drop-down/](web-development/ui-components-design-systems/navbar-with-drop-down/) | HTML, CSS | Advanced navigation with dropdown menu functionality |

### Backend & Frameworks

#### Python Web Framework
| Project | Location | Technologies | Description |
|---------|----------|---------------|-------------|
| **Bottle Framework Learning** | [web-development/backend-dev-frameworks/learning-bottle-framework/](web-development/backend-dev-frameworks/learning-bottle-framework/) | Python, Bottle | Educational project exploring the lightweight Bottle web framework |

---

## 🏗️ Data Structures & Algorithms

Core data structure implementations and algorithmic problem-solving exercises.

**Location:** [data-structure-algorithms/](data-structure-algorithms/)

---

## 🔌 Embedded Systems

Low-level programming, microcontroller projects, and hardware-focused development.

**Location:** [embedded-systems/](embedded-systems/)

---

## 🗺️ Geospatial Analysis & Mapping

Geographic Information Systems (GIS) projects showcasing web-based mapping, spatial data visualization, and geospatial analysis. These projects combine web technologies with geographic data.

**Location:** [geospatial-analysis-mapping/](geospatial-analysis-mapping/)

| Project | Location | Description |
|---------|----------|-------------|
| **Freetown Settlements** | [geospatial-analysis-mapping/freetown-settlements/](geospatial-analysis-mapping/freetown-settlements/) | Mapping and spatial analysis of settlements in Freetown |
| **Health Facilities** | [geospatial-analysis-mapping/health-facilities/](geospatial-analysis-mapping/health-facilities/) | Geographic data visualization of health facilities and locations |
| **PREESD Installations** | [geospatial-analysis-mapping/preesd-installations/](geospatial-analysis-mapping/preesd-installations/) | Spatial data visualization of installations and infrastructure |
| **Web Map** | [geospatial-analysis-mapping/web-map/](geospatial-analysis-mapping/web-map/) | Interactive web-based mapping application |

---

## 🤖 Automation Scripts

Utility scripts and automation tools for development and data processing tasks.

**Location:** [automation-scripts/](automation-scripts/)

## 📖 Project Organization

```
dev-notebook/
├── README.md (this file)
├── dev-notebook.code-workspace
├── cs-coursework-fundamentals/ (CS Coursework & Fundamentals)
│   └── c/
│       ├── README.md (detailed exercise documentation)
│       ├── Ex1.c through Ex8.c (individual exercises)
│       └── Game.c (menu-driven program)
├── web-development/ (Web Development)
│   ├── frontend-dev/
│   │   ├── tips-calculator/
│   │   └── to-do-List/
│   ├── ui-components-design-systems/
│   │   ├── checkout-form/
│   │   ├── master-signup-form/
│   │   ├── mini-css-library/
│   │   ├── navbar/ (v1, v2, v3)
│   │   └── navbar-with-drop-down/
│   └── backend-dev-frameworks/
│       └── learning-bottle-framework/
├── data-structure-algorithms/ (Data Structures & Algorithms)
├── embedded-systems/ (Embedded Systems)
├── geospatial-analysis-mapping/ (Geospatial Analysis & Mapping)
│   ├── freetown-settlements/
│   ├── health-facilities/
│   ├── preesd-installations/
│   └── web-map/
└── automation-scripts/ (Automation Scripts)
```

## 👨‍💻 Author

Mohamed S Harding

## 📝 Notes

- **CS Coursework & Fundamentals**: C programming exercises include detailed comments explaining problem statements and solutions, progressing from basic input/output to complex algorithmic thinking
- **Data Structures & Algorithms**: Core implementations and algorithm explorations demonstrating computer science principles
- **Embedded Systems**: Low-level programming and hardware-focused projects
- **Web Development**: Full-stack web applications, interactive tools, and responsive UI components demonstrating modern web development practices across frontend, backend, and UI design
- **Geospatial Analysis**: GIS projects showcase advanced web mapping and spatial data visualization capabilities
- **Automation Scripts**: Utility and automation tools for various development tasks
- Each domain builds upon core CS principles while showcasing specialized expertise in different development areas
- This repository serves as a comprehensive reference for my development journey and technical capabilities across multiple domains
