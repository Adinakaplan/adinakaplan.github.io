# Project 1: NYC Urban Planning & Collision Hotspot Analysis
This project analyzes New York City Motor Vehicle Collision data to identify high-risk corridors and inform urban safety interventions.

### Objective
To identify "High Injury Networks" within NYC by analyzing the geographic concentration of vehicle collisions and their impact on pedestrian and cyclist safety.

### Technical Methodology
* **Data Sourcing:** Utilized the NYC Open Data portal (NYPD Motor Vehicle Collisions).
* **Geospatial Analysis:** Processed Latitude and Longitude coordinates using `Pandas` to map collision density.
* **KABCO Scale Analysis:** Categorized injury severity using the KABCO scale (Killed, Severe Injury, Moderate, Minor, No Injury) to prioritize "Vision Zero" focus areas.
* **Feature Engineering:** Analyzed contributing factors such as "Driver Inattention" and "Yielding Violations" in relation to street design.

### Results
Identified top-tier priority intersections where infrastructure improvements (like curb extensions or leading pedestrian intervals) could most effectively reduce severe injuries.
