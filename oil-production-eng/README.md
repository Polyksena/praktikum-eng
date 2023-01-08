# Data

There are oil sample data from three different regions.

Data description:
• id — unique well identifier;
• f0, f1, f2 — three signs of dots (it doesn't matter what they mean, but they are important);
• product — the volume of reserves in the well (thousand barrels).

# Task 

Choose one of the three regions where the development of oil wells is most profitable. For this purpose investigate the quality indicators of wells in each of the regions, the potential profit and the risk of losses.

To build a model predicting the most "productive", i.e. wells with the highest estimates of values. And then, using the Bootstrap sampling, determine the distribution of profits and the probability of losses. Basing on this study, determine the most promising region for well development.

# Main stages  

1. Data preprocessing, exploration and visualization
2. Training and checking the model
3. Calculation of profit and risks

# Used libraries

- Pandas
- Matplotlib
- Seaborn
- Numpy
- Sklearn
  - LinearRegression
- Bootstrap sampling

