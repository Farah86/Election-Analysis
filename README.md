# Election-Analysis
##  A-Overview of Election Audit:
It's all the tasks that needed to be complete and review the information needed by the Colorado Board of Elections which included:

1a.Total number of votes cast.

2a.A complete list of candidates who received votes.

3a.Total number of votes each candidate received.

4a.Percentage of votes each candidate won.

5a.The winner of the election based on popular vote.

-------------------------------------------------------------------------------------------------------------------------------------

## B-Election-Audit Results:

1b.369,711 votes were cast in this congressional election

2b. the county final results:
  
  -Jefferson:10.5%(38,855)

  -Denver:82.8%(306,055)

  -Arapahoe:6.7%(24,801)

![This is an image](https://github.com/Farah86/Election-Analysis/blob/main/county%20results.png)

--------------------------------------------------------------
 
         county_percentage = float(votes) / float(total_votes) * 100
        county_results=(f"{county_name}:{county_percentage:.1f}%({votes:,})\n")
 
 3b. Denver county had the largest number of votes
 
   ![this is an image](https://github.com/Farah86/Election-Analysis/blob/main/largest%20county%20for%20votes.png)
 
    largest_county_results=(f"-----------------\n"f"largest_voter_turnout:{largest_county}\n"f"--------------------\n")
    
    
 4b. the candidates were 
 -Charles Casper Stockham: 23.0% (85,213)
 -Diana DeGette: 73.8% (272,892)
 -Raymon Anthony Doane: 3.1% (11,606)
 
 ![this is an image](https://github.com/Farah86/Election-Analysis/blob/main/candidate%20results.png)
 
 -----------------------------------------------------------
 
      votes = candidate_votes.get(candidate_name)
        
        vote_percentage = float(votes) / float(total_votes) * 100
        
        candidate_results = (
            f"{candidate_name}: {vote_percentage:.1f}% ({votes:,})\n")
            
   5b.  Diana DeGette won the election
      
      their vote count =272,892
      
      their percentage of the total votes= 73.8%
   
   ![this is an image](https://github.com/Farah86/Election-Analysis/blob/main/winning%20candidates.png)
   
   -------------------------------------------------------------------------
   
    if (votes > winning_count) and (vote_percentage > winning_percentage):
            winning_count = votes
            winning_candidate = candidate_name
            winning_percentage = vote_percentage

   
## C-Election-Audit Summary:
This is a small program build and modified to help collecting , access ,change data that given to find the winning county and their candidate and to provide full information to  the Colorado Board of Elections in this program we used syntax and coded belong to python which is easy use we used two methods in this program (list and dictionary) an objects contain both the (value and the key) and the list which allow us to delet,add and change to our index ,by that we will be able to use this program in any other requirments for example in student elections we can use the same steps and change the inputs see by using  :

    import csv
    import os
help us use statics for each country and thier numbers in excel sheet and upload them by proving the path to the os

    file_to_load = os.path.join("")
    file_to_save = os.path.join("")
help us load the file easily and save it easly ,and by using :
 
    my_list=[] as list 
    my_dictionary ={} as dictionary that will hold our (key and value)
    
the rest will be modified according to the requirments in the election    
  
    
            


