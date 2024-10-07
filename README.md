# The Double-Edged Sword of Deepfake: Public Perception towards Deepfake through Topic modelling and Sentiment analysis on Reddit

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
