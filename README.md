  # 🏦 Home Credit Default Risk Project
  
  ## 🔎 Business Problem & Objective
  Home Credit Group seeks to expand financial inclusion by offering loans to individuals who lack traditional credit histories. The challenge is that many applicants present **high uncertainty and financial risk**.  
  **Our Objective as Data Scientists:** Build a predictive model that estimates the probability of default, enabling smarter loan approvals while reducing losses.
  
  ## 💡 Group’s Solution
  Our team designed a machine learning pipeline that:
  
  - **Engineered features** from multiple relational tables (credit bureau, previous applications, demographics).  
  - Tested several models, including **logistic regression (baseline and regularized), random forests, and neural networks**.  
  - Conducted experiments using both **R and Python packages** to validate results across different environments and packages.  
  - Selected **Random Forests** as the best-performing model, balancing accuracy (AUC ≈ 0.734) and interpretability.  
  - Incorporated **external credit scores (EXT_SOURCE variables)** and employment/credit features as key drivers of default.  
  - Proposed a **cutoff threshold (0.49)** to reject the riskiest 5% of applicants, reducing default rates from 8% to ~6.9% and avoiding ~$16M in annual losses per 100k loans.
  
  ## 👤 My Contribution
  I contributed to the project by:
  - Implementing and tuning **Random Forests**, which became our strongest model.  
  - Experimenting with **neural networks** to capture nonlinear relationships.  
  - Building and refining **logistic regression baselines** for benchmarking and interpretability.  
  - Documenting model comparisons and ensuring reproducibility in notebooks.  
  - Explaining trade-offs between accuracy, interpretability, and operational use.
  
  ## 📈 Business Value
  - **Risk reduction:** Identified high-risk applicants before approval, lowering default rates.  
  - **Financial impact:** ~$16M in avoided losses per 100k loans.  
  - **Operational clarity:** Provided manager-friendly outputs and personas (e.g., “John vs. Jane” case study) to illustrate model decisions.  
  - **Inclusion:** Enabled safer lending to underserved populations.

    ![Improve Your Credit Score](https://assets.site-static.com/userFiles/1544/image/credit-score-to-buy-a-house.jpg)
  
  ## ⚠️ Difficulties Encountered
  - Managing **imbalanced data** and ensuring fair performance across demographics.  
  - Handling **missing values** in external credit scores.  
  - Balancing **model complexity vs interpretability** for business stakeholders.  
  - Debugging schema collisions and ensuring consistent feature definitions.  
  - Integrating workflows across **R and Python** introduced challenges.
  
  ## 🎓 Key Learnings
  - The importance of **feature engineering** and external credit proxies in financial risk modeling.  
  - How **ensemble methods** like Random Forests outperform baselines while remaining interpretable.  
  - The value of **clear documentation and semantic clarity** for collaboration.  
  - Practical experience in **translating technical outputs into actionable business rules** for decision-makers.
  
  ---
  
  ## 📂 Repository Structure
  [Fall Capstone project](https://github.com/sebastianperezparra/msba/tree/main/Fall%20Capstone)
