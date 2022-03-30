---
permalink: /docu
title: Documentation
layout: single
classes: wide
---

Time series data is managed by [TubeDB](http://environmentalinformatics-marburg.github.io/tubedb/)


## Import

Incoming TreeTalker measurement data is imported into the database periodically, e.g each morning.  
Alternatively or complementary to periodic imports, TreeTalker nodes directly send measurements to the database for instant updates.


## Graphical inspection
- Interactive map with TreeTalker locations
- Interactive visualisations of multi-sensor data

## Maintenance information
- Battery information
- Transmission failure
- Automatic messages for maintenance to do
- Working/broken TTs

## Calibration
- By individual scripts
- Sap flow
- Saturation index
- Relative to absolute value calculations / scaling
- User generated absolute calibration for wood moisture sensors

## Quality checks
- Sensor failure / Outlier screening
- Invalid values screening by multi sensor formula checks

## Processing
- Gap filling / interpolation
- Aggregation by time

## Export
Individual web browser based processing and data download.  
R interface for workflow automation.

Variable settings:
- Selection of TreeTalkers / Stations
- Selection of range of time
- Time Aggregation: none, hour, day, week, month, year
- Applied Quality checks
- File format

