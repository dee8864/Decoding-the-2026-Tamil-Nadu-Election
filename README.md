# Decoding-the-2026-Tamil-Nadu-Election

Numbers don't vote, but they reveal who did. In a state where 47.8% of reserved seats were decided by less than a five-percent margin, the story isn't about who won — it's about where the real fight happened.

# One-Line Description
A data-driven storytelling project that analyses the 2026 Tamil Nadu Assembly election results to uncover how reserved constituencies (SC/ST) voted differently from general seats and how TVK disrupted the two-party dominance.

# About the Project
# Why I Chose This Project
Election data is often reduced to headlines about winners and losers. But the real insights lie in the margins — in seats that flipped by a few hundred votes, in reserved constituencies that behave differently from the rest of the state, and in the flow of votes from old parties to new ones. I chose this project because it demanded not just technical skills but also the discipline of neutrality and the art of storytelling. The challenge explicitly rewarded framing over flashy visuals, which aligned with my belief that data analysis is ultimately about making people care.

# Why I Made This
AtliQ Media, a fictional news network, wanted a fact-based, non-partisan television show on the election. As a freelance data analyst, my task was to find 2-3 research questions, answer them with public Election Commission data, and pitch the story through a deck, a video walkthrough, and a dashboard. I built this project to demonstrate that I can take raw electoral data, clean it, analyse it, and translate it into a narrative that a producer or a general viewer can understand in under seven minutes.

# What Makes This Portfolio Stand Out
Most candidates stop at dashboards and notebooks. This project goes further: it includes a stakeholder deck, a video script, a public GitHub repo with reproducible analysis, and a Power BI dashboard that tells the same story from multiple angles. The focus is not on how many charts I can make but on whether I can answer the question: "What is the one headline that matters?" The project also respects strict neutrality — no causal claims, no party endorsements, no speculative commentary — which is rare in political data work.

# My Journey: From Raw Data to a Show-Ready Story
I started with three CSV files: 2021 results, 2026 results, and a constituency master file. The 2026 turnout column was intentionally blank — a deliberate obstacle to test data sourcing. Instead of wasting time on blocked web scraping, I pivoted. I realised that the research questions I selected (reserved seat story, geographic story, margin of victory story) did not require turnout percentages. I could compute winners, vote shares, margins, and flips directly from the candidate-level votes.

I aggregated 234 constituencies, identified winners for both years, and calculated how many seats changed hands. I then compared reserved seats (SC/ST) against general seats. The results were striking: reserved seats were consistently tighter, with lower average winner vote shares and higher proportions of nail-biter finishes. I visualised this through margin distribution charts and regional stacked bars.

Next, I traced TVK's vote sources. By analysing party-wise vote share changes, I discovered that in 119 constituencies, DMK lost the highest share to TVK — an average of nearly 17 percentage points. In 77 constituencies, AIADMK took the hit. This was not a three-way split; it was a direct transfer from the old guard.

I built a Power BI dashboard with four pages: an overview, a reserved seat deep dive, a TVK takeover analysis, and a geographic scatter plot. The dashboard uses measures for flip rate, average margins, and nail-biter percentages. Finally, I wrote a 7-minute video script and prepared an 11-slide deck. The entire process — from data cleaning to final submission — followed the Codebasics rubric, which rewards storytelling (70%) over analytical hygiene (30%).

# Project Overview
This project is a complete end-to-end data analysis and storytelling exercise for the 2026 Tamil Nadu Assembly election. It includes:
Data cleaning and aggregation using Python (Pandas)
Computation of winners, vote shares, margins, and flips for 234 constituencies
Comparative analysis between reserved (SC/ST) and general seats
Regional breakdown of reserved seat wins by party
Identification of the five closest reserved seats (nail-biters)
Vote source analysis for TVK: which parties lost the most vote share where TVK gained
A Power BI dashboard with four interactive pages
A stakeholder deck (8-11 slides) with narrative arc
A video script designed for a 5-7 minute pitch
A public GitHub repository with all code, data, and outputs

# Skills Showcased
Data Wrangling and Aggregation (Pandas, groupby, merges)
Exploratory Data Analysis (vote share, margin calculations)
Storytelling with Data (headline framing, narrative flow)
Data Visualisation (Matplotlib, Seaborn, Power BI)
Dashboard Design (measures, relationships, slicers, formatting)
Neutrality and Ethical Data Use (no causal claims, no editorialising)
Problem Solving (pivoting when turnout data was unavailable)
Communication (deck writing, video scripting, README documentation)
Version Control (Git, GitHub)

# Tech Stack
Python (Jupyter Notebook) - Pandas, NumPy, Matplotlib, Seaborn, Plotly (for Sankey diagram)
Power BI Desktop
Git / GitHub
Microsoft PowerPoint (or Google Slides)

# Key Highlights
1. Identified that reserved seats are more competitive: 47.8% of reserved seats had margins under 5%, compared to 43.1% for general seats.
2. Mapped reserved seat wins by region: TVK swept all 5 reserved seats in Chennai Metro and won 6 out of 9 in the South region.
3. Quantified vote transfers: In 119 constituencies, DMK lost an average of 16.9% vote share to TVK; in 77 constituencies, AIADMK lost 15.9%.
4. Listed the five closest reserved seats, including Kallakurichi (0.32% margin) and Tindivanam (0.37% margin), all in Central and South regions.
5. Built a Power BI dashboard with interactive region slicer, margin distribution charts, and a scatter plot of margin vs vote share.
6. Maintained strict neutrality throughout: every chart title is fact-based, no visual editorialising, no predictions or causal claims.

# What This Project Demonstrates
This project demonstrates that I can take a real-world, politically sensitive dataset and turn it into a clear, engaging, and non-partisan story. It shows that I understand the difference between correlation and causation, and that I respect data limitations. It also proves that I can work within a tight rubric, prioritising storytelling over unnecessary complexity. For a recruiter, this project signals that I am not just a person who can write Python code — I am someone who can frame insights, communicate them to non-technical audiences, and deliver a complete product from raw data to final pitch.

