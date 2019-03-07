+++
type = "itemized"
author = "George Jetson"
date = "2019-01-22"
title = "Job Salary Viz"
description = "Reinforcement Learning."
featured = ""
featuredpath = ""
featuredalt = ""
categories = ["data science"]
linktitle = ""
format = "Golang"
link = "#"
+++


<div>
  <link type="text/css" href="../../css/salary_style.css" rel="stylesheet" />
  <h1>Job Salaries</h1>
  <p>This visualization shows salaries from the past 5 years.</p>
  <p>Salaries are grouped by "experience qualifiers" on the job titles and "no_value" indicates a job has no experience qualifiers.</p>
  <p>The bars show lower quartile, upper quartile, and median. The tooltip gives additional metrics.</p>
  <div id="jobDropdown"></div>
  <div id="stateDropdown"></div>
  <div id="graph"></div>
  <script src="https://d3js.org/d3.v4.min.js"></script>
  <script src="../../js/salary_chart.js"></script>
</div>
