# Quantum Two-Class MI EEG Signal Classification

## Overview

This project implements a quantum machine learning approach for classifying two-class Motor Imagery (MI) EEG signals in Brain-Computer Interface (BCI) applications. The work explores the use of Quantum Support Vector Machine (QSVM) and quantum feature maps to evaluate the potential of quantum models compared to classical machine learning approaches.

The project is primarily experimental and focuses on understanding the capabilities, limitations, and scalability challenges of quantum models for EEG signal classification.

## Objectives

- Implement a quantum-based classifier for two-class MI EEG signals
- Encode classical EEG features into quantum states
- Design and simulate quantum circuits using Qiskit
- Compare quantum model performance with classical machine learning models
- Analyze limitations related to quantum hardware and simulation constraints

## Methodology

1. EEG signal preprocessing and feature preparation
2. Encoding classical features into quantum states using quantum feature maps
3. Construction of quantum circuits for classification
4. Training and evaluation using Quantum Support Vector Machine (QSVM)
5. Performance comparison with classical LDA and SVM models

## Models and Techniques

- **Quantum Support Vector Machine (QSVM)**: Primary quantum classification model
- **Quantum Feature Maps**: Encoding mechanism for classical-to-quantum data transformation
- **Quantum Circuit Simulation**: Implementation and testing environment

## Tools and Technologies

- **Python**: Primary programming language
- **Qiskit**: Quantum computing framework
- **NumPy**: Numerical computation library
- **Scikit-learn**: Classical machine learning algorithms
- **Google Colab**: Cloud-based development environment for initial experimentation

## Results and Analysis

- Quantum models were evaluated under simulated quantum backends
- Performance was analyzed relative to classical models
- Observations highlight both representational advantages and computational limitations of quantum approaches
- Scalability challenges were identified due to qubit and memory constraints

## Project Structure

```
Quantum-MI-EEG-Classification/
├── notebooks/
│   └── Quantum_MI_EEG_Classification.ipynb
├── data/
│   └── README.md
├── results/
│   └── observations.txt
├── requirements.txt
└── README.md
```

## Installation and Usage

### Prerequisites

Ensure you have Python 3.7 or higher installed on your system.

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/anujxsun/Quantum-MI-EEG-Classification.git
   cd Quantum-MI-EEG-Classification
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook:**
   - Open using Jupyter Notebook:
     ```bash
     jupyter notebook notebooks/Quantum_MI_EEG_Classification.ipynb
     ```
   - Alternatively, upload to Google Colab for cloud-based execution

## Limitations and Considerations

- This project uses quantum circuit simulation due to limited access to real quantum hardware
- Results are intended for research and exploratory purposes
- Further optimization may be possible with improved hardware availability and access to quantum processing units

## Future Work

- Integration with actual quantum hardware platforms
- Exploration of additional quantum feature encoding strategies
- Extension to multi-class MI EEG classification problems
- Performance optimization for larger datasets

## Contributing

Contributions, issues, and feature requests are welcome. Please feel free to check the issues page or submit a pull request.

## License

This project is available under the MIT License. See the LICENSE file for more details.

## Author

**Anuj Kumar Kashyap**

For questions or collaborations, please reach out through the repository's issue tracker.

## Acknowledgments

Special thanks to the Qiskit community and BCI research groups whose work has informed and inspired this project.

---

