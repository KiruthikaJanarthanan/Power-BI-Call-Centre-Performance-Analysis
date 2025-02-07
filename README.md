
# CALL CENTRE PERFORMANCE ANALYSIS REPORT

### **Overview of the Dashboard**

The Power BI dashboard provides a **360-degree view** of call center operations, focusing on key performance indicators (KPIs) such as **total calls, resolution rates, agent performance, customer satisfaction, and topic-wise analysis**. It helps in identifying areas of improvement and optimizing call center efficiency.

**Data Collection:**

As part of my virtual internship with PwC Switzerland, I was provided with a dataset to complete this project. The dataset consists of 10 columns and 5001 rows, including details such as Call ID, Agent, Date, Time, Topic, Answered (Y/N), Resolved, Speed of Answer, Average Talk Duration, and Satisfaction Rating.

**Data Cleaning & Preparation:**

Using Power BI, I carried out various data cleaning processes, such as:

- Replacing null values with 0 where appropriate.
- Standardizing response values in the Answered and Resolved columns.
- Adjusting the data format for Avg. Talk Duration and Time columns.

These steps ensured the dataset was refined and ready for analysis.

**KPIs & Measures Created:**

Several DAX measures were implemented to evaluate performance, including:

- **Calls with star ratings 4 and 5:**  Count of ratings between 4 and 5.
- **Total Calls Answered & Unanswered:** Aggregating call responses.
- **Overall Customer Satisfaction:** Derived using a percentage formula.
- **Weekday Segmentation:** Categorizing calls based on the day of the week.

**Key Insights from Each Page**

### **Page 1: Call Analysis**

- **Total Calls:** **5000** calls received.
- **Resolution Rate:** **3646 calls (about 89.94%)** were successfully resolved.
- **Call Rejection Rate:** **18.92% (946 calls rejected)**.
- **Average Answer Speed:** **67.5 seconds**.
- **Topic-Wise Performance:**
    - **Streaming** has the highest number of calls.
    - **Technical Support** has the highest number of unresolved calls.
    - **Contract-related issues** have the lowest resolution rate.
![CC PAGE1](https://github.com/user-attachments/assets/9a242b1a-e35a-47c6-931d-69005463a542)

 **Insights:** The technical support team may need additional resources or training to improve their resolution rate. The high rejection rate suggests that optimizing call handling processes could be beneficial.


### **Page 2: Agent Performance Analysis**

- **Top Performing Agent:** **Jim (Highest number of calls answered)**.
- **Highest Customer Satisfaction Rate:** **Dan**.
- **Lowest Performing Agent:** **Stewart (lowest call resolution rate)**.
- **Average Call Handling Time per Agent:**
    - **Fastest Answering Agent:** **Diane (52.4 seconds)**.
    - **Longest Call Duration:** **Dan (191.01 seconds)**.

**Insights:** Stewart may need coaching to improve performance, while Jim is handling the most workload. Monitoring call duration trends can help in balancing workload among agents.

![CC PAGE2](https://github.com/user-attachments/assets/3c5c9697-9404-4934-8214-65f690caaaa0)

### **Page 3: Customer Satisfaction Analysis**

- **Overall Satisfaction:** **40.46%** customers are satisfied.
- **Total Calls with 4 & 5 Star Ratings:** **2023**.
- **Agents with Highest Satisfaction:**
    - **Dan:** 2.85 rating.
    - **Becky & Jim:** 2.76 rating.
- **Topic-Wise Satisfaction:**
    - **Payment-Related Calls** have the highest satisfaction.
    - **Contract-Related Issues** have the lowest satisfaction.

 **Insights:** Improving contract-related service processes and training agents on handling contract-related queries better can improve overall satisfaction.

![CC PAGE3](https://github.com/user-attachments/assets/1900f323-6963-45d1-be3f-06960ab71373)

### **Recommendations**

 **Reduce Call Rejection Rate:** Investigate why **946 calls** were rejected and implement a strategy to minimize rejections. 

**Improve Technical Support Performance:** Additional training and resources may be needed to handle complex issues efficiently.

**Balance Workload Among Agents:** Distribute calls more evenly to avoid burnout and improve response times.

 **Enhance Customer Satisfaction for Contract-Related Issues:** Identify pain points in contract processes and streamline resolution strategies.

### **Conclusion**

The Power BI dashboard enables real-time monitoring of call center efficiency, helping managers make **data-driven decisions** to optimize agent performance, enhance customer satisfaction, and improve overall operations.
