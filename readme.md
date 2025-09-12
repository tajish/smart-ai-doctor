# Smart AI Doctor with SVC and Flask

Smart AI Doctor makes your life easier by analyzing multiple factors of your symptoms and predicting possible diseases for you.  
The model is built using **Support Vector Classifier (SVC)** and trained on a dataset with more than **15,000 historical records** and **41 features**.

---

## ✨ Features

- **Disease Prediction**  
  Takes symptoms as input and predicts possible diseases.

- **Description**  
  Provides a detailed description of the diagnosed disease, just like a real doctor.

- **Precautions**  
  Suggests important steps you should take to tackle the diagnosed disease.

- **Medication**  
  Recommends medications that could be helpful for the diagnosed condition.

- **Diet Chart**  
  Suggests dietary habits and nutritional guidance. 

- **Workout**  
  Suggests suitable workouts for better recovery and lifestyle improvement. 

---

## 🚀 Demo

To run a demo of the Smart AI Doctor:

```bash
# Clone this repository
git clone https://github.com/your-username/smart-ai-doctor.git

# Navigate into the folder
cd smart-ai-doctor

# Run the Flask app
python app.py
```

Then, open your browser and visit:  
👉 **http://127.0.0.1:5000/**

---

## 🛠️ Tech Stack

- **Python** – Core programming language  
- **Scikit-learn (SVC)** – Machine Learning model for disease prediction  
- **Flask** – Web framework for the user interface  
- **HTML/CSS/JS** – Frontend for user interaction

---

## 📂 Project Structure

```
smart-ai-doctor/
│── app.py                # Flask web app
│── model.pkl             # Trained SVC model
│── templates/            # HTML templates for Flask
│── static/               # CSS, JS, Images
│── requirements.txt      # Python dependencies
│── README.md             # Project documentation
```

---

## 🔧 How to Tweak the Project for Your Use Case

1. Replace the dataset in the `data/` folder with your own dataset.  
2. Retrain the model by modifying the training script.  
3. Add more features like advanced diet charts, personalized workout plans, or wearable device integrations.  

---

## 📸 Screenshots

### Home Page
![Home Page](Model/Demo_1.jpg)

### Results Page
![Input Page](Model/Demo_2.jpg)

### Features Page
![Features Page](Model/Demo_3.jpg)


---

## 📌 Future Work

- Improve accuracy with advanced models like Random Forest, XGBoost, or Neural Networks  
- Add personalized healthcare recommendations  
- Integrate with wearable devices for real-time health monitoring  
- Deploy the app on cloud platforms (AWS, GCP, Azure, or Heroku)  

---

## 🤝 Contributing

Contributions are always welcome!  
Please fork this repository and submit a pull request for any improvements.

---

## 📜 License

This project is licensed under the MIT License.  
You are free to use, modify, and distribute this project for personal or commercial purposes.

---

## 👨‍💻 Author

Developed with ❤️ by **Your Name**  

