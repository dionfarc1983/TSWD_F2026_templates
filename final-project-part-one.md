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



## Outline

Air travel dominates long-distance transportation in the United States because it is fast, efficient, and often cost-competitive. However, many travelers continue to choose Amtrak's long-distance train routes, spending more than two days crossing the country rather than arriving in a few hours. For first-time travelers, this creates an important question: **Is a 48–52 hour train journey worth the additional time and cost compared to flying?**

This project explores that question through a comparison of transportation options and travel experiences. Using route schedules, travel costs, delay statistics, and terrain characteristics, I will compare two of Amtrak's most iconic routes: the **California Zephyr** and the **Southwest Chief**. While traditional transportation comparisons focus primarily on efficiency, this project evaluates the value of the journey itself by examining how landscapes, scenery, and travel experiences change across the United States. The goal is to provide first-time travelers with a data-informed framework for deciding when train travel makes sense and which route best matches their priorities.

---

## Project Structure and Story Arc

### One-Sentence Summary

**Flying gets you across America quickly; train travel allows you to experience America along the way.**

### User Story

As a first-time cross-country traveler, I want to understand the trade-offs between flying and taking an Amtrak train so that I can decide whether the additional travel time is worth the scenic and experiential benefits.

### Story Arc

#### Part 1: Setup — The First-Timer's Dilemma

**Headline:** Flying Gets You There. Train Travel Shows You America.

This section introduces the reader to the central question. Most travelers can fly from Chicago to the West Coast in approximately four hours, while the same trip by train requires roughly 48 to 52 hours. The section uses personal travel photography and a hero banner to establish the contrast between speed and experience.

**Key Takeaway:**
Train travel is not simply transportation; it is a different way of experiencing the country.

---

#### Part 2: Tension — Time, Cost, and Reliability

**Headline:** Trading Hours for Scenery

This section presents the primary trade-offs faced by travelers.

Questions addressed include:

- How much longer does train travel take?
- How does the total cost compare with flying and driving?
- What is the cost per mile?
- How reliable are long-distance trains?

**Key Takeaway:**
The train experience comes with meaningful sacrifices in time and potential delays.

---

#### Part 3: Exploration — Watching America Unfold

**Headline:** 48 Hours Across 2,400 Miles

This section follows the journey segment-by-segment and shows how geography changes throughout the trip.

Major landscape transitions include:

1. Midwest Plains
2. High Plains
3. Rocky Mountains
4. Canyon Country
5. Desert Landscapes
6. Sierra Nevada
7. California Coast

Interactive maps and terrain visualizations will allow readers to follow the journey and identify where the most visually rewarding portions occur.

**Key Takeaway:**
Some of America's most iconic scenery can only be fully appreciated through a ground-level journey.

---

#### Part 4: Resolution — Choosing the Right Journey

**Headline:** Which Odyssey Fits Your Travel Style?

The final section synthesizes the findings into a traveler decision framework.

Recommendations will be tailored to:

- Budget-conscious travelers
- Scenic seekers
- Time-constrained travelers
- Bucket-list adventurers

A simple decision matrix will help readers determine whether they should take the California Zephyr, Southwest Chief, or choose to fly instead.

**Key Takeaway:**
There is no single "best" option; the best choice depends on individual travel priorities.

---

## Initial Sketches

### Sketch 1: Hero Banner

**AMTRAK Photo Typography**

Large title artwork using my personal travel photographs embedded into the letters of "AMTRAK."

Planned image themes:

| Letter | Theme |
|----------|----------|
| A | Eastern United States |
| M | Midwest Plains |
| T | Rocky Mountains |
| R | Red-Rock Deserts |
| A | Sierra Nevada |
| K | California Destination |

**Purpose:**
Introduce the project's theme and immediately communicate that this story is about experiencing the landscape, not simply reaching a destination.

---

### Sketch 2: Travel Mode Trade-Off

**Visual Type:** Slope Chart / Dot Plot

Comparison of:

- Commercial Air
- Driving
- Amtrak Coach
- Amtrak Roomette

Variables:

- Total travel time
- Total trip cost

**Expected Insight:**
Train travel requires dramatically more time but may offer competitive pricing and unique experiential value.

---

### Sketch 3: California Zephyr Scenic Profile

**Visual Type:** Combination Bar and Line Chart

Measures:

- Scenic rating by route segment
- Daylight visibility percentage
- Terrain type

**Expected Insight:**
The highest-rated scenery aligns with key daylight viewing periods in the Rocky Mountains and Sierra Nevada.

---

### Sketch 4: First-Time Traveler Decision Matrix

**Visual Type:** 2 × 2 Matrix

Axes:

- Time Flexibility
- Scenic Preference

**Expected Insight:**
Different routes serve different traveler goals and priorities.

---

# The Data

This project combines transportation, cost, and geographic data to compare cross-country travel experiences. The primary dataset will be constructed using route schedules and station information from Amtrak, supplemented by transportation cost information and rail performance statistics. Route-level information will be used to calculate travel times, cost-per-mile comparisons, and segment-level analysis of the California Zephyr and Southwest Chief.

To evaluate the experiential value of train travel, the project will also incorporate terrain classifications and scenic ratings for route segments. Each route segment will be categorized into landscape types such as plains, mountains, canyons, deserts, and urban areas. These classifications will support visualizations showing how scenery changes over time and where travelers are most likely to encounter high-value viewing opportunities. The resulting dataset will allow comparisons not only of transportation efficiency but also of the travel experience itself.

### Planned Dataset Structure

```text
Route_Name
Segment_ID
Start_Station
End_Station
Distance_Miles
Scheduled_Hours
Terrain_Type
Scenery_Rating
Daylight_Ratio
Coach_Fare_USD
Roomette_Fare_USD
Flight_Fare_USD
```

### Data Sources

| Name | URL | Description |
|------|-----|-------------|
| Amtrak Route Guides | https://www.amtrak.com/routes.html | Official route schedules, mileage, and station information. |
| Bureau of Transportation Statistics | https://www.bts.gov | Historical rail performance and delay metrics. |
| Google Flights | https://www.google.com/travel/flights | Reference airfare pricing for comparable routes. |
| AAA Fuel Cost Calculator | https://gasprices.aaa.com | Fuel-cost estimates for driving comparisons. |
| National Park Service | https://www.nps.gov | Landscape descriptions and scenic reference information. |

---

# Method and Medium

The final project will be developed as an interactive web-based narrative designed for desktop and mobile viewing. The storytelling structure will follow the Setup → Tension → Exploration → Resolution framework from *Good Charts*. Interactive visualizations will be created primarily in Tableau Public, while Python (Pandas, Matplotlib, and Seaborn) will be used for exploratory analysis and prototyping.

The final deliverable will be hosted through GitHub Pages and may incorporate Shorthand or ArcGIS StoryMaps for a more immersive storytelling experience. Personal travel photography from my transcontinental Amtrak journey will be integrated throughout the project to complement the quantitative analysis and strengthen the narrative.

---

## References

Berinato, S. (2016). *Good charts: The HBR guide to making smarter, more persuasive data visualizations*. Harvard Business Review Press.

Amtrak. (n.d.). Routes and destinations. https://www.amtrak.com/routes.html

Bureau of Transportation Statistics. (n.d.). https://www.bts.gov

National Park Service. (n.d.). https://www.nps.gov

---

## AI Acknowledgements

Microsoft Copilot was used to assist with refining the project scope, improving the narrative structure, and formatting GitHub Markdown content.

