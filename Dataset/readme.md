# Deepfake-Related Reddit Posts and Comments Data

This repository contains a dataset of Reddit posts and comments related to deepfake technology. The data was scraped using the Apify tool, specifically targeting discussions surrounding deepfake technology on Reddit. The dataset is intended for research and analysis purposes, particularly in the fields of natural language processing, sentiment analysis, and social media analysis.

## Dataset Overview

- **Filename**: `Deepfake_orignal.json`
- **Data Source**: Reddit (via Apify - https://apify.com/)
- **Data Type**: JSON
- **Sample Size**: 20458 records (including posts and comments)

- **Filename**: `Processed_deepfake.json`
- **Data Source**: Reddit (via Apify - https://apify.com/)
- **Data Type**: JSON
- **Sample Size**: 17720 records (including posts and comments)

### Content of the Dataset

The dataset includes the following fields for each Reddit post/comment:

- `id`: Unique identifier for the Reddit comment or post.
- `parsedId`: Parsed version of the Reddit ID.
- `url`: Direct link to the Reddit post or comment.
- `postId`: ID of the parent post associated with the comment.
- `parentId`: ID of the parent comment or post.
- `username`: The Reddit username of the author.
- `userId`: Unique identifier for the Reddit user.
- `category`: The subreddit category under which the post/comment was made.
- `communityName`: The name of the subreddit community.
- `body`: The text content of the comment or post.
- `createdAt`: Timestamp of when the comment or post was created.
- `scrapedAt`: Timestamp of when the data was scraped.
- `upVotes`: Number of upvotes the comment or post received.
- `numberOfreplies`: Number of replies to the comment.
- `html`: The HTML representation of the comment or post.
- `dataType`: Specifies whether the record is a post or a comment.

### Sample Content

The dataset contains various discussions from subreddits such as `r/technology` and others. These discussions often revolve around the ethical implications, technical aspects, and societal impact of deepfake technology.



## Applications

This dataset can be utilized for a variety of research and analysis purposes, including but not limited to:

- **Sentiment Analysis**: Analyze the sentiments expressed in discussions related to deepfakes.
- **Topic Modeling**: Identify the key topics discussed in relation to deepfakes on Reddit.


## Contributing

If you have any suggestions, improvements, or additional datasets related to deepfakes, feel free to contribute to this project by forking the repository and submitting a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any questions or feedback, please reach out at zxxu@gzist.edu.cn.
