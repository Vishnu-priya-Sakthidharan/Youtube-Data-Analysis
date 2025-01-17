# YouTube Data Analysis using YouTube API

## Overview
This project demonstrates how to analyze YouTube data using the YouTube Data API. It focuses on extracting and processing video metadata, channel statistics, and other relevant information for insightful analysis. The results are visualized to provide an understanding of YouTube trends and performance metrics.

## Features
- Fetch video and channel data using the YouTube Data API.
- Analyze metrics like views, likes, comments, and subscriber counts.
- Identify trends in video performance and content creation.
- Visualize data using Python libraries such as Matplotlib and Seaborn.
- Export data to CSV for further analysis.

### Prerequisites
1. **Python**: Make sure Python 3.7+ is installed on your system.
2. **Google Developer Console**: Obtain an API key for YouTube Data API v3.
   - Follow the [YouTube API Setup Guide](https://developers.google.com/youtube/registering_an_application).
3. **Libraries**: `google-api-python-client`, `pandas`, `numpy`, `matplotlib`, `seaborn`

Additionally, you need to set up the YouTube Data API:
1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project and enable the YouTube Data API v3.
3. Generate an API key.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Vishnu-priya-Sakthidharan/youtube-data-analysis.git
   cd youtube-data-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the root directory and add your API key:
   ```env
   YOUTUBE_API_KEY=your_api_key_here
   ```

## Usage
1. Run the script to fetch YouTube data:
   ```bash
   python YT-analysis.ipynb
   ```
2. Process and analyze the data:
   - Load the dataset using pandas.
   - Perform analysis on metrics like views, likes, and comments.
3. Visualize the results:
   - Use `matplotlib` and `seaborn` to create charts and graphs.

## Example Analysis
- **Top Performing Videos:** Identify videos with the highest engagement metrics.
- **Trend Analysis:** Understand how views and likes vary over time.
- **Channel Comparison:** Compare metrics across multiple channels.

## 📬 Contact
   If you have any questions or suggestions, feel free to reach out:

- Email: iamvishnupriya07@gmail.com
- GitHub: https://github.com/Vishnu-priya-Sakthidharan



