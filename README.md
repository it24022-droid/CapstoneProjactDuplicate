# Library Management System (Java Swing)

**Final Capstone Project - Part I: Proposal and Prototype**
Course: ICT-3107 Software Engineering and Project Management
Submitted by: Shayla Akter (ID: IT24022), Department of ICT, MBSTU
Supervised by: Professor Dr. Ziaur Rahman, Department of ICT, MBSTU

A desktop application for a small library: login (Admin / Librarian), book management and search,
member registration, issue and return with a 14-day loan period, automatic fine (Tk 5 per late day) and an overdue report.

The full proposal (process model, schedule, milestones, deliverables, Gantt chart, UML diagrams, test cases) is in
[`LibraryManagementSystemProjectProposal.pdf`](LibraryManagementSystemProjectProposal.pdf).

## Run in IntelliJ IDEA
1. Open the project folder (File > Open).
2. Right-click `src` > Mark Directory as > Sources Root. Use JDK 17 or newer.
3. Run `library.Main`.
4. Demo logins: `admin / admin123` (can delete books) and `librarian / lib123`.

Data is saved as CSV files in a `data/` folder that is created automatically on the first run.

## Run from the command line
```
javac -d out src/library/*.java
java -cp out library.Main
```

## Project structure
| Path | Content |
|---|---|
| `src/library` | Java source: User, Book, Member, IssueRecord, Fine, LibraryService, LoginFrame, MainFrame, Main |
| `report/main.tex`, `report/main.pdf` | LaTeX proposal |
| `docs/diagrams` | UML diagrams (PNG and PDF) |

## UML Diagrams

### 1. Data Flow Diagram (Level 0)
![DFD Level 0](docs/diagrams/dfd0.png)

### 2. Data Flow Diagram (Level 1)
![DFD Level 1](docs/diagrams/dfd1.png)

### 3. Use Case Diagram
![Use Case Diagram](docs/diagrams/usecase.png)

### 4. Activity Diagram
![Activity Diagram](docs/diagrams/activity.png)

### 5. Entity Relationship Diagram (ERD)
![ERD](docs/diagrams/erd.png)

### 6. Class Diagram
![Class Diagram](docs/diagrams/classdiagram.png)

### 7. Object Diagram
![Object Diagram](docs/diagrams/objectdiagram.png)
