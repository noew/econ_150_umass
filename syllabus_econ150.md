# Introduction to Data Science for Economics

**ECON 150 | Fall 2026**

*Instructor: Noé M. Wiener*

---

University of Massachusetts Amherst

### Course Details

| | |
|---|---|
| **Class time** | Tuesday & Thursday 2:30PM - 3:45PM |
| **Class location** | Morrill 1, Room N345 |
| **Credits** | 3 |
| **Instructor** | Noé M. Wiener ([nwiener@umass.edu](mailto:nwiener@umass.edu)) |
| **Office** | Gordon Hall, room 222 |
| **Student hours** | After class, and Wednesdays 1pm-3pm via video conference (sign-up link on Canvas) |

---

## COURSE DESCRIPTION (CATALOG)

This course introduces students to the concepts and practice of data science with special attention to economic applications. The class aims to prepare students to critically understand the collection, storage, retrieval, merging, tabulation, and presentation of quantitative data. Applying data science to social and economic analysis allows for the understanding and critiquing of the application of data science to social and economic problems. Focus will be on understanding the sources and quality of data and the relevance of decisions about data that is used. We will discuss and analyze case studies of particular data applications to illustrate the usefulness of the methods and to place data analysis within a political and normative context.

**Prerequisites:** None. This course is designed for students with no prior experience in data science or programming.

---

## LEARNING GOALS

Upon completion of this course, you will be able to:

- Identify and critically evaluate sources of economic and social data
- Explore and wrangle data (retrieve, clean, merge, and manage datasets)
- Recognize ethical and political dimensions of data collection, analysis and presentation
- Apply data science methods to real-world economic and social problems
- Communicate insights to different audiences in writing and using data visualizations
- Manage projects and computer code with a focus on reproducibility
- Collaborate effectively in a team-based data science workflow

---

## ASSESSMENTS

The grade for the class is based on the following elements:

| Assessment | Percent of Final Grade |
|---|---|
| Exit Tickets & In-Class Work | 20% |
| Pop Quizzes | 15% |
| Individual Worksheets | 35% |
| Group Data Project | 30% |

---

### Exit Tickets & In-Class Work

Regular attendance and active participation in class discussions are essential. We will frequently discuss case studies and debate the merits and limitations of data science applications in economics and public policy. Your thoughtful engagement in these discussions, along with completion of in-class coding exercises and activities, contributes to this portion of your grade.

On most class days, you will submit a brief response or your work-in-progress via Canvas before leaving. Prompts will vary. These are graded on a Complete/Incomplete basis, and you may miss up to 3 without penalty. No make-up tickets are offered; if you are absent, that day counts as one of your drops.

I reserve the right to also include active, respectful engagement with case study discussions and class debates as part of the grade.

---

### Pop Quizzes

Pop quizzes assess conceptual understanding through short multiple-choice, matching, and numeric fill-in questions. The quizzes will be in-person, using pen and paper. No electronic devices will be permitted during the quiz. There will be approximately 6 quizzes across the semester. The lowest 2 quiz scores will be dropped. No make-up quizzes will be offered.

---

### Individual Worksheets

Four worksheets combine conceptual questions with applied coding exercises, aligned with the major course units. These assignments deepen your understanding of data science principles and how they apply to economic problems. Each worksheet includes both written components and R coding work submitted as rendered Quarto HTML documents.

| Worksheet | Topic | Due Date |
|---|---|---|
| WS 1 | Getting started | Sept 20 |
| WS 2 | Visualization | Oct 4 |
| WS 3 | Data Wrangling | Oct 27 |
| WS 4 | Data Recoding & Modeling | Nov 20 |

**Grading:** Each worksheet is graded using a rubric evaluating (1) code correctness and reproducibility, (2) written explanations and interpretation, and (3) presentation and communication. Submissions must render as Quarto HTML. If your document does not render, it cannot receive full credit.

You are encouraged to collaborate with classmates on worksheets, but your submission must be your own work. 

---

### Group Data Project

