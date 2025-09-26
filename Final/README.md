# Final Work

This folder contains the notebooks developed during the second half of the project.

## 📁 Notebooks:

### Multivariate Regression

#### 1. `MLP_Regression_Autoencoder.ipynb`

- Multivariate Regression using autoencoder latent features.
- Trains a Multilayer Perceptron (MLP) to predict atmospheric parameters.

#### 2. `MLP_Regression_Quantum_Encoding.ipynb`

- Multivariate Regression on quantum amplitude-encoded features using MLP.
- Evaluates predictive power compared to autoencoder features.

#### 3. `MLP_Regression_Autoencoder_Planetary_Inputs.ipynb`

- Multivariate regression by adding planetary parameters (Rₚ, gₚ, Temp, etc.) as input parameters along with the autoencoder features.

#### 4. `MLP_Regression_Quantum_Encoding_Planetary_Inputs.ipynb`

- Multivariate regression by adding planetary parameters (Rₚ, gₚ, Temp, etc.) as input parameters along with the quantum encoded features.

---

### Quantum vs Classical Regression

#### 1. `Hybrid_Quantum_Regression_Model.ipynb`

- Implements quantum–classical hybrid univariate regression model with a 3-qubit, 2-layer QNN layer.

#### 2. `Ablation_Study.ipynb`

- Zeroes out the quantum layer in the hybrid model.
- Compares performance to identify the quantum layer’s impact.

#### 3. `Benchmark_Classical_Regression_Model.ipynb`

- Purely classical regression model designed with parameter count comparable to the hybrid.
- Serves as a fair baseline for performance comparison with hybrid model.

---

### Study Clusters

#### 1. `Relative_Concentration.ipynb`

- Evaluation of clusters made using encoded features (classical and quantum).
- Studies relative concentrations of H₂O, CO₂, CO, CH₄, and NH₃ across clusters.
