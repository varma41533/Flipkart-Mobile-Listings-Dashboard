# **Flipkart Mobile Listings Dashboard**

## **1. Introduction**  
This project focuses on creating an interactive dashboard using data collected by web scraping mobile phone listings from the Flipkart website. The primary objective is to analyze key trends in the mobile phone market, such as price distribution, brand performance, feature combinations, and customer engagement through ratings and reviews. This dashboard aims to help users and businesses make data-driven decisions regarding mobile phone purchases and marketing strategies.

---

## **2. Objective**  
The key objectives of this project are:  
- To extract data from Flipkart using web scraping techniques.  
- To analyze brand-wise market trends and price distribution.  
- To visualize the relationship between product specifications (RAM, ROM, Camera) and prices.  
- To evaluate customer engagement through ratings and reviews.  
- To create an interactive dashboard for easy exploration of data insights.  

---

## **3. Data Collection**  
### **Data Source**  
The dataset was collected by **web scraping Flipkart’s mobile phone listings** using Python libraries such as **BeautifulSoup**.  

### **Data Fields Collected:**  
- **Brand**: The manufacturer of the mobile phone.  
- **Model**: The specific model name/number of the phone.  
- **Price**: The listed price of the phone on Flipkart.  
- **RAM and ROM**: The RAM and internal storage specifications.  
- **Camera**: Primary and secondary camera specifications (MP).  
- **Number of Ratings**: Total user ratings for the mobile.  
- **Number of Reviews**: Total number of user feedback and comments.  

---

## **4. Tools and Technologies Used**  
- **Web Scraping:** Python (BeautifulSoup)  
- **Data Cleaning & Manipulation:** Pandas, Power BI
- **Visualization:** Power BI 
- **Dashboard Creation:** Power BI 

---

## **5. Data Analysis and Visualizations**  
### **Key Visualizations Used:**  
1. **Stacked Column Chart:** Top brands by the number of Models and price Segement.  
2. **Line and Stacked Column Chart :** Brand and Customer Engagement.
3. **WordMap:** Brand with highest number of models.  
4. **Treemap:** Popular RAM Specifications.  
5. **Guage:** Minimum,Maximum,Average price of mobiles.
6. **Cards:** Number of Brands, Models listed on Website

---

## **6. Key Performance Indicators (KPIs)**  
- **Average Mobile Price**: ₹22,000.  
- **Top 3 Brands by Model Count**: realme, vivo, SAMSUNG.  
- **Most Popular RAM**: 8GB.  
- **Top Price Segemnt by number of models**:₹10,000-₹15,000.
- **Highest Brand by average price of mobiles**: Apple.
 

---

## **7. Insights and Findings**  
- **Price Distribution:** Most mobiles are concentrated in the ₹10,000–₹25,000 range, indicating high demand for budget-friendly smartphones.  
- **Brand Performance:** Brands like realme and vivo dominate in terms of model count, especially in the mid-range segment.  
- **Customer Engagement:** Higher-rated mobiles tend to have more reviews, showing that quality influences user feedback.  
- **Feature Preferences:** 8GB configurations are popular in mid and premium range phones.  


---

## **8. Challenges Faced**  
- **Dynamic Website Structure:** Flipkart’s website uses JavaScript to load content, requiring the use of for loop to handle dynamic pages.  
- **Handling Inconsistent Data:** Some listings had missing or inconsistent information (e.g., no reviews or unclear specifications), which required additional data cleaning.  
- **Captcha & Rate Limits:** Encountered challenges with rate limits while scraping, which was managed by using for loops in requests.  

---

## **9. Conclusion**  
The Flipkart Mobile Listings Dashboard provides valuable insights into the smartphone market, including pricing patterns, feature preferences, and customer engagement trends. This project demonstrates proficiency in web scraping, data cleaning, visualization, and dashboard creation, making it a strong portfolio piece. The insights can be used by customers to make informed purchasing decisions and by businesses to develop targeted marketing strategies.  

---

## **10. Future Scope**  
- **Automation:** Schedule automated scraping to keep the data updated regularly.  
- **Sentiment Analysis:** Analyze customer reviews to understand user sentiments.  
- **Competitor Analysis:** Expand the project by scraping other e-commerce platforms for comparison.  
- **Recommendation Engine:** Build a recommendation engine to suggest phones based on user preferences and reviews.  

---

## **11. Project Deliverables**  
- **Python Code** for web scraping and data cleaning.  
- **Dashboard File** (Power BI / Tableau) showcasing the visualizations.  
- **Documentation** of the entire process.  

---

## **12. References**  
- **Flipkart Website:** [https://www.flipkart.com](https://www.flipkart.com)  
- **Python Libraries Used:** BeautifulSoup,Pandas,NumPy 
