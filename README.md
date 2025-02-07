# OpenMP & MPI Interactive Tutorial

## 📌 Overview
This repository provides an **interactive tutorial** on **OpenMP** and **MPI**, covering fundamental parallel computing concepts, practical exercises, and real-world examples. The content is structured for **ease of use** with step-by-step explanations and runnable code inside a Jupyter Notebook.

![OpenMP & MPI Tutorial](OpenMP-MPI.gif)


## 🚀 Getting Started
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/openmp-mpi-workshop.git
cd openmp-mpi-workshop
```

### 2️⃣ Install Dependencies
Ensure that you have **GCC with OpenMP support** and an **MPI implementation** installed:

```bash
# Install OpenMP support (GCC)
sudo apt install gcc

# Install MPI (MPICH or OpenMPI)
sudo apt install mpich
```

### 3️⃣ Run the Jupyter Notebook
Start Jupyter and open the tutorial:

```bash
jupyter lab tutorial.ipynb
```

### 4️⃣ Compile and Run OpenMP/MPI Programs
#### OpenMP Example
```bash
gcc -fopenmp examples/openmp_hello.c -o openmp_hello
./openmp_hello
```
#### MPI Example
```bash
mpicc examples/mpi_hello.c -o mpi_hello
mpirun -np 2 ./mpi_hello
```

## 📖 Topics Covered
- **OpenMP Basics**: Fork-Join Model, Parallel Loops, Work Sharing
- **MPI Basics**: Point-to-Point and Collective Communication
- **Synchronization**: Barriers, Critical Sections, Reduction
- **Advanced Concepts**: Custom Data Types, Communicators, Hybrid OpenMP+MPI

## 🛠 Contributions
Contributions are welcome! If you find any issues or improvements, feel free to open a **Pull Request**.

## 📜 License
This project is licensed under the MIT License.

---
Happy coding! 🚀
