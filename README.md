# Machine-Learning-to-detect-Cyberattacks-for-Healthcare-Systems
A healthcare network security solution leveraging Machine Learning-Based Cyberattack Detection (MCAD) for protecting sensitive patient data in Software-Defined Networks (SDNs)
## Overview
A healthcare network security solution leveraging Machine Learning-Based Cyberattack Detection (MCAD) for protecting sensitive patient data in Software-Defined Networks (SDNs). The MCAD (Machine Learning-based Cyber-Attack Detector) project is a cybersecurity solution designed for healthcare systems. It employs machine learning techniques to identify and defend against a variety of cyber threats, including intrusion attempts and unauthorized access.

## Installation
Follow these steps to set up and run the MCAD project:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/alladikarthik02/Machine-Learning-to-detect-Cyberattacks-for-Healthcare-Systems
   ```

2. Navigate to the project directory:
   ```bash
   cd MCAD_project
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the MCAD project using the following command:
```bash
python app.py
```
This command will initiate the application, enabling the machine learning-based cyber-attack detection capabilities.

## Project Details
### 1. Cyber-Attack Detection
The MCAD project adapts a layer three learning switch application to collect normal and abnormal traffic. It is deployed on the Ryu controller, utilizing machine learning algorithms such as KNN, Decision Tree, Random Forest, Naïve Bayes, Logistic Regression, Adaptive Boosting, and XGBoost to detect and defend against cyber-attacks.

### 2. Performance Comparison
The project includes comprehensive testing with various ML algorithms and attack scenarios. A performance comparison for each pair of ML algorithms is provided, illustrating their strengths and weaknesses against specific attacks.

### 3. Robust Performance
MCAD demonstrates robust performance with a high F1-score for both normal and attack classes, indicating reliability. It achieves a throughput rate of 5,709,692 samples per second for real-time operations.

Feel free to explore the codebase and customize the project to meet your specific requirements.

## License
This project is licensed under the [BSD 3-Clause License](LICENSE). See the [LICENSE](LICENSE) file for details.
