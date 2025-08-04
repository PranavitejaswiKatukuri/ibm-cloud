
# Power Distribution Fault Detection and Classification

This project leverages machine learning and IBM Watsonx.ai AutoAI to detect and classify faults in power distribution systems, aiming to improve reliability, stability, and real-time response in electrical grids.

**1. Problem Statement**
Power distribution networks often face faults such as:
- Line-to-Ground
- Line-to-Line
- Three-Phase Faults  

These faults can cause instability, outages, and reduced reliability. Due to overlapping signals and complex electrical patterns, accurately identifying and classifying these faults in real-time remains a significant challenge.

**2. Proposed Solution**
This system provides an AI-driven approach to:
- Detect and classify faults in real-time.
- Enhance grid stability and minimize downtime.
- Leverage electrical measurements and machine learning algorithms for accurate classification.

**Key Components**
1. **Data Collection**  
   - Structured dataset including voltage, current, power factor, frequency, and fault type labels.  
   - Dataset stored in IBM Cloud Object Storage.  
   - Includes labeled scenarios (e.g., Line Breakage, Overheating).

2. **Data Preprocessing**  
   - Automated using Watsonx.ai AutoAI, which:  
     - Cleans and processes noisy, missing, and inconsistent data.  
     - Performs feature engineering to identify patterns relevant for fault classification.

**Machine Learning Algorithm**  
   - Snap Logistic Regression selected by AutoAI for efficient multiclass classification.  
   - Model trained and deployed on IBM Watsonx.ai for real-time predictions.
   -
**3. System Development Approach**
   - Upload dataset → IBM Cloud Object Storage  
   - Preprocess & Train model → Watsonx.ai AutoAI  
   - Deploy model → Real-time classification interface

 **4. Results**
   - Achieved efficient and accurate fault classification.
   - Supports quick response for improving grid reliability.
     
 **5. Future Scope**
  - Integration with IoT devices for live data streaming.
  - Expansion to renewable energy grids.
  - Deployment on edge devices for faster response in critical environments.

**6. Technologies Used**
  - IBM Cloud (Object Storage, Watsonx.ai AutoAI)
  - Machine Learning(Snap Logistic Regression)
  - Python(for dataset preparation)
  - Power System Fault Data
