# Mouse Dynamics Authentication

## Project Overview
Mouse Dynamics Authentication leverages user-specific mouse interaction patterns to create a secure and non-intrusive biometric authentication system. This project employs machine learning models to classify users based on their mouse movement behaviors, including spatial and temporal patterns.

## Features
- **Machine Learning Architecture**: Combines CNN, LSTM, and ANN for feature extraction and classification.
- **Advanced Feature Engineering**: Includes dynamic features like speed, acceleration, click frequency, and idle time.
- **Class Balancing Techniques**: Uses SMOTE and random oversampling to handle class imbalance and improve model accuracy.
- **Optimized Performance**: Achieved 84% classification accuracy by leveraging hyperparameter tuning and oversampling strategies.

## Project Structure
```
Mouse-Dynamics-Authentication/
├── data/                # Raw and processed datasets
├── notebooks/           # Jupyter notebooks for exploration and visualization
├── src/                 # Core implementation files
│   ├── models.py        # Machine learning models
│   ├── preprocess.py    # Data preprocessing pipeline
│   ├── train.py         # Training and evaluation scripts
├── results/             # Model evaluation reports and metrics
├── .gitignore           # Git ignore file
├── README.md            # Project documentation
└── requirements.txt     # Python dependencies
```

## Technologies Used
- **Programming Language**: Python
- **Libraries**: TensorFlow, Keras, Pandas, NumPy, Scikit-learn, Matplotlib
- **Tools**: Jupyter Notebook, Git, Google Colab

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/Mouse-Dynamics-Authentication.git
   cd Mouse-Dynamics-Authentication
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Add your dataset to the `data/` directory.

## Usage
1. Preprocess the data:
   ```bash
   python src/preprocess.py
   ```

2. Train the model:
   ```bash
   python src/train.py
   ```

3. Evaluate the model:
   Check results and metrics in the `results/` folder.

## Key Results
- Achieved 84% classification accuracy on test data.
- Improved minority class performance using class balancing techniques.

## Future Work
- Explore advanced balancing strategies, such as hybrid sampling.
- Extend the feature set with additional behavioral metrics.
- Investigate the feasibility of real-time continuous authentication.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request for major changes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