This project allows you to identify an economic or social problem, locate and evaluate relevant data, and conduct a preliminary analysis. You will work in small groups of 3-4 students. The project unfolds across several milestones throughout the semester. Groups will be formed in **Week 3**. During group formation, each team will complete a **Team Charter** establishing roles, expectations, and communication norms.

#### Project Milestones

| Milestone | Due Date | Weight | Description |
|---|---|---|---|
| **Team Charter** | Oct 1 (Week 4) | 5% | One-page document: research interest, team roles, norms, and communication plan |
| **Data Proposal** | Oct 15 (Week 6) | 5% | 1-2 pages: research question, proposed data sources and feasibility assessment |
| **Progress Check-in** | Nov 5 (Week 9) | 5% | Submit at least one preliminary visualization |
| **Presentation** | Dec 15 | 15% | Present & submit your interactive report |

#### Accountability & Individual Adjustment

At the end of the semester, each group member will complete a confidential **peer evaluation** of their teammates adherence to the team charter. Individual project grades may be adjusted by up to 1 full letter grade (upwards or downward) based on these evaluations. Students who do not abide by the team charter will not receive the same grade as their teammates.

---

### Extra Credit: Canvas Q & A Forum Contributor (up to 5 points)

Students who are the **first to respond** with high-quality answers to peer questions on the Canvas Q & A forum may earn up to **5 points of extra credit** added to their final point total (out of 100). Credit is at the instructor's discretion; quality matters more than quantity.

---

## RESOURCES

### In-Class Coding Sessions

Many classes will include time for working through coding exercises. Bring a fully-charged laptop to every class.

### Office Hours

I hold regular office hours on Wednesday afternoons via video conference software. These are ideal for asking questions about the class, getting help with problem sets, or troubleshooting coding challenges. *Please register at least 2 hours before the start of my office hours using the sign-up link on Canvas.*

### Free Statistical Software

You will need to install the following free software on your own laptop:

- **R**, a system for statistical analyses and graphics. This is like the *engine* of our car.
- **RStudio**, an integrated development environment (IDE), which provides an interface for working with R. This is like the *dashboard* of our car.

Instructions on downloading and installing these tools on your computer can be found on Canvas.

### Readings

The main readings for this class are drawn from two free online textbooks:

