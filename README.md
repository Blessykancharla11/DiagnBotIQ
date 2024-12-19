
---

# DiagnoBotIQ

<img width="1278" alt="Screenshot 2024-12-19 at 4 49 24 PM" src="https://github.com/user-attachments/assets/bf57ccb4-3ff3-4562-9f0a-95798533556f" />

**DiagnoBotIQ** is an AI-driven health assistant that empowers users with timely disease predictions, actionable advice, and connections to healthcare professionals. Built with machine learning and natural language processing (NLP), it bridges the gap between technology and accessible healthcare.

---

## Features

- **Disease Prediction**: Identifies possible diseases based on user symptoms using the K-Nearest Neighbors (KNN) algorithm.  
- **Symptom Analysis**: Uses NLP to preprocess and analyze user-provided symptoms.  
- **Personalized Precautions**: Recommends tailored precautions and remedies.  
- **Specialist Suggestions**: Links users to healthcare specialists based on predicted conditions.  
- **Interactive Chatbot**: Engages users through a conversational interface for seamless interaction.

---

## Installation

### Prerequisites

- Python 3.8 or higher  
- Required libraries: Flask, Pandas, NumPy, SpaCy, NLTK, Joblib  

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/DiagnoBotIQ.git
   cd DiagnoBotIQ
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download SpaCy’s language model:
   ```bash
   python -m spacy download en_core_web_sm
   ```

4. Run the application:
   ```bash
   python app.py
   ```

5. Open the app in your browser at `http://127.0.0.1:5000`.

---
<img width="1279" alt="Screenshot 2024-12-19 at 4 49 33 PM" src="https://github.com/user-attachments/assets/b5810144-1caa-4d46-a7b9-8c10c294fe51" />


## Usage

1. Start the Flask application.  
2. Provide your name, age, and gender when prompted.  
3. Enter your symptoms for analysis.  
4. View predictions, precautionary advice, and specialist recommendations.

---

## Project Overview

- **Dataset**: Utilizes medical datasets for training and testing.  
- **Algorithm**: Implements KNN for disease prediction.  
- **Framework**: Built with Flask for a lightweight and responsive web application.  
- **NLP Integration**: Processes user inputs for better symptom matching.  

---

## File Structure

```plaintext
.
├── app.py                 # Main application logic
├── templates/             # HTML templates for the web app
├── static/                # CSS and JavaScript files
├── model/                 # Pre-trained machine learning models
├── Medical_dataset/       # CSV files for symptoms, severity, and diseases
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

---

## Future Scope

- **Enhanced ML Models**: Experiment with advanced algorithms for improved accuracy.  
- **Wearable Integration**: Leverage wearable health data for comprehensive predictions.  
- **Real-Time Updates**: Incorporate real-time symptom tracking.  
- **Mobile App**: Develop a cross-platform mobile application.  

---

## Contributing

Contributions are welcome! If you'd like to enhance DiagnoBotIQ, feel free to fork the repository and submit a pull request.

---


Uploading 1734607239859005.mp4…



## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Feel free to ask if you'd like further customizations or have additional information you'd like included!


With Love❤️ BlessyKancharla11 and CodingWithRAMKUMAR
