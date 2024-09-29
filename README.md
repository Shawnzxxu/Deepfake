# Deepfake Technology: Public Sentiment and Topic Insights from Reddit

This repository contains data, analysis, and insights derived from Reddit discussions about deepfake technology. The study aims to understand public sentiment and key discussion topics concerning deepfake technology using natural language processing (NLP) techniques such as topic modeling, sentiment analysis, and word cloud visualization.

## Repository Structure

- **/data**: Contains the raw and cleaned datasets used for the analysis.
- **/notebooks**: Includes Jupyter Notebooks for data preprocessing, exploratory data analysis (EDA), topic modeling, sentiment analysis, and word cloud generation.
- **/figures**: Stores figures generated during the analysis, such as word clouds, sentiment distribution charts, and topic modeling visualizations.
- **/scripts**: Python scripts for automating parts of the analysis.

### Notebooks

- **Data Preprocessing.ipynb**: Details the data cleaning process applied to the raw Reddit dataset, including removing duplicates, handling missing values, tokenizing text, and lemmatization. The processed data is saved for subsequent analysis.
- **Data Distribution.ipynb**: Provides an exploratory data analysis (EDA) of the cleaned dataset, visualizing the distribution of posts and comments across time, especially focusing on the number of samples per quarter.
- **Topic Modeling.ipynb**: Applies Latent Dirichlet Allocation (LDA) for topic modeling. It identifies and categorizes the main discussion topics from the Reddit posts related to deepfake technology.
- **Sentiment Analysis.ipynb**: Sentiment analysis is performed using two methods, TextBlob and VADER. This notebook explains how sentiment is classified into positive, negative, and neutral categories.
- **Wordcloud.ipynb**: Generates word clouds for each sentiment category (positive, negative, neutral) to visually represent the most frequently discussed words in the dataset.

## Data Overview

### Data Source

- The dataset was collected using the Apify tool, scraping posts and comments from Reddit between May 2019 and May 2024, resulting in 20,458 entries. After preprocessing, 17,720 entries remained for analysis.


## Key Figures from the Analysis

- **Figure 1: Overview of the Proposed Framework**: A flowchart depicting the entire analysis process, from data collection to sentiment and topic analysis.
- **Figure 2: Word Cloud of Extracted Posts and Comments**: A visual representation of the most frequent words in the dataset.
- **Figure 3: Example of Post and Comment in Deepfake**: Sample data entries showing typical Reddit posts and comments.
- **Figure 4: Quarterly Sample Distribution Bar Chart**: Visualizes the distribution of data over time, highlighting the concentration of posts in 2023 and 2024.
- **Figure 5: Coherence Score by Number of Topics**: Shows the coherence scores for different numbers of topics to determine the optimal topic number for LDA.
- **Figure 6: Inter-topic Distance Map and Top 30 Most Relevant Terms**: Visualization of topic separation and key terms within each topic.
- **Figure 7: Bar Chart of Word Frequency for Four Topics**: Shows the most frequent words associated with each identified topic.
- **Figure 8: Sentiment Classification Pie Chart**: Displays the overall sentiment distribution across the dataset (46% positive, 39% negative, 15% neutral).
- **Figure 9: Word Cloud of Positive, Negative, and Neutral Tweets**: Word clouds for each sentiment category, highlighting the key words associated with each.
- **Figure 10: Stacked Bar Chart of Sentiment Distribution Across Four Topics**: Illustrates the sentiment distribution within each identified topic, showing the variation in public sentiment.

## Conclusion

The analysis provides a comprehensive understanding of public sentiment and key discussion topics surrounding deepfake technology on Reddit. The findings emphasize the divided public opinion, with significant concerns about authenticity and legal issues, while also recognizing the potential in entertainment. This research can inform the development of legal and ethical frameworks to address the challenges posed by deepfake technology.

## How to Use

1. **Clone the repository**:

    ```bash
    git clone https://github.com/Shawnzxxu/Deepfake.git
    cd Deepfake
    ```

2. **Run the notebooks**:

    Open and run the Jupyter Notebooks in the respective folders to replicate the analysis or to use the data for further research.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please reach out at zxxu@gzist.edu.cn.
