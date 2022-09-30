# Election Analysis
 
The purpose of this project was to submit the Colorado election results to the Colorado election commission board. The following election results included a written analysis of the voter turnout, votes per county, and determining the county with the highest turnout. 

## Project Overview

### Resources
- Data Source: election results.csv
- Software: Python 3.7.16, Visual Studio Code

### Summary of Results

One of the Colorado Board of Elections employees tasked us with the following:

#### 1. Calculate the total number of votes cast.

Based on the findings there was a total of 369,711 votes.This was calculated by creating a variable that kept the tally of the total count when the program iterated through the entire dataset. The below image captures the declared variable and count.
     
![Total_vote counter](https://user-images.githubusercontent.com/112028534/193154560-4c6920e8-96f7-43e0-aed0-acccd398b56f.PNG)

![count for total](https://user-images.githubusercontent.com/112028534/193165879-f95fb949-a4c3-45ba-95ac-717dafc9015a.PNG)

#### 2. Get a complete list of candidates who received votes.

There were three candidates that received votes which included Diana DeGette, Charles Casper Stockham, and Raymon Anthony Doane. A conditional statement was used to capture the candidates names and then append them to a list when the program iterated through the data. This is seen in the graphic.

![Candidate_counter](https://user-images.githubusercontent.com/112028534/193155205-7dae8594-8c79-4725-b073-1b6907af6728.PNG)

#### 3. Calculate the total number of votes each candidate received.

Doane received 11,606 votes

Stockham received 85,213 votes

DeGette received 272,892 votes

As the program converts the dataset into a list of dictionaries it is tasked with tracking the amount of votes per candidate and this was achieved by declaring a dictionary variable in the for loop that would store the candidate name and its voter tally. When the program iterates over a different candidate’s name a conditional statement will catch the name change and start a new count for that specific candidate. 

![candidate_count_name](https://user-images.githubusercontent.com/112028534/193166296-01a6972a-41eb-453e-ab58-acb5f6a32caf.PNG)
     
#### 4. Calculate the percentage of votes each candidate won.

Diana DeGette: 73.8%

Charles Casper Stockham: 23.0%

Raymon Anthony Doane: 3.1%

![vote percentage](https://user-images.githubusercontent.com/112028534/193166400-951489f0-d20f-462a-bf93-bcec9f4e3921.PNG)

Since the program is tracking both the individual vote count and the total count we can then describe the percentage of votes that went to each candidate.
     
#### 5. Determine the winner of the election based on popular vote.

The winner of the election based on popular vote was Diana DeGette who received 272,892 Votes which was 73.8% of the total amount of votes. The graphic below captures the key results gathered from the data.

![Election_Result](https://user-images.githubusercontent.com/112028534/193153987-932d8836-073b-478f-9d1e-79f5614c0a49.PNG)
 
 ## Conclusion

In summary, this program provides a fast and accurate method of providing key statistics and information regarding Colorado's elections process. Because the program captures voter turnout out per county it can show which counties may need more campaign funding to provide a higher turnout. Or it could show which areas where increased campaign funding doesn’t lead to higher turnouts. If the program was tailored to capture voting demographics it could illustrate which candidate is more likely to win based on their political party and policies; therefore, with this information candidates could better tailor their campaigns based on the voting base. As a business plan this program could help campaigns be more efficient and effective with their spending. 
