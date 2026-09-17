| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Title: Evaluating and Redesigning a Real-Time Production Performance Dashboard

## Project Overview

This project evaluates a real-time production performance dashboard used in Coin Production Line 2 as a case study in data visualization design. The dashboard is displayed on a large monitor within the production area and serves as a primary source of operational information for operators, supervisors, and managers. It communicates production output, operator performance, quality indicators, and target attainment in real time to support daily production management.

Using data visualization principles discussed in class, the project examines how effectively the dashboard communicates critical information and supports operational decision-making. The analysis identifies both strengths and areas for improvement related to visual hierarchy, usability, readability, and cognitive load. Based on this assessment, a redesign concept will be proposed to improve clarity, focus user attention on the most important performance indicators, and enhance the dashboard's ability to support timely and informed decisions on the shop floor.

### Objective

To assess the effectiveness of an existing manufacturing performance dashboard and develop redesign recommendations that improve communication, situational awareness, and decision support for production personnel.

## Step one: the visualization

### Shift Production Performance (Line 2)

<img src="Shift-Production-Dashboard-Line-2.png" alt="Shift Production Dashboard - Line 2" width="850">
<br>Note: Certain information, including the operator's name, photograph, and DENO (product category), has been anonymized or altered due to confidentiality requirements.

#### Personal Critique
The dashboard provides valuable real-time production and quality information, helping promote transparency and operational awareness on the shop floor. However, the crowded layout, extensive use of colors, and limited emphasis on critical metrics make it difficult to quickly identify issues. A redesigned dashboard focused on visual hierarchy, target attainment, and exception-based monitoring could improve situational awareness and support faster decision-making.

#### Preliminary Redesign Ideas
The redesigned dashboard should help users quickly answer three questions:
1. Is the line meeting its target?
2. Which operator or machine needs attention?
3. Should quality performance remain on this dashboard, or would it be more effective to focus exclusively on real-time production metrics given that quality indicators are already tracked in the Overall Cumulative Production Dashboard?

#### Possible Changes
- Remove non-essential graphics and simplify the layout, including evaluating whether quality metrics should remain on the dashboard.
- Apply a consistent color scheme (Green = On Target, Yellow = Warning, Red = Action Required).
- Use larger text and improved spacing to enhance readability from a shop-floor viewing distance.
- Separate each line performance and overall line performance from individual operator performance to establish a clearer visual hierarchy.
  

## Step two: the critique

The production dashboard effectively supports real-time monitoring by consolidating production, operator, and quality information into a single display, making it a valuable tool for operators, supervisors, and managers. Using Stephen Few's Data Visualization Effectiveness Profile as an evaluation framework, the dashboard was assessed based on clarity, visual hierarchy, readability, and its ability to support efficient decision-making (Few, 2021). Its greatest strength is the level of operational detail and transparency it provides. However, the crowded layout, extensive use of colors, and limited visual hierarchy make it difficult to quickly identify the most critical information, such as overall line performance and target attainment, which are essential characteristics of effective dashboard design (Few, 2006). 

For the redesign, I plan to focus on reducing visual clutter, improving readability, strengthening visual hierarchy, and highlighting performance indicators that require immediate attention. I would also like to use this opportunity to gather feedback from my peers on our dashboard to identify additional opportunities for improving its clarity, usability, and decision-support capabilities.

## Step three: Sketch a solution

Following the principles discussed in *Good Charts* by Scott Berinato, I approached the redesign as a storytelling exercise rather than a visual makeover. Instead of focusing on adding new information, I concentrated on improving how the dashboard communicates the most important message to operators, supervisors, and managers. The following mockups document my design journey from the existing dashboard to the final proposed design.

---

#### Mockup 1: Understanding the Existing Dashboard

I started by examining our existing production dashboard from the perspective of an operator, supervisor, and manager. What immediately stood out to me was that the dashboard contained a wealth of useful operational information, including output, machine performance, operator performance, quality indicators, and line attainment. However, I realized that users needed to scan several sections before understanding the most important message: **How is the production line performing right now?** Although the dashboard was information-rich, it required significant effort to identify the overall status and priorities. This observation led me to focus on improving visual hierarchy rather than simply removing information.

<img src="Mockup 1- Understanding the Existing Dashboard.png" width="500">

---

#### Mockup 2: Elevating the Main Message

The first question I asked myself was, *"What is the single most important thing a user should know within a few seconds of viewing the dashboard?"* For me, the answer was overall production performance. Inspired by the idea in Good Charts that important messages should be immediately visible, I moved overall and line-level performance to the top of the layout. This approach is also consistent with Few's recommendation that dashboards should emphasize the most important performance indicators through strong visual hierarchy (Few, 2006). My goal was to ensure that users could instantly determine whether the line was on track before diving into detailed operational information.

<img src="Mockup 2- Elevating the Main Message.png" width="500">

---

#### Mockup 3: Removing Distractions

After promoting the key performance indicators, I looked for elements that competed for attention. I noticed that large graphics, decorative elements, and quality visuals occupied valuable screen space and distracted from the production story the dashboard was trying to tell. Since quality metrics are already available in another management dashboard, I challenged myself to remove or reduce these elements. This step taught me that effective dashboard design is often less about adding information and more about deciding what information does not need immediate visibility.

<img src="Mockup 3- Removing Distractions.png" width="500">

---

#### Mockup 4: Organizing Information into Logical Zones

At this stage, I realized that the dashboard still felt visually busy because users were being asked to process strategic and operational information simultaneously. To address this, I introduced two distinct information zones. The first zone focuses on overall and line-level performance, while the second focuses on operator and machine-level details. My intention was to create a natural flow that mirrors how supervisors make decisions: first understand overall performance, then investigate the factors contributing to that performance. This separation is consistent with dashboard design principles that recommend grouping related information to reduce cognitive load and improve user comprehension (Few, 2006).

