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

### **Target Audience Persona**
* **Name:** Maya (The First-Time Cross-Country Explorer)
* **Profile:** A 28-year-old professional with flexible remote work hours, interested in eco-conscious travel, scenic photography, and slow travel experiences, but constrained by limited vacation budget and time.
* **Key Question:** *"If I trade a 4-hour flight for a 50-hour train ride, what am I paying per mile, what scenery will I actually see during daylight, and which route offers the best experience?"*

### **User Story**
> **As a reader**, I want to virtually ride along on an Amtrak transcontinental journey so that I can see how America's landscapes, travel costs, and time investments change from coast to coast through a data-driven narrative supported by maps, timelines, and visualizations.

### **Project Structure & Story Arc (*Good Charts Chapter 8*)**

+-----------------------------------------------------------------------------------+ | 1. SETUP: The First-Timer's Dilemma                                              | |    - Flying gets you there fast; rail travel shows you America.                    | |    - Hero Visual: AMTRAK title banner with region-filled photography.             | +-----------------------------------------------------------------------------------+ | v +-----------------------------------------------------------------------------------+ | 2. CONFLICT/TENSION: Time, Cost, and Delay Reality Checks                         | |    - The 4-hour vs. 50-hour trade-off.                                           | |    - Price per mile: Air vs. Coach vs. Roomette Sleeper.                        | |    - On-Time Performance & delay friction points across long-distance lines.      | +-----------------------------------------------------------------------------------+ | v +-----------------------------------------------------------------------------------+ | 3. EXPLORATION: Geographic Scenery Density & Terrain Breakdown                    | |    - Mapping 2,400 miles segment by segment.                                      | |    - California Zephyr (Mountains & Canyons) vs. Southwest Chief (Deserts & Red-Rock)| |    - Daylight Scenery Window: How much peak landscape occurs while you're awake?  | +-----------------------------------------------------------------------------------+ | v +-----------------------------------------------------------------------------------+ | 4. RESOLUTION: The First-Timer's Decision Matrix                                  | |    - Interactive 2x2 Matrix: Time Flexibility vs. Scenic Preference.             | |    - Clear recommendations tailored to budget, timeline, and travel goals.        | +-----------------------------------------------------------------------------------+

---

## 3. Initial Sketches & Wireframes

Below are initial sketches laying out key narrative sections and visual chart prototypes:

### **Sketch 1: Hero Header Title Art (AMTRAK Letter Photo Banner)**
*(Concept adapted from Phase 1 proposal)*

+-----------------------------------------------------------------------------------+ |                                                                                   | |    █████  ███    ███ ████████ ██████   █████  ██   ██                             | |   ██   ██ ████  ████    ██    ██   ██ ██   ██ ██  ██                              | |   ███████ ██ ████ ██    ██    ██████  ███████ █████                               | |   ██   ██ ██  ██  ██    ██    ██   ██ ██   ██ ██  ██                              | |   ██   ██ ██      ██    ██    ██   ██ ██   ██ ██   ██                             | |                                                                                   | |   [ A ] Galesburg Station | [ M ] River Valley       | [ T ] Glenwood Canyon     | |   [ R ] Desert Sunset     | [ A ] Donner Lake Pines  | [ K ] Pacific Coast       | |                                                                                   | |   SUBTITLE: Transcontinental Train Travel — Flight Speed vs. Rail Serenity        | +-----------------------------------------------------------------------------------+

---

### **Sketch 2: Travel Mode Trade-Off (Time vs. Cost Scatter / Dot Plot)**
*(Good Charts Ch. 3 & 4: Comparison & Persuasion)*

TOTAL TRAVEL TIME vs. COST COMPARISON (Chicago to West Coast)
Time (Hours)                                Cost ($ USD) 50 hrs |----------- [Amtrak Roomette] -----------| $1,200 (Includes meals/bed) 48 hrs |----------- [Amtrak Coach] --------------| $210   (Budget option) 36 hrs |----------- [Driving - Gas/Tolls] -------| $450   (2 passengers) 4 hrs |----------- [Commercial Air] ------------| $280   (Economy seat) +-----------------------------------------+
![Travel Mode Trade-Off](chart1_travel_mode_tradeoff.png)

---

### **Sketch 3: Segment Scenery & Terrain Distribution (Combination Bar / Line Chart)**
*(Good Charts Ch. 2 & Appendix B: Proportions over journey segments)*

