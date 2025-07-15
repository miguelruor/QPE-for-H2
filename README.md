# Quantum Phase Estimation for Molecular Ground State Energy

This project implements the **Quantum Phase Estimation (QPE)** algorithm using [PennyLane](https://pennylane.ai/), with a focus on computing the **ground state energy of the hydrogen molecule (H₂)**. It includes both classical and quantum simulations and visualizations.

## 🧠 Main Features

- ✅ General QPE circuit construction (`circuit_qpe`)
- ✅ Classical computation of eigenvalues for verification
- ✅ Decomposition of the H₂ Hamiltonian using the Bravyi-Kitaev transformation
- ✅ Efficient 2-qubit simulation by exploiting Hartree-Fock state symmetries
- ✅ Trotter-Suzuki approximation for time evolution
- ✅ Energy surface generation (exact & QPE-estimated)
