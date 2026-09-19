| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


> Important note: this template includes major elements of Part I, but the instructions on Canvas are the authoritative source.  Make sure to read through the assignment page and review the rubric to confirm you have everything you need before submitting.  When done, delete these instructions before submitting.

# Outline
> Include a high-level summary of your project.  This should be a couple paragraphs that describe what you're interested in showing with your final project. 
 
Text here...

> A project structure that outlines the major elements of your story.  Your Good Charts text talks about story structure in Chapter 8 - you should describe what you hope to achieve.  Make sure the outline is detailed enough that we can see how you anticipate your story unfolding.  You can incorporate your Story Arc from the in-class exercise along with your user stories and one sentence summary to make the topic even more clear. 

Text here...

## Initial sketches
> Post images of your anticipated data visualizations (sketches are fine). They should mimic aspects of your outline, and include elements of your story.  

Text here...

# The data
> A couple of paragraphs that document your data source(s), and an explanation of how you plan on using your data. 

Text here...

> A link to the publicly-accessible datasets you plan on using, or a link to a copy of the data you've uploaded to your Github repository, Box account or other publicly-accessible location. Using a datasource that is already publicly accessible is highly encouraged.  If you anticipate using a data source other than something that would be publicly available please talk to me first. 

| Name | URL | Description |
|------|-----|-------------|
|      |     |             |
|      |     |             |
|      |     |             |

# Method and medium
> In a few sentences, you should document how you plan on completing your final project. 

Text here...

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._


# Final Project Part I Proposal: Transcontinental Train Travel — Flight Speed vs. Rail Serenity

---

