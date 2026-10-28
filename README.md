<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=374151,4B5563,9CA3AF&height=220&section=header&text=Python%20Problem%20Solving%20Suite&fontSize=38&fontColor=ffffff&fontAlignY=38&desc=Competitive%20Programming%2C%20Control%20Flow%2C%20%26%20Conditionals&descSize=16&descAlignY=60&descAlign=50" width="100%" alt="Python Problem Solving Banner"/>

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![HackerRank](https://img.shields.io/badge/HackerRank-Verified%20Solutions-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/)
[![Competitive Programming](https://img.shields.io/badge/Domain-Problem%20Solving-4B5563?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)](#)

</div>

---

## 📌 Executive Summary / Overview

The **Python Problem Solving Suite** (`Jeshwanthika7`) is a dedicated competitive programming repository containing verified solutions to core algorithmic challenges from platforms such as HackerRank, LeetCode, and CodeChef.

Beginning with conditional flow control (`001 Python if-else.py`), the repository captures solutions that enforce boundary handling, efficient time complexities, and clean syntax according to standardized competitive programming constraints.

---

## 📖 Interactive Table of Contents

- [Executive Summary / Overview](#-executive-summary--overview)
- [Key Features & Capabilities](#-key-features--capabilities)
- [Algorithmic Decision Tree & Logic](#-algorithmic-decision-tree--logic)
- [Tech Stack Breakdown](#-tech-stack-breakdown)
- [Problem Specification & Rules](#-problem-specification--rules)
- [Reproducible Quickstart & Setup](#-reproducible-quickstart--setup)
- [Project Directory Layout](#-project-directory-layout)
- [Author & Contributions](#-author--contributions)

---

## ✨ Key Features & Capabilities

- **Strict Boundary Evaluation**: Implements precise range checks conforming to competitive problem specifications ($n \in [1, 100]$).
- **Fast Standard I/O**: Parses integer inputs using stripped stream buffers (`input().strip()`).
- **Optimal Time & Space Efficiency**: Achieves $O(1)$ constant time complexity and $O(1)$ space complexity.
- **Idiomatic Guard Clauses**: Uses clean `if __name__ == '__main__':` execution guards for modular imports.

---

## 🏗️ Algorithmic Decision Tree & Logic

```mermaid
flowchart TD
    A[Read Integer n from Standard Input] --> B{Is n Odd?}
    B -->|Yes: n % 2 != 0| C[Print 'Weird']
    B -->|No: n % 2 == 0| D{Check Value Range of n}
    D -->|2 <= n <= 5| E[Print 'Not Weird']
    D -->|6 <= n <= 20| F[Print 'Weird']
    D -->|n > 20| G[Print 'Not Weird']
```

---

## 🛠️ Tech Stack Breakdown

| Category | Technologies & Tools |
| :--- | :--- |
| **Language** | Python 3.9+ |
| **Domain** | Competitive Programming, Algorithmic Logic |
| **Platforms** | HackerRank, LeetCode, CodeChef |
| **Complexity Profile**| $O(1)$ Time, $O(1)$ Auxiliary Space |

---

## 📋 Problem Specification & Rules

Given an integer $n$, perform the following conditional actions:
- If $n$ is **odd**, print `Weird`.
- If $n$ is **even** and in the inclusive range of **2 to 5**, print `Not Weird`.
- If $n$ is **even** and in the inclusive range of **6 to 20**, print `Weird`.
- If $n$ is **even** and **greater than 20**, print `Not Weird`.

---

## 🚀 Reproducible Quickstart & Setup

### Prerequisites
- Python 3.x installed

### Step 1: Clone the Repository
```bash
git clone https://github.com/Jeshwanthika07/Jeshwanthika7.git
cd Jeshwanthika7
```

### Step 2: Run the Script
```bash
python "001 Python if-else.py"
```
Enter an integer (e.g. `3` or `24`) to observe the evaluated classification output.

---

## 📂 Project Directory Layout

```text
Jeshwanthika7/
│
├── 001 Python if-else.py      # Solved conditional action problem script
└── README.md                  # Comprehensive problem solving documentation
```

---

## 👩‍💻 Author & Contributions

Authored by **[Jeshwanthika Pothamchetty](https://github.com/Jeshwanthika07)**  
*Alliance University | Department of Computer Applications*

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=374151,4B5563,9CA3AF&height=100&section=footer" width="100%" alt="Footer Banner"/>

</div>
