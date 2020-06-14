# Phandeeyar_Assignment

# Description
        Open Hluttaw is a zone with a core mission to make it easy for citizens and their parliamentary respresentative to engage in an active and informed dialogue.
        - Do you want to find who your respresentatives are?
        - Do you want to know an information about them?
        - Or identify who belongs to a committee you care about?
        The objective of Open Hluttaw can help you through hundreds of parliamentary respresentative profiles.
       
# Data Understanding 
    - Data is collected from  http://api.openhluttaw.org/my/persons as a json format. It has many variables but I had selected the related variables.I would like to know the number of MPs and the number of constituency for each region in that json file.I extracted 1 call of API , recieved 30 number of ids(MPs) and searched the constituency value is located at (memberships > post > label).
    - Region value is getting from constituency value which is used split() method in python.
    - Create a dataframe(Phandeeyar) includes (MP_ID,Region,Constituency).
    - Checked the number of rows and columns,how many unique count,missing values.
    - Save Phandeeyar dataframe as a Phandeeyar.txt file to apply data visualization part in Power BI.
    - Upload Phandeeyar.txt file in Power BI.
    - Displays the number of MPs in each region using Pie chart and the number of Constituency in each region using bar graph. 
    - If you don't have power bi software in your machine, I added Phandeeyar_Dashboard_Image in git repo.
