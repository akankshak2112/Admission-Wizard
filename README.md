# 🎓 Admission Wizard

**Admission Wizard** is a C++-based project developed to help students navigate admission-related information based on different categories and candidate details.

The project uses a **menu-driven approach** and organizes admission data into separate header files based on reservation category and gender.

This project was developed as part of my learning journey in **C++ programming, data structures, modular programming, and Git/GitHub**.

---

## 📌 About the Project

Choosing and understanding admission options can involve going through a large amount of category-wise information.

**Admission Wizard** provides a simple command-line interface where users can enter/select their details and access the corresponding admission data.

The project currently covers the following categories:

- Open
- EWS
- OBC
- SC
- ST

The data is further organized based on:

- Male candidates
- Female candidates

---

## ✨ Features

- Category-wise admission information
- Separate data for male and female candidates
- Menu-driven command-line interface
- Modular organization using C++ header files
- Simple and lightweight implementation
- Easy to extend with additional admission data

---

## 🛠️ Technologies Used

- **C++**
- **C++ Header Files**
- **Data Structures**
- **Conditional Statements**
- **Functions**
- **Git & GitHub**

---

## 📂 Project Structure

```text
Admission-Wizard/
│
├── README.md
├── ds.cpp
│
├── openF.h
├── openM.h
│
├── ewsF.h
├── ewsM.h
│
├── obcF.h
├── obcM.h
│
├── scF.h
├── scM.h
│
├── stF.h
└── stM.h
```

### 📄 File Organization

| File      | Description                                       |
| --------- | ------------------------------------------------- |
| `ds.cpp`  | Main C++ source file containing the program logic |
| `openF.h` | Open-category data for female candidates          |
| `openM.h` | Open-category data for male candidates            |
| `ewsF.h`  | EWS data for female candidates                    |
| `ewsM.h`  | EWS data for male candidates                      |
| `obcF.h`  | OBC data for female candidates                    |
| `obcM.h`  | OBC data for male candidates                      |
| `scF.h`   | SC data for female candidates                     |
| `scM.h`   | SC data for male candidates                       |
| `stF.h`   | ST data for female candidates                     |
| `stM.h`   | ST data for male candidates                       |

---

## ⚙️ How the Project Works

The basic flow of the program is:

```text
              Start
                │
                ▼
       Enter/Select Details
                │
                ▼
        Select Category
                │
       ┌────────┼────────┐
       ▼        ▼        ▼
     Open      EWS      OBC
       │        │        │
       └────────┼────────┘
                │
             SC / ST
                │
                ▼
         Select Gender
                │
          ┌─────┴─────┐
          ▼           ▼
        Male        Female
          │           │
          └─────┬─────┘
                ▼
        Display Relevant
        Admission Data
```

The project separates the admission data into different `.h` files. The main program uses the appropriate data depending on the options selected by the user. 
