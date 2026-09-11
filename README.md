# spaceX-analysis
SpaceX revolutionized aerospace economics by advertising Falcon 9 rocket launches at $62 million, whereas traditional launch providers exceed $165 million. Much of these cost savings are driven by the successful recovery and reuse of the Falcon 9 first stage.

# Core Research Objective:
This data science capstone project builds an end-to-end
analytics workflow to predict the landing success of the Falcon 9 first-stage booster,
allowing commercial competitors to bid optimally against SpaceX.

# Summary of Data Science Methodologies: 
Data was successfully compiled via
programmatic REST API requests and automated HTML web scraping. Advanced feature
engineering included mean value imputation for payload data, custom One-Hot data
encoding transformations, geospatial map clustering models with Folium, and reactive
interactive visualizations with Plotly Dash.

# Summary of Empirical Project Results: 
First-stage booster landings follow a strong
operational curve, showing a sharp increase in success rates past Flight 40. Standardized
predictive machine learning classification algorithms (specifically KNN, SVM, and Logistic
Regression) tied for top performance, achieving a verified 83.33% predictive test
accuracy score on unseen validation holdouts.
