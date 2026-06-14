# Dev Notebook

A comprehensive portfolio showcasing both coursework from my Computer Science degree and practical development projects. This repository demonstrates my progression from foundational programming concepts to full-stack web applications, geographic information systems, and modern web technologies.

## 📚 Portfolio Domains

This repository is organized by development domain and specialty area:

- **[Coursework & Fundamentals](#-coursework--fundamentals)** - Computer Science fundamentals (C Programming)
- **[Web Development](#-web-development)** - Full-stack web applications, UI/UX, and frameworks
- **[Geospatial Analysis & Mapping](#%EF%B8%8F-geospatial-analysis--mapping)** - GIS projects and geographic visualization

## 🎓 Coursework & Fundamentals

### C Programming

C is the foundational language taught at the beginning of most Computer Science programs. This folder contains structured university coursework covering fundamental computer science concepts and programming principles.

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
gcc -o Ex1 c/Ex1.c
./Ex1
```

Or on Windows:
```bash
gcc -o Ex1 c\Ex1.c
Ex1.exe
```

To compile and run the menu-based Game program:
```bash
gcc -o Game c/Game.c
./Game
```

**Learning Resources:**
- [TutorialsPoint - C Programming](https://www.tutorialspoint.com/cprogramming/index.htm)
- [c/README.md](c/README.md) - Detailed exercise documentation

---

## 💻 Web Development

This domain encompasses full-stack web applications, interactive user interfaces, and web frameworks. Projects demonstrate responsive design, form handling, and modern web technologies.

### Frontend Development

#### Interactive Applications
| Project | Location | Technologies | Description |
|---------|----------|---------------|-------------|
| **Tips Calculator** | [js/tips-calculator/](js/tips-calculator/) | JavaScript, CSS | Interactive tip calculation tool with real-time computation |
| **To-Do List** | [js/to-do-List/](js/to-do-List/) | JavaScript, CSS | Task management application with add/complete/delete functionality |

#### UI Components & Design Systems
| Project | Location | Technologies | Description |
|---------|----------|---------------|-------------|
| **Checkout Form** | [css/checkout-form/](css/checkout-form/) | HTML, CSS | Responsive checkout form with validation and styling |
| **Master Signup Form** | [css/master-signup-form/](css/master-signup-form/) | HTML, CSS | Comprehensive user authentication forms (signup, login, password recovery) |
| **Mini CSS Library** | [css/mini-css-library/](css/mini-css-library/) | HTML, CSS | Custom CSS utilities and reusable component library |
| **Navigation Bars** | [css/navbar/](css/navbar/) | HTML, CSS | Multiple navbar implementations showcasing responsive design patterns |
| **Navbar with Dropdown** | [css/navbar-with-drop-down/](css/navbar-with-drop-down/) | HTML, CSS | Advanced navigation with dropdown menu functionality |

### Backend & Frameworks

#### Python Web Framework
| Project | Location | Technologies | Description |
|---------|----------|---------------|-------------|
| **Bottle Framework Learning** | [python/learning-bottle-framework/](python/learning-bottle-framework/) | Python, Bottle | Educational project exploring the lightweight Bottle web framework |

---

## 🗺️ Geospatial Analysis & Mapping

Geographic Information Systems (GIS) projects showcasing web-based mapping, spatial data visualization, and geospatial analysis. These projects combine web technologies with geographic data.

| Project | Location | Description |
|---------|----------|-------------|
| **Freetown Settlements** | [gis/freetown-settlements/](gis/freetown-settlements/) | Mapping and spatial analysis of settlements in Freetown |
| **Health Facilities** | [gis/health-facilities/](gis/health-facilities/) | Geographic data visualization of health facilities and locations |
| **PREESD Installations** | [gis/preesd-installations/](gis/preesd-installations/) | Spatial data visualization of installations and infrastructure |
| **Web Map** | [gis/web-map/](gis/web-map/) | Interactive web-based mapping application |

---

## 📖 Project Organization

```
dev-notebook/
├── README.md (this file)
├── dev-notebook.code-workspace
├── c/ (Coursework & Fundamentals)
│   ├── README.md (detailed exercise documentation)
│   ├── Ex1.c through Ex8.c (individual exercises)
│   └── Game.c (menu-driven program)
├── js/ (Web Development - Frontend)
│   ├── tips-calculator/
│   └── to-do-List/
├── css/ (Web Development - UI Components)
│   ├── checkout-form/
│   ├── master-signup-form/
│   ├── mini-css-library/
│   ├── navbar/ (v1, v2, v3)
│   └── navbar-with-drop-down/
├── python/ (Web Development - Backend)
│   └── learning-bottle-framework/
└── gis/ (Geospatial Analysis & Mapping)
    ├── freetown-settlements/
    ├── health-facilities/
    ├── preesd-installations/
    └── web-map/
```

## 👨‍💻 Author

Mohamed S Harding

## 📝 Notes

- **Coursework & Fundamentals**: C programming exercises include detailed comments explaining problem statements and solutions, progressing from basic input/output to complex algorithmic thinking
- **Web Development**: Full-stack web applications, interactive tools, and responsive UI components demonstrating modern web development practices
- **Geospatial Analysis**: GIS projects showcase advanced web mapping and spatial data visualization capabilities
- Each domain builds upon core CS principles while showcasing specialized expertise in different development areas
- This repository serves as a comprehensive reference for my development journey and technical capabilities across multiple domains
