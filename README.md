# Assist.org Equivalent Class Search
This project leverages every articulation agreement available for a specified year on Assist.org, providing a comprehensive list of equivalent community college classes corresponding to a specific course at your college.

#  Sample Resulting Output

<img width="807" alt="Screenshot 2023-12-01 at 5 22 07 PM" src="https://github.com/Efferescent/Assist.org-Equivalent-Classes/assets/152109516/e806f089-bdce-4632-a081-ecd6a6bc6af3">

#  Important need to knows to use the code
1. Know your college 'code' (i.e. Cal Poly SLO is CPSLO).
2. Know the major the class is under and input it in this format: UPPER_CASE_MAJOR, B.S.  
   For example: COMPUTER SCIENCE, B.S.
3. Know the class code, class code number, name, and unit count of the class you want to take.     
   For example: CSC 202 - Data Structures (4.00)                        
   Class Code:            CSC                                 
   Class Code Number:     202                                    
   Name:                  Data Structures                                                   
   Unit Count:            (4.00)                                                   
5. Know if there is a 'same as' class for the class you want to take at your college. 
6. Click on the calculator icon next to the data frame to see all of the classes.
   
Please note that all of these inputs are CASE SENSITIVE.

Also, in the resulting data frame, there are duplicates of certain classes due to formatting issues in the API (i.e.   'CS__141' and 'CS_141' or 'ies' and 'y').

#  Why
At this current time, it's difficult to know all the equivalent community college classes for a specific class at your college or community college. Under the current system, you would need to manually pull up every single PDF for each community college which can take up to several hours.

#  Future Improvements
1. Add what community college the course is located in the resulting data frame.
2. The current code takes 2 minutes to run. While, it still does save hours on time, improvements should be made to speed up the code.

#  Acknowledgements
User jacobtbigham has done something similar before using similar API's, however, what spurred me to create this script is for the functionality and ease of use. After trying to implement his code, errors prevented me from using its functionality.

#   Notes
Code was created and tested on Google Colab. There is a possibility that this won't work on other text editors without modification. I would suggest changing the output directory. In Google Colab, the defult output directory is '.' For other text editors, creating a folder with the output specified to it would work.
