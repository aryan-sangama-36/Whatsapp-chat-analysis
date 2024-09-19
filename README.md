# Whatsapp Chat Analyzer

This repository contains a Streamlit application for analyzing WhatsApp chat data. The application provides various insights and visualizations about the chat history, including message statistics, timelines, activity maps, and more.

## Features:

**Upload WhatsApp Chat File:** Upload your WhatsApp chat file in .txt format for analysis.

**User Selection:** Analyze data for specific users or for the overall chat.

**Statistics:** View total messages, words, media shared, and links shared.

**Timelines:** Visualize chat activity over time with monthly and daily timelines.

**Activity Maps:** See which days of the week and months are the busiest.

**Weekly Activity Heatmap:** Detailed heatmap showing activity throughout the week.

**Busiest Users:** Identify the most active users in the chat group.

**Word Cloud:** Generate a word cloud for the most frequently used words.

**Most Common Words:** Bar chart of the most common words in the chat.

**Emoji Analysis:** Detailed analysis of emoji usage, including a pie chart of the most used emojis.

## Installation:

**Clone the repository:**
git clone https://github.com/yourusername/whatsapp-chat-analyzer.git

**Navigate to the project directory:**
cd whatsapp-chat-analyzer


**Install the required dependencies:**
pip install -r requirements.txt


**Usage**
Run the Streamlit application:
streamlit run app.py


Open your web browser and go to https://whatsapp-chat-analysis-aryan36-unofficial-intelligence.streamlit.app/ to access the application.


Upload your WhatsApp chat file in the sidebar and select the user for analysis.


Click on "Show Analysis" to view various statistics and visualizations.


## File Structure:

**app.py:** Main script for running the Streamlit application.

**helper.py:** Contains helper functions for data processing and visualization.

**preprocessor.py:** Contains functions for preprocessing the chat data.

**requirements.txt:** List of Python libraries required to run the application.


## Dependencies:

streamlit

matplotlib

seaborn

urlextract

wordcloud

pandas

emoji


## Contributing:

Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue.


