# My-run-on-the-Sample-based-Krylov-quantum-diagonalization-of-a-fermionic-lattice-model-tutorial
This is my run of the "Sample-based Krylov quantum diagonalization of a fermionic lattice model" tutorial provided by IBM Quantum Platform Tutorials. I mostly kept the notebook unchanged. In sample-based-krylov-quantum-diagonalization.html, you can see the outputs I obtained when running the code. 

What I learned:
1) How to use Sample-based Quantum Diagonalization (SQD) to estimate the ground state energy of a fermionic lattice model.
2) Create a Single-impurity Anderson model (SIAM) Hamiltonian to map onto a quantum circuit.

Installation & Usage: To open this up, I used Ubuntu to create a Python environment. This was done by opening Ubuntu and placing the following commands:

python3 -m venv venv source venv/bin/activate jupyter lab --no-browser --ip=0.0.0.0 --port [insert a port number] To run this, however, you may need to create a new runtime service, as this was designed to be for participants in the summer school program.

To create a service to run on quantum hardware, be sure to implement the following code with at least this much information at the beginning of your cells: QiskitRuntimeService.save_account( channel="insert appropriate channel", token='insert API key', instance="insert CRN number", overwrite=True )

#Notes: The quantum hardware used when executing the Qiskit primitives was ibm_torino.