- (**R4DS**) *R for Data Science*, Wickham & Grolemund, [r4ds.hadley.nz](https://r4ds.hadley.nz)
- (**IMS**) *Introduction to Modern Statistics*, Çetinkaya-Rundel & Hardin, [openintro-ims.netlify.app](https://openintro-ims.netlify.app)

Additional readings are linked below and on Canvas. 

---

## CLASS SCHEDULE

### Unit 1: Getting Started (Sep 8–17)

| # | Date | Topic | Readings |
|---|------|-------|----------|
| 1 | Sep 8 | Welcome to Data Science for Economics | — |
| 2 | Sep 10 | Meet the Toolkit | [R4DS Intro](https://r4ds.hadley.nz/intro.html) · [IMS Ch. 1](https://openintro-ims.netlify.app/data-hello) |
| 3 | Sep 15 | What Is Data? Observations, Variables & the Politics of Measurement | [NYT: American Puzzle](https://www.nytimes.com/interactive/2023/10/16/us/census-race-ethnicity.html) |
| 4 | Sep 17 | *Lab:* Reproducible Workflow | [R4DS Ch. 6](https://r4ds.hadley.nz/workflow-scripts.html) · [R4DS Ch. 28](https://r4ds.hadley.nz/quarto.html) |

---

### Unit 2: Visualizing Data (Sep 22–Oct 1)

| # | Date | Topic | Readings |
|---|------|-------|----------|
| 5 | Sep 22 | Introduction to Data Visualization | [R4DS Ch. 1](https://r4ds.hadley.nz/data-visualize.html) |
| 6 | Sep 24 | Visualizing Numerical & Categorical Data | [IMS Ch. 4](https://openintro-ims.netlify.app/04-explore-categorical) · [IMS Ch. 5](https://openintro-ims.netlify.app/05-explore-numerical) |
| 7 | Sep 29 | Effective Data Visualization: Storytelling vs Misrepresentation | [IMS Ch. 6](https://openintro-ims.netlify.app/explore-applications) |
| 8 | Oct 1 | *Lab:* Redlining, Maps & Geospatial Data | — |

---

### Unit 3: Data Gathering & Wrangling (Oct 6–Nov 10)

| # | Date | Topic | Readings |
|---|------|-------|----------|
| 9 | Oct 6 | Data Wrangling: Working with a Single Data Frame | [R4DS Ch. 3](https://r4ds.hadley.nz/data-transform.html) |
| 10 | Oct 8 | Data Wrangling: Single Data Frame (continued) | — |
| 11 | Oct 13 | Tidy Data: Introduction to Pivoting and Reshaping | [R4DS Ch. 5](https://r4ds.hadley.nz/data-tidy.html) |
| 12 | Oct 15 | Tidy Data: Time Series & Panel Data | [R4DS Ch. 17](https://r4ds.hadley.nz/datetimes.html) |
| 13 | Oct 20 | Working with Multiple Data Frames | [R4DS Ch. 19](https://r4ds.hadley.nz/joins.html) |
| 14 | Oct 22 | *Lab:* Joins & Ethics of Data Consolidation | [Ayoub (2026)](https://www.brennancenter.org/our-work/research-reports/dangers-trump-administrations-data-consolidation-efforts) |
| 15 | Oct 27 | Data Types & Classes | [R4DS Ch. 16](https://r4ds.hadley.nz/factors) |
| 16 | Oct 29 | Data Import, Recoding & Cleaning | [R4DS Ch. 7](https://r4ds.hadley.nz/data-import.html) |
| — | Nov 3 | *Election Day — No Class* | — |
| 17 | Nov 5 | Data Recoding & Cleaning; Text-as-Data | [R4DS Ch. 14](https://r4ds.hadley.nz/strings.html) |
| 18 | Nov 10 | *Lab:* Wrangling & Visualizing our Time-Use Survey | — |

---

### Unit 4: Modeling, Prediction & Algorithmic Fairness (Nov 12–Dec 1)

| # | Date | Topic | Readings |
|---|------|-------|----------|
| 19 | Nov 12 | Modeling: Trend Lines as Summaries | [IMS Ch. 7](https://openintro-ims.netlify.app/07-model-slr) |
| 20 | Nov 17 | Modeling: Shapes of Relationships | TBD |
| 21 | Nov 19 | Scientific Studies, Confounding & Simpson's Paradox | [IMS Ch. 2](https://openintro-ims.netlify.app/02-data-design) |
| 22 | Dec 1 | *Lab:* Algorithmic Decision-Making & Fairness *(classes resume)* | [ProPublica, "Machine Bias" (2016)](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing) |

---

### Unit 5: Communicating Results with Interactive Dashboards & Reports (Dec 3–15)

| # | Date | Topic | Readings |
|---|------|-------|----------|
| 23 | Dec 3 | Interactive Data Visualization | TBD |
| 24 | Dec 8 | Generating Interactive Reports | — |
| 25 | Dec 10 | Work on group projects | — |
| 26 | Dec 15 | Presentations *(last day)* | — |

---

## CLASS POLICIES

1. Do not ridicule, use derogatory language, or intimidating behavior.

2. Do not record what takes place in this class and publish it elsewhere (which is a violation of Massachusetts Recording laws). What we say in person or on Canvas remains in our class.

3. University policies regarding Accommodations, Academic Honesty, and Title IX apply to all courses. The policies can be found [here](https://www.umass.edu/senate/book/non-responsible-employee-required-syllabus-statements).

### Communication Expectations

- *Please post any questions to the Q & A forum on Canvas*. You are likely not the only person with this question, and others will benefit from the answer. (Note: High-quality first responses to peer questions are eligible for extra credit.)
- If you have personal questions or concerns that you would rather not share with the class, you are of course welcome to email me. In this case, please include "ECON 150" in the subject line.

### Attendance Policy

**Class attendance:**

While attendance is not explicitly graded as a standalone category, regular attendance is essential for success. Class discussions involve analyzing real case studies and debating the merits and limitations of data applications. Additionally, many classes include hands-on coding practice that cannot be easily made up. Missing more than 3 classes will result in a deduction from your participation grade.

**If you need to miss a class:**

- Review the posted slides and materials on Canvas.
- Check Canvas for any announcements or updates.
- Reach out to a classmate for notes.
- After reviewing materials on your own, come to office hours if you have questions about missed material.
- Please do not email me to ask if you've missed anything important. 

### Late Work Policy

- Worksheets are due on the stated due date via Canvas (rendered Quarto HTML).
- Late submissions will be penalized 10% per day, up to a maximum of 3 days late. After 3 days, submissions will not be accepted without prior arrangement.
- Project milestones (charter, proposal, report, presentation) have firm deadlines. Contact me immediately if your group foresees any difficulty meeting these deadlines.
- Peer reviews submitted late will receive a grade of zero, as delayed feedback has no value to the recipient.

### Group Work Policy

Data science is collaborative work. In this course, your group project requires meaningful contribution from all members. The following expectations apply:

- All group members are expected to contribute equitably to every milestone.
- If a group is experiencing difficulties (e.g., a member is unresponsive or not contributing), contact me as early as possible. Do not wait until the end of the semester.
- Confidential peer evaluations at the end of the term will be used to adjust individual grades.

### Acceptable Use of Large Language Models / Chatbots

We are at a very early stage of understanding how best to use Large Language models (LLMs) in teaching and learning. It seems clear that there are benefits, but also substantial downsides to using LLMs in your education (wrong answers, "hallucinations", undermining of learning). In our class, we will adhere to the following rules:

- If you choose to use an LLM for a *permitted* assignment, you need to include a prominent acknowledgment section at the end of your document. In this section, you need to specify *how* you have used the LLM in your assignment. For example: "I used ChatGPT to generate initial R code for data cleaning, which I reviewed, debugged, and modified. I take full responsibility for all final code and results."
- LLMs may *not* be used during in-class quizzes.
- LLMs should not be used to generate written explanations that you submit as your own work without significant modification and acknowledgment.
- When in doubt, ask me.

### Accessibility & Accommodations

If you have a documented disability and require academic accommodations, please register with the Disability Services office *as soon as possible*. I am committed to providing an inclusive learning environment.

### Disruption-Resilient Instruction

Should circumstances require that this course be moved to remote delivery, we will continue to use Canvas for communication and sharing of course content. Lectures will be made available as pre-recorded videos for asynchronous viewing, and Zoom may be used for optional synchronous sessions during scheduled class time.

### Disclaimer

My lectures and course materials, including presentation slides, videos, assignments, datasets, and similar materials, and all course recordings, are protected by U.S. copyright laws and by university policy (unless otherwise noted, see below). I am the exclusive owner of the copyright in materials I create. You may take notes and make copies of course materials for your own use in this class. You may also share those materials with another student who is registered and enrolled in this course. You may NOT reproduce, distribute, upload, or display any lecture notes or recordings or course materials in any other way — whether or not a fee is charged — without my express written consent. If you do so, you may be subject to disciplinary action under the UMass Code of Student Conduct. Similarly, you own the copyright to your original projects and exam responses.

Parts of the course curriculum is adapted from [Data Science in a Box](https://datasciencebox.org). Those materials and ideas are [Creative Commons Attribution-ShareAlike International](https://creativecommons.org/licenses/by-sa/4.0/) licensed. 

---

## GRADING THRESHOLDS

Final grades will be assigned according to the thresholds below. Extra credit points are added to the final point total before applying these thresholds. There will be no rounding up (or down).

| Letter Grade | Point Range |
|---|---|
| A | 93–100+ |
| A- | 90–92.99 |
| B+ | 87–89.99 |
| B | 83–86.99 |
| B- | 80–82.99 |
| C+ | 77–79.99 |
| C | 73–76.99 |
| C- | 70–72.99 |
| D+ | 67–69.99 |
| D | 60–66.99 |
| F | 0–59.99 |