# SENTIMENT_ANALYSIS_DS04  
### Analyzing Public Opinion on Social Media through Sentiment Analysis of Tweets  

## Table of Contents  
- [Description](#description)  
- [Overview](#overview)  
- [Data Source](#data-source)  
- [Installation](#installation)  
- [Usage](#usage)  
    - [Data Cleaning and Analysis](#data-cleaning-and-analysis)  
    - [Exploratory Data Analysis](#exploratory-data-analysis)  
- [Recommendations](#recommendations)  
- [Contributors](#contributors)  
- [Contributing](#contributing)  
- [License](#license)  

___  

## Description  
This project aims to analyze sentiment from tweets related to various topics or entities by using sentiment analysis techniques. By categorizing tweets into **Positive**, **Negative**, and **Neutral** sentiments, the project seeks to understand the public’s opinion on brands, products, and other significant entities. This analysis can offer valuable insights for businesses, governments, and organizations to gauge public perception and improve their reputation management strategies.  

___  

## Overview  
The project involves:  
1. Collecting and analyzing tweets related to various entities.  
2. Cleaning the dataset to ensure the quality of data for analysis.  
3. Performing **data cleaning** operations like removing duplicates and handling missing data.  
4. Conducting **Exploratory Data Analysis (EDA)** to uncover insights from tweet sentiments.  
5. Identifying trends in sentiment toward different entities/brands and exploring the relationship between sentiment and tweet content.  
6. Providing recommendations for businesses and brands based on sentiment analysis results.  

Key Python libraries used include `pandas`, `matplotlib`, `seaborn`, and `wordcloud` for data manipulation, visualization, and analysis.  

___  

## Data Source  
The dataset used in this project contains tweets from Twitter and is publicly available on Kaggle: [Sentiment Analysis on Twitter Dataset](https://www.kaggle.com/datasets)  

___  

## Installation  

To set up the project, follow these steps:  

1. Clone the repository to your local machine:  
    ```bash  
    git clone https://github.com/ibtj21/SENTIMENT_ANALYSIS_DS04.git  
    ```  

2. Navigate to the project directory:  
    ```bash  
    cd SENTIMENT_ANALYSIS_DS04  
    ```  

3. Install the required dependencies:  
    ```bash  
    pip install -r requirements.txt  
    ```  

Dependencies include:  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- wordcloud  

___  

## Usage  

### Data Cleaning and Analysis  
1. **Data Cleaning**:  
   - Remove any duplicate rows from the dataset.  
   - Handle missing values, especially in the 'Tweet Text' column.  
   - Convert sentiment labels into a categorical format (Positive, Negative, Neutral).  

2. **Exploratory Data Analysis (EDA)**:  
   - Analyze the distribution of sentiment categories.  
   - Generate visualizations such as bar charts, histograms, and word clouds for exploring sentiment distributions.  
   - Identify which entities/brands have the highest positive or negative sentiment.  
   - Analyze the relationship between sentiment and specific keywords or hashtags in tweets.  

Key findings include:  
- Certain brands, such as **Borderlands 3**, consistently show **positive sentiment** from users.  
- Brands like **FIFA** and **Madden NFL** tend to receive **negative sentiment** due to gameplay issues or dissatisfaction with updates.  

Find the complete implementation [here](https://github.com/ibtj21/PRODIGY_DS_04/blob/main/Sentiment_analysis.ipynb).  

___  

## Recommendations  

1. **Leverage Positive Sentiment for Growth**:  
   - Brands with a high percentage of positive sentiment, such as **Borderlands 3** and **Cyberpunk 2077**, should maintain their focus on community engagement and content development. Regularly monitor sentiment trends and reinforce positive sentiment through social media campaigns, events, and community-building activities.  

2. **Address Negative Sentiment for Reputation Management**:  
   - Negative sentiment toward brands such as **FIFA** and **Madden NFL** requires immediate attention. The brands should address user complaints promptly, such as fixing gameplay bugs, providing better customer support, and releasing quality content updates. Offering exclusive content or promotions can help shift sentiment toward a more positive view.  

3. **Engage with Neutral Sentiment**:  
   - Brands like **Amazon** and **WorldOfCraft** with **neutral sentiment** can take this opportunity to engage more actively with users. Highlight new features, run targeted campaigns, and encourage user-generated content to create a more favorable perception.  

By following these recommendations, brands can build stronger relationships with users, increase customer loyalty, and improve their reputation.  

___  

## Contributors  
- Hanna Hailemarima Gashaw  

___  

## Contributing  
Contributions are welcome! To contribute:  
1. Fork the repository.  
2. Create a new branch (e.g., `feature/your-feature`).  
3. Commit your changes.  
4. Submit a pull request.  

Ensure your contributions align with the project's coding standards.  

___  

## License  
This project is licensed under the MIT License. See the [LICENSE](https://github.com/ibtj21/PRODIGY_DS_04/blob/main/LICENSE) file for details.  
