# 🎯 Monty Hall Problem Simulator

This project simulates the classic Monty Hall Problem and explores how the probability of winning changes with different strategies and an increasing number of doors. Through thousands of iterations and variations in door count, it visualizes the counterintuitive advantage of switching.

---

## 🧠 Conclusion: What Did We Learn?

### Key Takeaways

- ✅ **Switching wins more often**:  
  The simulation confirms that switching doors gives a significantly higher chance of winning.

- 🎲 **Probabilities**:  
- **Staying with initial choice**: P(stay) = 1 / n  
- **Switching after the host opens doors**: P(switch) = (n - 1) / n

  As \( n \) increases, the advantage of switching becomes even more pronounced.

### What the Simulation Shows

- With **3 doors**, switching gives a ~66.7% chance of winning.
- With **100 doors**, switching gives you a ~99% chance of winning.
- Staying remains fixed at just 1/n.

### Real-World Analogy

> Pick 1 door out of 100. The host opens 98 other doors, all goats.  
> Your initial chance was 1%. Now only one unopened door remains.  
> That door has a 99% chance. **Switching is the smarter move.**

---

## 📁 Project Structure

- `simulation.ipynb`: Jupyter notebook with code, plots, and analysis.
- `plots/`: Generated visualizations showing probability convergence.
- `README.md`: Summary, theory, and learnings.

---

## 🧰 Technologies Used

- Python 3
- NumPy
- Matplotlib
- Jupyter Notebook

---


