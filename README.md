# About Me

I am a software engineer focused on building practical, data-driven applications that help users move from raw information to faster decisions.

I enjoy working on projects that involve large datasets, real-time data ingestion, backend systems, automation, analytics, and AI-assisted workflows. A lot of my work is centred around taking complex data, structuring it properly, and turning it into useful product features that help users understand trends, compare outcomes, and make better decisions without manually digging through thousands of data points.

My main interests include:

- Full-stack application development
- Real-time data pipelines
- Sports analytics and live data systems
- AI-assisted analysis tools
- Data scraping, cleaning, and transformation
- Backend architecture and database design
- Cloud-based data storage and retrieval
- Building products that turn large datasets into simple user-facing insights

I like building applications where the backend does the heavy lifting: collecting data, processing it, storing it securely, and giving users a clean interface to interact with the results.

---

# Featured Project: WYNZ

WYNZ is a sports social and analytics platform designed to help users follow live sports, analyze odds, view historical matchup data, chat with other fans, and compete in free-to-play sports prediction challenges.

The goal of WYNZ was to combine live sports data, historical performance, odds movement, social interaction, and competition into one platform. Instead of forcing users to jump between sportsbooks, stat websites, social platforms, and spreadsheets, WYNZ brings the core sports decision-making experience into one application.

## What WYNZ Does

WYNZ allows users to:

- Follow live games across major sports leagues
- View live and historical sports data
- Analyze odds and matchup trends
- Compare historical head-to-head results between teams
- Chat with other users during games
- Sync sportsbook-related data
- Join free-to-play prediction challenges
- Compete with other users for prizes and leaderboard position

The product was built around the idea that sports fans and bettors should be able to understand the context behind a matchup faster. Rather than only showing surface-level scores or odds, WYNZ focuses on giving users historical and live data that helps them form better conclusions.

## Live Sports Data System

One of the core technical features of WYNZ was its live sports data pipeline.

The application used Azure to detect live games through sports APIs and trigger data collection as soon as new live game data became available from the API. This allowed WYNZ to pull and store live sports data with approximately a **5 to 15 second delay**, depending on the league, game state, and source availability.

WYNZ collected and stored live data across major North American sports leagues, including:

- MLB
- NHL
- NBA
- NFL

It also supported major European football competitions, including:

- La Liga
- Premier League
- Ligue 1
- Serie A
- Bundesliga

The system was built to handle both live and historical sports data, allowing the application to compare current matchups against previous results.

## Azure-Based Data Storage and Retrieval

WYNZ used Azure as the cloud layer for storing and serving sports data. Live API data, historical matchup data, odds data, and processed analytics were stored in Azure so users could interact with the data through the application with stronger security, better efficiency, and lower latency.

Azure helped support:

- Secure storage of live and historical sports data
- Faster retrieval of matchup and odds information
- Cloud-based access for user-facing analytics
- More efficient handling of large sports datasets
- Scalable backend infrastructure for live game updates
- Reliable storage of continuously updated API data

This architecture allowed WYNZ to separate raw data ingestion from user-facing application performance. The backend handled live detection, data collection, cleaning, and storage, while the frontend could retrieve structured data from Azure for a faster and cleaner user experience.

## Historical Sports Analytics

WYNZ used historical data from the past five years to maintain consistency in analysis and comparison. This helped avoid relying on incomplete or inconsistent datasets.

The platform used historical sports data to show:

- Past matchups between teams
- Head-to-head results over a five-year period
- Team performance trends
- Historical outcomes based on similar matchups
- Context around live odds and betting lines
- Patterns in team performance across seasons

By combining live data, historical results, and odds data, WYNZ helped users evaluate matchups with more context instead of relying only on current game lines or recent headlines.

## Odds and Matchup Analysis

WYNZ also worked with live and historical sports odds data. The purpose was to help users understand how odds related to previous outcomes, team performance, and matchup history.

The platform used this data to support analysis around:

- Future matchup outcomes
- Historical betting trends
- Team-vs-team performance
- Odds movement
- Past results under similar conditions
- Comparison between current odds and previous matchup data

The goal was not just to display odds, but to give users a better understanding of the data behind them.

## Data Collection and Processing

I used Python-based data ingestion scripts to collect and structure sports data from publicly available and permissioned sources, then cleaned and stored that data for live and historical analysis.

These scripts helped automate the process of pulling sports information, transforming it into usable formats, and storing it in Azure for application use.

The backend focused on:

- Detecting live games from sports APIs
- Pulling live game data as new data became available
- Cleaning inconsistent sports data
- Structuring team, league, game, and odds information
- Storing live and historical results
- Supporting fast retrieval for frontend analytics
- Maintaining consistency across multiple leagues and competitions

This data pipeline was one of the most important parts of the project because the quality of the user-facing analysis depended directly on how clean, consistent, and reliable the backend data was.

## Social and Competition Features

WYNZ was not only built as a sports analytics tool. It was also designed as a social sports platform.

Users could interact with sports data while also participating in community-based prediction challenges. The challenge system was built around free-to-play sports competitions where users could enter contests, compete on predictions, and win prizes.

The broader product vision was to create a social competition layer for sports betting and sports analytics. Users could follow games, analyze data, discuss matchups, and compete with other users from the same platform.

## Demo Video

A demo video .mp4 has been attached to this repository, showing the WYNZ platform in action. 

The demo walks through the main product experience, including live sports data, matchup analysis, historical results, odds-related insights, social features, and the challenge system. It demonstrates how users can move from viewing live games to analyzing historical data and participating in prediction-based competitions.

---

# What I Learned Building WYNZ

Building WYNZ gave me experience working across the full product stack, from backend data ingestion to frontend user experience.

Some of the main areas I worked on included:

- Designing real-time data workflows
- Using Azure for cloud-based data storage and retrieval
- Detecting live games through sports APIs
- Building scripts to collect and process sports data
- Structuring historical datasets for analysis
- Working with live and delayed sports data feeds
- Creating backend logic for matchup and odds analysis
- Building user-facing features around complex datasets
- Thinking through product design, monetization, and scalability
- Turning raw sports data into useful insights for users

WYNZ represents the type of software I enjoy building: applications that combine large datasets, automation, analytics, cloud infrastructure, and user-focused design to help people make faster and better decisions.
