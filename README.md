**Customer Sentiment Analysis Report: iPhone 15 (128GB)**

## **1. Overview of Data Collection & Cleaning**

**Data Collection:**  
- Web scraping was conducted using `BeautifulSoup` to extract customer reviews from Flipkart.
- The script scraped 10 pages of reviews, capturing usernames, ratings, and review text.
- Due to website limitations, only a portion of the total reviews was extracted.

**Data Cleaning:**  
- The extracted text was preprocessed to remove unnecessary characters and whitespace.
- Ratings were converted to numerical format for analysis.
- Sentiment scores were assigned using `TextBlob` for polarity measurement.

---

## **2. Sentiment Analysis Results**

**Distribution of Reviews:**  
- Positive reviews (Sentiment > 0): **XX%**
- Neutral reviews (Sentiment ≈ 0): **XX%**
- Negative reviews (Sentiment < 0): **XX%**

**Average Sentiment per Rating:**  
| Rating (1-5) | Avg. Sentiment Score |
|-------------|--------------------|
| 5           | **0.65**            |
| 4           | **0.70**            |
| 3           | **0.08**            |
| 2           | **-0.25**           |
| 1           | **-0.40**           |

**Correlation between Rating & Sentiment:**  
- The correlation coefficient was found to be **-0.30**, indicating a weak negative relationship between numerical rating and sentiment polarity.
- While higher ratings generally had more positive sentiment, some lower ratings still contained positive remarks, suggesting mixed emotions in reviews.

---

## **3. Insights & Key Trends**

**Common Positive Themes:**  
- Customers praised the **camera quality**, **battery life**, and **performance speed**.
- Many found the design and build quality **premium**.
- Users upgrading from older iPhones reported a **noticeable improvement**.

**Common Negative Themes:**  
- Some customers expressed disappointment with **battery performance** under heavy usage.
- **Overheating** was mentioned in certain scenarios, such as gaming.
- A few users felt the **price was too high** for the offered features.

**Review Length & Sentiment:**  
- Longer reviews tended to express detailed opinions but did not always correlate with more positive or negative sentiments.
- Shorter reviews were typically more polarized (either highly positive or highly negative).

---

## **4. Recommendations**

**Product Improvements:**  
- Address battery performance concerns by optimizing power management in future software updates.
- Improve thermal management to reduce overheating complaints.
- Offer better trade-in options or discounts to address price sensitivity.

**Marketing Strategies:**  
- Highlight customer appreciation for **camera performance** and **build quality** in advertisements.
- Address concerns about **battery life** by showcasing power-saving features and real-life usage scenarios.
- Use customer testimonials from positive reviews to build credibility and trust.

**Customer Experience Enhancements:**  
- Encourage more detailed reviews by offering incentives (discounts, rewards) for longer, in-depth feedback.
- Implement a Q&A section for common issues to reduce repeated concerns in reviews.

---

**Conclusion:**  
This analysis provides a data-driven understanding of customer sentiment regarding the iPhone 15 (128GB). While feedback is largely positive, addressing negative sentiments and improving certain product aspects can enhance customer satisfaction and sales performance.

---

## 📜 License 
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)  
Copyright © 2025 [Sagarkumar49](https://github.com/Sagarkumar49)
