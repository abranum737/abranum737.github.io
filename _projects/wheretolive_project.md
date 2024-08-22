---
layout: page
title: Where to Live
description: PowerBI dashboard exploring living locations
img: assets/img/4.jpg
importance: 3
category: work
related_publications: false
---

# Where to Live Dashboard

This dashboard provides insights into various factors to consider when choosing where to live such as college ranking, rental data, weather, and recreation.

<div style="position: relative; padding-bottom: 47.48%; height: 0; overflow: hidden;">
  <iframe title="Where to live" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://app.powerbi.com/reportEmbed?reportId=b3f99e25-36de-479f-9fc7-d6ff8e2c640c&autoAuth=true&ctid=83ff14a6-eb6b-4250-b745-21bea66253dc" frameborder="0" allowFullScreen="true"></iframe>
</div>

## About This Dashboard

<p>This dashboard offers a comprehensive view of universities across the United States, complemented by state-specific demographic, weather, and recreation information.</p>

<h3>Main Dashboard View</h3>
<ul>
  <li><strong>U.S. Map:</strong>
    <ul>
      <li>States colored by university density</li>
      <li>Click on a state to filter data</li>
      <li>Hover over a state to access detailed state information</li>
    </ul>
  </li>
  <li><strong>University Table:</strong>
    <ul>
      <li>Columns: Rank, Name, Tuition Cost, Enrollment, Location, Description</li>
      <li>Filterable by college ranking slider</li>
    </ul>
  </li>
</ul>

<h3>State-Level Information (Drill-Through)</h3>
<ol>
  <li><strong>Demographic Data by City:</strong>
    <ul>
      <li>Average rent</li>
      <li>Average income</li>
      <li>Male and female age distributions</li>
      <li>City slicer for specific views</li>
    </ul>
  </li>
  <li><strong>Weather Information:</strong>
    <ul>
      <li>Yearly average temperatures</li>
      <li>Number of drought-affected counties over time (where available)</li>
      <li>Total water area in square miles</li>
    </ul>
  </li>
  <li><strong>National Parks Data:</strong>
    <ul>
      <li>Total number of parks in the state</li>
      <li>Total area of parks in km²</li>
      <li>List of individual park names and their acreage</li>
    </ul>
  </li>
</ol>

<p>This interactive tool enables users to explore relationships between university locations, state demographics, climate conditions, and recreational opportunities. It provides valuable insights for students, researchers, and anyone interested in U.S. education and state-level data analysis.</p>

## Data Source

This dashboard uses data from the following Kaggle dataset:

US Drought Monitor. (2023). United States Droughts by County. Kaggle. https://www.kaggle.com/datasets/us-drought-monitor/united-states-droughts-by-county
The dataset provides weekly drought information for every county in the United States from 2011 to 2023. It includes data on drought severity levels, affected population, and more.

TheDevastator. (2023). National Universities Rankings: Explore Quality Through Data. Kaggle. https://www.kaggle.com/datasets/thedevastator/national-universities-rankings-explore-quality-t
This dataset provides comprehensive information on national university rankings, including factors such as tuition, enrollment, acceptance rates, and various quality indicators. The data is sourced from the 2022-2023 US News National University Rankings.

TheDevastator. (2023). The United States National Parks. Kaggle. https://www.kaggle.com/datasets/thedevastator/the-united-states-national-parks
This dataset provides comprehensive information about the United States National Parks, including details such as park names, locations, establishment dates, areas, and visitor statistics. The data offers insights into the diverse natural heritage preserved within the U.S. National Park System.

Berkeley Earth. (2023). Climate Change: Earth Surface Temperature Data. Kaggle. https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data
This comprehensive dataset provides Earth surface temperature data from 1750 to 2015. It includes global land and ocean temperature data, as well as temperature data by country, state, and city. The data was compiled by Berkeley Earth, which is affiliated with Lawrence Berkeley National Laboratory.

Rokahr, A. (2023). Complete Census Data on 250,000 Census Blocks. Kaggle. https://www.kaggle.com/datasets/axelrokahr/complete-census-data-on-250000-census-blocks
This comprehensive dataset provides detailed census information for approximately 250,000 census blocks across the United States. It includes a wide range of demographic, economic, and housing variables, offering a granular view of population characteristics at the census block level.

_Note: The data has been processed and aggregated for this visualization. For the original dataset, please refer to the Kaggle link above._
