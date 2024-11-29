# **Next-Word Prediction Using GPT-2**

This project demonstrates a Next-Word Prediction application fine-tuned on the **Sherlock Holmes** text dataset. The repository includes the training code, dataset, and an interactive web interface to generate next-word suggestions.

---

## **Features**
- Fine-tuned **GPT-2** and **DistilGPT-2** models on custom text data.
- Flask API for generating next-word predictions.
- A web interface for user-friendly interaction.

---

## **Repository Structure**
```
├── NextWordPrediction.ipynb  # Jupyter notebook containing the training and API code
├── sherlock.txt              # Dataset used for fine-tuning the models
├── index.html                # Webpage for the interactive interface
```

---

## **Installation Instructions**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your_username/Next-Word-Prediction.git
   cd Next-Word-Prediction
   ```

2. **Set Up a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask API**
   - Navigate to the folder containing the Jupyter notebook and execute the code to start the Flask server.

5. **Open the Web Interface**
   - Open `index.html` in a web browser to access the prediction interface.

---

## **Usage**

- Enter the starting part of a sentence in the input box on the webpage.
- The app will suggest possible next words based on the fine-tuned GPT-2 models.

---

## **Dataset**

- The dataset used for training is **sherlock.txt**, consisting of text from Sherlock Holmes stories.

---

## **Demo**

- **Local Use**: Run the Flask server from the notebook and use `index.html` for predictions.

---

## **Technologies Used**
- **Python**: Programming language for training and API development.
- **Hugging Face Transformers**: Library for GPT-2 fine-tuning and text generation.
- **Flask**: Backend API for prediction.
- **HTML**: Frontend interface.

---

## **Future Improvements**
- Extend the dataset for better generalization.
- Integrate additional fine-tuned models.
- Add more interactive web features.

---

## **Author**
Parth Sharma  
github.com/ParthYuki  

Feel free to contribute or suggest improvements! 😊

---
