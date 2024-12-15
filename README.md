# Xray-Imaging-Project

# Computational Toolkit for X-ray Optics and Imaging

This repository contains a Python-based project that explores the theoretical and computational aspects of X-ray optics and imaging. The goal is to showcase implementations of key algorithms, simulations, and advanced techniques to tackle ill-posed problems in imaging, such as phase retrieval, tomography, and diffraction modeling.

---

## Features

1. Simulate X-ray generation processes like Bremsstrahlung and characteristic X-rays, along with their interactions with matter, such as absorption and scattering.
2. Implement Fourier transforms to study diffraction patterns and simulate Fraunhofer and Fresnel diffraction for various apertures.
3. Model wavefront propagation to visualize how wavefronts evolve in free space under different approximations.
4. Solve ill-posed problems like phase retrieval using iterative algorithms such as Gerchberg-Saxton and incorporate regularization techniques like Tikhonov and Total Variation.
5. Implement tomographic reconstruction using the Radon transform, handling challenges like sparse data and limited angles.
6. Simulate the effect of noise on reconstructions and analyze reconstruction quality with metrics like signal-to-noise ratio (SNR).
7. Integrate machine learning techniques for denoising and phase retrieval, and provide an interactive visualization tool using Streamlit for real-time exploration of parameters.

---

## Project Structure

Here is the structure of the project:

```plaintext
.
├── src
│   ├── xray_physics.py        # Simulates X-ray generation and interaction models
│   ├── fourier_optics.py      # Handles Fourier transforms and diffraction simulations
│   ├── wavefront.py           # Models wavefront propagation
│   ├── phase_retrieval.py     # Contains phase retrieval algorithms
│   ├── tomography.py          # Implements Radon transform and reconstruction
│   ├── regularization.py      # Includes regularization techniques for inverse problems
│   ├── noise_analysis.py      # Simulates noise and evaluates its impact
│   ├── machine_learning.py    # Applies neural network-based reconstruction
│   └── app.py                 # Streamlit dashboard for interactive visualization
├── data                       # Stores sample datasets and synthetic data
├── notebooks                  # Contains Jupyter notebooks for detailed analysis
├── tests                      # Includes unit tests for all modules
├── README.md                  # Documentation for the project
├── requirements.txt           # Lists Python dependencies
└── LICENSE                    # License information
```

---

## Setup Instructions

To set up and run the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/xray-toolkit.git
   cd xray-toolkit
   ```

2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the interactive application:
   ```bash
   streamlit run src/app.py
   ```

4. Explore the Jupyter notebooks in the `notebooks` directory for step-by-step demonstrations and analyses.

---

## Key Modules

- **X-ray Physics**: Simulates X-ray spectra and their interactions with different materials.
- **Fourier Optics**: Implements 2D Fourier transforms and models diffraction patterns for different apertures.
- **Wavefront Propagation**: Visualizes wavefront evolution under Fresnel and Fraunhofer approximations.
- **Phase Retrieval**: Provides algorithms like Gerchberg-Saxton to recover phase information from intensity data.
- **Tomography**: Implements the Radon transform and tackles reconstruction challenges such as sparse data.
- **Noise Analysis**: Simulates and evaluates the impact of noise on reconstructions.
- **Machine Learning**: Introduces neural network-based solutions for denoising and solving inverse problems.

---

## Highlights

This project emphasizes:

- Clear, interactive visualizations of diffraction patterns, wavefronts, and reconstructions.
- A modular codebase, making it easy to extend with new algorithms or techniques.
- A focus on showcasing expertise in numerical computing, X-ray physics, and addressing ill-posed imaging problems.

---

## Future Improvements

- Incorporating support for real-world experimental datasets.
- Exploring advanced phase retrieval techniques like ptychography.
- Expanding machine learning integrations with more robust models.

---

## Contributing

Contributions are welcome! If you'd like to improve the project, feel free to open an issue or submit a pull request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
