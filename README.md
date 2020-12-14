# COVID19-DataSet
This is the data repository for the COVID-19. We try to unify the format of the COVID-19.  
We have already unified that in Japan! Now, we attempt to create unified data for each area narrower than prefecture (prefecture is like a U.S. state).  
  
Every data is stored by the same JSON format. Item "date" and "data" has values in list. 
- data
  - positiveIncrease
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
  - population
- parent
- child
  
Description for each item　is shown below.
- positiveIncrease: today's the number of new positive cases
- deathIncrease: today's the number of new death cases
- hospitalizedCurrently: currently hospitalization 
- inspection: today's the number of inspections

