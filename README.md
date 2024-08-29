"# Predicting-Credit-Card-Approval" 
![image](https://github.com/user-attachments/assets/ca6a984a-a648-438a-9347-e6591a968135)


🏦 Building the Credit Card Approval Prediction App 🚀
👨‍💼 Defining the Business Problem
Ever wondered if you could get approved for a credit card without hurting your credit score? I'm creating an app that does just that! By leveraging advanced machine learning models, this app predicts your approval chances—no hard inquiries required! 💳

📊 Data Source
The project is powered by data from Kaggle's Credit Card Approval dataset, providing a solid foundation for building accurate predictions.

🔍 Methods
I'm using a combination of:

Exploratory Data Analysis
Bivariate & Multivariate Analysis
Model Deployment via AWS S3 & Streamlit
⚙️ Tech Stack
For this project, I'm working with:

Python 🐍 for the core logic
Streamlit 🌐 for the user interface
AWS S3 ☁️ for secure model storage
🌟 Key Results
I've identified that Gradient Boosting, with a Recall of 90%, is the top-performing model 📈. Given the economic context during a bull market, I'm prioritizing recall to minimize the risk of defaults.

📚 Lessons Learned
Through this project, I've discovered that income, family size, and employment length are the strongest predictors for credit card approval. I'm focusing on these features to improve the model's accuracy.

🚀 How to Run the App Locally
Set up the environment: Use conda to create a virtual environment with the necessary dependencies.
Start the app: Run the Streamlit server with streamlit run cc_approval_pred.py to launch the app locally.
🌐 Deployment
I'm making deployment easy with Streamlit! Simply follow a few steps to deploy your own version. Don’t forget to add your AWS/GCP secret keys for secure model storage.

📂 Repository Structure
assets/: Contains images and environment files
datasets/: CSV files for training and testing
notebooks/: Jupyter notebook with analysis and model training
🤝 Contribution
I'm excited to welcome contributions! If you have ideas or improvements, feel free to open a pull request. Let's collaborate and enhance this app together! 💡
