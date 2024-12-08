# OCR Based Hand Written Digit Recognition

This repository contains the implementation and results of an Optical Character Recognition (OCR) project aimed at identifying handwritten digit sequences from images. The project uses a custom-trained Convolutional Neural Network (CNN) model and includes preprocessing steps to enhance prediction accuracy.

---

## Repository Contents

### 1. **Code**
- `recognition.ipynb`:  
  Contains the full implementation of the OCR process, including preprocessing, digit segmentation, model prediction, and visualization of results.  
  **Highlights**:
  - Step-by-step preprocessing.
  - Predictions for all 41 test images.
  - Accuracy calculations and error analysis.

### 2. **Model**
- `cnn-model.h5`:  
  The trained CNN model used for digit recognition.

### 3. **Data**
- `Assignment_CV/`:  
  A folder containing the 41 test images used in this project. Each image represents a sequence of handwritten digits.

- `ground_truth.csv`:  
  The ground truth data for all 41 images, listing the correct digit sequences.

- `predicted_digits.csv`:  
  The predictions made by the model for each test image.

- `mismatched_results.csv`:  
  A file detailing mismatches between the predicted and ground truth sequences, along with identified errors.

### 4. **Report**
- **Google Doc**: [Detailed Report](https://docs.google.com/document/d/18b4Y_bEoNDCCxkhDMwwz74BaY0S4uxI4THRK2LkhJao/edit?tab=t.0)  
  Comprehensive documentation of the project, including:
  - Approach and methodology.
  - Challenges faced and solutions.
  - Model architecture and parameter choices.
  - Results and analysis.

- **.docx Report**:  
  The same detailed report is available as a `.docx` file in the repository for offline reference.

---

## How to Use

1. **Run the Code**:  
   Open `recognition.ipynb` to explore the entire OCR workflow. Ensure the `Assignment_CV` folder and `cnn-model.h5` are in the same directory before running the code.

2. **Review the Predictions**:  
   Check `predicted_digits.csv` for model predictions and `mismatched_results.csv` for discrepancies compared to `ground_truth.csv`.

3. **Read the Report**:  
   For a detailed understanding of the project, review the Google Doc linked above or the `.docx` file provided in the repository.

---
