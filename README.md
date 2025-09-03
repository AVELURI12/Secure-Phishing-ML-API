# Secure-Phishing-ML-API
A machine learning project for detecting phishing websites, with a focus on secure deployment. Currently, the ML model is trained and evaluated. Next steps involve deploying it as an API with authentication and monitoring.

---

## Overview
Phishing websites are one of the most common attack vectors in cybersecurity.  
This project combines machine learning with security-focused deployment practices to build a phishing detection system that is both accurate and safe to use.

---

## Current Progress
- Trained a Multilayer Perceptron model using TensorFlow/Keras to detect if website is legitimate, suspicious, or phishy.  
- Preprocessed and cleaned dataset.  
- Achieved 93% accuracy.  

---

## Planned Features
- Demonstrate secure deployment and operations practices for ML models.
- API Deployment: Serve the model via FastAPI.  
- Authentication: Protect API access with JWT tokens or API keys.  
- Monitoring & Logging: Track requests, detect suspicious usage, and log predictions.  
  
---

##  Dataset
- UCI Repository
- https://archive.ics.uci.edu/dataset/327/phishing+websites   
- Contains features describing website structure and behavior (e.g., URL length, HTTPS usage, Domain based).  
