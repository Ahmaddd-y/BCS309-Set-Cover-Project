

# Set Cover Problem Visualizer & Complexity Analysis
### BCS 309 — Algorithms I | Spring 2026
**Developer:** Ahmad Karasi  
**Institution:** Canadian University Dubai

## 📌 Project Overview
This project is an interactive educational tool designed to demonstrate the **Set Cover Problem**, a classic NP-complete problem. The tool visualizes the trade-offs between an exact **Brute-Force** approach and a practical **Greedy Approximation** algorithm. 

The primary goal is to illustrate why certain problems are computationally "hard" and how we use heuristics to find near-optimal solutions in polynomial time.

## ⚙️ Features
* **Interactive Visualization:** Step through algorithms line-by-line with pseudocode highlighting and real-time state explanations.
* **Algorithm Comparison:** Side-by-side execution of Brute-Force vs. Greedy to compare operation counts and execution time.
* **NP-Completeness Proof:** An interactive reduction diagram showing the transformation from **Vertex Cover** to **Set Cover**.
* **Complexity Analysis:** Live growth charts showing the trajectory of different algorithm paradigms as input size increases.

## 🧠 Technical Concepts Explored
### 1. NP-Completeness
The project proves Set Cover is in **NP** by identifying a polynomial-time verifier. It further proves it is **NP-hard** via a reduction from the Vertex Cover problem, mapping edges of a graph to a universe $U$ and vertices to subsets $S_v$.

### 2. Greedy Paradigm
The tool implements the Greedy heuristic, which consistently picks the set covering the maximum number of remaining elements at each step. 
* **Approximation Ratio:** The algorithm is guaranteed to stay within an $H(n)$ (harmonic number) factor of the optimal solution, which is approximately $\ln n$.

### 3. Brute-Force Analysis
The tool demonstrates the exhaustive search method with a time complexity of $O(2^m \cdot m \cdot n)$. The visualizer highlights the "combinatorial explosion" that occurs as the number of sets ($m$) increases, eventually becoming intractable.

## 🛠️ Built With
* **HTML5/CSS3:** Minimalist, professional UI designed for pedagogical clarity.
* **JavaScript:** Custom visualization engine and algorithm implementations.
* **SVG:** Dynamic rendering of graphs and set-element relationships.

## 📄 Academic Integrity
This project was developed for the Algorithms I (BCS 309) course under the supervision of **Dr. Arash Kermani**. All work adheres to the Academic Integrity Policy of the Canadian University Dubai.
