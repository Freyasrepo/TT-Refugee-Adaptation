# **TikTok Refugee Migration and Adaptation Analysis on Xiaohongshu**

## **Project Overview**
This project investigates the **migration behavior of TikTok users to Xiaohongshu** (also known as "RedBook") and analyzes their **content adaptation strategies and engagement patterns**. Using **unsupervised machine learning techniques**, we classify user adaptation strategies, identify key behavioral trends, and detect anomalies in engagement.

## **Research Objectives**
- **Understand TikTok users’ adaptation strategies** after migrating to Xiaohongshu.
- **Classify user engagement and identity reconstruction** using **K-Means clustering** and **NMF topic modeling**.
- **Analyze interaction behaviors** and identify key factors influencing retention.
- **Detect anomalous users (e.g., influencers, bots, silent users)** using **DBSCAN and graph-based methods**.
- **Provide business insights** to optimize Xiaohongshu’s content recommendation system.

## **Dataset**
- **Source**: Crawled posts from Xiaohongshu (Jan 1, 2025 – Feb 28, 2025).
- **Size**: **3,000 user posts**, including text content, engagement metrics, and timestamps.
- **Features**:
  - **Behavioral Features**: `collect_count`, `comment_count`, `share_count`, `like_count`
  - **Text Features**: `title`, `content`
  - **Time Features**: `create_time`, `post_hour`
  - **Categorical Features**: `post_type`

## **Project Structure**

## **Methodology**
1. **Data Cleaning & Preprocessing**  
   - Handled missing values, standardized numeric fields, and cleaned text data.
   - Extracted **TF-IDF features** and **time-based engagement metrics**.

2. **Exploratory Data Analysis (EDA)**
   - **Statistical analysis** of user engagement.
   - **Keyword extraction** to identify frequent discussion topics.

3. **Unsupervised Learning Models**
   - **K-Means Clustering**:
     - Grouped users based on behavioral engagement metrics.
     - Identified **three primary adaptation groups**: imitators, social explorers, and cultural adapters.
   - **NMF Topic Modeling**:
     - Extracted latent **text topics** to classify user discussions.
   - **DBSCAN Anomaly Detection**:
     - Identified **potential bots, influencers, and silent users**.
   - **Graph-Based Community Analysis**:
     - Used **Louvain algorithm** to detect **sub-communities**.
     - Built **network visualizations** to highlight key influencers.

4. **Results & Key Insights**
   - **Most TikTok users gradually adapted**, but retention rates varied by group.
   - **Cultural adapters** engaged more deeply, while **social explorers struggled to integrate**.
   - **Anomalous users included both hyper-engaged influencers and silent users**.
   - **Recommendations** were made to improve user retention and engagement strategies.

## **Key Findings & Business Implications**
✅ **Enhance Personalization**: Adjust content recommendations based on user adaptation strategies.  
✅ **Encourage Interaction**: Increase incentives for social explorers to participate in Xiaohongshu’s ecosystem.  
✅ **Support Influencers**: Identify and amplify the reach of cultural adapters.  
✅ **Monitor Anomalies**: Improve bot detection mechanisms to reduce artificial engagement.  

## **Next Steps**
🔹 **Expand dataset**: Incorporate additional months of data for trend analysis.  
🔹 **Predictive modeling**: Develop supervised models to predict user retention likelihood.  
🔹 **Enhance network analysis**: Identify **influencer-driven engagement cascades** in Xiaohongshu’s ecosystem.  
🔹 **Improve recommendation algorithms**: Design adaptive strategies to personalize user experiences based on adaptation groups.  

---

## **How to Run the Project**
### **Setup**

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tiktok-refugee-adaptation.git
   cd tiktok-refugee-adaptation

