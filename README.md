# 🏏 India vs Pakistan T20 Winner Predictor

Predict the winner of India vs Pakistan T20 matches using **Machine Learning** with an **interactive Gradio dashboard**.  
This project demonstrates an end-to-end workflow from data preprocessing to model prediction and interactive visualization.



## **📌 Project Overview**

This project uses historical T20 match data to predict match winners. It includes:  

- Single match prediction with inputs: **India runs, Pakistan runs, toss winner, pitch condition**  
- Batch predictions via **CSV upload**  
- Colorful, interactive **Gradio dashboard** for instant visualization  

The model automatically handles categorical inputs and calculates **run difference** for better insights.


Kaggle: https://www.kaggle.com/lokendra

GitHub: https://github.com/lokendra
## **🛠 Features**

1. **Single Match Prediction**
   - Enter match data to predict the winner  
   - Winner is **color-coded**:  
     - 🟢 India  
     - 🔵 Pakistan  
   - Shows **run difference** with emojis  

2. **Batch Prediction (CSV Upload)**
   - Upload a CSV file with multiple matches  
   - Predict winners for all matches at once  
   - Download CSV with **predicted_winner** column  

3. **Automatic Categorical Handling**
   - Toss winner and pitch conditions are selected by **name**  
   - Model internally encodes categorical variables  

4. **Interactive Gradio Dashboard**
   - Works inline in Kaggle notebooks  
   - Shareable public link  

---

## **📈 Roadmap**

- **Phase 1: Data Collection & Preprocessing**
  - Gather historical T20 match data  
  - Clean data and calculate additional features (run difference, encoded categories)  

- **Phase 2: Model Training**
  - Train ML models (Random Forest/XGBoost)  
  - Evaluate using accuracy, confusion matrix  

- **Phase 3: Interactive Dashboard**
  - Build **Gradio dashboard** for single and batch predictions  
  - Add colorful HTML outputs and emojis for better visualization  

- **Phase 4: Deployment & Sharing**
  - Launch notebook on Kaggle  
  - Connect to GitHub for version control and sharing  

---

## **📂 Folder Structure**


---

## **⚡ Installation & Usage**

1. Clone the repository:  
```bash
git clone https://github.com/Guddubhaiya07/India_VS_Pakistan-Match-_prediction
cd t20-winner-predictor
pip install -r requirements.txt
