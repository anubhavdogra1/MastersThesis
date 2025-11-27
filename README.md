## Project - The Impact of External Interventions on Governance Outcomes in Fragile and Non-Fragile States

- Extracted and cleaned a **7.5 GB** raw dataset, integrating Fragile States Index and World Bank data to create a final dataset of **30 countries** (15 fragile, 15 non-fragile) from 2006-2022 (**pandas**).

- Developed three alternative hypotheses suggesting that “External Intervention” has negative relationships with:

  - **H1** - “State Legitimacy”, **H2** - “Political Stability & Absence of Violence”, **H3** - “Rule of Law”.

- Produced a **summary statistics** table, highlighting significant variability in governance and intervention levels (e.g., “External Intervention” exhibited a wide range, from a min. value **0.3** to a max. value **10**, with a median of **5.7** and a standard deviation of **3.66**).

- Generated a **correlation matrix heatmap**, displaying correlations between “External Intervention” and Governance variables.

- Designed **scatter plots** showing general trends, such as fragile states with high levels of “External Intervention” often struggle with weak “Rule of Law”, while non-fragile states with limited external involvement show strong legal frameworks (**seaborn**, **Matplotlib**).

- Executed **Fixed-effects regression (PanelOLS)** , which isolates the country-specific factors (such as culture, historical influences) and reflects the true effects of foreign involvement on the governance structures of these nations (**statsmodels**).

  - The coefficient β is **0.0720**, and p-value is **0.0000** in H1, indicating that when “External Intervention” **increases**, then the “State Legitimacy” **increases**.

  - The coefficient β is **-0.0307**, and the p-value is **0.0000** in H2, indicating that when “External Intervention” **increases**, then the “Political Stability & Absence of Violence” **decreases**.

  - The coefficient β is **0.0079**, and the p-value is **0.0306** in H3, indicating that when “External Intervention” **increases**, the “Rule of Law” **increases**.

- Concluded that external intervention can improve state legitimacy and the rule of law but may undermine political stability and weaken governance effectiveness when domestic authorities are already strong.

