# ICS Quadratic Grader - Lushomo Muteteete 202407579

This single-page web app performs two functions:
1. **Solves a quadratic equation (ax² + bx + c = 0)**  
2. **Converts a numeric score (0–100) into a letter grade**

---

## 🧮 Quadratic Solver

### Inputs:
- a, b, c → Coefficients of the quadratic equation  
- Validation ensures:
  - `a` cannot be 0  
  - All inputs must be valid numbers  

### Outputs:
- Discriminant (D = b² - 4ac)
- Nature of roots:
  - D > 0 → Two distinct real roots  
  - D = 0 → One real repeated root  
  - D < 0 → Two complex conjugate roots  
- Computed roots displayed with two decimal places.

---

## 🎓 Grading System

### Input:
- A single score (integer from 0 to 100)

### Output:
- The corresponding letter grade based on this scale:

| Score Range | Grade |
|--------------|--------|
| 85–100 | A+ |
| 75–84 | A |
| 65–74 | B+ |
| 60–64 | B |
| 55–59 | C+ |
| 50–54 | C |
| 0–49 | D |

---

## 🧠 Edge Cases
- Handles invalid or empty inputs gracefully.
- Example:
  - 85 → A+
  - 49 → D
  - 100 → A+

---

## ⚙️ How to Run

1. Download or clone this repository:
https://github.com//ICS-Quadratic-Grader-Lushomo-Muteteete
2. Make sure all three files are in the same folder:
- index.html  
- style.css  
- script.js
3. Double-click `index.html` to open it in your browser.  
✅ Works completely offline.

---

## 💡 Test Cases

### Quadratic Solver
| a | b | c | Expected Roots |
|---|---|---|----------------|
| 1 | -3 | 2 | x₁=2, x₂=1 |
| 1 | 2 | 1 | x₁=x₂=-1 |
| 1 | 2 | 5 | Complex roots |

### Grading System
| Score | Expected Grade |
|--------|----------------|
| 100 | A+ |
| 85 | A+ |
| 75 | A |
| 65 | B+ |
| 55 | C+ |
| 49 | D |

---

---

## 🧾 Author
**Name:** Lushomo Muteteete
**Course:** ICS  
**StudentNumber:** 202407579
**Project:** Quadratic Solver & Grading System
