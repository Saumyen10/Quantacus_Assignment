𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞𝐬:

The goal of this project was to analyze and optimize an email marketing campaign for an e-commerce company. The key objectives were:
•	Analyze how users responded to a recent email campaign.
•	Build a machine learning model to predict user engagement (clicks).
•	Simulate improvements to click-through rate (CTR) using the model.
•	Explore performance across different user segments.


𝐂𝐚𝐦𝐩𝐚𝐢𝐠𝐧 𝐏𝐞𝐫𝐟𝐨𝐫𝐦𝐚𝐧𝐜𝐞 𝐌𝐞𝐭𝐫𝐢𝐜𝐬:

•	Open Rate: 10.35%
•	Click-Through Rate (CTR): 2.12%
•	Click-to-Open Rate: 20.48%


𝐏𝐫𝐞𝐝𝐢𝐜𝐭𝐢𝐯𝐞 𝐌𝐨𝐝𝐞𝐥𝐬:

Two models were trained to predict the likelihood of a user clicking on an email:

•	Random Forest
    ROC AUC Score: 𝟎.𝟓𝟖𝟗𝟐 (moderate performance)
•	XGBoost (Optimized)
    ROC AUC Score: 𝟎.𝟕𝟐𝟓𝟓 (strong performance)

𝐒𝐞𝐠𝐦𝐞𝐧𝐭 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬:

i) by emails:

•	Personalized emails boosts CTR.
•	Short emails outperforms long ones.
•	𝐒𝐡𝐨𝐫𝐭 + 𝐩𝐞𝐫𝐬𝐨𝐧𝐚𝐥𝐢𝐳𝐞𝐝 emails perform best.

ii) by hour:

•	𝐇𝐨𝐮𝐫 𝟐𝟑 (𝟏𝟏:𝟎𝟎 𝐏𝐌) is the best time to send emails to maximize user engagement.
•	Evening hours between 𝟖 𝐏𝐌 𝐚𝐧𝐝 𝟗 𝐏𝐌 show the lowest engagement, suggesting those times should be avoided for email campaigns.


𝐂𝐨𝐧𝐜𝐥𝐮𝐬𝐢𝐨𝐧:
 
The project demonstrated how machine learning can:
•	Enhance targeting in email campaigns.
•	Nearly triple the CTR through intelligent user selection.
•	Identify optimal email formats and timing strategies.
