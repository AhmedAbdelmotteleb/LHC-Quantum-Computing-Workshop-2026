# LHC-Quantum-Computing-Workshop-2026

## Day 1

- You are expected to work on **9 questions** in the notebook found in the directory [`Day1/Qiskit_Intro.ipynb`](./Day1/Qiskit_Intro.ipynb).
- If you mange to finish those, please continue with [`Day1/noise_model.ipynb`](./Day1/noise_model.ipynb), then [`Day1/chsh_bell.ipynb`](./Day1/chsh_bell.ipynb), then [`Day1/transpile_compare.ipynb`](./Day1/transpile_compare.ipynb).
- If you manage to finish all of the above, you can continue with [`Day1/hhl_toy.ipynb`](./Day1/hhl_toy.ipynb).
- You are encouraged go at your own pace, explore, and enjoy all Qiskit has to offer. A notebook with the model answers for all the questions will be posted shortly after today's session.
- If you don't manage to finish on time, you can continue working in Day 2, or in your own time. 
- You are also encouraged to make use of the [IBM Quantum Composer](https://quantum.ibm.com/composer) (hopefully IBM continues to support it).
- It is also a good idea to play around with the [interactive Bloch Sphere](https://javafxpert.github.io/grok-bloch/) to understand how different quantum gates combine to affect your (1 qubit) circuit.

---

## Day 2

There are multiple exercises to complete in the [`Day2`](./Day2) directory:

- [Deutsch-Jozsa Algorithm Exercise](./Day2/Deutsch_Jozsa.ipynb)  
- [QAOA Exercise](./Day2/QAOA.ipynb)  
- [Grover's Algorithm Exercise](./Day2/Grover.ipynb)
- [QML Exercise](./Day2/PennyLane_QML_Example.ipynb) (note this is the most time consuming of the bunch, better leave to the end)
- You can also finish up any notebooks from Day 1.

---

## How to run the notebooks

### Option 1: Run online using **Binder** (recommended)

You can launch the entire workshop repository interactively in your browser without installing anything by using [MyBinder](https://mybinder.org/):

- Open this link to launch the workshop:  
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AhmedAbdelmotteleb/LHC-Quantum-Computing-Workshop-2026/HEAD)

- This will open a Jupyter notebook interface where you can navigate to the `Day1` and `Day2` folders and run the notebooks.

---

### Option 2: Run locally on your machine

1. Clone the repository:

   ```bash
   git clone https://github.com/AhmedAbdelmotteleb/LHC-Quantum-Computing-Workshop-2026.git
   cd LHC-Quantum-Computing-Workshop-2026
   ```
2. Create and activate a Python virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use: venv\Scripts\activate
    ```

3. Install required packages:
   
    ```bash
    pip install -r requirements.txt
    ```
    Note that the QML exercise requires additional requirements, which are detailed in the notebook.

5. Launch Jupyter Notebook:

    ```bash
    jupyter notebook
    ```
    You could also use something like [`VSCode`](https://code.visualstudio.com/) if you want to open and run the Jupyter notebooks.

6. Navigate to the `Day1` and `Day2` folders and open the notebooks to start working.


## Contact

If you have any questions, issues, or feedback about the workshop, feel free to reach out on ahmedsamehwagih@gmail.com / ahmed.abdelmotteleb@cern.ch

## Thanks

Many thanks to Jacco De Vries and Xenofon Chiotopoulos for proof-reading the exercises. Xenofon also provided the QML example.
