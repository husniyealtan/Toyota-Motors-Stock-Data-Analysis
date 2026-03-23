# Toyota-Motors-Stock-Data-Analysis
Financial data analysis and trend reporting for Toyota Motors Stock Dataset using Python.

📌 Project Description

This is a group project focused on analyzing Toyota's historical motors stock data to identify long-term trends and volatility.

👤 My Role & Technical Contributions:

As the Lead Analyst, I was responsible for project coordination, final control, and the core technical pipeline:

Data Preprocessing & Feature Engineering: Cleaned raw financial data and engineered new features to enhance model sensitivity.

Data Scaling & Time Series Splitting: Implemented robust scaling and ensured chronological integrity through proper time-series data partitioning.

Dimensionality Reduction (PCA & Kernel PCA): Applied PCA and Kernel PCA to identify principal components and handle non-linear relationships in stock fluctuations.

<img width="1790" height="490" alt="pca-kernelpca" src="https://github.com/user-attachments/assets/67fa0a1e-3d8d-4965-9028-541570a33351" />
🔍 Analytical Interpretation
As illustrated in the comparison, while Standard PCA shows a central density, the RBF Kernel reveals a circular manifold structure, and the Polynomial Kernel tends to compress data along a single axis.

Despite these geometric transformations, a clear decision boundary between "Decrease" (Blue) and "Increase" (Red) classes was not achieved, with significant class overlap remaining. This observation aligns with the discussions by Schölkopf et al. (1998) regarding the limitations of kernel methods in isolating high-noise, stochastic financial time series.

Conclusion: These findings demonstrate that geometric transformation alone is insufficient for this complex dataset, necessitating the use of Support Vector Machines (SVM) to optimize marginal decision boundaries for better classification.


Model Evaluation: Conducted rigorous evaluation of the PCA outputs to ensure the captured variance aligned with financial trends.

Project Management: Coordinated task distribution among team members and performed the final technical audit of the entire project.

🛠 Tech Stack

Language: Python (Pandas, NumPy, Scikit-learn).

Analysis Techniques: Dimensionality Reduction (PCA/KPCA), Time Series Analysis, Feature Engineering.

Visualization: Matplotlib, Seaborn.
