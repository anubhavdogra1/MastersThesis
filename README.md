# The Impact of External Interventions on Governance Outcomes

- Cleaned and extracted a large dataset of 7.5 GB using the pandas library, integrating datasets from Fragile States Index (FSI) and World Bank Group organisations. Lastly, the selected dataset includes 30 countries (15 fragile and 15 non-fragile) from 2006 to 2022.

- Developed three Hypotheses suggesting that “External Intervention” has negative relationships with H1 - “State Legitimacy”, H2 - “Political Stability & Absence of Violence”, H3 - “Rule of Law”.

- Created a summary statistics table, highlighting significant variability in governance and intervention levels (e.g., “External Intervention” exhibited a wide range, from a min. value 0.3 to a max. value 10, with a median of 5.7 and a standard deviation of 3.66).

- Developed a correlation matrix heatmap (seaborn, Matplotlib), displaying correlations between “External Intervention” and Governance variables.

- Created scatter plots (Matplotlib) showing general trends, such as in fragile states with high levels of “External Intervention” often struggle with weak “Rule of Law”, while non-fragile states with limited external involvement show strong legal frameworks.

- Executed Fixed-effects regression (PanelOLS), which isolates the country-specific factors (such as culture, historical influences) and reflects the true effects of foreign involvement on the governance structures of these nations.

- The coefficient β is 0.0720, and 0.01 < p-value < 0.05 in H1, indicating that when “External Intervention” increases, then the “State Legitimacy” increases.

- The coefficient β is -0.0307, and the p-value is 0.0000 in H2, indicating that when “External Intervention” increases, then the “Political Stability & Absence of Violence” decreases.

- The coefficient β is 0.0079, and the p-value is 0.0306 in H3, indicating that when “External Intervention” increases, the “Rule of Law” increases.

- External intervention can improve state legitimacy and the rule of law, but may undermine political stability and weaken governance effectiveness when domestic authorities are already strong.

---
