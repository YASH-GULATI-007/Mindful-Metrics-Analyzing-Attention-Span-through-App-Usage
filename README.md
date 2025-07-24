# Read-Me
---
## 🌱 Mindful Metrics: Understanding Attention Through App Usage

  - Ever wondered how your phone habits affect your ability to stay focused?
  - This project explores that question using data from different devices to uncover patterns between digital behavior and attention span.

---

📌 What’s This Project About?

  - We use machine learning to analyze how people interact with their phones—how long they spend on screens, how they respond to notifications, and whether they’re
  using productivity or entertainment apps.

---

Our goal?

- To see if these patterns can tell us something about how long someone can stay focused.

---

🔄 How It Works

  This project is split into three stages:


  🔧 Data Preparation

  - Cleaned and transformed raw usage data

  - Encoded app categories, screen time, and notification behavior

  - Saved as processed_data.csv


  📊 Data Visualization

  - Created easy-to-understand graphs

  - Helped us see trends like:

  - Who uses more productivity apps?

  - Does screen time relate to attention span?

  - Which behavior patterns matter most?


  🤖 Machine Learning

  - Tried several models (Random Forest, Gradient Boosting, etc.)

  - Predicted a person’s attention span category

  - Best models gave us an accuracy of around 55%

---

🔍 What Data Did We Use?

  - The dataset includes real-world-inspired behaviors such as:

  - Notification handling (ignore, interact, turn off, etc.)

  - App types (productivity vs social/gaming)

  - Screen activity (work-related vs entertainment)

  - Screen time (daily average across devices)

---

💡 What Did We Find?

- People who ignore or delay notifications tend to stay focused longer

- Not using Productivity apps correlate positively with attention

- Entertainment-heavy usage (like social media or games) may shorten attention span

- These patterns were consistent even across multiple device types

---

⚙️ Tools Used

- Python (Pandas, NumPy, Scikit-learn)

- Data Viz: Matplotlib, Seaborn

- Machine Learning: Classification & Regression

- Storage: CSV files at each step to keep everything modular

---

📁 File Structure

- data_preparation.py → Prepares and saves cleaned data

- data_visualization.py → Plots trends and insights

- ml_models.py → Trains and evaluates different ML models

- processed_data.csv → Used between steps

- main_data.csv → Raw behavioral data

- final_output.csv → Can be generated post-modeling

---

🚀 Why This Matters

- In a world of constant digital noise, projects like this help us better understand our habits—and maybe even change them.

- Whether you’re building digital wellness apps or just curious about your own attention span, this project shows how data can tell a deeper story.
