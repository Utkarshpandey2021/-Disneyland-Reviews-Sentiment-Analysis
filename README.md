# -Disneyland-Reviews-Sentiment-Analysis
Understanding customer sentiment is crucial for enhancing theme park experiences. In this project, I analyzed Disneyland visitor reviews to extract insights on customer satisfaction, sentiment trends, and areas for improvement using Natural Language Processing (NLP) and Data Visualization.
**Disneyland Reviews Sentiment Analysis – Detailed Project Report**

---

## **1. Introduction**

### **1.1 Project Overview**
Customer feedback plays a crucial role in shaping the services and experiences of businesses. Disneyland, being one of the most popular theme parks globally, receives thousands of customer reviews that reflect visitors’ experiences. This project aims to analyze Disneyland reviews, extract insights from customer sentiment, identify common themes, and suggest improvements using **Natural Language Processing (NLP) and Data Visualization**.

### **1.2 Objectives**
The key objectives of this project are:
- To clean and preprocess Disneyland review data for analysis.
- To perform **Exploratory Data Analysis (EDA)** to identify trends.
- To apply **Sentiment Analysis** to categorize reviews into positive, negative, or neutral sentiments.
- To visualize the findings using **Matplotlib, Seaborn, and Plotly**.
- To provide data-driven recommendations for improving customer satisfaction.

### **1.3 Tools and Technologies Used**
- **Python**: Primary programming language.
- **Pandas, NumPy**: For data manipulation and preprocessing.
- **Matplotlib, Seaborn, Plotly**: For data visualization.
- **NLTK (Natural Language Toolkit), VADER Sentiment Analysis**: For sentiment classification.
- **Jupyter Notebook**: For interactive coding and analysis.

---

## **2. Data Collection and Preprocessing**

### **2.1 Dataset Description**
The dataset consists of customer reviews of Disneyland across different locations, including **Disneyland California, Disneyland Paris, and Disneyland Hong Kong**. The dataset includes the following columns:
- **Review ID**: Unique identifier for each review.
- **Reviewer Name**: Name of the person who left the review.
- **Review Text**: Actual review content.
- **Rating**: A numerical rating (usually from 1 to 5).
- **Date of Visit**: The date when the visitor experienced Disneyland.
- **Branch (Location)**: The Disneyland park the review corresponds to.

### **2.2 Data Cleaning and Preparation**
Before conducting any analysis, it’s essential to clean and prepare the data:
- **Handling Missing Values**: Any missing values in the dataset were either removed or imputed appropriately.
- **Removing Duplicates**: Duplicate reviews were identified and removed to prevent bias.
- **Text Preprocessing**:
  - Convert text to lowercase.
  - Remove special characters, punctuation, and stopwords.
  - Tokenization: Splitting text into individual words.
  - Lemmatization: Converting words to their root forms.

---

## **3. Exploratory Data Analysis (EDA)**

### **3.1 Understanding Review Distribution**
- Analyzed the distribution of reviews across different Disneyland locations.
- Examined the **average ratings** for each location.
- Identified the **most common words and themes** in reviews.

### **3.2 Visualization of Review Trends**
- **Bar charts** to show the count of positive, neutral, and negative reviews.
- **Pie charts** to visualize sentiment distribution.
- **Line plots** to analyze trends over time.
- **Word Clouds** to highlight frequently used words in reviews.

---

## **4. Sentiment Analysis**

### **4.1 Sentiment Classification Using VADER**
- Used **VADER (Valence Aware Dictionary and Sentiment Reasoner)** for sentiment analysis.
- Each review was classified into **Positive, Neutral, or Negative Sentiment** based on the compound sentiment score.

### **4.2 Analyzing Sentiment Across Locations**
- Compared the percentage of positive, neutral, and negative reviews for each Disneyland location.
- Identified locations with **higher negative sentiment** to determine potential issues.

### **4.3 Most Common Positive & Negative Phrases**
- Extracted **top positive words** (e.g., “amazing,” “magical,” “friendly staff”).
- Extracted **top negative words** (e.g., “long lines,” “expensive,” “bad service”).

---

## **5. Data Visualization & Insights**

### **5.1 Key Findings from Data Visualization**
- **Positive Reviews Dominated**: Majority of reviews were positive, indicating high customer satisfaction.
- **Long Wait Times and Pricing Were Major Concerns**: Many negative reviews mentioned **long queues and high ticket prices**.
- **Staff Friendliness and Park Experience Were Highly Praised**: Many customers appreciated the **Disneyland experience and customer service**.

### **5.2 Visualizations Used**
- **Sentiment Distribution Bar Chart**: Showed the percentage of positive, neutral, and negative reviews.
- **Word Clouds**: Displayed commonly used words in positive and negative reviews.
- **Time-Series Analysis**: Examined trends in sentiment scores over time.
- **Heatmaps**: Visualized correlations between review sentiment and rating scores.

---

## **6. Business Impact and Recommendations**

### **6.1 How This Analysis Benefits Disneyland**
- **Improved Customer Satisfaction**: Understanding visitor complaints helps address concerns effectively.
- **Enhanced Marketing Strategies**: Positive sentiment insights can be used for advertising and promotions.
- **Operational Improvements**: Long wait times and pricing issues can be addressed to enhance visitor experience.

### **6.2 Data-Driven Recommendations**
✅ **Reduce Wait Times**: Implement **fast-track passes, efficient crowd management strategies, and real-time queue monitoring**.
✅ **Optimize Pricing Strategies**: Introduce **discounted packages for families and off-peak pricing incentives**.
✅ **Enhance Customer Experience**: Train staff further to **handle visitor complaints and improve overall service**.
✅ **Monitor Real-Time Sentiment**: Implement **real-time feedback collection tools** to track visitor satisfaction.

---

## **7. Conclusion**
This project provided a comprehensive analysis of **Disneyland customer reviews** using **sentiment analysis and data visualization techniques**. By leveraging **Natural Language Processing (NLP)**, we successfully categorized reviews into positive, neutral, and negative sentiments, uncovering valuable insights into visitor experiences. The findings from this analysis can help Disneyland **enhance customer satisfaction, optimize pricing, and improve park operations**.

---

## **8. Future Scope**
For further enhancement of this project, we can:
- Implement **machine learning models** to predict review sentiment with greater accuracy.
- Perform **topic modeling** to categorize reviews into themes such as food, rides, and customer service.
- Integrate **real-time sentiment tracking** using web scraping and live review analysis.

---

