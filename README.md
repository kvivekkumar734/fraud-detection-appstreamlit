<h1> Fraud Detection System using Logistic Regression</h1>

<p>
A Machine Learning based <b>Fraud Detection System</b> developed using
<b>Logistic Regression , naive bayes , knn and the best result got in Logistic regression</b> and deployed with <b>Streamlit</b>.
The project was built completely using the <b>Anaconda</b> environment.
</p>

<hr>

<h2> Project Overview</h2>
<p>
This project focuses on detecting fraudulent transactions using supervised
machine learning techniques. Both <b>Linear Regression</b> and
<b>Logistic Regression</b> were implemented and evaluated, but
<b>Logistic Regression</b> was finalized due to its superior performance
for binary classification problems.
</p>

<hr>

<h2> Features</h2>
<ul>
  <li>Binary classification: Fraud vs Legitimate</li>
  <li>Logistic Regression based ML model</li>
  <li>Interactive Streamlit web application</li>
  <li>End-to-end ML pipeline</li>
</ul>

<hr>

<h2> Tech Stack</h2>
<ul>
  <li><b>Language:</b> Python</li>
  <li><b>Environment:</b> Anaconda</li>
  <li><b>Libraries:</b> NumPy, Pandas, Scikit-learn</li>
  <li><b>Visualization:</b> Matplotlib, Seaborn</li>
  <li><b>Deployment:</b> Streamlit</li>
</ul>

<hr>

<h2>Project Structure</h2>
<pre>
Fraud-Detection-System/
│
├── app.py                  # Streamlit application
├── model.ipynb             # Model training notebook
├── dataset.csv             # Dataset (or external link)
├── requirements.txt        # Dependencies
└── README.md
</pre>

<hr>

<h2> Dataset</h2>
<p>
The dataset consists of transaction-related features with the target variable:
</p>
<ul>
  <li><b>0</b> → Legitimate Transaction</li>
  <li><b>1</b> → Fraudulent Transaction</li>
</ul>

<p>
<b>Dataset Link:</b><br>
<a href="https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset">
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
</a>
</p>

<p><i>Note: Dataset is not uploaded to GitHub due to large size.</i></p>

<hr>

<h2>⚙️ Installation & Setup</h2>

<h3>1️ Clone the Repository</h3>
<pre>
git clone https://github.com/your-username/fraud-detection-system.git
cd fraud-detection-system
</pre>

<h3>2️ Create Conda Environment</h3>
<pre>
conda create -n fraud_env python=3.10
conda activate fraud_env
</pre>

<h3>3️ Install Dependencies</h3>
<pre>
pip install -r requirements.txt
</pre>

<hr>

<h2> Run the Application</h2>
<pre>
streamlit run app.py
</pre>

<p>
Open the URL shown in the terminal (usually
<b>https://frauda.streamlit.app/</b>).
</p>

<hr>

<h2> Model Details</h2>
<ul>
  <li><b>Algorithm:</b> Logistic Regression</li>
  <li><b>Why Logistic Regression?</b>
    <ul>
      <li>Best suited for binary classification</li>
      <li>Provides probability-based predictions</li>
      <li>Easy to interpret</li>
    </ul>
  </li>
  <li><b>Evaluation Metrics:</b> Accuracy, Precision, Recall, Confusion Matrix</li>
</ul>

<hr>

<h2> Future Improvements</h2>
<ul>
  <li>Apply advanced models (Random Forest, XGBoost)</li>
  <li>Cloud deployment (Streamlit Cloud )</li>
  <li>Add model explainability </li>
</ul>

<hr>

<h2> Author</h2>
<p>
<b>Vivek Upadhyay</b><br>
Data Scientist
</p>

<hr>


