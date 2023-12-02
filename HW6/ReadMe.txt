# Digit Classification with SVM

## Team Members
- Safa Asrar
  - Email: [asrars20@students.ecu.edu]
- Shemar Allen
  - Email: [allens20@students.ecu.edu]
- Abid Haq
  - Email: [haqa19@students.ecu.edu]

## Parameters and Results Comparison

### Linear Kernel
- **Best Parameters:** {'svc__C': 3.845401188473625}
- **Training Accuracy (RandomizedSearchCV):** 0.9527
- **Test Accuracy:** 0.9556
- **Cross-Validation Accuracy:** 0.9193

### Radial Kernel (RBF)
- **Best Parameters:** {'svc__C': 1.6601864044243653}
- **Training Accuracy (RandomizedSearchCV):** 0.9861
- **Test Accuracy:** 0.9806
- **Cross-Validation Accuracy:** 0.9711

### Polynomial Kernel
- **Best Parameters:** {'svc__C': 7.319987722668247, 'svc__degree': 3}
- **Training Accuracy (RandomizedSearchCV):** 0.9805
- **Test Accuracy:** 0.9833
- **Cross-Validation Accuracy:** 0.9499

## Usage
1. Clone the repository.
2. Install required dependencies.
3. Run the notebook or script for SVM digit classification.

