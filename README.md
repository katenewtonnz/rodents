# Mapping Manhattan's Rats

A project to analyse and map NYC 311 complaints about rodent sightings, as part of [Andrew Ba Tran's R for Journalists course](http://learn.r-journalism.com), through the [Knight Center for Journalism](https://knightcenter.utexas.edu/).

This repository contains the data and code I used to make a bar chart and then choropleth of rodent sightings between 2010 and 2018 (ft. bonus Pizza Rat).

- [Data](#data)
- [Analyses](#analyses)
- [Feedback](#feedback)

### Prerequisites

You'll need the latest versions of [R](https://www.r-project.org/) and [R Studio](https://www.rstudio.com/).
This project was created with R version 3.5.1.

## Data: Service_Requests_from_2010-to_Present_rodents.zip

The analysis, chart and map is based on [open-source 311 data](https://nycopendata.socrata.com/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9) collected by the City of New York.
The entire complaints database is ~20GB so the data included in the repo is a zip file of pre-filtered data (selecting 'Rodent' under the 'Complaint Type' variable).
Users wanting to recreate the chart or map using updated data will need to re-filter and download the data from the above link (work in progress sorry- I haven't worked out how to provide a link to the live, filtered data yet).

## Analysis: rodent_data.Rmd and rodent_data.html

R Markdown and html files containing the R code used to import, analyse, chart and map this data.

---

## Feedback

I created this project as a new R user so would welcome feedback on the code or any other aspect of this repo - I'm still learning!
[I'm a journalist at Radio New Zealand (RNZ)](https://www.radionz.co.nz/authors/kate%20-newton) - you can contact me at kate.newton@rnz.co.nz
