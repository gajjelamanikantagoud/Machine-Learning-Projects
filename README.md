

  <h1>🏡 Machine Learning Projects<h1>
    <h1>Project - 1  Best Model For House Price Prediction (Ames) </h1>

  <div class="box">
    <h2>📌 Project Overview</h2>
    <p>
      This project implements multiple regression models to predict <span class="highlight">house prices</span> 
      using the <code>Ames Housing Dataset</code> from OpenML.  
      It demonstrates how different machine learning algorithms perform on a real-world dataset, 
      comparing their accuracy and evaluation metrics.
    </p>
  </div>

  <div class="box">
    <h2>🧠 Problem Statement</h2>
    <p>
      Given housing features (location, size, quality, etc.), predict the <span class="highlight">final house sale price</span>.  
      This assists in property valuation, real estate decision-making, and mortgage risk assessment.
    </p>
  </div>

  <div class="box">
    <h2>🛠️ Technologies Used</h2>
    <ul>
      <li>Python</li>
      <li>Pandas, NumPy</li>
      <li>Matplotlib, Seaborn</li>
      <li>Scikit-learn (sklearn)</li>
      <li>OpenML Dataset</li>
    </ul>
  </div>

  <div class="box">
    <h2>🔍 Workflow</h2>
    <ol>
      <li>Data Loading using <code>fetch_openml()</code></li>
      <li>Exploratory Data Analysis (EDA)</li>
      <li>Data Preprocessing (handling missing values, encoding, scaling)</li>
      <li>Model Building:
        <ul>
          <li>Linear Regression</li>
          <li>Ridge Regression</li>
          <li>Lasso Regression</li>
          <li>Random Forest</li>
        </ul>
      </li>
      <li>Model Evaluation using R² Score, RMSE</li>
      <li>Performance Comparison</li>
    </ol>
  </div>

  <div class="box">
    <h2>📊 Results & Observations</h2>
    <table border="1" cellpadding="8" cellspacing="0">
      <thead>
        <tr>
          <th>Model</th>
          <th>RMSE</th>
          <th>R² Score</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Linear Regression</td>
          <td>36879.82</td>
          <td>0.8227</td>
        </tr>
        <tr>
          <td>Ridge Regression</td>
          <td>36878.88</td>
          <td>0.8227</td>
        </tr>
        <tr>
          <td>Lasso Regression</td>
          <td>36879.82</td>
          <td>0.8227</td>
        </tr>
        <tr>
          <td><strong>Random Forest</strong> 🌟</td>
          <td><strong>29225.38</strong></td>
          <td><strong>0.8886</strong></td>
        </tr>
      </tbody>
    </table>
    <p>
      ✅ <span class="highlight">Random Forest</span> outperformed other models, achieving the best accuracy (lowest RMSE, highest R²).
    </p>
  </div>

</body>
</html>

<h3> ⚡Visualization<h3>
<img width="645" height="622" alt="download" src="https://github.com/user-attachments/assets/a5b72980-80ae-4917-8e7e-9f8c7a83b664" />
