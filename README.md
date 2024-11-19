# Social Buzz Content Categories Analysis

## Project Overview  
This project is part of a simulated data analytics exercise for Social Buzz, a rapidly growing social media platform preparing for an Initial Public Offering (IPO). The objective of the project is to leverage Social Buzz's vast user data to analyze content categories, identify key insights, and create a visually engaging Power BI dashboard.  

The analysis aims to assist Social Buzz in understanding user engagement trends, optimizing content strategies, and developing targeted marketing efforts to ensure IPO success.  

---

## Objectives  
1. **Data Cleaning**: Preprocess raw data to remove inconsistencies, handle missing values, and ensure usability for analysis.  
2. **Data Extraction**: Efficiently retrieve relevant data from Excel files to support content category analysis.  
3. **Dashboard Creation**: Design an interactive Power BI dashboard to visualize insights and provide actionable recommendations.  

---

## Features  
- **Data Cleaning**: Python script to preprocess raw Excel datasets, ensuring consistency and accuracy for analysis.  
- **Data Extraction**: Python script to extract key data points from Excel files for focused analysis.  
- **Power BI Dashboard**: An interactive dashboard showcasing:
  - Top-performing content categories.  
  - Engagement metrics by content type.  
  - User reaction trends and audience segmentation insights.  

---

## Project Files  
### 1. Python Scripts  
- **`Data Cleaning and Modelling.ipynb`**:  
   - Cleans the raw dataset by handling missing values, removing duplicates, and standardizing formats.
   - Outputs a cleaned dataset ready for analysis.

- **`data_extraction.py`**:  
   - Extracts specific columns and rows from the dataset based on predefined criteria.  
   - Ensures only relevant data is passed for further analysis.

### 2. Power BI Dashboard  
- **`SocialBuzz_Dashboard.pbix`**:  
   - A Power BI file visualizing cleaned data to provide actionable insights.  
   - Key features include:
     - Most popular content categories.
     - Engagement trends by content type.
     - Seasonal engagement patterns and user reactions.

### 3. Sample Dataset  
- **`sample_data.xlsx`**:  
   - A sample dataset mimicking the structure and content of Social Buzz’s data for demonstration purposes.
     
## Installation and Usage  
### Prerequisites  
- Python 3.x  
- Power BI Desktop  
- Libraries: Install required libraries using `pip install -r requirements.txt`.

### Steps to Run the Project  
1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/your-username/SocialBuzz-Analysis.git
   cd SocialBuzz-Analysis
   ```

2. **Run the Python Scripts**:  
   - For data cleaning:
     ```bash
     python scripts/data_cleaning.py
     ```
   - For data extraction:
     ```bash
     python scripts/data_extraction.py
     ```

3. **Open the Power BI Dashboard**:  
   - Launch Power BI Desktop and open the `SocialBuzz_Dashboard.pbix` file.  

4. **Visualize Insights**:  
   - Use the dashboard to explore content categories and user engagement metrics.

---

## Insights and Recommendations  
1. **Key Insights**:  
   - Animals and Science are the most popular content categories.  
   - Healthy Eating outperforms Food content by 0.76%, indicating user interest in lifestyle topics.  

2. **Recommendations**:  
   - Partner with influencers in Healthy Eating and Food for campaigns.  
   - Leverage seasonal strategies to enhance engagement in the Food category.  
   - Develop interactive content (quizzes, live sessions) for Animals and Science to boost engagement.  
   - Target IPO-related marketing to users interested in finance-related content.  

---

## License  
This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments  
- This project was completed as part of a Forage job simulation for Accenture’s Data Analytics and Visualization program.  
- Special thanks to Social Buzz for providing a challenging and engaging business problem for analysis.
