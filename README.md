# Scool District Analysis

## Overview of the school district analysis
The school board has notified that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. We have to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Then we have to repeat the school district analysis.

## Results

- How is the district summary affected?
We can detect a small decrease in the averages. The overall average decreased 0.3
![District_Summary_Anterior](/Resources/District_Summary_Anterior.png)
![Data](/Resources/District_Summary_Nuevo.png)

- How is the school summary affected?

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

- How does replacing the ninth-grade scores affect the following:

  - Math and reading scores by grade
  
  - Scores by school spending
  
  - Scores by school size
  
  - Scores by school type
## Election Audit Recomendations

We can use the same code to analyze other elections. To achieve this goal we have to consider change some things in our current code

1. The first thing we need to consider is changing the name of files we need to open and the paths

```# Add a variable to load a file from a path.
file_to_load = os.path.join("Resources", "election_results.csv")
```

2. The second thing to consider is having the data organized in the same way that it is organized now. For instance:


![Data](imagen_datos.png)
