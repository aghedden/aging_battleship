# aging_battleship
Data cleaning, wrangling, and analysis code for project examining how aging impacts feedback-based learning from information and reward.

## About the project
This project began as an Honors Thesis at the University of Chicago, where I majored in Neuroscience and Psychology with Honors and graduated *magna cum laude* in 2023. 

Here, we aimed to understand how the ability to learn from informative and rewarding feedback changed across the lifespan. 

I received the following grants/awards to support this project:
- Quad Faculty Research Grant, awarded to connect faculty with talented College students to support their research projects and to develop their research skills
- Earl R. Franklin Research Fellowship, a highly competitive fellowship given by the University of Chicago Psychology Department to support rising fourth-year students’ summer research based on a research proposal, personal statement, transcript, and letters of recommendation; awarded to three students in 2022 
- Jeff Metcalf Odyssey Fellowship Grant (5 separate awards), awarded to support unpaid research and internships conducted during the academic year 

## Files
- `Battleship Dashboard.pdf`: PDF of a static of a dashboard I created in Tableau with some of the study's main findings, specifically through the lens of exploration in the task.
- `aging_bship_main_analyses.Rmd`: An R Markdown file containing the main analyses and visualizations from the study. This is limited to the final set of analyses and visualizations.
- `bs_info_rew_exploration_calcuations.ipynb`: A Jupyter Notebook Python file containing code that calculates reward, information, and Euclidean distance for each tile on a 5x5 grid (25 tiles total) for every choice, within every trial, for each participant and calculates various types of exploration using such values. 
- `bship_mousetracking_wrangling.ipynb`: A Jupyter Notebook Python file containing initial wrangling steps for a complex mousetracking data file. Wrangled to a dataframe containing 11M+ data points.
