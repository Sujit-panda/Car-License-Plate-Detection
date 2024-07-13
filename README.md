
# License Plate Detection


The Automatic Car Number Plate Detection System employs computer vision and machine learning to automatically detect and recognize vehicle license plates, enhancing traffic management and law enforcement applications.

The introduction presents the "Automatic Car Number Plate Detection System," a computer vision-based project with Python, OpenCV, TensorFlow, Keras, and Tesseract OCR. It addresses the significance of automated license plate recognition in traffic management, parking systems, and law enforcement. The system's core functionalities include license plate detection and character recognition.

# Requirement specifications

- Functional Requirements
    - Image input
    - License Plate Detection
    - Character Segmentation
    - Character Recognition
    - Text Recognition
    - User Interface
- Non - Functional Requirements
    - Accuracy
    - Resource Efficiency
    - Compatibility
    - Scalability
    - Security
    - Documentation and Support

# Software Tools
    * OpenCV
    * NumPy
    * TensorFlow & Keras
    * Tesseract OCR
    * Python Imaging Library(PIL)

# Methodology

- Preprocess the input image by blurring, converting to grayscale, and finding    
  vertical edges.

- Apply Thresholding and morphological transformations to reveal the license 
  plate area.

- Find contours and validate their size ratios and areas to identify the license 
  plate region.

- Segment and recognize individual characters using adaptive thresholding and 
  contour analysis.

# Implementation
    + Data Collection & Preprocessing
    + License Plate Detection Module
    + Character segmentation
    + Character Recognition Model
    + Text Recognition
    + User Interface Development
    + Integration & Flow
    + Testing & Validation
    + Optimisation & Refinement
    + Documentation & Deployment


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Limitation & Future Scope
 # Limitations
         Limited Dataset Diversity
         Performance under Extreme Conditions
         Hardware Constraints
         Non-Standard License Plates
         Occluded or Partially Visible Plates
         Inaccurate Character Recognition
         Language Limitations
         Deployment Environment
 # Future Scope
         Multi-language Support
         Cloud Deployment
         Mobile App Integration
         Vehicle Colour Detection
         Enhanced User Interface
         Security Enhancements
         Vehicle Make and Model Recognition
         Real time license plate detection




