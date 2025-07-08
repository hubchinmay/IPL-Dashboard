# IPL-Dashboard
### 1. Project Title

🏏 MatchMaster: IPL Insights & Team Performance Dashboard
An interactive Power BI dashboard that analyzes Indian Premier League (IPL) match data—focusing on team wins, player performance, match margins, and game trends to support fan engagement, team benchmarking, and strategic insights.


### 2. Short Description

The MatchMaster Dashboard is a visually rich and data-driven Power BI report built to explore detailed IPL match records. It enables users to analyze matches, team performances, win margins, player impact, and game trends across multiple seasons for actionable insights.


### 3. Tech Stack

The dashboard was built using the following tools and technologies:

* Power BI Desktop – Main platform for data visualization and report creation.
* Power Query – Used for data transformation, unpivoting team columns, and formatting.
* DAX (Data Analysis Expressions) – Applied for KPI calculations such as total matches, averages, and derived metrics.
* Data Modeling – Single-table model with a calculated table to handle match counts per team.
* File Format – `.pbix` file for development, exports as `.png` or published to Power BI Service.


### 4. Data Source

Source: Excel file `IPL.xlsx`, sheet: `IPL_Team`
The dataset includes structured information on IPL matches, such as Match ID, Date, Teams, Winner, Win Margin, Win Type, Player of the Match, Total Runs, Wickets Taken, Strike Rate, and Economy Rate—used to generate performance-based visuals and KPIs.


### 5. Highlights

#### • Business Problem

With IPL being one of the most followed cricket leagues globally, there’s a need to convert raw match statistics into visual insights. Teams, fans, and analysts often struggle to understand performance trends, player impact, and win margins quickly using spreadsheets alone.

Key questions such as:
– Which team has the highest win count?
– Who are the most impactful players?
– What are the average win margins across seasons?
– Is there any correlation between strike rate and economy rate?
… are difficult to answer at a glance.


#### • Goal of the Dashboard

To create an intuitive and visually engaging Power BI dashboard that:
– Analyzes team and player performance using match data
– Highlights key performance indicators like strike rate and economy rate
– Provides interactive filters to explore trends by team, date, and win type
– Supports better understanding of IPL dynamics through visual storytelling


#### • Walkthrough of Key Visuals

### KPI Cards

* Total Matches Played
* Total Runs Scored
* Average Strike Rate
* Average Economy Rate

### Team Performance

* Matches Won per Team: Bar chart showing the number of matches won by each team
* Matches Played per Team: Bar chart built using unpivoted data from Team1 and Team2 columns

Win Margin Analysis

* Column chart displaying average win margins (runs/wickets) per winning team, with optional legend by win type

### Win Type Distribution

* Pie or donut chart showing the proportion of wins by runs vs. wickets

### Trend Analysis

* Line chart showing win margin trends over time (by match date)

### Player Performance

* Bar chart for frequency of "Player of the Match" awards

### Performance Comparison

* Scatter plot of Strike Rate vs. Economy Rate, optionally sized by Total Runs

### Interactive Filters

* Date slicer
* Team slicer
* Win Type slicer

### • Business Impact & Insights

Team Benchmarking: Easily identify the most consistent and dominant teams over multiple seasons
Player Recognition: Spot top performers based on match awards and key metrics
Tactical Strategy: Analyze win types and margins to refine team strategies
Audience Engagement: Fans can visually explore favorite teams’ journey and player stats
Performance Trends: Discover correlations in strike rate, economy rate, and total runs to drive commentary and analysis

### 6. Screenshots
* Dashboard Preview (https://github.com/hubchinmay/IPL-Dashboard/blob/main/Snapshot%20of%20Dashboard.png)
