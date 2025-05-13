
# MediScan AI Platform

A modern healthcare platform that combines AI-powered disease prediction with telemedicine capabilities, built on a microservices architecture with dedicated machine learning and application backends.

## 🌟 Features

* **AI Disease Prediction**

  * Multiple ML models (Logistic Regression, Random Forest, SVM, etc.)
  * Symptom-based disease analysis
  * Real-time disease prediction API
  * Covers 41 distinct disease categories

* **Telemedicine Portal**

  * Separate dashboards for doctors and patients
  
  * Real-time online consultations
  * Medical report uploads and viewing
  * Smart appointment scheduling system

* **User Experience**

  * Sleek, responsive UI with React and Tailwind CSS
  * Intuitive symptom input interface
  * Smooth authentication and navigation flow
  * Works across desktops, tablets, and mobile devices

## 🔧 Tech Stack

### Frontend (`/frontend`)

* React (with TypeScript)
* Tailwind CSS for UI styling
* Vite as the build tool
* Google OAuth via `@react-oauth/google`

### Main Backend (`/backend`)

* Node.js with Express.js
* MongoDB as the primary database
* JWT for secure authentication
* WebSockets/real-time communication
* File upload and Google OAuth integration

### ML Backend (`/6ml`)

* Python Flask API
* Machine Learning models using `scikit-learn`:

  * Logistic Regression
  * Decision Trees
  * Random Forest
  * SVM
  * Naive Bayes
  * K-Nearest Neighbors
* `pandas` for data processing and input handling

