# My First ETL Project: Pulling Kenyan News Into PostgreSQL with Python

Today I completed my first ETL (Extract, Transform, Load) project — and honestly, it made a lot more sense than I expected. Huge thanks to LuxDevHQ, who helped me figure out everything from setting up the API to loading data into my database.

## 🔧 What I Built

- Pulled live news about **Kenya** from [NewsAPI](https://newsapi.org/)
- Transformed the data using `pandas` to keep only what I needed
- Loaded everything into a **PostgreSQL database** hosted on Aiven

This helped me understand how data flows from raw form into something structured and ready for analysis.

## 📰 What I Found

Most of the headlines were related to the **Kenyan police**, especially around custody-related incidents and the excessive force by police during the maandamano/peacefull protests. The topic is not only trending locally, but has also been covered by international sources like BBC, Al Jazeera English And even ABC news.

## 🛠️ Tools I Used

- `requests` to pull API data  
- `pandas` to transform it  
- `SQLAlchemy` to load into PostgreSQL  
- Aiven for the database hosting and DBeaver 

## 💡 Why This Matters

Before today, ETL was just another buzzword. Now it feels like something I can actually use — whether it's analyzing news, financial data, or social trends. It’s a small project, but a big first step.

## 🙏 Thanks

Big shoutout to **Lux** — you really helped me connect the dots today.
