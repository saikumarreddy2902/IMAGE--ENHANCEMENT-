
# 🚀 HPC Project

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![NumPy](https://img.shields.io/badge/NumPy-Library-green.svg)
![MPI](https://img.shields.io/badge/MPI-Parallel%20Computing-red.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📖 Overview

This project demonstrates the implementation of **High Performance Computing (HPC)** techniques to solve computationally intensive problems efficiently. The project leverages parallel processing concepts, optimized algorithms, and scientific computing libraries to improve execution speed and resource utilization.

The implementation is developed in Python using Jupyter Notebook and focuses on distributed and parallel computation methodologies commonly used in HPC environments.

---

## 🎯 Objectives

* Understand High Performance Computing concepts.
* Implement parallel and distributed algorithms.
* Improve computational efficiency using multiple processors.
* Analyze performance metrics such as execution time and scalability.
* Compare sequential and parallel execution approaches.

---

## 🛠️ Technologies Used

| Technology       | Purpose                  |
| ---------------- | ------------------------ |
| Python           | Programming Language     |
| Jupyter Notebook | Development Environment  |
| NumPy            | Numerical Computation    |
| MPI4Py           | Parallel Processing      |
| Matplotlib       | Data Visualization       |
| HPC Concepts     | Performance Optimization |

---

## 📂 Project Structure

```text
HPC_PROJECT/
│
├── HPC_PROJECT_2.ipynb
├── README.md
├── requirements.txt
└── datasets/
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/2303a52223/HPC_PROJECT.git
cd HPC_PROJECT
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install numpy matplotlib mpi4py jupyter
```

---

## ▶️ Running the Project

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
HPC_PROJECT_2.ipynb
```

### For MPI Execution

```bash
mpiexec -n 4 python script.py
```

Replace `4` with the number of processes required.

---

## 🔬 HPC Concepts Implemented

* Parallel Computing
* Distributed Processing
* Process Communication
* Load Balancing
* Performance Optimization
* Execution Time Analysis
* Scalability Evaluation

---

## 📊 Performance Analysis

The project compares:

### Sequential Execution

* Single processor execution
* Higher execution time
* Limited scalability

### Parallel Execution

* Multiple processor utilization
* Reduced execution time
* Improved throughput
* Better resource efficiency

Performance metrics analyzed:

* Execution Time
* Speedup
* Efficiency
* Scalability

---

## 📈 Expected Results

The implementation demonstrates:

* Faster execution for large computational tasks.
* Better CPU utilization.
* Reduced processing bottlenecks.
* Improved scalability with increasing processors.

---

## 📷 Sample Output

```text
Number of Processes: 4
Execution Time: 2.15 seconds
Speedup: 3.42x
Efficiency: 85.5%
```

---

## 🚀 Future Enhancements

* GPU Acceleration using CUDA.
* OpenMP integration.
* Hybrid MPI + OpenMP architecture.
* Cloud-based HPC deployment.
* Advanced performance profiling.

---

## 🧪 Testing

Run validation tests:

```bash
python test.py
```

Verify:

* Correct output generation.
* Parallel execution accuracy.
* Performance consistency.

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature-name
```

3. Commit changes.

```bash
git commit -m "Add feature"
```

4. Push changes.

```bash
git push origin feature-name
```

5. Create a Pull Request.

---

## 👨‍💻 Author

**Sai Kumar Reddy**

GitHub: https://github.com/2303a52223

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project useful:

⭐ Star the repository

🍴 Fork the repository

📢 Share with others

---

**High Performance Computing Project – Parallel Computing for Faster and Efficient Computation**
