# Whatsapp-chat-analyser

WhatsApp Chat Analyzer is a web application built using Streamlit that allows users to analyze their WhatsApp chat data. It provides insights into messaging patterns, most active users, common words, media sharing, and more. The analysis includes visual representations like word clouds, bar charts, and heatmaps.

# Features
1.Top Statistics: Displays total messages, words, media shared, and links shared by the user.
2.Monthly and Daily Timeline: Visualizes message activity trends over time.
3.Activity Maps: Shows the most active days and months for messaging.
4.Heatmap: Provides a weekly activity heatmap for messaging patterns.
5.Wordcloud: Generates a word cloud of the most frequent words used in the chat.
6.Most Common Words: Identifies the most common words excluding common stop words.
7.Most Busy Users: Shows the users with the highest messaging activity.

# How to Use
1.Upload WhatsApp Chat File: Export your WhatsApp chat in .txt format and upload it to the app.
2.Select User for Analysis: Choose whether to analyze the overall chat or a specific user.
3.View Statistics: The app will display various metrics and visualizations based on the chat data.

# Installation
1.Clone the repository:
git clone https://github.com/your-username/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer

2.Install the required dependencies:
pip install -r requirements.txt

3.Run the app:
streamlit run app.py

# Requirements
Python 3.x
Streamlit
Pandas
Matplotlib
Seaborn
WordCloud
URLLib
Sample Data
You can test the application using sample WhatsApp chat data by exporting your own WhatsApp chats or using the provided sample data.

# Future Enhancements
Add support for emoji analysis and categorization.
Improve performance for larger chat files.
Add more detailed user-based insights.
Contributing
Feel free to fork this repository and submit pull requests. Contributions are welcome!

# License
This project is licensed under the MIT License.
