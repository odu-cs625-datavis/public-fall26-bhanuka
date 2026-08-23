# Semester Project

**Due:** Thursday, October 15 by 11:59pm

The main goal of the project is for you to apply your theoretical knowledge in a creative effort. Your final deliverable will be a single, static explanatory visualization that communicates an interesting insight. In this [blog post](https://ws-dl.blogspot.com/2025/01/2025-01-06-data-visualization-class.html), Dr. Weigle has included three student projects from Fall 2024, which you may use for inspiration. There are more examples available under [Combining Datasets in Visualization](combining-datasets.md) as well. 

The project has two milestones in addition to the final visualization. You will receive feedback for each milestone that can be applied to next iteration of your project. The milestones are required and will be part of your final score for the project grade. 

The final submission of your project must include the completed visualization, a demo video, and a written report for your visulization. 

As the final task, you will have to review and provide feedback on atleast three projects. Your review can be a limitation about the visualization, potential improvement, alternative design, ask a question, etc. The peer review component is a part project requirements and will also count towards your final project grade. 


|Milestone|Main Tasks|Deadline|
|---|---|---|
|1|choose your topic, potential datasets, brainstorm interesting questions|Sunday, September 12|
|2|explore data, discover interesting finding, sketch proposed final charts|Sunday, October 04 |
|Final|final chart, video, and report|Thursday, October 15|
|Peer Review|comment/feedback on classmates' projects|Friday, October 16|


The full semester project is due Thursday, October 15 by 11:59pm.

Here are general guidelines, and I will post detailed requirements throughout the semester:

* This is an individual assignment. No group work allowed.
* You may use any tool of your choice to perform your *data cleaning and exploratory analysis*.
* If you are a Computer Science student, you must use either Python or Vega-Lite to build your final chart. Otherwise, you may use any tool of your choice to build your final chart.
* The goal is to present your findings about your chosen topic. Although you may do exploratory analysis to understand your data, your visualization should focus on showing the audience what you learned.

Because you will be building a static chart, there will be an emphasis on your attention to detail. I expect to see high-quality charts produced in this project.

## Milestone 1 - Topic/Datasets/Questions

In this first step of the project, you will choose a topic and dataset and brainstorm questions to explore about the data. To submit this milestone, you will post in a Canvas Discussion Board so that you and your classmates can provide feedback on each others' work.

**Topic Selection:**  Since you can ask better questions about data you know about, you should pick a topic that you have some knowledge about or that you are personally interested in learning more about. If you have taken CS 620/DASC 620 (Intro to Data Science), you may use the same topic/dataset from your final project if it is appropriate.

This is also an opportunity to use ChatGPT or other GenAI tool to help you brainstorm ideas and/or learn more about your topic.  As an example, I used the following prompts on the topic of climate change:

* `Help me brainstorm about visualization project topics related to climate change.`
* `Where can I find data about oceans and acidifcation?`
* `What are some climate factors that could affect ocean acidification?`

You can view the full conversation at <https://chat.openai.com/share/51344d2f-fc7c-4325-b245-8d82592cd8e0>.

**Data Sources:** [Data Sources](data.md) contains links to several public data sources. Be careful about the size of the dataset. You probably want on the order of 100s-1000s of items rather than millions.

**Questions:** Propose at least 2 questions about your topic that you could answer via visualization. For each question, state one or more hypotheses of what you might find in the data. (It doesn't matter if they turn out to be true or not.)

Good questions may involve data from multiple data sources or comparisons between attributes in a large dataset, looking for correlations or patterns in the data. For example, "[How have CO2 levels and air temperature changed over time?](http://coastalslr.blogspot.com/2018/01/sea-level-rise-for-hampton-roads-2017.html)" or "What has been the main factor in winning percentage for the top 25 college football teams -- total yards offense per game, total turnovers per game, passing yards per game, or rushing yards per game?". These should be non-trivial questions that could lead to further questions, like "why is there a difference?". Make sure that the questions are ones that would be appropriate for visualization. For example, "What is the ODU football team's highest winning percentage?" is just a matter of sorting and can be answered without visualization. See [Examples of Combining Datasets in Visualizations](combining-datasets.md) for more examples.

### Submission

See the [Project Milestone 1 - Topic](https://canvas.odu.edu/courses/212983/discussion_topics/1685979) Discussion Board for the items required for submission.

## Milestone 2 - Data Exploration/Interesting Finding/Sketch Charts

**Data Exploration:** After choosing your topic and initial questions, you should start exploring your data. You may want to use exploratory data analysis (EDA) techniques that you have learned in this and other classes. Through this exploration, you should be narrowing down and refining your initial questions into *a single question* that can be addressed in your visualization. 

**Interesting Finding:** During your EDA process, you may create intermediate charts to help you analyze the data. Through this, you should narrow your focus on discovering an interesting finding that you can present through a chart.

**Sketch 2 Charts:** After you have performed EDA on your data and have discovered your interesting finding, sketch *at least 2 potential charts* that could illustrate your finding. The charts should be different idioms to allow you to evaluate which will end up being the most effective representation. Your sketches should include labels, annotations, etc. The data lines/points don't need to be exact, but I want to see a full version of what you are thinking to implement in your sketches. These sketches should preferably be done on paper, but you may use a simple drawing tool as well. At this point, I *do not* want to see charts created by any tool like Excel, Tableau, or any code. 

*If through your EDA process you decide that your chosen dataset/topic is not appropriate, you may change your dataset or topic at this stage, but you must go back and complete Milestone 1 for the new dataset/topic before continuing.*

### Submission

See the [Project Milestone 2 - Sketches](https://canvas.odu.edu/courses/212983/discussion_topics/1685978) Discussion Board for the items required for submission.


## Final Chart

Use principles from data journalism/storytelling to implement and refine **one of your proposed charts** from Milestone 2.  You *must* include a headline that summarizes the main finding of your chart (as opposed to a title that only describes your chart) and appropriate axis labels. You are strongly encouraged to include annotations or context as needed.  This will be your final chart, so care should be taken in choosing fonts, colors, and other design/aesthetic aspects.

This final chart is to be a *single chart*. The goal is to have an explanatory visualization that showcases your interesting finding to the viewer. This is *not* meant to provide an exploratory view of your data. 

Reminder: Students in the Computer Science MS or PhD programs must use either Python or Vega-Lite to implement their final chart.

### Demo Video

Create a short demo video where you walk through and explain your final visualization. You should point out the question you are addressing and how the visualization idiom you chose helps to answer the question and highlights your interesting finding.  Point out interesting aspects of your visualization and mention any parts that you are particularly proud of (for example, if there was something difficult that you figured out how to implement).  This demo video should be at most 5 minutes long and will be shared with your classmates (see [Submission](#submission) for instructions).

### Report

As always, I expect your report to include your name, CS625, date, and appropriate headings and Markdown markup for clarity and neatness. You will lose points if there are many spelling or grammatical errors.

Your report, named `project-report.md`, should include the following information:

* a brief description of your chosen dataset(s) (including link to the original source of the data)
* final question that you addressed / interesting finding that you discovered
* appropriately-sized image of your final chart
* link to your final chart (similar to Homework 3, include whatever links or files are needed to view the implementation of your final chart)
* explanation of how your final chart answers the question and how your headline fits your chart
* "Final Thoughts" section that provides a commentary on the development process, including roughly how much time you spent developing your visualization and what aspects took the most time
* "References" section that includes links to any examples and references that you used in completing this assignment

### Submission

You should be working in the private GitHub repo that was created for you in the odu-cs625-datavis organization. If you are working locally, make sure that you have committed and pushed your local repo, including any images you reference, to GitHub.

Submit the URL of your report (not the URL of your repo) in Canvas under [Semester Project](https://canvas.odu.edu/courses/212983/assignments/3335616).  *If you make changes to your report after submitting in Canvas, we will use the last commit time in your repo as your assignment submission time.*

Submit the URL of your demo video in the [Project Demo Videos Discussion Board](https://canvas.odu.edu/courses/212983/discussion_topics/1685977). In your reply, note if the video is publicly available (e.g., via YouTube) or if it requires an ODU login (e.g., ODU Zoom video published via Panopto or in ODU OneDrive).

*By Friday, October 16 at 11:59pm, you must have provided some constructive feedback in the Discussion Board regarding at least three of your classmate's videos.*