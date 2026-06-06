# Learning Quantum With Qiskit!
## This is a qiskit learning repository by Rachit Jajoo.

This repo is my hands on journey into quantum computing using Qiskit.

Instead of just reading theory, I tried to actually build everything I learned. Circuits, simulations, measurements, visualizations. The idea was simple. If I cannot implement it, I probably do not understand it.

A lot of the stuff loosely follows the Qiskit Pocket Guide by O Reilly. But this is not a copy of the book. It is me working through the ideas until they made sense.

---

## 🧭 How to go through this

The folders are in order. Just go top to bottom.

If you follow them properly, you will see the jump from basic circuits to more abstract stuff like quantum information and operator flow.

---

## 1. Quantum Circuits And Operations

`1_Quantum_Circuits_And_Operations`

This is where everything starts.

Building circuits from scratch, understanding gates, and figuring out what is actually happening when you apply them. Also includes parameterized circuits.

---

## 2. Running Quantum Circuits

`2_Running_Quantum_Circuits`

Running the circuits on simulators.

BasicAer and Aer, how execution works, and what the results actually mean instead of just printing counts and moving on.

---

## 3. Visualizing Quantum Measurements

`3_Visualizing_Quantum_Measurements`

Things start becoming clearer here.

Looking at measurement distributions, statevectors, and circuit diagrams. This part helped a lot in building intuition.

---

## 4. Quantum Information

`5_Quantum_Information`

This is where it gets deeper.

Working with states, operators, density matrices, and how quantum information is represented internally.

---

## 5. Operator Flow

`6_Operator_Flow`

More advanced concepts.

Operator based workflows, expectation values, and how computations can be expressed in a different way.

---

## 🧠 Things that clicked while doing this

A qubit is not just 0 or 1 until you measure it.  
Measurement collapses the state and you do not get it back.  
Entanglement creates correlation, not communication.  
Simulators are helpful but they hide real world limitations.

---

## 🔬 Some things I tried out

Creating superposition using Hadamard gate.  
Building Bell states.  
Visualizing measurement probabilities.  
Exploring statevectors and operators.  

---

## 🛠️ Tech

Python  
Qiskit  
Jupyter Notebook  

---

## 🚀 Running this

pip install qiskit matplotlib  
jupyter notebook  

---

## 📌 Why this exists

To learn properly.  

Also to have something that shows I can take a concept, implement it, and not just memorize definitions.  

---

## 📚 Reference

Qiskit Pocket Guide  
James L Weaver and Frank J Harkins