CALIFORNIA ZEPHYR TERRAIN & DAYLIGHT PROFILE
Segment:  [Chicago-Omaha] | [Omaha-Denver] | [Denver-Glenwood] | [Glenwood-Salt Lake] | [Reno-Emeryville] Terrain:  Plains/Farmland  | High Plains   | Rockies/Canyons   | Red Desert/Canyons   | Sierra Nevada Daylight: [  NIGHT / AM  ] | [  DAYLIGHT ] | [  PEAK DAYLIGHT] | [    TWILIGHT      ] | [  PEAK DAYLIGHT] Scenery:  ★★☆☆☆            | ★★★☆☆         | ★★★██ (5/5)       | ★★★★☆              | ★★★██ (5/5)
![Zephyr Scenery Profile](chart2_zephyr_scenery_profile.png)

---

### **Sketch 4: First-Timer's Decision Matrix (2x2 Concept Matrix)**
*(Good Charts Ch. 5: Capturing Concepts with a 2x2 Matrix)*

           HIGH SCENIC PRIORITY
                     |
  [ TAKE THE ZEPHYR ]|  [ ZEPHYR ROOMETTE ]
  Scenic seeker on   |  Ultimate bucket-list
  a budget (Coach)   |  luxury experience
TIME                     | FLEXIBILITY -------------+----------------------- NO TIME FLEXIBILITY (Low Speed)              |                        (High Speed) [ SOUTHWEST CHIEF ]|  [ FLY COMMERCIAL ] Culture/History    |  Business travel / focus (Desert)     |  Strict schedule | LOW SCENIC PRIORITY
![Decision Matrix](chart3_decision_matrix.png)

---

## 4. Data Plan & Documentation

### **Data Sources Identified**
1. **Amtrak Route Timetables & Schedules:** Station arrival/departure times, route mileage, and scheduled segment durations for the *California Zephyr* and *Southwest Chief* (Sourced directly from official Amtrak Route Guides).
2. **Transportation Cost Comparison Dataset:** Sample economy airfares (Google Flights median), Amtrak Coach & Roomette fares, and driving expenses (AAA fuel & toll estimates).
3. **Bureau of Transportation Statistics (BTS) Long-Distance Performance:** Historical on-time performance and delay metrics for long-distance train lines.
4. **National Park Service (NPS) Trails & Rails Guides:** Qualitative scenery classification ratings across major route segments.

### **Data Structure & Repository Link**
The compiled dataset is stored in a clean CSV format within this repository:
📄 **Data File:** [`data/amtrak_route_comparison.csv`](../data/amtrak_route_comparison.csv)

```csv
Route_Name,Segment_ID,Start_Station,End_Station,Distance_Miles,Scheduled_Hours,Terrain_Type,Scenery_Rating_1to5,Daylight_Ratio,Coach_Fare_USD,Roomette_Fare_USD,Flight_Fare_USD
California Zephyr,CZ_01,Chicago IL,Omaha NE,500,9.5,Plains,2,0.30,65,320,180
California Zephyr,CZ_02,Omaha NE,Denver CO,538,10.0,High Plains,3,0.80,75,380,180
California Zephyr,CZ_03,Denver CO,Glenwood Springs CO,185,5.8,Rockies/Canyons,5,1.00,45,210,180
California Zephyr,CZ_04,Glenwood Springs CO,Salt Lake City UT,382,9.2,Desert/Canyons,4,0.40,55,260,180
California Zephyr,CZ_05,Salt Lake City UT,Reno NV,588,11.0,Great Basin Desert,3,0.50,70,310,180
California Zephyr,CZ_06,Reno NV,Emeryville CA,244,7.0,Sierra Nevada,5,0.90,45,190,180
Southwest Chief,SW_01,Chicago IL,Kansas City MO,437,7.2,Midwest Prairie,2,0.60,60,290,175
Southwest Chief,SW_02,Kansas City MO,Albuquerque NM,888,16.5,Great Plains/Mesa,3,0.50,95,450,175
Southwest Chief,SW_03,Albuquerque NM,Flagstaff AZ,313,5.3,Red-Rock Desert,4,0.85,50,220,175
Southwest Chief,SW_04,Flagstaff AZ,Los Angeles CA,620,11.5,Mojave/SoCal,3,0.40,75,340,175
5. Method and Medium
Interactive Storytelling Platform: Shorthand (or ArcGIS StoryMaps) for the responsive long-form digital presentation.
Data Visualization Tools: Tableau Public for interactive embedded charts + Python (Matplotlib/Seaborn) for static prototyping.
Project Hosting & Documentation: GitHub Pages hosting markdown progress logs (final_project.md), visual chart assets, and CSV datasets.
Tools Avoided: Standard presentation software (MS PowerPoint) and spreadsheets (MS Excel) are avoided to ensure an interactive, stand-alone digital web deliverable.

---
