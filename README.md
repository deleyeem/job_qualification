# Job Qualification Analysis

## Project Overview
This is the first iteration of a job qualification analysis to apply the visualizations and statistics for one specific cover letter. Note that this was created in a very short duration due to job application time sensitivity.

## Background
This project explores an objective qualitative assessment of my qualifications applying data analytics and data science knowledge.

## Tools and Libraries Used
- Python: For data manipulation and analysis
- Pandas: For handling data structures
- Matplotlib: For creating visualizations
- NumPy: For numerical operations
- SciPy: For numerical operations
- Jupyter Notebooks: Data collection, analysis and visualizations

## Process Description
Step 1: Quantification

First, I extracted the required skills, experience, and desirable qualifications from the job posting. Then, I assigned a numerical weighted criteria to both the qualitative requirements and qualifications to quantify their potential relative importance. This approach allows for a systematic and objective evaluation of candidates. Below is the breakdown of the weighted criteria:

Required Skills and Experience (1-8): Constitute 75% of the total score.
Desirable Qualifications (9-10): Constitute 25% of the total score.
Within each category, it's possible to further assign weights to individual points based on their importance. Each point is weighted equally, with 1-8 being equally weighted due to time sensitivity, and 9-10 equally weighted because they're both desirable but not required.

Step 2: Scoring My Qualifications

I rated my level of qualification for each requirement on a scale (e.g., 0-10, where 10 is fully qualified).

Step 3: Calculate Weighted Scores

Each score was multiplied by its respective weight. For the required skills (1-8), each point receives about 9.375% of the total category weight, while for desirable skills (9-10), each point accounts for 12.5% of the total category weight.

Step 4: Visual Representation - Radar Chart

I created a radar chart to visually represent the raw scores. Each axis represents one of the skills or experiences, and the plotted points reflect my score. This visual displays how well-rounded my skills are in relation to the job requirements. I used the raw scores rather than weighted scores to standardize the radar circle to 10.

Step 5: Statistical Measurements

To incorporate statistical measurements:

Mean: Calculated the average weighted score across all categories to show my overall qualification level.
Standard Deviation: Measured the variance in my scores to highlight strengths (high scores) and areas for development (low scores).
Quartiles: Provided additional insights into the distribution of scores.
Step 6: Visual Representation - Box Plot

I created a Box Plot chart to visually represent the distribution and comparison of both weighted and raw scores.

## Conclusion
The best visualization to use is the radar chart
![Alt Text](url)


## Next Interation
Make this an automated tool I can apply to any job application. 