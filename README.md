# ✈️ Airline Passenger Satisfaction Analysis  

## 📌 Project Overview  
Understanding passenger satisfaction is crucial for **airlines** to enhance customer experience and operational efficiency. This project explores key factors influencing **passenger sentiment** using **Exploratory Data Analysis (EDA), statistical hypothesis testing, and A/B testing** to derive actionable business insights.  

## 📊 Data Overview  
The dataset consists of various attributes affecting airline passenger satisfaction, including:  
- **Inflight Service Ratings**  
- **Food & Drink Ratings**  
- **Seat Comfort Scores**  
- **Baggage Handling Feedback**  
- **Cleanliness Perceptions**  
- **Satisfaction Level** (Neutral/Dissatisfied or Satisfied)  

## 🔍 Key Insights  

### ✈️ **Inflight Service & Satisfaction**  
- Higher inflight service ratings strongly correlate with passenger satisfaction.  
- Some **satisfied passengers** still rated service lower, indicating other factors (e.g., seating, delays) impact overall experience.  

### 🍽️ **Food & Drink Ratings**  
- Higher food ratings generally contribute to satisfaction, but **some satisfied passengers still gave low food ratings**, suggesting **menu variety or dietary preferences** may play a role.  

### 💺 **Seat Comfort & Experience**  
- **Seat comfort ratings significantly impact satisfaction** but are not the sole driver of passenger sentiment.  
- Some **Economy Plus** passengers reported similar seat comfort levels to **Economy**, raising concerns about premium pricing justification.  

### 🎒 **Baggage Handling & Customer Perception**  
- While **most satisfied passengers** rated baggage handling well, **some dissatisfied passengers still gave high ratings**, implying it’s not a primary dissatisfaction driver.  

---

## 📊 **Hypothesis Testing & A/B Testing**  

To **validate key assumptions**, an **independent t-test** was performed comparing passenger satisfaction between **Economy and Economy Plus** classes.  

### ✅ **Results**  
**T-statistic:** -11.32  
**P-value:** 1.52e-29  

🚀 **Conclusion:** There is a **statistically significant difference in satisfaction levels** between Economy and Economy Plus, confirming the need for strategic service enhancements in premium economy offerings.  

---

## 💡 Business Impact & Strategic Recommendations  

📌 **Enhance Service Differentiation**  
- Improve the **value proposition of Economy Plus** through additional benefits (better seating, exclusive perks).  

📌 **Address Key Service Pain Points**  
- Improve **inflight service quality**, **cleanliness**, and **seat comfort consistency** based on low-rated touchpoints.  

📌 **Leverage Customer Segmentation**  
- Use **data-driven insights** to offer **personalized services and targeted marketing campaigns** to improve loyalty and retention.  

---

## 🛠️ **Tech Stack & Tools Used**  

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, SciPy)  
- **Statistical Testing** (t-test for hypothesis validation)  
- **Exploratory Data Analysis (EDA)**  
- **Data Visualization** (Boxplots, Histograms, Heatmaps)  
- **A/B Testing** for comparative analysis  

---

## 🚀 **Next Steps**  
- **Predictive Modeling:** Build an ML model to predict passenger satisfaction.  
- **Deep Dive into Pricing Strategies:** Evaluate **premium economy pricing vs. passenger sentiment**.  
- **Sentiment Analysis:** Use **NLP** to analyze **text-based passenger reviews** for deeper insights.  

