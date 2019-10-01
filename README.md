# Regional Solicitation Congestion Analysis

## Background
The Regional Solicitation is a process that the Metropolitan Council (the metropolitan planning organization for the 7-county Minneapolis-St. Paul region) leads every 2 years, when the Council is responsible for disbursing $2 million in federal funds to transportation projects.  At the beginning of the Solicitation cycle, jurisdictions (generally cities/townships or counties) apply for funds for a project (or projects).  Their proposed (or in-process) project is then scored on a number of metrics.  One of the metrics is the most excessive congestion seen on the road segments of the proposed project.  This repo contains scripting to analyze Streetlight Data from a Congestion Analysis project to obtain the most congested speed on the segment at any time (weekend or weekday) and compare it to the free flow (reference or off-peak) speed (defined as 12am-6am) of that segment.  These speeds are then input into an online application from which Solicitation applicants are instructed to obtain the information during the course of their application.

## Required libraries
*data.table
*tidyverse
*plotly
*extrafont
*sf
*leaflet