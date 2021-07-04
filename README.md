# -A-Fine-Windy-Day-HackerEarth
Problem  Moving from traditional energy plans powered by fossils fuels to unlimited renewable energy subscriptions allows for instant access to clean energy without heavy investment in infrastructure like solar panels, for example.  One clean energy source that has been gaining popularity around the world is wind turbines. Turbines are massive structures that are strategically placed in perpetually windy places to generate the most energy. Wind energy is generated when the power of the atmosphere’s airflow is harnessed to create electricity. Wind turbines do this by capturing the kinetic energy of the wind. Factors such as temperature, wind direction, turbine status, weather, blade length, etc. influence the amount of power generated. Task  Predict the power that is generated (in KW/h) based on the various features provided in the dataset. Data description  The dataset folder contains the following files:      train.csv: 28200 x 22     test.csv: 12086 x 21  Evaluation metric  score = max(0 ,100*metrics.r2_score(actual, predicted))