# Jamboree Education - Business Case Analysis

## 📚 Overview

This project analyzes the educational technology company Jamboree, examining their customer retention patterns and identifying strategies to reduce attrition rates. The analysis focuses on demographic segmentation and behavioral modeling using logistic regression techniques.

---

### **Business Problem**

- Understand factors driving student attrition
- Predict which students are likely to drop out
- Develop targeted retention strategies for high-risk segments

---

### **Analysis Approach**

**Key Insights:**
- 📊 **Target**: 31% of Jamboree customers experience churn
- 🔍 **Feature Engineering**: Enrollment duration, payment history, engagement metrics
- 🎯 **Segmentation**: Multi-class logistic regression approach to identify at-risk groups

---

### **Methodology Highlights**

| Aspect | Analysis | Result |
|--------|----------|--------|
| Sample Size | 3016 customers | Multi-class prediction |
| Classes | High-Low-Medium-Athlete | 4 categories |
| Approach | Probabilistic + thresholding | Strategic segmentation |

---

### **Strategic Recommendations**

✅ **Multi-Class Prediction**: Segment students into retention risk tiers
✅ **Targeted Interventions**: Different strategies for each segment
✅ **Predictive Analytics**: Implement automated churn prediction system

---

### **Technical Implementation**

```python
# Logistic regression with stratified cross-validation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression

def predict_churn(df):
    X = df.drop(columns=['class'])
    y = df['class']
    # Apply probability thresholds based on segment risk
```

---

### **Business Impact**

Reducing attrition through data-driven insights will improve customer retention and reduce acquisition costs. The multi-class approach enables personalized engagement strategies for different customer segments.

---

*By Rahul Sharma | Senior Business Analyst transitioning to AI/DS roles*