<img src="Mockup 4- Organizing Information into Logical Zones.png" width="500">

---

#### Mockup 5: Improving Accountability Through Performance Cards

As I continued refining the design, I wanted to make operator and machine performance easier to compare. In the original dashboard, performance was grouped by production teams, which made comparisons less intuitive. I experimented with operator-centered performance cards that used a consistent structure and visual format. This redesign made it easier to identify high and low performers at a glance while preserving accountability. More importantly, it shifted the dashboard from simply reporting data to supporting action and intervention.

<img src="Mockup 5- Improving Accountability Through Performance Cards.png" width="500">

---

## Mockup 6: Creating the Final Dashboard

The final design represents my effort to transform the dashboard into a decision-support tool. Instead of asking users to search for information, the dashboard now guides them through a deliberate sequence. First, it presents overall and line-level performance to establish the current production status. Next, it highlights operator and machine-level performance to explain what is driving the results. Throughout the design, I intentionally reduced visual clutter, simplified color usage, and created clearer groupings of information to improve dashboard effectiveness and support rapid identification of operational issues (Few, 2006; Few, 2021). My goal was not to change the underlying data but to improve how the story is communicated so that users can quickly understand the situation and determine where intervention is needed.

<img src="Mockup 6- Creating the Final Dashboard.png" width="500">

---

#### Design Decision: Retaining the Dark Background

One design element I intentionally retained from the original dashboard was the black background. While I explored several background color options during the redesign process, the final choice was based on actual testing and stakeholder feedback rather than personal preference. Because the dashboard is displayed on a large LED monitor in the production area, readability from a distance was a key consideration. Through demonstrations using different background colors and a survey of operators, supervisors, and managers, the dark background consistently received better feedback in terms of visibility, contrast, and ease of recognizing performance indicators from across the shop floor.

I also found that the black background allowed key performance indicators and status colors to stand out more prominently. The green, yellow, and red performance indicators became easier to distinguish, helping users quickly identify areas that were on target and those requiring attention. Rather than treating the background as a visual design choice, I considered it part of the dashboard's operational environment and usability requirements.

While dashboard design guidance often emphasizes readability and contrast over aesthetic preferences, the final decision was based on actual user testing and operational needs within the production environment (Few, 2006).

<img src="Prod Dashboard (Draft).png" alt="ABC Production Dashboard - Line 2" width="850">
<br>Note: Certain information, including the operator's name, photograph, and DENO (product category), has been anonymized or altered due to confidentiality requirements.


## Step four: Test the solution

#### Interview Results

| Question | Person 1 | Person 2 | Person 3 |
|-----------|-----------|-----------|-----------|
| Can you tell me what you think this is? | Not immediately clear. | Looks like a performance display. | Looks like a dashboard. |
| Can you describe to me what this is telling you? | Hard to understand because of the acronyms. | Shows Line 2 performance. | Shows some performance information. |
| Is there anything you find surprising or confusing? | Too many colors. Unfamiliar acronyms (MLN, ECC, EQPT, PERF). | Colors can be improved. | Avoid different colors. |
| Is there anything you would change or do differently? | Use fewer colors. Black background is more readable than white. | Place Line 2 performance in sequential format. | Add the word "DASHBOARD" in the title. |

#### My Observations

During the interviews, respondents were generally unable to quickly determine the purpose of the visualization. Most participants struggled to explain what insights could be derived from the illustration. The anonymization of critical information, including the operator's name, photograph, and DENO (product category), further reduced understanding because the context behind the data became less clear.

#### Synthesis Matrix

| Theme | Feedback | Design Change |
|---------|---------|---------|
| Too Many Colors | The dashboard uses too many colors, making it harder to focus on important information. | The dashboard colors represent production codes and standard performance indicators. Because the intended users are already familiar with them, I would retain the current color scheme. |
| Lack of Clarity | Users found the purpose of the dashboard and the acronyms difficult to understand. | Add **"DASHBOARD"** in the title and, as much as possible, avoid abbreviations. |
| Need Better Organization | The information is not arranged in a way that is easy to follow. | Reorganize the layout and place information in a logical sequence. |


## Step five: build the solution

<img src="PF Dashboard (Final).png" alt="Production Performance Dashboard - Line 2" width="850">
<br>Note: Certain information, including the operator's name, photograph, and DENO (product category), has been anonymized or altered due to confidentiality requirements.

#### Reflection

I realized from this exercise that dashboards should be designed for their intended audience, not necessarily for everyone. At first, I wanted the dashboard to be understandable to all users, but the interviews made me realize that this may not be appropriate in security-sensitive environments such as currency production, military, or government operations. In these cases, limiting what outsiders can understand helps protect sensitive information and supports the "need-to-know" principle in information security.

At the same time, the dashboard should be clear and easy to use for authorized personnel. Even if outsiders do not understand the acronyms or operational details, the intended users should be able to quickly understand performance, identify issues, and make decisions. This exercise taught me that good dashboard design is about finding the right balance between usability and security while meeting the needs of the target audience.


## References
- Berinato, S. (2024). Good charts workbook: Tips, tools, and exercises for making better data visualizations. Harvard Business Review Press.
- Few, S. (2006). Information dashboard design: The effective visual communication of data. O'Reilly Media.
- Few, S. (2021). Data visualization effectiveness profile. Perceptual Edge.
- [Company Name Redacted]. (2026). Production Performance Dashboard (Line 2)


## AI acknowledgements
Microsoft Copilot was used to improve writing clarity, refine wording, and assist with GitHub Pages and Markdown (.md) formatting. It supported the presentation of this portfolio but did not replace my own analysis, design decisions, or conclusions.

