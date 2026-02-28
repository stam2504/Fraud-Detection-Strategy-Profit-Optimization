# Fraud-Detection-Strategy-Profit-Optimization
End-to-end Fraud Detection system using Deep Learning &amp; Random Forest, featuring a Power BI Profit Optimization Dashboard to balance operational costs vs. fraud losses.
Here is the complete, professional README.md in English. This version is designed to impress recruiters by highlighting the transition from technical metrics to business value.

💳 Credit Card Fraud Detection: Strategy & Profit Optimization
📌 Project Overview

This project goes beyond simple fraud prediction by applying Quantitative Analysis to identify the ideal balance between operational costs and financial loss prevention. By comparing advanced Machine Learning and Deep Learning models, we propose a strategy that maximizes the bank's Net Profit.
🚀 Key Features

    Deep Learning Implementation: Developed a Neural Network using TensorFlow/Keras that achieved an outstanding ROC AUC of 0.98.

    Class Imbalance Handling: Utilized Class Weights (0: 1, 1: 500) to address the highly imbalanced nature of fraud data.

    Profit Optimization (Quant Analysis): Calculated the Optimal Threshold (0.99) to minimize manual inspection costs while mitigating fraud losses.

    Interactive Power BI Dashboard: Designed a dynamic two-page report for real-time strategic decision-making.

📊 Model Comparison & Results

The analysis demonstrated that the Deep Learning model provides the most stable and profitable solution for the business:
Metric	Random Forest	Deep Learning (Neural Net)
ROC AUC	0.96+	0.98
Best Threshold	0.07	0.99
Max Net Profit	5.43€	1.32€

    Strategic Insight: While Random Forest showed high profit in specific low-threshold scenarios, Deep Learning was selected as the final solution due to its superior classification power (AUC 0.98). At the 0.99 threshold, it reduces Inspection Costs to just 0.02%, allowing the bank to operate with maximum efficiency.

💻 Technical Stack

    Languages: Python (Pandas, NumPy, Scikit-learn).

    Deep Learning: TensorFlow & Keras.

    Visualizations: Matplotlib, Seaborn.

    Business Intelligence: Power BI (DAX, Interactive Slicers).

📈 Power BI Insights

The dashboard is built on two strategic pillars:

    Fraud Analytics Strategy: An overview of total alerts and protected capital (Saved Capital: 54.63K€).

    Profit Optimization: A dynamic tool to find the point where Net Profit is maximized, allowing managers to adjust strategy based on the cost per manual inspection.
