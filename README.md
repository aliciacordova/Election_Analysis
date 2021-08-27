# Election_Analysis
The purpose of this review is to help Tom conduct an audit so he can discuss it with the Colorado Board of Elections.
For this, an analysis was carried out where the total of the votes, the candidates who participated and what were their results (in % and number of votes) were obtained. Also, it was shown who was the candidate who won the election and with what participation.

Aditionally, we want to help Tom get the breakdown of the results by county. In this way we add to the analysis and modify the original script, which were the results by county (in % and number of votes) and which was the winning county.

## Election - Audit Results

### 1. How many votes were cast in this congressional election?
   ![Totalvotes](https://user-images.githubusercontent.com/87447639/131141413-467f2433-89fe-434c-8963-240acc5de79b.PNG)

- To print total votes we created this code:
   
   ![totalvotescode](https://user-images.githubusercontent.com/87447639/131146237-a2bf253a-8b30-4688-acce-f2c391b5fa74.PNG)


### 2. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
   ![totalvotescounty](https://user-images.githubusercontent.com/87447639/131141423-8dbed4b9-7a43-40cc-87fd-b416c2c5b475.PNG)
 
To calculate county votes we need to created:

- First an If statement:

 ![candidateif](https://user-images.githubusercontent.com/87447639/131145828-64b9ac58-46d0-46d7-9410-2cc73d4d5248.PNG)


- Second a loop statement: 
  ![countyloop](https://user-images.githubusercontent.com/87447639/131145697-d2618f6c-f7ea-4f45-bfaf-80ad30cf5c82.PNG)


### 3. Which county had the largest number of votes?
   ![winningcounty](https://user-images.githubusercontent.com/87447639/131141460-53f499a3-921d-4579-884f-9f70fbf7daa1.PNG)

- To print total county votes we created this code:

   ![winningcountycode](https://user-images.githubusercontent.com/87447639/131146187-197d4bbe-7c8a-441e-aa12-7f783d6b443b.PNG)


### 4. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
   ![candidatesvotes](https://user-images.githubusercontent.com/87447639/131141304-9668edf1-7cce-48ad-818c-bf1d79247c15.PNG)

To calculate candidate votes we need to created:

- First an If statement:

 ![countyif](https://user-images.githubusercontent.com/87447639/131145755-59392077-6383-42e6-85ac-cb2606548776.PNG)


- Second a loop statement: 
 
 ![candidateloop](https://user-images.githubusercontent.com/87447639/131145620-6806c11e-3aea-49bc-81a5-fd5b63561149.PNG)


### 5. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
   ![winningcandidate](https://user-images.githubusercontent.com/87447639/131141479-97568edd-8380-4f78-89c7-1cd5bb94c903.PNG)

- To print which candidate won we created this code:

   ![winningcandidatecode](https://user-images.githubusercontent.com/87447639/131146471-e946b0b9-92db-44d0-8ba9-307789faeea9.PNG)

  
## Election- Audit Summary

Election comision could be insterested in use this scrip in the future for other eleccion. In order to achive that we need to do some modifications. 

In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.
  - Example 1
  - Example 2 
