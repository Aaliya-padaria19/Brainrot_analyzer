# Brainrot_analyzer
This is a python based analyzer to track the mental well being of individual based on their brain rot consumption. :)

ANALYZER PROJECT STRUCTURE
─ Module 1: Data Loading & Parsing
─ Module 2: Content Classification  
─ Module 3: Brainrot Scoring Engine
─ Module 4: Mental Health Risk Assessment
─ Module 5: Report Generation & Visualization
─ Module 6: User Interface (Streamlit)

TECH STACK:

+ DATA SOURCE - own insta data (IN BEGINNING) or INSTAGRAMAPI (TRY)
+ DATA PROCESSING - PANDAS
+ CONTENT_CLASSIFICATION - nltk / keyword based
+ MENTAL HEALTH SCORING - based on recent pyschology articles/ studeis
+ VISUALIZATION - SEABORN / MATPLOTLIB
+ STORAGE - sqlite3
+ GUI - streamlit
+ INTERACTIVE DASHBOARD - plotly
+ SENTIMENT ANALYSIS - textblob or transformers
+ API CALLS - requests

FEATURES:
What I've Build

Phase 1: Content filter + feed blocker

Phase 2: Recommendation engine (suggest good accounts)

Phase 3: Analytics dashboard (show impact)

Phase 4: AI-powered personalization

STRATERGY TO SELL - 

--> ANALYZER - free to analyse your mental well being
--> Filter(placeholder name rn) - will filter out the brainrot content and give you personalized feed.(prevents mindless scrolling) $$payed version. ;)

MODULES BREADKDOWN :

///////Module 1: Data Loading & Parsing

User provides Instagram data export JSON file
Extract watch history (video watched, duration, timestamp)
Convert to structured format

+ Tech used:

Python: file handling, JSON parsing
pandas: DataFrames, reading JSON

///////Module 2: Content Classification

Look at video titles/descriptions
Categorize each video: Educational, News, Creative, Entertainment, Brainrot
Brainrot markers: memes, trending sounds, short clips, low substance

+ Tech used:

String manipulation in Python
Pattern matching with regex (this made stuff much simple)
Simple rule-based classification


//////Module 3: Brainrot Scoring Engine

Calculate total hours spent on Brainrot
Calculate percentage: (Brainrot hours / Total hours) × 100
Calculate daily average consumption

+ Tech used:

Python math & datetime operations
Time calculations and aggregations

//////Module 4: Mental Health Risk Assessment

Create a scoring algorithm based on brainrot consumption
Risk levels: Low (0-30%), Medium (30-60%), High (60-80%), Critical (80%+)
Include warnings about sleep, productivity, attention span

+ Tech used:

Conditional logic (if/else)
Dictionary/JSON for storing risk profiles

//////Module 5: Report Generation

Create visualizations: pie charts, time series, category breakdown
Generate text report with insights
Export to PDF or HTML (optional)

+ Tech used:

matplotlib / seaborn for charts
String formatting for nice reports

///////Module 6: User Interface

Simple interface where user uploads Instagram export
Displays analysis results
Option to download report

+ Tech used:

streamlit (easiest) OR CLI with click



