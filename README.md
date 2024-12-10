Leveraging Quantum Machine Learning for Mars Exploration Data

This repository contains the code and resources for our Senior Design Project, where we leverage **Quantum Machine Learning** to comprehensively integrate and analyze data from Mars exploration missions.

Project Overview

The goal of this project is to combine quantum and classical algorithms to process Mars surface images collected by the Curiosity Rover. We aim to use **Quantum Neural Networks (QNNs)** to enhance the classification and analysis of labeled Mars datasets, contributing to more efficient data processing and potentially deeper insights from planetary exploration data.

 Key Aspects:
- **Quantum Encoding**: Utilization of **Binary** and **Amplitude Encoding** to map Mars surface data into qubits.
- **Hybrid Model**: Integration of classical and quantum algorithms to improve model performance.
- **Dataset**: Mars surface image dataset, version 1, labeled for training.

 System Diagram

1. **Pre-Processing**:
   - Image Resizing
   - Normalization
   - Quantum Feature Mapping (Encoding)
   
2. **Quantum Encoding**:
   - **Binary Encoding**: Transforms real numbers into binary format, mapping them into qubits.
   - **Amplitude Encoding**: Uses wave functions to encode large datasets efficiently with an exponential advantage.

3. **Quantum Circuit Deployment**:
   - The quantum system processes the encoded data using qubits, facilitating quantum-classical hybrid model execution.

Technologies Used

- **Quantum Computing**: Quantum circuits and algorithms for encoding and classification.
- **Classical Algorithms**: Used in combination with quantum algorithms to form a hybrid model.
- **Python**: Main programming language.
- **Libraries**: 
  - Qiskit (Quantum framework)
  - TensorFlow (Classical model support)
  - NumPy, SciPy (Data processing)
  
 Challenges and Complexities

- Limited availability of resources and papers on Quantum Machine Learning.
- Dataset issues and versioning complexities.
- Compatibility challenges with library updates and quantum environments.

 Installation and Setup

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/mahmudresin/Senior-Design-Project-499.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Senior-Design-Project-499
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the main program:
   ```bash
   python main.py
   ```

## Project Structure

```plaintext
Senior-Design-Project-499/
│
├── data/               # Mars surface images dataset
├── src/                # Source code files
│   ├── main.py         # Entry point for the project
│   ├── qnn.py          # Quantum Neural Network implementation
│   └── utils.py        # Utility functions for pre-processing
├── models/             # Pre-trained models and configurations
├── tests/              # Unit tests
├── README.md           # Project documentation
└── requirements.txt    # Dependencies and libraries
```



## Contributing

We welcome contributions! If you'd like to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-branch
   ```
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

We extend our gratitude to our project supervisor Dr. Shahnewaz Siddique for his support and guidance throughout the project.

---

For any questions, feel free to reach out via email.
yeaminmahmudres@gmail.com