## 📍 Navigation
[Portfolio Home](../README.md) | **Part I Proposal** | [Part II (In Progress)](#) | [Part III (Final)](#)

---

## 1. High-Level Project Summary

Across the United States, long-distance transportation is overwhelmingly dominated by commercial air travel due to speed and efficiency. However, an increasing number of travelers are intrigued by the romance, sustainability, and unique perspective of cross-country rail journeys on Amtrak’s long-distance network. First-time travelers face a foundational dilemma: **Is a 48–52 hour transcontinental train journey worth the substantial investment in travel time and cost compared to flying, and what visual landscapes do you actually gain along the way?**

This project evaluates the first-time traveler's journey across America by analyzing **travel duration, cost per mile, delay patterns, and geographic landscape density**. By comparing two iconic transcontinental routes—the **California Zephyr** (Chicago to Emeryville/San Francisco via the Rockies and Sierra Nevada) and the **Southwest Chief** (Chicago to Los Angeles via the Red-Rock Deserts and Santa Fe Trail)—this interactive narrative provides first-time travelers with a data-grounded decision framework to determine whether to take the train or stick to flying.

---

## 2. User Persona & Story Arc

### Target Audience Persona
* **Name:** Maya (The First-Time Cross-Country Explorer)
* **Profile:** A 28-year-old professional with flexible remote work hours, interested in eco-conscious travel, scenic photography, and slow travel experiences, but constrained by limited vacation budget and time.
* **Key Question:** *"If I trade a 4-hour flight for a 50-hour train ride, what am I paying per mile, what scenery will I actually see during daylight, and which route offers the best experience?"*

### User Story
> **As a reader**, I want to virtually ride along on an Amtrak transcontinental journey so that I can see how America's landscapes, travel costs, and time investments change from coast to coast through a data-driven narrative supported by maps, timelines, and visualizations.

---

### Project Story Arc (Good Charts Chapter 8)

1. **SETUP: The First-Timer's Dilemma**
   * *Core Message:* Flying gets you there fast; rail travel shows you America.
   * *Hero Visual:* AMTRAK title banner framing geographic landscape transitions from east to west.

2. **CONFLICT / TENSION: Time, Cost, and Delay Reality Checks**
   * *Core Message:* The steep investment of 4 hours vs. 50 hours.
   * *Metrics:* Cost per mile comparison across Air, Amtrak Coach, and Roomette Sleeper; historical delay friction points.

3. **EXPLORATION: Geographic Scenery Density & Terrain Breakdown**
   * *Core Message:* Mapping 2,400 miles segment by segment.
   * *Comparison:* California Zephyr (Rockies & Sierra Nevada) vs. Southwest Chief (Red-Rock Deserts & Santa Fe Trail).
   * *Daylight Analysis:* How much peak scenery occurs during waking hours?

4. **RESOLUTION: The First-Timer's Decision Matrix**
   * *Core Message:* Matching travel style to the optimal route.
   * *Actionable Output:* A 2x2 matrix guiding travelers based on time flexibility and scenic preference.

---

## 3. Initial Visual Sketches & Prototypes

Below are initial visual concepts and chart prototypes designed following **Good Charts** principles (restrained color, direct labeling, and focus on takeaway titles):

### 1. Title Banner Concept (AMTRAK Geographic Arc)
> **AMTRAK: Transcontinental Train Travel — Flight Speed vs. Rail Serenity**  
> * **[ A ]** Galesburg Station (Midwest Origin)  
> * **[ M ]** River Rail Valleys  
> * **[ T ]** Glenwood Canyon Tunnel  
> * **[ R ]** Desert Sunset & Steel Bridges  
> * **[ A ]** Donner Lake & Sierra Pines  
> * **[ K ]** Pacific Coast Terminus  

---

### 2. Travel Mode Trade-Off (Time vs. Cost Analysis)
*Comparing total travel hours against dollar investment from Chicago to the West Coast.*

![Travel Mode Trade-Off](chart1_travel_mode_tradeoff.png)

---

### 3. Route Terrain & Daylight Visibility Profile
*Analyzing scenery density ratings (1–5 stars) alongside daylight visibility ratios across route segments.*

![Zephyr Scenery Profile](chart2_zephyr_scenery_profile.png)

---

### 4. First-Timer's Decision Matrix
*A 2x2 framework categorizing choices by time flexibility and landscape priorities.*

![Decision Matrix](chart3_decision_matrix.png)

---

## 4. Data Plan & Documentation

### Data Sources Identified
1. **Amtrak Route Timetables & Schedules:** Station arrival/departure times, route mileage, and scheduled segment durations (Sourced from official Amtrak Route Guides).
2. **Transportation Cost Comparison Dataset:** Sample economy airfares (Google Flights median), Amtrak Coach & Roomette fares, and driving expenses (AAA fuel/toll estimates).
3. **Bureau of Transportation Statistics (BTS) Long-Distance Performance:** Historical on-time performance and delay metrics across long-distance lines.
4. **National Park Service (NPS) Trails & Rails Guides:** Qualitative scenery classification ratings across major route segments.

### Data Structure Summary
📄 **Dataset File:** [`data/amtrak_route_comparison.csv`](../data/amtrak_route_comparison.csv)

| Route Name | Segment Start / End | Distance | Duration | Primary Terrain | Scenery (1-5★) | Daylight Ratio | Coach Fare | Roomette Fare |
| :--- | :--- | :---: | :---: | :--- | :---: | :---: | :---: | :---: |
| **California Zephyr** | Chicago IL → Omaha NE | 500 mi | 9.5 hrs | Plains & Farmland | 2★ | 30% | \$65 | \$320 |
| **California Zephyr** | Denver CO → Glenwood Springs CO | 185 mi | 5.8 hrs | Rockies & Canyons | 5★ | 100% | \$45 | \$210 |
| **California Zephyr** | Reno NV → Emeryville CA | 244 mi | 7.0 hrs | Sierra Nevada | 5★ | 90% | \$45 | \$190 |
| **Southwest Chief** | Kansas City MO → Albuquerque NM | 888 mi | 16.5 hrs | Great Plains & Mesas | 3★ | 50% | \$95 | \$450 |
| **Southwest Chief** | Albuquerque NM → Flagstaff AZ | 313 mi | 5.3 hrs | Red-Rock Desert | 4★ | 85% | \$50 | \$220 |

---

## 5. Method and Medium

* **Interactive Storytelling Platform:** **Shorthand** (or **ArcGIS StoryMaps**) for the responsive long-form web presentation.
* **Data Visualization Tools:** **Tableau Public** for interactive embedded charts + **Python (Matplotlib/Seaborn)** for clean static prototyping.
* **Project Hosting & Documentation:** **GitHub Pages** hosting markdown progress logs (`final_project.md`), visual chart assets, and CSV datasets.
* **Formats Avoided:** Traditional static slide software (MS PowerPoint) and raw spreadsheets (MS Excel) are omitted to deliver a modern, interactive web-native story.
