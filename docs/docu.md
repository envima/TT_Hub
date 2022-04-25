---
permalink: /docu
title: Features
layout: single
classes: wide
header:
  image: /assets/images/splash_wide.png
  caption: "Photo credit: [**Environmental Informatics Marburg**](https://www.uni-marburg.de/en/fb19/disciplines/physisch/environmentalinformatics)"
---



Wishlist of features to be included in the Tree Talker Hub.

Theses functionalities and how to implement them could be discussed in the GitHub repo to this page, [here](https://github.com/envima/TT_Hub){:target="_blank"}.

It would make sense to include the already available Hub functionalities 
of **TubeDB** for climate station data ([Landing page](http://environmentalinformatics-marburg.github.io/tubedb/){:target="_blank"}, [Paper](https://doi.org/10.1016/j.cageo.2020.104641){:target="_blank"}) 
into the Tree Talker Hub.
 
Examples below are taken from **TubeDB**




## Dash board and inspections

###  Graphical inspections
- Interactive map with TreeTalker locations [(Examples)](http://environmentalinformatics-marburg.github.io/tubedb/usage/web/#map---interactive-map-of-plots){:target="_blank"}
- Interactive visualisations of multi-sensor data [(Examples)](http://environmentalinformatics-marburg.github.io/tubedb/usage/web/#visualisation---visualisation-of-climate-data){:target="_blank"}

### Maintenance information
- Battery information [(Examples)](http://environmentalinformatics-marburg.github.io/tubedb/usage/web/#status---interactive-detailed-up-to-date-status-of-plots){:target="_blank"}
- Transmission failure [(Examples)](http://environmentalinformatics-marburg.github.io/tubedb/usage/web/#status---interactive-detailed-up-to-date-status-of-plots){:target="_blank"}
- Working/broken TTs
- Automatic messages for maintenance

### Quality checks
- Sensor failure / Outlier screening
- Invalid values screening by multi sensor formula checks


## Data storage and IO

Time series data stored and managed by [TubeDB](http://environmentalinformatics-marburg.github.io/tubedb/){:target="_blank"}

### Raw data import
- Incoming TreeTalker measurement data is imported into the database periodically, e.g each morning.
- Alternatively or complementary to periodic imports, TreeTalker nodes directly send measurements to the database for instant updates.

### Data export
- Individual web browser based processing and data download.  
- **R interface** for flexible and reproducible workflows [(Examples)](http://environmentalinformatics-marburg.github.io/tubedb/usage/rpackage/){:target="_blank"}


## Processing

### Calibration
- By individual scripts
- Sap flow
- Saturation index
- Relative to absolute value calculations / scaling
- User generated absolute calibration for wood moisture sensors

### Gap filling / interpolation

### Flexible aggregation by time intervals (e.g. days, months)












