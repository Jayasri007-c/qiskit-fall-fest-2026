# Qiskit Fall Fest 2026: Challenge Solutions

**Event:** Qiskit Fall Fest 2026 (IBM Quantum)
**Venue:** Vishnu Institute of Technology, Bhimavaram
**Participant:** [Your Name] · [Roll Number]

Solutions to the four Qiskit Fall Fest 2026 challenges, all built with Qiskit and run on the Aer simulator with 100 shots per experiment.

## Challenges
| # | Challenge | Notebook |
|---|---|---|
| 1 | Predict the Output | [Challenge_1_Predict_the_Output.ipynb](Challenge_1_Predict_the_Output.ipynb) |
| 2 | Make the Quantum Coin Biased | [Challenge_2_Biased_Quantum_Coin.ipynb](Challenge_2_Biased_Quantum_Coin.ipynb) |
| 3 | Can You Change the Correlation? | [Challenge_3_Change_the_Correlation.ipynb](Challenge_3_Change_the_Correlation.ipynb) |
| 4 | Quantum Correlation Switch | [Challenge_4_Quantum_Correlation_Switch.ipynb](Challenge_4_Quantum_Correlation_Switch.ipynb) |

## Summary
1. **Challenge 1:** X flips the qubit, two X gates cancel, and H gives a random 50/50 result.
2. **Challenge 2:** H, T, H biases the coin to about 85/15, and an X gate at the start flips the bias.
3. **Challenge 3:** adding an X gate on qubit 1 to the Bell circuit changes the outcomes from `00`/`11` to `01`/`10`.
4. **Challenge 4:** the same X gate acts as a switch between correlated and opposite outcomes.

## How to run
```bash
pip install qiskit qiskit-aer matplotlib pylatexenc jupyter
jupyter notebook
```

## Tools
Python, Qiskit, Qiskit Aer simulator, Matplotlib
