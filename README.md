

---

```markdown
# 🌱 AgriAI: Smart Crop Recommender & Sustainability Assistant

An AI-powered agriculture assistant that helps farmers and agriculture experts recommend the best crops based on real-time soil and climate conditions. Designed to enhance productivity while promoting sustainable practices.

## 🚀 Features (Case 1 Completed)

✅ **Crop Recommendation System**  
- Based on user input: Soil pH, Soil Moisture, Temperature, and Rainfall  
- Suggests **top 2 suitable crops** for a given region  
- Uses a trained Machine Learning classification model (Random Forest)

✅ **Sustainability Score**  
- Displays a mock sustainability score (100/100)  
- Can be extended in future versions to reflect real environmental impact metrics

## 🧠 How It Works

1. The system takes user inputs:
   - 🌡️ Temperature
   - 🌧️ Rainfall
   - 💧 Soil Moisture
   - ⚗️ Soil pH

2. Processes the inputs through a trained ML model

3. Returns the **top 2 recommended crops** suited to the environment

4. Displays a **sustainability score** along with recommendations

---

## 📊 Sample Output

```

Enter Soil pH (e.g., 6.5): 6.8
Enter Temperature (°C) (e.g., 28): 27
Enter Rainfall (mm) (e.g., 120): 150
Enter Soil Moisture (%) (e.g., 25): 30

✅ 🌾 Recommended Crops for Your Region:
1️⃣ Corn
2️⃣ Wheat

🌿 Sustainability Score: ✅ 100 / 100

```

---

## 🛠️ Tech Stack

- **Python**
- **Pandas, Scikit-learn**
- **Jupyter Notebook / Google Colab**
- **Machine Learning**: Random Forest Classifier

---

## 📂 Project Structure

```

AgriAI/
│
├── data/                   # CSV dataset with soil and crop details
├── model/                  # Trained ML models (if saved)
├── notebooks/              # Jupyter notebooks for training/testing
├── crop\_recommender.py     # Interactive command-line app
├── README.md               # Project description and instructions

```

---

## 📌 Setup Instructions

1. Clone the repo:
```

git clone [https://github.com/yourusername/agri-ai.git](https://github.com/yourusername/agri-ai.git)
cd agri-ai

```

2. Install dependencies:
```

pip install pandas scikit-learn

```

3. Run the script:
```

python crop\_recommender.py

```

---

## 🌱 Future Enhancements

- ✅ Case 2: Farming Advice Chatbot (COMING NEXT)
- 🔄 Real-time data from sensors/APIs
- 📈 Sustainability score using actual environmental metrics
- 🌐 Deploy as a web or mobile application
- 🧠 Add deep learning for smarter recommendations

---

## 🤝 Contributing

Contributions, ideas, and suggestions are welcome!  
Please open an issue or submit a pull request.

---

## 📃 License

This project is licensed under the [MIT License](LICENSE).

---

## ✨ Acknowledgements

- Dataset sources: [your-dataset-source-name]
- Inspired by the need for intelligent and sustainable agriculture tools

---

```




