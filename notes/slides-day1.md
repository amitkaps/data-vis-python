theme: work, 3
slidenumber: true
autoscale: true

[.slidenumber: false]
# [fit] **Data Visualisation**
# *Narrative & Interactive Data-Vis in Python*

*18th & 19th Sept 2019*
*Mumbai, IN*

Workshop Notes: Day #1

<br>

[Amit](https://amitkaps.com) & [Vikrant]()

---

# **Workshop Introduction**

- **Objectives:** Intent & learning outcomes
- **Context:**: Purpose & role of data visualisation, narrative & interactive types, tools & python
- **Approach**: Conceptual & exercise based, group formations 
- **Intros:** Participant & facilitator introductions
- **Expectations**: Alignment & discussion 
- **Checkin**: Python setup and installation readiness

---

# **Objectives**

- Understand the *value of data visualisation* and the role it plays in business analytics and decision making
- Learn the *theory of data visualisation* including grammar, types, color, annotation, flow, animation, interaction etc.
- Build an understanding of *visual perception and cognition* to gain an intuitive sense of how data visualisation work
- Get exposure to tools that can be used to create *data-visualisation in python.*

---

# **Context**

Learn through practice the two contexts in which data visualisation is used with business stakeholders

– *Narrative visualisation* (say, telling a compelling data-story in a presentation)
– *Interactive visualisation* (say, allowing business user to visually explore a complex data-set or a model)

---

# **Approach**

- The workshop is structured with a mix of *conceptual learning* (40%) and *practice sessions* (60%) 
- This is a *hands-on workshop* and we will learn by using *python and notebook*
- There will be a *case-study based approach* - Telco Churn Example - to learn from.
- Each day will have *four main sessions*: see session plan next

---

# **Day 1 Sessions**

- **Workshop Introduction** (0930 - 1000) 
- **Session #1: Value of Data Visualisation** (1000 - 1120)
- Break (1120 - 1140)
- **Session #2: Tools & Abstractions for Data Visualisation** (1140 - 1300)
- Lunch (1300 - 1400)
- **Session #3: Theory of Data Visualisation** (1400 - 1520)
- Break (1520 - 1540)
- **Session #4: Guidelines for Better Data Visualisation** (1540 - 1700) 
- **Day One Summary** (1700 - 1730)
- **Data-Story Group Exercise** (1730 - 1900)

---

# **Day 2 Sessions**

- **Recap & Questions** (0930 - 0950)
- **Data-Story Presentations** (0950 - 1020)
- **Session #5: Crafting Visual Stories with Data** (1020 - 1120)
- Break (1120 - 1140)
- **Data-Story Rework** (1140 - 1210)
- **Session #6: Interactivity** (1210 - 1320)
- Lunch (1320 - 1420)
- **Session #7: Explorable Vis for Business Users** (1420 - 1540)
- Tea Break (1540 - 1600)
- **Session #8: Putting together an Interactive Application** (1600 - 1720)
- **Overall Summary & Way Forward** (1720 - 1800)

---

# **Introduction & Expectations**

- Tell us about yourself
    - Name & Role
    - Experience with Python
    - Experience with Analytics
    - One thing you want to learn from the workshop

---

# **Group Formation**

- Groups of 4 or 5 
- Mixed experience of Python & Analytics
- For the data-story work & presentation

---

# **Installation Check In**

*Workshop Repo*
[https://github.com/amitkaps/data-vis-workshop](https://github.com/amitkaps/data-vis-workshop)

- Did you follow the instruction in the README.md?
- Any issues you faced?

---

# [fit] **Narrative Visualisation**

---

# **#1: Value of Data Visualisation**

---

![](img/warstories.jpg)
### **War Stories &** 
### **Killer Charts**

---

# __**analysis**__
# __**numbers**__
# __**argument**__


---

> *Humans are* 
> __**pattern-seeking**__ 
> __**story-telling**__ 
> *animals.*


---

# ~~analysis~~ __**Synthesis**__
# ~~numbers~~ __**Visuals**__
# ~~argument~~ __**Story**__

---

![fit](img/framework.jpeg)

---

--

# **What is visualisation?**

---

# **Exercise:** Visualise this data in at least 10 different ways - using paper & pen

![inline](img/exercise.png)

---

> _**Visualisation** is the **transformation** of the **symbolic** into **geometric.**_
-- McCormick et al.

---

![inline fit](img/pendulum.gif)

---

## **Start with Data**

![original](img/exercise-00.jpg)

---

## **Identify the Variables**

![original](img/exercise-01.jpg)

---

## **Pick Marks and Scales**

![original](img/exercise-02.jpg)

---

## **Map to Coordinate**

![original](img/exercise-03.jpg)

---

## **Example #1**

![original](img/exercise-04.jpg)

---

![original](img/exercise-05.jpg)

---

## **Vis Examples: 1-5**

![original](img/exercise-04.jpg)

---

![original](img/exercise-05.jpg)

---

## **Vis Examples: 6-10**

![original](img/exercise-06.jpg)

---

![original](img/exercise-07.jpg)

---

## **Vis Examples: 11-15**

![original](img/exercise-08.jpg)

---

![original](img/exercise-09.jpg)

---

## **Vis Examples: 16-20**

![original](img/exercise-10.jpg)

---

![original](img/exercise-11.jpg)


---


![](img/see.jpeg)
## **Learning to See**

---

> _**Visualisation** is the use of computer-generated, **interactive, visual representations** of **abstract data** to **amplify cognition.**_
-- Card, Mackinlay, & Shneiderman

---

# **Types of data visualisation with examples**

  - Explore & Explain 
  - Static & Interactive
  - Analytical & Emotive

--- 

# **Analytics Process, Visualisation & Audience** 

- Linkage with analytical problem solving process: *Why - What - How - So What - So Why*
- Audience needs and understanding: *type, data & visual literacy*
- Engagement in different context: *personal, presentation & participation*

---

![fit](img/analytics-basic.png)

---

# **Analytics Process**

1. **The Why** — Define the Problem
2. **The What** — Frame the Analytical Questions
3. **The How** — Conduct Analytics: Data–Model–Vis
4. **The So What** — Build the Insights
5. **The So Why** — Explain through Narrative

---

![fit](img/analytics.png)

---

# **Visualisation & Analytics**

- *Visual Exploration*: Exploratory Data Analysis
- *Insight Dashboard*: Interactive Visualisation
- *Visual Explanation*: Narrative Visualisation

---

![fit](img/analytics-vis.png)


---

# **Audience Types**

- *Analytics*: Rich data and modelling experience, high comfort with complex usage 
- *Operational*: Mainly metrics driven with detailed drill-down requirements to build understanding
- *Business*: CxO or Business roles, looking for explanation and actions

---

# **Audiences & Participation Mode**

*Visual Exploration*: 
Personal mode with Analytics Audience 

*Insight Dashboard*:
Participative mode with Operational Audience

*Visual Explanation*
Presentation mode with Business Audience

---

# **Four Layers of Visual Abstraction**

- Data Layer
- Visual Layer
- Annotation Layer
- Interaction Layer

---

![](img/layers-00.jpg)

---

# **Data Layer**

Types
- Categorical: Nominal, Ordinal
- Continuous: Temporal, Quantitative

Transforms
- Reshape (e.g. tall <-> wide)
- Aggregation (e.g. bins)
- Basic Stats (e.g. min, max, sum, ...)
- Calculate e.g. New Variables, Window
- Filtering, Sampling
 
---

# **Visual Layer**

- Marks: Points, Ticks, Lines, Bar, Area, Glyphs,
Polygon, ...
- Channels: Position-X, Position-Y, Size, Color, Shape, Path, ...
- Scale: Linear, Log, ...
- Coordinate: Cartesian, Polar, Geo, Parallel
- Layout: Single, Facet, Multi-Chart

---

# **Annotation Layer**

- Title and Labels
- Axis and Tick marks
- Legends
- Grids and Reference Marks
- Text Annotation
- Story Elements

---

# **Interaction Layer**

- Select e.g. Highlight
- Explore & Navigate e.g. Pan, Zoom, Scale, Rotate
- Connect e.g Brushing & Linking
- Filter & Conditions e.g. Dynamic Queries
- Reconfigure e.g. Sorting
- Transition e.g. Scrolling, Layers
- Staging & Animation


---

# **Data Types**

- What are the types of data on which we are learning?
- Can you give example of say measuring temperature?

---

# **Data Types e.g. Temperature**

**Categorical** 
    - *Nominal*: Burned, Not Burned
    - *Ordinal*: Hot, Warm, Cold

**Continuous**
    - *Interval*: 30 °C, 40 °C, 80 °C 
    - *Ratio*: 30 K, 40 K, 50 K 

---

# **Data Types**

**Categorical**
- *Nominal (N)* e.g. OSX, Windows, Android
- *Ordinal (O)* e.g. Good, Better, Best 

**Continuous** 
- *Interval* (zero arbitrary) e.g. 
  -> *Temporal (T)*: dates & time
  -> *Geographic*: latitude & longitude
- *Ratio (Q)* (zero fixed) e.g. length, mass
 

---

# **Data Types: Operations**

**Categorical** 
  - *Nominal*: = , !=
  - *Ordinal*: =, !=, >, <

**Continuous**
  - *Interval*: =, !=, >, <, -, % of diff 
  - *Ratio*: =, !=, >, <, -, +, %

---

# **Data Structures**

- Tabular (2d arrays) e.g. spreadsheet 
- n-Dimension arrays e.g. images, videos
- Hierarchical data e.g. folders of text
- Spatial data e.g. for maps
- ...

---

# **Common Data Types & Structure**

| Matrix |  Example |  Shape                |
|:-------|:---------|:----------------------|
| 2D     | Tabular  | (samples, features)    |
| 3D     | Sequence (Time & Text) | (samples, steps, features)    |
| 4D     | Images   | (samples, height, width, channels)    |
| 5D     | Videos   | (samples, frames, height, width, channels)    |

---

# **#2: Tools & Abstractions for Data Visualisation**

---

# **Tools Abstraction:** 

- Charting vs. Grammar vs. Canvas
- Static vs. Interactive
- SVG vs Canvas vs WebGL Rendering
- Data loading & transformation strategy

---

![fit](img/charting.jpg)

---


![fit](img/pixel.jpg)


---

![fit](img/grammar.jpg)

---


![fit](img/code.jpg)

---

![fit](img/visual.jpg)

---

### **Python Data-Vis Libraries**

![original fit](img/landscape-colors.png)

---

# **Python Libraries**

**Static e.g.**
`matplotlib`, `seaborn`, `pandas`

**Interactive e.g.**: 
`altair`, `bokeh`, `plotly`, `holoviews`


---

# **Rendering Capabilities**

Number of Data Points
— SVG: ~10^3
— Canvas: ~10^4 
— Web.gl: ~10^6

---

# **Exercise**: Start with the small dataset 

- Getting started with Altair
- Let us use the sample dataset 
- Please make at least 2 visualisation from the hand-drawn examples

---

# **Case Introduction**

- Context: Telco Churn Data
- Start with Why & What
- Dataset introduction


---

![fit](img/analytics-basic.png)

---

# **Exercise – Basic Visualisation**

**Create simple static visualisations**
- 1D Continuous 
- 1D Categorical
- 2D Continuous and Categorical 
- 2D Continuous & Continuous
- 2D Categorical & Continuous

---

# **Visualisation Guides**


> _Visualization gives you **answers to questions you didn't know you had.**_
-- Ben Schneiderman


---

![fit](img/questions-0.jpg)

---

![fit](img/questions-1.jpg)

---

# **Who & What**: _Distribution[^1]_

![inline 90%](img/example-distribution.gif)

[^1]: [Capabilities Premium](https://www.strategyand.pwc.com/eref/capabilities_premium_ma/ma-interactive-tool.html?sector=retail)

---

![fit](img/questions-2.jpg)

---

# **How Many**: _Comparison[^2]_

![inline 120%](img/example-comparsion.png)

[^2]: [Working Capital Profiler](...)

---

![fit](img/questions-3.jpg)

---

# **Where**: _Maps[^3]_

![inline](img/wind.gif)

[^3]: [Wind Map](http://hint.fm/wind/gallery/oct-30.js.html)

---

![fit](img/questions-4.jpg)

---

# **When**: _Timeline[^4]_

![inline fit](img/meat.jpg)

[^4]:[New York Times](https://archive.nytimes.com/www.nytimes.com/imagepages/2011/03/15/science/15food_graphic.html)

---

![fit](img/questions-5.jpg)

---

# **How**: _Relationship[^5]_

![inline](img/the_color_of_notes.gif)

[^5]: [Amit Kapoor](https://amitkaps.com/data-portraits)

---

![fit](img/questions-6.jpg)


---

# **Why**: **Deduction & Prediction[^6]**

![inline ](img/example-prediction.gif)

[^6]: [Mike Bostock](https://bost.ocks.org/mike/nations/)

---

![fit](img/questions-6.jpg)

---

# **Guide to choosing appropriate visualisation**

**FT Visual Vocabulary**
[ft.com/vocabulary](http://ft.com/vocabulary)

**Vega-lite version**
[gramener.github.io/visual-vocabulary-vega/](https://gramener.github.io/visual-vocabulary-vega/)

---

![fit](img/visual-vocabulary.jpg)

---

#  **Exercise - Purpose:** 

**Creating visualisation with purpose & objective**
- Distribution
- Ranking
- Magnititude
- Correlation

---

# **#3: Theory of Data Visualisation**

---

> "We do data visualisations to _**learn**_ something new, not just to _**confirm**_" 
-- Edward Tufte

---

# **Encoding Grammar** 

**Deep dive into the grammar of graphics**
- *Data*: wide tabular, long tabular
- *Transform*: bin, sort, filter, calculate, age
- *Mark*: symbol-type, length-type, area-type
- *Channels*: X, Y, size, colour, shape, text
- *Scales*: continuous, discrete, discretising
- *Guides*: axis, legends, labels
- *Coordinates*: cartesian, geographic

---

# **Exercise – Encoding** 

Encode the telco churn data visualisation using different marks & channels
- Alternate mark representation
- Alternate channel choices

---

# **Decoding Principles** 

Understand how *visual perception* works 
- Gestalt & visual perception
- Ranking of channel effectiveness & efficiency

Apply to *select appropriate visualisations*
- Error in decoding & empirical evidence

---

# **Exercise – Decoding** 

Visualisation decoding critique and improving an existing visualisation
- Alternate transformation & representations
- Alternate scale representations

---

# **#4: Guidelines for Better Data Visualisation**

---

# **Concept – Enhancing Visualisation** 

Guidelines for enhancing static data visualisation 
- Comparing & sorting
- Add encoding variables
- Optimal scales & reference lines
- Layering & facets
- Over-plotting reduction

---

# **Exercise – Enhance**

Enhancing an existing static visualisation in python

- Adding facets & layers exercise
- Handling over-plotting reduction

---


# **Concept – Color & Guides** 

Effective use of color & guides in data visualisations
- Chart junk & data-ink ratio
- Guidelines on axes and legends
- Color for categorical & continuous encoding
- Aesthetics & theming to have consistent style

---

# **Exercise – Redesign** 

Redesign of an existing visualisation to improve guides, color & aesthetics


---

# **Narrative Group Exercise** 

---

# **Data-Story Exercise**

**Building narrative with purpose & audience context**
- To prepare a three-slide data-visual-story to be presented tomorrow morning.
- Presentation timing is 2 mins
- Groups to get started on the assignment

---

# **Day One Summary** 

- Recap of day one concepts and lessons
- Set the context for day two sessions
- Questions & Answers on Day 1 scope

---

# **Day 2 Sessions**

- **Recap & Questions** (0930 - 0950)
- **Data-Story Presentations** (0950 - 1020)
- **Session #5: Crafting Visual Stories with Data** (1020 - 1120)
- Break (1120 - 1140)
- **Data-Story Rework** (1140 - 1210)
- **Session #6: Interactivity** (1210 - 1320)
- Lunch (1320 - 1420)
- **Session #7: Explorable Vis for Business Users** (1420 - 1540)
- Tea Break (1540 - 1600)
- **Session #8: Putting together an Interactive Application** (1600 - 1720)
- **Overall Summary & Way Forward** (1720 - 1800)
