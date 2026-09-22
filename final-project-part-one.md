| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


## Outline

Air travel dominates long-distance transportation in the United States because it is fast, efficient, and often cost-competitive. However, many travelers continue to choose Amtrak's long-distance train routes, spending more than two days crossing the country rather than arriving in a few hours. For first-time travelers, this creates an important question: **Is a 48–52 hour train journey worth the additional time and cost compared to flying?**

This project explores that question through a comparison of transportation options and travel experiences. Using route schedules, travel costs, delay statistics, and terrain characteristics, I will compare two of Amtrak's most iconic routes: the **California Zephyr** and the **Southwest Chief**. While traditional transportation comparisons focus primarily on efficiency, this project evaluates the value of the journey itself by examining how landscapes, scenery, and travel experiences change across the United States. The goal is to provide first-time travelers with a data-informed framework for deciding when train travel makes sense and which route best matches their priorities.

---

## Project Structure and Story Arc

#### One-Sentence Summary

Flying gets you across America quickly; train travel allows you to experience America along the way.

#### User Story

As a first-time cross-country traveler, I want to understand the trade-offs between flying and taking an Amtrak train so that I can decide whether the additional travel time is worth the scenic and experiential benefits.

#### Story Arc

<img src="Project Story Arc.png" alt="__" width="700">
<br>*Source: Author's visualization created using Python (Matplotlib and Seaborn), adapted from Berinato's (2016) Good Charts storytelling framework. Microsoft Copilot was used to assist in code refinement and visualization design.*

<br>This visualization serves as the narrative blueprint for the project. The story begins by introducing the dilemma faced by first-time travelers: whether to prioritize speed through air travel or experience through rail travel. The tension rises as travelers confront trade-offs involving travel time, cost, comfort, and reliability. The narrative reaches its peak during the exploration of route scenery and landscapes, highlighting the unique experiences offered by long-distance train travel. Finally, the story resolves through a decision matrix that provides practical recommendations based on traveler preferences.



---

## Initial Sketches

#### Sketch 1: Hero Banner

**AMTRAK Photo Typography**

Large title artwork using my personal travel photographs embedded into the letters of "AMTRAK."

Letter image themes:

| Letter | Theme |
|----------|----------|
| A | Colorado River, Eastern Rockies Corridor |
| M | Rodeo, California |
| T | White River National Forest |
| R | Tahoe National Forest |
| A | Laguna, New Mexico |
| K | Eldorado Springs |

<img width="1272" height="371" alt="image" src="https://github.com/user-attachments/assets/31747b6a-5e6d-4aaf-bb7b-05bcb60c8bd9" />

**Purpose:**
Introduce the project's theme and immediately communicate that this story is about experiencing the landscape, not simply reaching a destination.

---

#### Sketch 2: Travel Mode Trade-Off

<img src="Travel Mode Trade-Off.png" alt="__" width="700">
<br>*Source: Author's visualization created using Python (Matplotlib and Seaborn).*

Looking at the chart, my first instinct is that flying is the obvious winner. It is by far the fastest option and costs only slightly more than an Amtrak coach seat.

But then I realized that this comparison is only measuring transportation cost. The Amtrak Roomette is not really just a train ticket. It also includes a private room, bed, meals, and access to onboard amenities for two nights of travel.

If I think of the Roomette as transportation + hotel + meals, the cost starts to make more sense. Some of the $1,200 fare is paying for comfort and accommodation, not just getting from Pittsburgh to Seattle.

This raises a question: am I comparing travel modes, or am I comparing travel experiences?

For someone focused on reaching the destination quickly, flying clearly wins. For someone who sees the journey as part of the trip, the Roomette offers value that is not captured in a simple cost-versus-time chart.

**Working insight:** 
<br>The chart may overstate the cost disadvantage of the Roomette because it treats bundled lodging and meals as transportation costs.


---

## The Data

This project combines transportation, cost, and geographic data to compare cross-country travel experiences. The primary dataset will be constructed using route schedules and station information from Amtrak, supplemented by transportation cost information and rail performance statistics. Route-level information will be used to calculate travel times, cost-per-mile comparisons, and segment-level analysis of the California Zephyr and Southwest Chief.

To evaluate the experiential value of train travel, the project will also incorporate terrain classifications and scenic ratings for route segments. Each route segment will be categorized into landscape types such as plains, mountains, canyons, deserts, and urban areas. These classifications will support visualizations showing how scenery changes over time and where travelers are most likely to encounter high-value viewing opportunities. The resulting dataset will allow comparisons not only of transportation efficiency but also of the travel experience itself.

#### Data Sources

| Source | URL | Purpose in Project |
|----------|----------|----------|
| Amtrak Routes and Destinations | https://www.amtrak.com/routes.html | Route maps, station locations, schedules, and mileage information for long-distance train routes. |
| Bureau of Transportation Statistics (BTS) | https://www.bts.gov | Transportation statistics, rail performance data, and travel-related metrics. |
| Google Flights | https://www.google.com/travel/flights | Reference airfare prices for comparable city-pair routes. |
| AAA Fuel Cost Calculator | https://gasprices.aaa.com | Fuel cost estimates for automobile travel comparisons. |
| National Park Service (NPS) | https://www.nps.gov | Scenic, geographic, and landscape information related to train routes. |

---

## Method and Medium

#### Interactive Storytelling Platform

At this stage, I am exploring **Shorthand** as the primary platform for presenting my story. I like the idea of a scrolling narrative that blends text, visuals, maps, and reflections into a single experience. Since this project is as much about the journey as the analysis, I want readers to feel like they are traveling alongside me rather than simply viewing a report.

#### Data Visualization Tools

As I continue developing the project, I plan to use **Tableau Public** to create interactive visualizations that allow readers to explore selected aspects of the journey on their own. For initial sketches and experimentation, I have been using **Python** to test different ways of presenting the data and to understand which visuals best support the story I want to tell.

#### Project Hosting and Documentation

I am using **GitHub Pages** as a working space to document the project's development. It serves as a place to organize notes, visual drafts, datasets, references, and progress updates.

#### Formats Avoided

Traditional presentation formats such as **Microsoft PowerPoint** and spreadsheet-centric delivery through **Microsoft Excel** are intentionally avoided. 

---

## Software and Tools

| Tool | Purpose |
|--------|--------|
| Python | Data cleaning, analysis, and visualization development. |
| Pandas | Data manipulation and processing. |
| NumPy | Numerical calculations and analysis. |
| Matplotlib | Statistical charts and custom visualizations. |
| Seaborn | Enhanced data visualization styling and presentation. |
| Microsoft Copilot | Assisted with visualization design, code refinement, and writing support. |
| Google Colab | Interactive coding environment used for analysis and visualization generation. |

---

## References

- Amtrak. (n.d.). *Routes and destinations*. https://www.amtrak.com/routes.html
- American Automobile Association. (n.d.). *AAA fuel price and cost calculator*. https://gasprices.aaa.com
- Berinato, S. (2016). *Good charts: The HBR guide to making smarter, more persuasive data visualizations*. Harvard Business Review Press.
- Bureau of Transportation Statistics. (n.d.). *Bureau of Transportation Statistics*. U.S. Department of Transportation. https://www.bts.gov
- Google. (n.d.). *Google Flights*. https://www.google.com/travel/flights
- National Park Service. (n.d.). *National Park Service*. U.S. Department of the Interior. https://www.nps.gov

---


## AI Acknowledgements

Microsoft Copilot was used to assist with refining the project scope, improving the narrative structure, and formatting GitHub Markdown content.

