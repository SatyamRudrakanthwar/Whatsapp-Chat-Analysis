WhatsApp Chat Analysis

Overview
WhatsApp Chat Analysis is a Python-based project designed to analyze and generate insights from WhatsApp chat exports. The project processes chat data and extracts valuable statistics such as message counts, emoji usage, word counts, and more, while also visualizing trends in communication. This tool can be used to gain a deeper understanding of individual or group chat dynamics.


Features

- Basic Statistics:
  - Total messages sent
  - Number of media messages
  - Emojis used
  - Links shared

- Advanced Insights:
  - Message frequency over time
  - Active hours and days
  - Word count per message
  - User-specific analysis for group chats

- Visualizations:
  - Interactive charts for message trends
  - Count boxes below each plot for better readability
  - Heatmaps for user activity patterns

- Anomaly Detection:
  - Detect days with anomalous message frequency using rolling mean and standard deviation.



Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/WhatsApp-Chat-Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd WhatsApp-Chat-Analysis
   ```
3. Install the required dependencies:

------------------------------------------------------------------------
Usage

1. Export the chat from WhatsApp as a `.txt` file.
2. Place the chat file in the project directory.
3. Run the analysis script:
   ```bash
   python chat_analysis.py
   ```
4. View the results and visualizations.

------------------------------------------------------------------------

Tech Stack

- Programming Language: Python
- Libraries Used: Pandas, Matplotlib, Seaborn, re, emoji, nltk

-------------------------------------------------------------------------

Project Structure

```
WhatsApp-Chat-Analysis/
├── chat_analysis.py      # Main script for analysis
├── requirements.txt      # List of dependencies
├── README.md             # Project documentation
└── data/
    └── chat.txt          # Example WhatsApp chat file
```

-------------------------------------------------------------------------

Example Visualizations

- Daily Messages:
  ![Daily Messages Plot](example_plots/daily_messages.png)
- Active Hours Heatmap:
  ![Active Hours Heatmap](example_plots/active_hours_heatmap.png)

-------------------------------------------------------------------------

Future Enhancements

- Sentiment analysis of messages
- Word cloud generation for frequently used words
- Support for multilingual chat analysis

-------------------------------------------------------------------------

Contributing

Contributions are welcome! Please fork this repository, create a new branch for your feature or bug fix, and submit a pull request.

--------------------------------------END--------------------------------
