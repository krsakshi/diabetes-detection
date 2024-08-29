<body> <header> <div class="container"> <h1>Diabetes Prediction using Machine Learning</h1> </div> </header> <div class="container content"> <h2>Overview</h2> <p>Diabetes is a chronic disease characterized by high blood sugar levels due to insulin deficiency or resistance. Early detection and management are crucial to prevent severe complications. This study evaluates the performance of various machine learning models for predicting diabetes using patient health data.</p> <h2>Dataset</h2> <p>The publicly available diabetes dataset used in this study comprises 9 rows and 9 columns. The columns are:</p> <ul> <li>Pregnancies</li> <li>Glucose</li> <li>Blood Pressure</li> <li>Skin Thickness</li> <li>Insulin</li> <li>BMI</li> <li>Diabetes Pedigree Function</li> <li>Age</li> <li>Outcome (target variable)</li> </ul> <h2>Models Evaluated</h2> <p>The following classification algorithms were evaluated:</p> <ul> <li>Logistic Regression (LR)</li> <li>Random Forest (RF)</li> <li>Support Vector Machine (SVM)</li> <li>K Nearest Neighbors (KNN)</li> <li>Gradient Boosting Classifier (GB)</li> </ul> <h2>Methodology</h2> <ol> <li><strong>Dataset Loading:</strong> The dataset was loaded and prepared for analysis.</li> <li><strong>Feature Selection:</strong> Features were selected based on their importance.</li> <li><strong>Feature Scaling:</strong> The selected features were scaled to a specific range.</li> <li><strong>Data Preparation:</strong> The dataset was split into training and test sets.</li> <li><strong>Model Training:</strong> The models were trained using the training data.</li> <li><strong>Model Validation:</strong> The models were evaluated using the test data.</li> </ol> <h2>Performance Metrics</h2> <p>The models were assessed using the following metrics:</p> <ul> <li>Accuracy</li> <li>Precision</li> <li>Recall</li> <li>F1-Score</li> </ul> <h3>Classification Report</h3> <table> <thead> <tr> <th>Algorithm</th> <th>Precision</th> <th>Recall</th> <th>F1 Score</th> </tr> </thead> <tbody> <tr> <td>Logistic Regression (LR)</td> <td>0.7778</td> <td>0.5765</td> <td>0.6621</td> </tr> <tr> <td>Random Forest (RF)</td> <td>0.8000</td> <td>0.5765</td> <td>0.7225</td> </tr> <tr> <td>Support Vector Machine (SVM)</td> <td>0.7937</td> <td>0.5882</td> <td>0.6756</td> </tr> <tr> <td>K Nearest Neighbors (KNN)</td> <td>0.7534</td> <td>0.6471</td> <td>0.6962</td> </tr> <tr> <td>Gradient Boosting (GB)</td> <td>0.7639</td> <td>0.6471</td> <td>0.7006</td> </tr> </tbody> </table> <h3>Model Accuracy</h3> <table> <thead> <tr> <th>Algorithm</th> <th>Accuracy</th> </tr> </thead> <tbody> <tr> <td>Random Forest (RF)</td> <td>81.39%</td> </tr> <tr> <td>Gradient Boosting (GB)</td> <td>79.65%</td> </tr> <tr> <td>K Nearest Neighbors (KNN)</td> <td>79.22%</td> </tr> <tr> <td>Support Vector Machine (SVM)</td> <td>79.22%</td> </tr> <tr> <td>Logistic Regression (LR)</td> <td>78.35%</td> </tr> </tbody> </table> <h2>Conclusion</h2> <p>Among the evaluated models, Random Forest achieved the highest accuracy (81.39%) and F1-score (0.7226), indicating it as the most suitable model for this dataset. Gradient Boosting was the second-best performer, followed by SVM, KNN, and Logistic Regression.</p> <h2>Getting Started</h2> <p>To replicate the results or explore further, follow these steps:</p> <ol> <li><strong>Clone the repository:</strong></li> <div class="code"> <code>git clone https://github.com/your-username/diabetes-prediction.git</code> </div> <li><strong>Navigate to the project directory:</strong></li> <div class="code"> <code>cd diabetes-prediction</code> </div> <li><strong>Install the required dependencies:</strong></li> <div class="code"> <code>pip install -r requirements.txt</code> </div> <li><strong>Run the script to perform the analysis:</strong></li> <div class="code"> <code>python main.py</code> </div> </ol><h2>Acknowledgements</h2> <ul> <li>Machine Learning Libraries: Scikit-learn, Pandas, NumPy</li> </ul> </footer> </body> </html>
