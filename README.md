# Assist.org Equivalent Class Search
This project leverages every articulation agreement available for a specified year on Assist.org, providing a comprehensive list of equivalent community college classes corresponding to a specific course at your college.

#  Why?
At this current time, it's difficult to know all the equivalent community college class for a specific class at your college or community college. Under the current system, you would need to manually pull up every single PDF for each community college which can take up to several hours.

#  Sample Resulting Output

<img width="807" alt="Screenshot 2023-12-01 at 5 22 07 PM" src="https://github.com/Efferescent/Assist.org-Equivalent-Classes/assets/152109516/e806f089-bdce-4632-a081-ecd6a6bc6af3">

#  Important need to knows to use the code:
1. Know your college 'code' (i.e. Cal Poly SLO is CPSLO).
2. Know the major the class is under and input it in this format: UPPER_CASE_MAJOR, B.S.  
   For example: COMPUTER SCIENCE, B.S.
3. Know the title, unit count, and if there is a 'same as' class of the class you want to take.
4. Click on the calculator icon next to the data frame to see all of the classes.
   
Please note that all of these inputs are CASE SENSITIVE.

Also, in the resulting data frame, there are duplicates of certain classes due to formatting issues in the API (i.e. 'CS  141' and 'CS 141' or 'ies' and 'y').

#  Future Improvements
1. Add what community college the course is located in the resulting data frame.
2. The current code takes 2 minutes to run. While, it still does save hours on time, improvements should be made to speed up the code.

#  Acknowledgements
User jacobtbigham has done something similar before using similar API's, however, what spurred me to create this script is for the functionality and ease of use. After trying to implement his code, errors prevented me from using its functionality.

#   Notes
Code was created and tested on Google Colab. There is a possibility that this won't work on other text editors without modification. 
