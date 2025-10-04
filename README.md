# Quantum Computing Algorithms with Qiskit

This repository contains a comprehensive collection of quantum computing algorithms and tutorials implemented using IBM's Qiskit framework. The notebooks range from basic quantum gates to advanced quantum algorithms and applications.

## 📚 Repository Contents

### 🔰 Fundamentals & Basic Concepts

#### `Basic QC gates-qiskit.ipynb` (Lesson 01)
- **Environment Setup**: Virtual environment creation and Qiskit installation
- **Basic Quantum Gates**: Hadamard, CNOT gates and circuit construction
- **Quantum States**: Statevector manipulation and visualization
- **Measurements**: Probability distributions, counts, and sampling
- **State Evolution**: Using Pauli operators and SparsePauliOp
- **Simulation Backends**: BasicSimulator and Qiskit Aer
- **Circuit Transpilation**: Converting high-level circuits to basic gates
- **Density Matrices**: Mixed state representations
- **Bloch Sphere Visualization**: Single qubit state visualization

#### `rotation around bloch spere.ipynb`
- Geometric representation of single qubit rotations
- Bloch sphere visualizations and state transformations

### 🚀 Quantum Protocols & Communication

#### `Teleportation.ipynb`
- **Quantum Teleportation Protocol**: Complete implementation
- **Bell State Preparation**: Entanglement creation and analysis
- **Classical Communication**: Measurement and correction operations
- **Different Bell States**: Φ+, Φ-, Ψ+, Ψ- implementations
- **Conditional Operations**: Classical control of quantum gates

### 🔍 Search Algorithms

#### `Grover Algo.ipynb`
- **Grover's Search Algorithm**: Quantum database search
- **Oracle Implementation**: Marking specific items in search space
- **Amplitude Amplification**: Systematic probability enhancement
- **Performance Analysis**: Quadratic speedup demonstration

### 🎯 Oracle-Based Algorithms

#### Bernstein-Vazirani Algorithm Collection
Multiple notebooks exploring different aspects of the Bernstein-Vazirani algorithm:

- `Bernstein-Vazirani basic algo.ipynb`: Core algorithm implementation
- `Bernstein-Vazirani-Oracle-cnot.ipynb`: CNOT-based oracle construction
- `Bernstein-Vazirani-circuit-matrix.ipynb`: Matrix representation analysis
- `Bernstein-Vazirani-classical-vs-quantum.ipynb`: Comparative performance analysis
- `Bernstein-Vazirani-description-in-details.ipynb`: Detailed theoretical explanation
- `Bernstein-Vazirani-dual-secrect-code.ipynb`: Multiple secret string scenarios
- `Bernstein-Vazirani-oracle-phase-kcuckback.ipynb`: Phase kickback mechanisms

**Key Concepts Covered:**
- Hidden string determination with single query
- Oracle design patterns
- Classical vs quantum complexity comparison
- Phase kickback techniques

### 🌊 Quantum Fourier Transform (QFT)

#### `QFT-algo.ipynb`
- **QFT Implementation**: Core algorithm construction
- **Rotational Gates**: Controlled rotations and phase relationships

#### `QFT-example.ipynb`
- **Practical Examples**: QFT applications and demonstrations
- **Circuit Analysis**: Step-by-step QFT execution

#### `QFT with Inverse QFT.ipynb`
- **Inverse QFT**: Reversible quantum Fourier transform
- **Round-trip Operations**: QFT followed by inverse QFT

### 🔢 Advanced Quantum Algorithms

#### `QPE-OrderFinding-Shors-Grovers-Full.ipynb`
Comprehensive exploration of interconnected quantum algorithms:
- **Quantum Phase Estimation (QPE)**: Eigenvalue estimation
- **Order Finding**: Periodic function analysis
- **Shor's Algorithm**: Integer factorization
- **Algorithm Integration**: How these algorithms build upon each other

