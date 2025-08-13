# EE5180 – Machine Learning Programming Assignments

This repository contains solutions and implementations for the **EE5180** course programming assignments at **IIT Madras**.  
The assignments cover **Linear Regression**, **Neural Networks**, **Support Vector Machines**, and **Reinforcement Learning**.

---

## 📂 Contents

### **Assignment 1 – Linear Regression (Gradient Descent)**
- **Goal:** Implement simple linear regression using gradient descent from scratch.
- **Tasks:**
  1. Generate synthetic dataset with known parameters (θ\* = 2.5, θ₀\* = 3).
  2. Compute total loss for dataset.
  3. Derive and implement gradients for parameters.
  4. Implement gradient descent for **T = 10,000** iterations.
  5. Plot cost function vs. iterations.
- **Key Insight:** Gradient descent converges to the true parameters when learning rate and initialization are chosen appropriately.

---

### **Assignment 2 – Non-Linear Regression & SVM**
- **Part A: Neural Networks**
  - **Goal:** Implement a two-layer neural network (from scratch) for regression tasks.
  - **Architecture:**  
    - Input nodes: m₁ = 30  
    - Hidden nodes: m₂ = 10 (ReLU activation)  
    - Output nodes: m₃ = 1 or 2  
  - **Tasks:**
    - Feed-forward computation.
    - Backpropagation for weight and bias updates.
    - Combine feed-forward and backprop for gradient descent-like optimization.
    - Track and plot cost function across iterations.
  - **Restriction:** No inbuilt Python neural network libraries allowed.

- **Part B: Support Vector Machines (SVM)**
  - **Goal:** Implement SVM for binary classification.
  - **Allowed:** scikit-learn SVM library functions.
  - **Tasks:**
    - Define custom input data.
    - Plot cost function vs. iteration.
    - Visualize classification boundaries with supporting hyperplanes.

---

### **Assignment 3 – Reinforcement Learning**
- **Part A: Markov Decision Processes**
  - **Topics Covered:** Policy Iteration, Value Iteration.
  - **Environment:**  
    - Default: (4 × 4) grid, deterministic transitions.  
    - Custom: (5 × 5) grid.
  - **Tasks:**
    1. Implement policy evaluation & improvement.
    2. Modify reward structures and observe effects.
    3. Compute policies for β = 0.5, 0.9, 0.99.
    4. Extend to 5×5 grid scenario.
    5. Solve small 4-state MDP problem with policy iteration & value iteration.

- **Part B: Q-Learning**
  - **Goal:** Implement Q-learning for the 4-state MDP problem.
  - **Tasks:**
    - Implement ϵ-greedy exploration.
    - Compare learned Q-values with optimal values from value iteration.
    - Test different discount factors (β = 0.9, 0.5).
  - **Key Insight:** Q-learning converges to optimal Q\* when step sizes are chosen properly and sufficient exploration is ensured.

---

## 🛠️ Technologies Used
- **Languages:** Python  
- **Libraries:** NumPy, Matplotlib, scikit-learn (only for SVM)  
- **Concepts:** Linear Regression, Neural Networks (from scratch), Support Vector Machines, Markov Decision Processes, Policy Iteration, Value Iteration, Q-Learning.

---
   git clone https://github.com/yourusername/EE5180-Assignments.git
   cd EE5180-Assignments
