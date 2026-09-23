# Control Systems Mastery Roadmap

Welcome to the **Control Systems Mastery Roadmap**! This is a comprehensive, interactive, ~20-month learning path designed to take you from foundational mathematics to advanced reinforcement learning and modern control theory.

This roadmap consists of **7 phases** and **21 hands-on projects**. It is structured to bridge the gap between theoretical textbook math and real-world physical implementation, heavily emphasizing software (Python) and accessible hardware (Arduino) projects.

## How to Read & Use This Roadmap

This roadmap is provided as a self-contained, interactive web page (`index.html`). To get the most out of it:

1. **Open `index.html` in any web browser.** You do not need a local server; just double-click the file to view it.
2. **Navigate through the Phases:** Use the sidebar (or mobile navigation menu) to jump between the 7 distinct phases of the roadmap.
3. **Track Your Progress:** At the bottom of each phase, you will find a **"PHASE CHECKLIST"**. Check off these items as you master the concepts. Your progress is automatically calculated and saved to your browser's local storage cache, so it will persist even if you close the tab or refresh the page.
4. **Dark/Light Mode:** You can toggle between comfortable dark and light themes using the ☀️/🌙 icon in the top left corner of the sidebar (or in the mobile navigation). Your preference is saved locally.
5. **Dive into Projects:** Each phase contains detailed, real-world projects. Click on any project card to expand it and view the hardware/software requirements, step-by-step instructions, and deep-dive questions.

## Roadmap Summary

The journey is broken down into 7 sequential phases:

### Phase 1: Mathematical Foundations (6–8 weeks)

Every control equation is written in the language of this phase. A solid mathematical foundation is required to grasp everything that follows.

- **Key Topics**: Signals & Systems, Linear Algebra, Differential Equations.
- **Primary Tools**: Python, NumPy, SciPy, Matplotlib.

### Phase 2: Classical Control (8–10 weeks)

The foundation of 90% of real industrial controllers (like PID). Learn how to tune, design, and implement.

- **Key Topics**: PID Control, Frequency Domain Design (Bode, Nyquist, Root Locus), System Identification.
- **Primary Tools**: Arduino (for hardware PID), python-control, SciPy.

### Phase 3: Modern Control — State-Space (8–10 weeks)

The language of multi-variable systems (robotics, aircraft, power grids). Introduces optimal control (LQR) and observers.

- **Key Topics**: State-Space Representation, Optimal Control (LQR/LQG), State Observers (Luenberger).
- **Primary Tools**: python-control, SciPy.

### Phase 4: Digital Control & Filters (6–8 weeks)

Learn how controllers actually run on microcontrollers at discrete sample rates. Covers critical filtering techniques for noisy real-world sensors.

- **Key Topics**: Z-Transforms, Digital Control Implementation, Kalman Filters, Complementary/Particle Filters.
- **Primary Tools**: Arduino, MPU-6050, filterpy, NumPy.

### Phase 5: Nonlinear Control & MPC (10–12 weeks)

Real physics is nonlinear. Learn tools for when linearization fails, including Model Predictive Control (MPC) for systems with hard constraints.

- **Key Topics**: Nonlinear Control (Sliding Mode), Model Predictive Control, Robust Control (H-infinity).
- **Primary Tools**: casadi, do-mpc, cvxpy.

### Phase 6: Machine Learning for Control (10–12 weeks)

When the physics model is unknown, too complex to compute, or needs to adapt to changing conditions, Machine Learning steps in.

- **Key Topics**: Neural Network Controllers, Gaussian Process Control, Hybrid Neural MPC.
- **Primary Tools**: PyTorch, JAX, GPyTorch, do-mpc.

### Phase 7: Intelligent & Reinforcement Learning Control (10–12 weeks)

The cutting-edge of control logic. Train policies to learn optimal control behaviors purely from interaction with an environment.

- **Key Topics**: Deep Reinforcement Learning (PPO, SAC, DDPG), Sim-to-Real Transfer, Safe RL.
- **Primary Tools**: Gymnasium (OpenAI Gym), PyTorch, ROS/MuJoCo.

## Getting Started

To get started, simply open `index.html` in your favorite web browser, read through **Phase 1**, and begin the first project!

Ensure you have a standard Python environment set up with `numpy`, `scipy`, and `matplotlib` to tackle the early software simulation projects. For hardware projects, an Arduino and basic electronic components (servos, IMUs, DC motors) are recommended.