### 🧬 Optimization & Variational Algorithms

#### `VQE_QAOA_VQA_Variants.ipynb`
- **Variational Quantum Eigensolver (VQE)**: Ground state energy finding
- **Quantum Approximate Optimization Algorithm (QAOA)**: Combinatorial optimization
- **Variational Quantum Algorithms (VQA)**: General framework and applications
- **Ansatz Design**: Parameterized quantum circuits

#### `VQERNAfoldstruct.ipynb`
- **Bioinformatics Application**: RNA secondary structure prediction
- **QUBO Formulation**: Quadratic Unconstrained Binary Optimization
- **Molecular Modeling**: Quantum approaches to biological problems

### 🔄 Optimization Problem Formulations

#### `QUBO-Ising Hamiltonian simulation.ipynb`
- **QUBO Problems**: Quadratic optimization formulations
- **Ising Model**: Spin system representations
- **Hamiltonian Simulation**: Time evolution of quantum systems

#### `Qubo-problem.ipynb`
- **Problem Modeling**: Converting real-world problems to QUBO form
- **Solution Techniques**: Various approaches to QUBO solving

## 🛠️ Technical Requirements

### Dependencies
```bash
pip install qiskit
pip install qiskit-ibm-runtime
pip install 'qiskit[visualization]'
pip install qiskit-aer
pip install qiskit-optimization
```

### Python Environment
- Python 3.8+
- Jupyter Notebook or JupyterLab
- Matplotlib for visualizations

## 🎯 Learning Path

### Beginner Track
1. Start with `Basic QC gates-qiskit.ipynb` for fundamentals
2. Explore `rotation around bloch spere.ipynb` for geometric intuition
3. Learn quantum protocols with `Teleportation.ipynb`

### Intermediate Track
4. Study the Bernstein-Vazirani algorithm series
5. Implement search with `Grover Algo.ipynb`
6. Master QFT with the quantum Fourier transform notebooks

### Advanced Track
7. Dive into `QPE-OrderFinding-Shors-Grovers-Full.ipynb`
8. Explore variational algorithms in `VQE_QAOA_VQA_Variants.ipynb`
9. Apply to real problems with optimization notebooks

## 🔬 Key Concepts Covered

- **Quantum Gates & Circuits**: Building blocks of quantum computation
- **Quantum States**: Superposition, entanglement, and measurement
- **Quantum Algorithms**: Search, factoring, and optimization
- **Quantum Simulation**: Modeling physical and biological systems
- **Variational Methods**: Hybrid classical-quantum optimization
- **Error Handling**: Dealing with noise and decoherence
- **Real Device Deployment**: Running on actual quantum hardware

## 📖 Educational Features

- **Step-by-step Implementation**: Detailed code explanations
- **Visual Representations**: Circuit diagrams and state visualizations
- **Mathematical Foundations**: Theory behind each algorithm
- **Performance Analysis**: Classical vs quantum comparisons
- **Practical Applications**: Real-world problem solving

## 🌟 Notable Implementations

- **Complete Teleportation Protocol**: With all Bell state variants
- **Comprehensive Bernstein-Vazirani**: Multiple oracle implementations
- **Full Shor's Algorithm**: Including order finding and phase estimation
- **Biological Applications**: RNA folding using quantum optimization
- **Hardware-Ready Circuits**: Transpiled for real quantum devices

## 🚀 Getting Started

1. Clone this repository
2. Set up your Python environment with required dependencies
3. Start with the basic tutorials and progress through the learning path
4. Experiment with the code and modify parameters to deepen understanding

## 🤝 Contributing

Feel free to contribute by:
- Adding new quantum algorithms
- Improving existing implementations
- Adding more detailed explanations
- Creating additional visualizations
- Reporting bugs or suggesting improvements

## 📝 License

This educational repository is designed for learning quantum computing concepts with Qiskit.

---

*Happy Quantum Computing! 🚀⚛️*