# **TikTok Refugee Migration and Adaptation on Xiaohongshu**

## **Project Overview**

This project investigates how **TikTok users migrate to Xiaohongshu** and adapt to the new platform. The study focuses on **identity reconstruction and content adaptation strategies** using **unsupervised learning techniques**. By analyzing user behavior, text content, and engagement patterns, we explore whether these users retain their **TikTok-style content strategies** or transition towards **Xiaohongshu’s native engagement model**.

## **Key Research Questions**

- How do TikTok refugees’ behavioral patterns change after migration?
- Do they maintain their **TikTok-oriented content style**, or do they gradually adapt to Xiaohongshu?
- What factors influence whether a user becomes **an active participant** in Xiaohongshu’s community?
- What **themes dominate user discussions**, and how do they correlate with retention?
- Are there **anomalies** such as **bot activity** or **hyper-engaged influencers**?

## **Methodology**

We apply **unsupervised learning models** to analyze user migration and adaptation strategies:

### **1. Exploratory Data Analysis (EDA)**

- Dataset: **3,000 user posts** collected from Xiaohongshu (Jan–Feb 2025)
- Feature extraction:
  - **Behavioral Features**: Collects, comments, shares, likes
  - **Temporal Features**: Posting time and frequency
  - **Text Features**: Keyword extraction via **TF-IDF**
- **Visualization techniques**: Distributions, keyword frequency, correlation heatmaps

### **2. Unsupervised Learning Models**

- **K-Means + NMF Topic Modeling**
  - User segmentation into **different adaptation strategies**
  - Identification of **common content themes** among migrated users
- **Graph Neural Networks (GNN) + DBSCAN**
  - **Community detection** to identify tightly-knit engagement groups
  - **Anomaly detection** to detect bot-like behavior and outliers

### **3. Results & Business Implications**

- **User segmentation analysis**: Understanding different migration strategies
- **Network graph analysis**: Detecting core communities & peripheral users
- **Adaptation strategies**: Implications for Xiaohongshu’s **content recommendation system**
- **Identifying high-potential cross-platform creators** for targeted platform support

## **Repository Structure**

```
├── data/                      # Dataset (processed and raw data)
├── notebooks/                 # Jupyter Notebooks with EDA & modeling
├── src/                       # Python scripts for preprocessing & modeling
├── results/                   # Model outputs and analysis results
├── report/                    # Final PDF report
├── README.md                  # Project overview
├── requirements.txt           # Python dependencies
```

## **Installation & Usage**

To reproduce the results, clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/tiktok-refugee-analysis.git
cd tiktok-refugee-analysis
pip install -r requirements.txt
```

Run the Jupyter notebooks for **data processing, modeling, and visualization**:

```bash
jupyter notebook notebooks/
```

## **Key Findings**

- **Most TikTok refugees gradually adapt** to Xiaohongshu but retain **some TikTok-style behaviors**.
- **Community engagement is a strong predictor** of user retention.
- **Cultural adapters (cross-platform users)** exhibit the highest long-term engagement.
- **Graph-based anomaly detection** reveals possible **bot-like or fraudulent activity**.

## **Future Work**

- **Expand the study** to analyze **longer-term adaptation trends**.
- **Enhance graph-based community detection** to refine engagement patterns.
- **Develop predictive models** for user retention.

For any inquiries, please contact jiwu3340\@Colorado.edu.

## **License**

This project is licensed under the CC **BY-NC 4.0  License**.\


---

This README provides a **comprehensive overview** of your project, making it easy for others to **understand, install, and use** your code. Let me know if you need any modifications! 🚀

