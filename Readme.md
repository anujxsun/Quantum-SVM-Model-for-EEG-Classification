
---

```markdown
# Quantum Two-Class MI EEG Signal Classification

## Overview
This project implements a quantum machine learning approach for classifying
two-class Motor Imagery (MI) EEG signals in Brain–Computer Interface (BCI)
applications. The work explores the use of Quantum Support Vector Machine (QSVM)
and quantum feature maps to evaluate the potential of quantum models compared
to classical machine learning approaches.

The project is primarily experimental and focuses on understanding the
capabilities, limitations, and scalability challenges of quantum models
for EEG signal classification.

---

## Objectives
- Implement a quantum-based classifier for two-class MI EEG signals
- Encode classical EEG features into quantum states
- Design and simulate quantum circuits using Qiskit
- Compare quantum model performance with classical machine learning models
- Analyze limitations related to quantum hardware and simulation constraints

---

## Methodology
1. EEG signal preprocessing and feature preparation
2. Encoding classical features into quantum states using quantum feature maps
3. Construction of quantum circuits for classification
4. Training and evaluation using Quantum Support Vector Machine (QSVM)
5. Performance comparison with classical LDA and SVM models

---

## Models and Techniques
- Quantum Support Vector Machine (QSVM)
- Quantum Feature Maps
- Quantum Circuit Simulation

---

## Tools and Technologies
- Python
- Qiskit
- NumPy
- Scikit-learn
- Google Colab (for initial experimentation)

---

## Results and Analysis
- Quantum models were evaluated under simulated quantum backends
- Performance was analyzed relative to classical models
- Observations highlight both representational advantages and
  computational limitations of quantum approaches
- Scalability challenges were identified due to qubit and memory constraints

---

## Project Structure
```

Quantum-MI-EEG-Classification/
│
├── notebooks/
│   └── Quantum_MI_EEG_Classification.ipynb
│
├── data/
│   └── README.md
│
├── results/
│   └── observations.txt
│
├── requirements.txt
└── README.md

```

---

## How to Run
1. Clone the repository:
```

git clone [https://github.com/anujxsun/Quantum-MI-EEG-Classification.git](https://github.com/anujxsun/Quantum-MI-EEG-Classification.git)

```
2. Install dependencies:
```

pip install -r requirements.txt

```
3. Open the notebook using Jupyter Notebook or Google Colab

---

## Notes
- This project uses quantum circuit simulation due to limited access to
real quantum hardware
- Results are intended for research and exploratory purposes
- Further optimization may be possible with improved hardware availability

---

## Author
Anuj Kumar Kashyap
```
