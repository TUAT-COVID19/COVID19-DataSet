# COVID19-DataSet
This is the data repository for the COVID-19. We try to unify the format of the COVID-19.  
We have already unified that in Japan! Now, we attempt to create unified data for each area narrower than prefecture (prefecture is like a U.S. state).  
  
Every data is stored by the same JSON format. Item "date" and "data" has values in list. 
- data
  - positiveIncrease_release
    - date
    - data
  - positiveIncrease_onset
    - date
    - data
  - deathIncrease
    - date
    - data
  - hospitalizedCurrently
    - date
    - data
  - inspection
    - date
    - data
  - consulations
    - date
    - data
  - population
- parent
- child
  
Description for each item　is shown below.
- positiveIncrease_release: today's the number of new positive cases (**reported date base**)
- positiveIncrease_onset: today's the number of new positive cases (**onset date base**)
- deathIncrease: today's the number of new death cases
- hospitalizedCurrently: currently hospitalization 
- inspection: today's the number of inspections
- consultations: today's the number of consultaions to Coronavirus Consultation Center
- population: population in the area
- parent: list of parent directory
- child: list of subdirectory

