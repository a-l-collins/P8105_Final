Unmasking Variables: A Descriptive Analysis of Gun Violence Correlates
in New York
================

### Authors

- Ainsel Levitskaia-Collins (HL2710)
- Alissa Shams Orchi (AO2965)
- Kino Watanabe (KW3180)
- Miho Kawanami (MK4996)
- Te-Hsuan Huang (TH3147)

### Project Motivation

Gun violence is a persistent public health crisis in the United States.
In New York City, for example, we had the [Midtown Manhattan mass
shooting](https://www.cnn.com/2025/08/03/us/manhattan-shooting-timeline-911-calls)
in July 2025. It showed us that even our busiest, most protected
neighborhoods are impacted by gun violence. We would like to perform a
descriptive exploration of socioeconomic, geographic, and temporal
factors that are potentially positively or negatively associated with
firearm shootings in Manhattan, NYC.

### Intended Final Products

Five separate analyses into the factors (see planned analyses) that
contribute to gun violence within New York City, and one summary report
combining and comparing the results of these five analyses.

### Anticipated Data Sources

- [Gun shooting data by year (historic,
  2006-2024)](https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Year-To-Date-/5ucz-vwe8/about_data)
- [Gun shooting data in
  2025](https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8/about_data)
- [Social
  conditions](https://a816-dohbesp.nyc.gov/IndicatorPublic/data-explorer/social-conditions/?id=2317#display=summary)
- [American community
  survey](https://data.census.gov/all?q=American+Community+Survey)
- [Street lights
  data](https://data.cityofnewyork.us/Transportation/DOT-Street-Lights-and-Traffic-Signals-311-Service-/jwvp-gyiq)
- [Weather data](https://www.ncdc.noaa.gov/cdo-web/search)
- [Holiday data](https://www.redcort.com/us-federal-bank-holidays)
- [Green space](https://www.nycgovparks.org/about/data)

### The planned analyses / visualizations / coding challenges

#### Outcome: gun violence, characterized by shooting incidents

- Multiple years available (2006-2025)
- We intend to both analyze a longitudinal outcome of a range of years
  based on available data, and a cross-sectional outcome of 2025
  specifically.

#### Exposures under consideration

- Gun violence
  - operationalized as occurrences of shootings reported by the NYPD
- Street light/lighting in the area, time of day
  - Will be operationalized as poor street lighting determined by street
    lamp condition
- Social/environmental conditions dataset
  - Characterize this via public/green spaces (any open green space), as
    opposed to income/SES/etc
  - Green spaces perationalized as parks property managed partially or
    solely by NYC parks
  - Neighborhood disadvantage operationalized as low presence of green
    space and poor distribution of street lamps reported by the
    Department of Transportation
- Weather/time of year (seasonality)
  - Holidays/day of week
  - Focus on COVID-19’s influence (1/20/2020 first case in USA)
- Location
  - latitude and longitude
  - neighborhood
  - boro
  - precinct
  - location classification
  - inside vs.outside
- Victim gender
- Murder flag

#### Planned analyses:

- **Locational gun violence**
  - Analyze locational data as discussed in exposures
  - Initial descriptive analysis: make visualizations of the key
    variables in “Shooting incident” dataset to discover patterns and
    potential coding errors
  - Using latitude and longitude data to identify the shooting hotspots
    - Compare by borough and identify if Manhattan is, indeed, our best
      option for this analysis
    - If Manhattan is not the best option, determine which borough would
      be best, or if a full-city analysis would be better
  - Create locational shooting occurrence plots to be used in other
    analyses
- **Neighborhood disadvantage compared to gun violence**
  - Neighborhood disadvantage operationalized as discussed in exposures
  - Overlay green spaces in chosen borough with location of shooting
    occurrences
  - Overlay locations of street lamps in chosen borough with location of
    shooting occurrences
  - Compare/overlay green space and street lamp location to investigate
    if areas with low green space and poor lighting are associated with
    increased gun shooting incidents
- **Trends of gun violence over time**
  - Weather
  - Time of year (seasonality)
  - Holidays
  - Day of week
  - Time (hour; day/morning/etc)
  - Focus on COVID-19’s influence (1/20/2020 first case in USA)
- **Patterns of victim demographics within each neighborhood**
  - Victim gender
  - Murder flag

#### Visualizations

Generate maps that compare spatial patterns using latitude and longitude
data, in combination with other critical factors, to determine which
factors have the most significant influence.

- Map of shooting incidence by latitude and longitude.
- Map of green space presence by zipcode/neighborhood.
  - Could do a multi-polygon
  - Separate by zipcode
- Map of broken street lamp location with latitude and longitude.
- Time trends
  - Line graph of incidents by month/year
  - Can see seasonality and COVID-19’s influence
  - Box plot and/or violin plot of incidents by month (aggregated for
    all years)
  - Can also do incidents per day
  - Bar chart of days of the week and average incidents per day
  - Line graph of hourly time charts

#### Coding Challenges

Handling missing or inconsistent data across multiple sources might be
challenging. For example, the shooting data is contingent on the NYPD’s
administrative reporting, which may be inconsistent across precincts in
different boroughs. There may be coding errors that we would need to
carefully consider after reviewing the initial visualizations. In
addition, spatial mismatches may occur when datasets use different
geographic units, requiring careful alignment before merging. Variable
naming and key matching (e.g., dates, geographic identifiers) will need
to be standardized to ensure accurate joins and reproducible analyses.

### The planned timeline

- Nov 6: begin initial data checking of the shooting incident datasets
- Nov 7: submit proposal
- Nov 11 and Nov 13: check all datasets for merging (feasibility, what
  variables to merge on, etc.)
- Nov 18 and Nov 20: check the initial visualizations
- Nov 25 and Nov 27: combine all visualizations
- Dec 2 and Dec 5: finalize project state so the video can be recorded
- Dec 6: project due
