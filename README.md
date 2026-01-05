### **Executive Summary: Olist Customer Loyalty Prediction**

**The Challenge:** E-commerce platforms face severe attrition; for Olist, **98.8% of customers are one-time buyers**. This project builds a scalable Big Data solution to identify the rare 1.2% of potential loyalists within this high-churn environment.

**The Solution:** Using **PySpark’s distributed framework**, we integrated five transactional datasets to engineer behavioral **RFM (Recency, Frequency, Monetary)** and logistics features. To overcome the extreme class imbalance, the pipeline implemented **manual class weighting** and iterative **feature selection**.

**The Implementation:** We executed a three-stage experimental loop (Baseline → Top-K Selection → Hyperparameter Tuning) across six algorithms. The **Tuned Logistic Regression** model, utilizing just the **top four features**, emerged as the most efficient solution.

**The Result:** Achieving a **PR AUC of 0.9926** and catching **~49% of loyalists**, this framework provides a **40x improvement** in targeting precision. It allows Olist to move from broad-spectrum guesswork to mathematically precise, high-ROI retention marketing.
