---
layout: post
title:  "Job Search and my findings"
date:   2024-11-10 
categories: jekyll update
permalink: /post1/
---

In the middle of 2024, I was looking for a new job opportunity in the field of Data Science / Analytics and collected plenty of interesting data on the jobs available at that point. As a result, I produced some interesting visualisations on this topic that could be interesting to those interested to apply to a Data Scientist position.

# Application statistics

First, some facts on the application process:
- When I started applying, I was 27 years of age, with roughly 3 years of mixed experience in Data Science and Analytics;
- I have a BSc in Nutrition and MSc in Biotechnology (Bioinformatics);
- Over a period of 01.05.2024 - 16.07.2024 (roughly **2.5 months**), I made a total of **501 job applications**.

# Job application website

<!-- <img src="{{ site.url }}/images/241110_job_search/241110_job-application-source.png" width=700 style="display: block; margin: 0 auto"> -->

<!-- <img src="/images/241110_job_search/241110_job-application-source.png" width=700 style="display: block; margin: 0 auto"> -->

<img src="/images/241110_job_search/241110_job-application-source.png">

<!-- ![](/images/241110_job_search/241110_job-application-source.png) -->

<!-- ![Replica logo]({{ '/images/241110_job_search/241110_job-application-source.png' | relative_url }}) -->

<!-- ![image](/images/241110_job_search/241110_job-application-source.png) -->

<!-- ![alt text]({{ site.url }}/assets/images/job-application-source.png) -->

# Job titles

The titles of the jobs I applied for can be seen in the Word Cloud below. Please note that the original diversity was reduced by removing the following keywords from the titles:
- Removed mode of work: hybrid, remote, on-site
- Removed location: Mexico, Santa Fe, MX
- Split numerous keywords into split ones, e.g. `Data Analyst with Power BI" into "Data Analyst" and "Power BI"
- Skill-related keywords, such as "bilingual", "python", "SQL", into a separate word cloud.

<img src="/images/241110_job_search/word-cloud-1.png">

Here is the word cloud for the proficiencies / skills mentioned in the job titles: 

<img src="/images/241110_job_search/word-cloud-2.png" style="display: block; margin: 0 auto">

# Work mode and location

The applied jobs were roughly equally mixed in their work modality:

<img src="/images/241110_job_search/work-mode.png" style="display: block; margin: 0 auto">

As for the location of the job postings, most of those that I applied for were in Mexico city:

<img src="/images/241110_job_search/job-location.png" style="display: block; margin: 0 auto">

# Salary and experience

For the jobs below, although some specify the salary in netos (i.e. after the taxes), the majority do not specify whether it's brutos or netos or say brutos, so we count it as brutos. 

Median was considered to account for extreme salaries offered for each level (note: changing the frequency metric to “average” does not change the plot too much). 
Here we can see that, not considering cases when experience is not specified, when salary is specified it is mostly for 3 years of experience. Many job postings would post their salary as “competitive”, but I would argue that for each year of 3experience it should be at least this. Median 


<img src="/images/241110_job_search/salary-experience.png" style="display: block; margin: 0 auto">

# Application outcomes

Here is the Sankey diagram of the application progress. 
- Approximately 90% of the times the recruiters did not respond;

<img src="/images/241110_job_search/sankey.png" style="display: block; margin: 0 auto">

> Apart from the activities outlined in the diagram above, I also had to take 10 online tests that on average lasted 25 minutes.

# Take-home lessons

There are different things I learned from this experience. 

Bad things:
- For the majority of applications, likely you will not get a reply;
- Recruitment in middle - and large-sized companies can take a very long time - months - so be patient

Good things:
- Excellent benefits: for big companies looking for 3+ years of experience, the benefits have been consistently good

Most important skills: 
- Python
- SQL
- general ML
- Working with cloud-based servers, such as Google Cloud, Azure, or AWS

# Note

I made the visualisations in Power BI. The word cloud was made on [this free website](https://worditout.com/word-cloud/create). The Sankey Diagram was [made here](https://sankeymatic.com/build/). 
