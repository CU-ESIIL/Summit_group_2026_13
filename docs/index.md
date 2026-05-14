---
title: Team Home
public_mode_toggle: true
---
# Team name: Lucky 13
# Predicting Water Impacts from Current and Future Mining in the Black Hills, SD
### (w/ a Digital Twin framework)

![Sacred Sites in the Black Hills region, SD](assets/BadHeartBull_Map.png)

!!! tip "How to use this page during the Summit" - This page is your team’s
shared workspace and final report-out page. It captures your group’s process and
thinking throughout the Summit and will be used to share your work with others.

    - Use this page as your team’s working record during the Summit and your final report-out.

    - The Summit has several different goals and thus you will use the page differently each day: Day 1 is for alignment, Day 2 is for building one useful thing, and Day 3 is for synthesis and report- out.

    - Look for the green buttons to indicate what you need to edit.

    - Megaphones 📣 indicate which items you will be presenting during the end-of-day report-outs.

    - Only the items with megaphones will be visible when you hit the 'Summit Report Out' button.

    - If you turn off 'Instructions' then you will only see the page content for public display.

## Team (lucky) 13:

!!! note "Day 1 directions" Change the title to the name of your project.

    [Edit Day 1 setup in Markdown](https://github.com/CU-ESIIL/Summit_group_2026_13/edit/main/docs/index.md?plain=1#L21){ .md-button target="_blank" rel="noopener" }

!!! tip "For ESIIL staff" Group Number: 13

    Breakout Room #: S127

    [ESIIL staff edit in Markdown](https://github.com/CU-ESIIL/Summit_group_2026_13/edit/main/docs/index.md?plain=1#L28){ .md-button target="_blank" rel="noopener" }

![Team hero image](assets/hero/hero.png)

!!! note "How to replace the image above" Upload an image that represents your
project and welcome people to your page.

    Upload your own image to `docs/assets/hero/` and replace the file named `hero.png`. Use a wide image if you can, then refresh the site preview to check how it looks.
    Keep the file path `docs/assets/hero/hero.png` if you want the Markdown above to keep working.

    [Open image folder for changing image](https://github.com/CU-ESIIL/Summit_group_2026_13/tree/main/docs/assets/hero){ .md-button target="_blank" rel="noopener" }

[See a completed example](example.md){ .md-button }

## People { #people .oasis-report-out-context }

!!! note "Day 1 task" Get to know your team: share your cards (5-7 mins). Update
your team roster (2-3 min).

    Use the in-person name cards to guide quick introductions.

    | Name card prompts | Follow-up notes |
    |---|---|
    | ![Name card prompts for name, institution, area of expertise, research difference, and questions](assets/team/name-card-prompts.png) | ![Follow-up notes card with space for names and follow-up ideas](assets/team/name-card-followups.png) |

    [Edit People in Markdown](https://github.com/CU-ESIIL/Summit_group_2026_13/edit/main/docs/index.md?plain=1#L63){ .md-button target="_blank" rel="noopener" }

| Name                  | Affiliation                 | Contact                | Github          |
| --------------------- | --------------------------- | ---------------------- | --------------- |
|                       |                             |                        |                 |
| Naupaka Zimmerman     | University of Kansas        | naupaka@gmail.com      | naupaka         |
| Lala Kounta           | Michigan State University   | kountalala@msu.edu     | lkounta         |
| Lilly Jones           | CIRES Earth Lab, CU Boulder | lijo8146@colorado.edu  | daearconsulting |
| Joni Tobacco          | Salish Kootenai College     | jktobacco@gmail.com    | jonit12324      |
| Elisha Yellow Thunder | Oglala Lakota College/SDSU  | eyellowthunder@olc.edu | wakinyanzi      |
| C. Jason Tinant       | Oglala Lakota College       | jtinant@olc.edu        | cjtinant        |
| Chong Seok Choi       | Cornell University          | cc3226@cornell.edu     | chongseokchoi   |
| Sankung Fatty       | --          | fattysankung9@gmail.com     | --   |
| Al Kaushkis       | --          | akuslikis@gmail.com     | --   |
| Max Cook       | Colorado State University | maxwell.cook@colostate.edu     | maxwellCcook   |
| Erica Laundreaux | -- | erica.lx32@gmail.com | -- |


## Team Norms and Decision Making { #team-norms-and-decision-making }

!!! note "Day 1 task"

    Suggested Self-Facilitation Instructions:

    - Round Robin: Everyone shares 1 norm that they think will be important for their team during the Summit and perhaps following the Summit (2 min).

    - After everyone has shared, make a list with as many norms as possible in GitHub (5–7 min).

    - Vote on your top 3 ideas. (Each person gets 3 votes; you can use all your votes on 1 idea or spread them out) (2 min).

    - In GitHub, move all team norms with votes to the top of the list.

    | Gradients of agreement |
    |---|
    | ![Gradients of agreement scale for Summit teams](assets/hero/norms.png) |

    [Edit Team Norms in Markdown](https://github.com/CU-ESIIL/Summit_group_2026_13/edit/main/docs/index.md?plain=1#L87){ .md-button target="_blank" rel="noopener" }

Our team norms:

- Define everything:
  - **Goals:**
  - To predict water impacts from current and future mining in the Black Hills,
    SD.
  - Raise awareness on Tribal issues of mining impacts.
  - Grow and share our data science knowledge.

- **transparency and processes**
  - Include only open data
  - Centralize in repository

- **How we will keep a team log**
- **How we protect others intellectual property**
- **What is our AI authorship agreement**
- **What are our Possible pitfalls**
- **What is our decision making strategy:**

...

## Our product(s) 📣 { #product-direction .oasis-report-out-section .oasis-report-out-day2 }

!!! note "Day 2 Tasks" Morning Focus: questions, hypotheses, context; add at
least one visual (photo of whiteboard/notes)

    Afternoon Focus: try a few datasets and analyses. Keep it visual, keep it simple. Update the site to reflect what you test.

    [Edit content below here in Markdown](https://github.com/CU-ESIIL/Summit_group_2026_13/edit/main/docs/index.md?plain=1#L106){ .md-button target="_blank" rel="noopener" }

Short term:

- Acquire mining permit information and geospatial locations of proposed and
  current mine sites
- Set up agentic AI to scrape and extract information from mining permits
- Gather and harmonize (agentic LLM) input data including:
- - Topography (DEM)
  - Climate (PRISM, Temp/Precip)
  - Geologic Maps
  - Land Use / Land Cover
  - Stremflow data (USGS)
  -     - streamstats tool
  - OpenET for Evapotranspiration data
  - Snow cover
  - SSURGO (soils)

Long term:

- Integrate two models for water quality monitoring:
- - SWAT (Soil and Water Assessment Tool)
  - Stream Vulnerability Index

![Day 2 morning whiteboard or notes photo](assets/IMG_6386.png)

_Morning whiteboard or notes showing the question, hypotheses, and context we
used to start Day 2._

## Our question(s) 📣 { #project-question .oasis-report-out-section .oasis-report-out-day2 }

Our working question:

How are existing and proposed mine sites in the Black Hills region of South
Dakota impacting water resources downstream? How are sacred sites in Black Hills
geogrpahically related to proposed mining exploration?

What would count as progress:

Progress might look like a framework for a Digital Twin for the Black Hills
region that can integrate water impact models (e.g., SWAT). A case study
integrating mining permits and water modeling would be ideal! Eventually, we
want a dashboard to allow users to explore potential impacts at a gievn
location.

## Hypotheses/Intentions [Optional: probably not relevant if you are creating an educational tool]

## Why this matters (the “upshot”) 📣 { #why-this-matters .oasis-report-out-section .oasis-report-out-day2 }

This matters because:

...

People who could use this:

...

## Data sources we’re exploring 📣 { #data-exploration .oasis-report-out-section .oasis-report-out-day2 }

!!! note "data exploration" Provide a snapshot showing some initial data
patterns.

    Add 2-4 promising data sources (links +1-line notes)

![Exploration figure](assets/explorations/explore_data_plot.png)

_Snapshot showing initial data patterns._

Promising data sources:

- [Data source 1](#): ...
- [Data source 2](#): ...
- [Data source 3](#): ...
- [Data source 4](#): ...

## Methods/technologies we’re testing 📣 { #methods-and-code .oasis-report-out-section .oasis-report-out-day2 }

!!! note "methods" Add 2-4 methods/technologies we're testing (stats, models,
viz).

- LLM/agentic harmonization of input data (topography, weather, streamflow,
  geology, land use, etc.)
- LLM-based PDF scraping of mine permit information (location, type, etc.)
- SWAT (Soil and Water Assessment Tool)
- Stream Vulnerability Index

[View shared code](https://github.com/CU-ESIIL/Summit_group_2026_13/tree/main/code){
.md-button }

Methods/technologies we are testing:

| Method or technology | What we tested | Early note |
| -------------------- | -------------- | ---------- |
| ...                  | ...            | ...        |
| ...                  | ...            | ...        |
| ...                  | ...            | ...        |
| ...                  | ...            | ...        |

### Challenges identified

- Finding mine permits and extracting geographic information
- Water quality data is sparse

### Visuals

![Method or workflow visual](assets/figures/figure1.png)

### Next Steps

Short term:

Long term:

!!! note "Day 3 Tasks" Sythesis: highlight 2-3 visuals that tell the story; keep
text crisp. Practice a 6-minute walkthrough of the homepage. Why -> Questions ->
Data/Methods -> Findings -> Next

    [Edit content below here in Markdown](https://github.com/CU-ESIIL/Summit_group_2026_13/edit/main/docs/index.md?plain=1#L203){ .md-button target="_blank" rel="noopener" }

## Team Photo { #team-photo }

![Team photo](assets/team/team_photo.jpg)

_Team members and collaborators who contributed to this project._

## Findings at a glance 📣 { #findings-at-a-glance .oasis-report-out-section .oasis-report-out-day3 }

Headline 1 — what, where, how much

...

Headline 2 — change/trend/contrast

...

Headline 3 — implication for practice or policy

...

## Visuals that tell a story 📣 { #story-visuals .oasis-report-out-section .oasis-report-out-day3 }

![Story visual](assets/figures/main_result.png)

_Visual 1: the main pattern or output we want people to remember._

## What’s next? 📣 { #whats-next .oasis-report-out-section .oasis-report-out-day3 }

Short term:

- ...

Long term:

- ...

Who should see this next

- ...

## Cite & Reuse { #cite-reuse }

If you use these materials, please cite:

Summit Team. (2026). _Summit Group 2026 Team 13 — Innovation Summit 2026_.
https://github.com/CU-ESIIL/Summit_group_2026_13

License: CC-BY-4.0 unless noted.
