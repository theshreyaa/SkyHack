# 📞 Call Center Data Analysis & IVR Optimization Project

### 🚀 Project Overview
This project focuses on optimizing the call center operations for **United Airlines** by analyzing key call metrics, such as **Average Handle Time (AHT)** and **Average Speed to Answer (AST)**, and automating self-solvable call issues using an **Interactive Voice Response (IVR)** system. The goal is to enhance **operational efficiency**, reduce **agent workload**, and improve **customer satisfaction** through targeted recommendations for automation.

### 🔍 Problem Statement
The call center experiences high traffic due to recurring, self-solvable customer queries (e.g., **seating, booking, upgrades**), which escalate to agents, increasing their workload. This project aims to:
- Analyze **call reasons**, **AHT**, **AST**, and **sentiment** to uncover patterns.
- Propose **IVR system enhancements** that automate common call reasons and reduce agent intervention.
- Quantify the potential **efficiency gains** by implementing these improvements.

### 🎯 Key Objectives
1. **Reduce Average Handle Time (AHT)** through call automation.
2. **Enhance customer experience** by offering self-service options in the IVR.
3. **Improve operational efficiency** by analyzing the most frequent call reasons and optimizing agent workflows.

---

## 📊 Data Sources
The analysis relies on multiple datasets containing key information:
- **calls.csv**: Contains details on call start/end times, transcripts, and agent interactions.
- **reason.csv**: Provides the primary reason for each call.
- **sentiment_statistics.csv**: Includes customer/agent sentiment, average sentiment score, and silence percentages.
- **customers.csv**: Contains customer information including loyalty status and unique identifiers.

### Example Columns:
- `call_id`, `customer_id`, `agent_id`, `primary_call_reason`
- `average_sentiment`, `silence_percent_average`, `call_start_datetime`

---

## 🛠️ Approach & Methodology

### 1. **Data Preprocessing**
   - **Merge** relevant datasets using `call_id` as the key.
   - **Clean** the data by handling missing values, removing duplicates, and standardizing formats.
   
### 2. **Exploratory Data Analysis (EDA)**
   - **Frequency Analysis**: Identifying the most and least frequent call reasons.
   - **Time Analysis**: Analyzing **AHT** and **AST** for each call reason.
   - **Sentiment Analysis**: Understanding customer-agent interaction patterns using sentiment scores and silence percentages.

### 3. **IVR System Automation Impact**
   - Quantified the reduction in **handle time** by automating self-solvable calls (17.82% of the total call volume).
   - Analyzed **call distribution** before and after automation to estimate operational gains.

### 4. **Visualization**
   - Bar charts, heatmaps, and scatter plots are used to visualize call frequency, AHT, AST, sentiment distribution, and potential efficiency improvements through automation.

### 5. **Clustering for Customer Insights**
   - **K-means clustering** based on call sentiment and silence percentage to identify patterns in customer behavior and tailor automation strategies accordingly.

---

## 📈 Key Visualizations
- **Frequency of Primary Call Reasons**: Bar chart displaying the most common reasons customers contact the call center.
- **Average Handle Time (AHT) & Average Speed to Answer (AST)**: Visualizing these metrics by call reason to identify areas for improvement.
- **Call Sentiment Clustering**: Cluster analysis based on sentiment scores and silence percentages, highlighting different customer interaction groups.

---

## 🔧 Tools & Libraries Used

- **Python**: For data processing and analysis.
- **Pandas**: For data manipulation and merging multiple datasets.
- **Matplotlib & Seaborn**: For visualizing trends and patterns in the data.
- **Scikit-learn**: For clustering algorithms (K-means).
- **Numpy**: For numerical computations.
- **Jupyter Notebook**: To structure and run the analysis interactively.

---

## 🌟 Key Findings & Recommendations

- **Automating 17.82% of calls** that are related to self-solvable issues (such as seating, booking, upgrades) will reduce the workload on call center agents and improve customer satisfaction.
- The **Average Handle Time (AHT)** for common call reasons like **IRROPS** (Irregular Operations) is significantly higher compared to other categories.
- **Sentiment analysis** shows that the tone of conversations affects both the AHT and the AST, indicating the importance of agent training to handle frustrated customers more efficiently.
- Recommended **IVR enhancements** to allow customers to directly resolve common queries without agent intervention, drastically reducing the need for escalations.

---

## 🚀 Next Steps

- **Implement the IVR improvements** targeting self-solvable issues.
- **Monitor the financial and operational impact** post-implementation to quantify savings in AHT and AST.
- **Extend sentiment analysis** to refine agent training programs for improving customer satisfaction.
- **Scale the solution** across different customer service touchpoints, including web and mobile platforms, for a seamless customer experience.

---

## 👩‍💻 How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/theshreyaa/SkyHack.git
    ```
2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the analysis:
    - Open the Jupyter Notebook `call_center_analysis.ipynb`.
    - Execute the cells step by step to view the data cleaning process, analysis, and visualizations.

---

## 🤝 Contributions
Feel free to contribute by:
- Reporting issues
- Suggesting new features or improvements
- Submitting pull requests

---

## 📝 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 📧 Contact
If you have any questions or feedback, feel free to reach out at [shreyaa3183@gmail.com](mailto:shreyaa3183@gmail.com).

---

