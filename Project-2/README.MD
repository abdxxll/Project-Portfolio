# 🛒 NÜDGE CRM – Customer Segmentation Project

## 🚀 Overview
This project explored how a hypothetical lifestyle-commerce brand (“NÜDGE”) could leverage **customer segmentation and behavioral nudging** to improve retention, personalization, and revenue. Using synthetic user data (age, income, spending score, loyalty score), we applied multiple clustering algorithms to identify actionable personas and design a CRM playbook tailored to shopper behaviors.

👉 [View the Full Presentation (PDF)](CRM%20Project.pdf)

---

## 🛠 Business Challenge
The brand asked:
- **Who are our customers, really?**  
- **What nudges work for different types of buyers?**  
- **How can segmentation improve conversion, loyalty, and lifetime value?**  

---

## 📈 Methodology
We tested **nine clustering models** to uncover meaningful customer segments:
- K-Means  
- HDBSCAN  
- DBSCAN  
- Agglomerative Hierarchical Clustering  
- Gaussian Mixture Models (GMM)  
- Spectral Clustering  
- BIRCH  
- Mean Shift  
- Affinity Propagation  

**Evaluation metrics:** Silhouette Score, Calinski-Harabasz Index, Davies-Bouldin Index.  

**Chosen Models:**  
- **K-Means** – Simple, interpretable, highest Silhouette & Calinski-Harabasz scores.  
- **HDBSCAN** – Detected outliers, handled complex cluster shapes, provided noise labeling.  

---

## 💡 Key Insights
- Segmentation based on **behavioral data** (spending, loyalty, engagement) outperforms demographic-only clustering.  
- Personas revealed actionable traits: cautious earners, rising stars, wallflowers, FOMO fanatics, advocates, etc.  
- Different personas require different nudges:  
  - **Cautious Earner:** trust-building, reward-focused.  
  - **Rising Star:** brand-building nudges, loyalty reinforcement.  
  - **FOMO Fanatic:** urgency and time-sensitive offers.  
  - **Advocate:** community, referrals, and rewards.  

---

## 🎯 Business Impact
- **For the Brand:** Personalized campaigns driving loyalty, higher AOV, and lower churn.  
- **For Customers:** Shopping experiences that feel tailored, not marketed at.  
- **For CRM Systems:** Segmentation as the backbone of customer lifecycle management and campaign optimization.  

---

## 👤 My Role & Contributions
- Built and evaluated clustering models (K-Means, HDBSCAN, others).  
- Designed **persona profiles** and aligned them to CRM product strategies (NÜDGE Picks, Rewards, Circles, Pulse).  
- Contributed to presentation design and stakeholder storytelling.  

---

## 📂 Deliverables
- [📑 CRM Project Presentation (PDF)](CRM%20Project.pdf)

---

## 🛠 Skills & Tools Used
- **Machine Learning:** K-Means, HDBSCAN, DBSCAN, clustering evaluation  
- **Data Analysis:** Python (pandas, scikit-learn, matplotlib)  
- **Business Strategy:** Persona development, CRM integration, behavioral economics  
- **Visualization & Communication:** Canva, stakeholder engagement, data storytelling  

---

## 📌 Notes
This repository hosts the project presentation for portfolio purposes. Source code is not included, as the primary deliverable was an analysis and stakeholder-facing presentation.
