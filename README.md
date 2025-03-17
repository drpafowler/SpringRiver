# Project Title

## My package
This repository is my exploration of predicting springtime streamflows from data obtained from the USGS, USDA, and NOAA

## Goals
The primary goal here is to investigate methods of predicting the discharge of a river.  I see there being two key components to this.  First, is the onset of the peak flow.  Second, is the magnitude of the peak flow.  

## History of my efforts
My first effort was the Rio Hondo in New MExico.  This turned out to not be an optimal choice as I discovered that there were two flood prevention structures upstream of Roswell NM.  This made the data less useful.  Then I moved on to the Yellowstone river.  I specifically selected this river as I knew that it was undammed and would likely work better.  This worked quite well.  

## Overview
The data is is collected from the USGS, USDA, and NOAA using the fetch_data script.  The one caveat to this is that the NOAA data is delayed by six months.  If the most recent data from NOAA is needed, it has to be downloaded from the NOAA website as a CSV file.

## Author(s)
Philip Fowler
