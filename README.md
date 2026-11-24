# 🧠 Computational Neuroscience Research Suite

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Domain](https://img.shields.io/badge/Domain-Neuroscience%20%26%20Dynamical%20Systems-purple.svg)](https://github.com/KABURAKURIA/computational-neuroscience)

A comprehensive research suite comprising **27 mathematical modeling notebooks** implementing biophysical neuron dynamics, synaptic plasticity (STDP), dynamical network systems, cognitive attractor memory, and predictive coding.

---

## 🔬 Mathematical Models & Simulations

This repository implements canonical equations in computational neuroscience:

### 1. Single-Neuron Biophysics
- **Izhikevich Spiking Model**: Simulates regular spiking, fast spiking, bursting, and chattering cortical neurons.
  $$\frac{dv}{dt} = 0.04v^2 + 5v + 140 - u + I$$
  $$\frac{du}{dt} = a(bv - u)$$
- **Hodgkin-Huxley & Morris-Lecar Models**: Conductance-based ionic channel kinetics ($Na^+$, $K^+$, leak currents).
- **FitzHugh-Nagumo Model**: Two-dimensional reduction of action potential generation and excitability.

### 2. Synaptic Plasticity & Learning
- **Spike-Timing-Dependent Plasticity (STDP)**: Asymmetric Hebbian learning rules based on millisecond spike intervals.
- **Neuromodulation Models**: Dopaminergic reward-prediction error effects on synaptic weight matrices.

### 3. Population Dynamics & Synchrony
- **Wilson-Cowan Equations**: Excitatory and inhibitory coupled neural population limit cycles.
- **Kuramoto Oscillator Model**: Phase synchronization, order parameters, and emergent coherence across brain regions.
- **Attractor & Hopfield Networks**: Content-addressable memory retrieval, energy landscape minimization, and pattern completion.

### 4. Cognitive & Behavioral Systems
- **Bayesian Brain & Predictive Coding**: Hierarchical inference and sensory error minimization.
- **Central Pattern Generators (CPG)**: Rhythmic locomotion and motor control circuits.
- **Spatial Navigation**: Grid cell and place cell toroidal attractors for spatial representation.

---

## 📚 Notebook Directory

```
├── Single_Neuron_Models.ipynb              # Leaky Integrate-and-Fire, Hodgkin-Huxley
├── Izhikevich_Neuron_Model.ipynb           # 20 distinct neurocomputational firing modes
├── FitzHugh_Nagumo_Model.ipynb             # Phase plane analysis & nullclines
├── Morris_Lecar_Model.ipynb                # Barnacle muscle fiber conductance dynamics
├── Dendritic_Computation.ipynb             # Cable equation & active dendritic integration
├── Synaptic_Plasticity_STDP.ipynb          # Millisecond-level spike timing learning
├── Hebbian_Learning.ipynb                  # Long-term potentiation (LTP) & depression (LTD)
├── Spiking_Neural_Networks.ipynb           # SNN architectures with temporal coding
├── Wilson_Cowan_Model.ipynb                # E-I balanced population firing rates
├── Kuramoto_Model.ipynb                    # Macroscopic phase synchronization
├── Hopfield_Network_Memory.ipynb           # Associative memory & energy functions
├── Attractor_Networks.ipynb                # Continuous & discrete neural attractors
├── Advanced_Network_Dynamics.ipynb         # Small-world and scale-free neural topologies
├── Neural_Encoding.ipynb                   # Tuning curves, Poisson spike trains
├── Neural_Decoding.ipynb                   # Population vector decoding, Bayesian estimators
├── Sensory_Processing.ipynb                # Receptive fields (Gabor filters, cochlear models)
├── Motor_Control_Models.ipynb              # Optimal feedback control & internal forward models
├── Central_Pattern_Generators.ipynb        # Coupled oscillators for locomotion
├── Decision_Making_Models.ipynb            # Drift-diffusion models & race models
├── Working_Memory_Models.ipynb             # Persistent neural activity & recurrent gating
├── Spatial_Navigation_Models.ipynb         # Grid cells, place cells, and head direction cells
├── Astrocyte_Neuron_Interactions.ipynb     # Tripartite synapse & gliotransmission
├── Neuromodulation_Models.ipynb            # Dopamine, serotonin, and noradrenaline dynamics
├── Bayesian_Inference_Brain.ipynb          # Prior integration and likelihood weighting
├── Predictive_Coding.ipynb                 # Rao-Ballard hierarchical predictive processing
├── Reinforcement_Learning_Neuro.ipynb      # TD-learning and basal ganglia dopamine pathways
└── Computational_Neuroscience_Guide.ipynb  # Comprehensive synthesis and pedagogical guide
```

---

## 💻 Environment Setup

```bash
git clone https://github.com/KABURAKURIA/computational-neuroscience.git
cd computational-neuroscience

python -m venv venv
source venv/bin/activate

pip install numpy scipy matplotlib jupyter
jupyter notebook
```

---

## 📄 License

MIT License.
