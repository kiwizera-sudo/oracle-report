# oracle-report
Oracle PDB Configuration Report 

names: KWIZERA DIEUDONNE

ID: 27623

Task 1: Create a New Pluggable Database
I created a new PDB named 'di_pdb_27623' with an admin user 'di_plsqlauca_27623' and password '1234'.
![](https://github.com/user-attachments/assets/680dce58-a192-4cba-b145-1a23f039d637)

Task 2: Create and Delete Another PDB
I created a temporary PDB named 'di_to_delete_pdb_27623' and deleted it after verifying successful creation.
 ![](https://github.com/user-attachments/assets/6ebf3c60-8958-429f-b365-2246dfa1540c)
 ![](https://private-user-images.githubusercontent.com/124999593/498478047-4ace7a8b-51ad-488f-9cfc-824c5f352599.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTk4NjMwNDgsIm5iZiI6MTc1OTg2Mjc0OCwicGF0aCI6Ii8xMjQ5OTk1OTMvNDk4NDc4MDQ3LTRhY2U3YThiLTUxYWQtNDg4Zi05Y2ZjLTgyNGM1ZjM1MjU5OS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUxMDA3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MTAwN1QxODQ1NDhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT05ZWMyM2Q0ZGY2ODAzYzE2YzA1ODk5YjI4NGI3YTg5YTUwNjk2YThiZWUyZDk3YjA3YTY0MGFkNzU3MGMyNDg2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.DyAl_of5X1F3xTc9I0LOF85_m6YBOGLmPCvacW471yA)
 
Task 3: Oracle Enterprise Manager (OEM) / SQL Developer Dashboard
Since 'emctl' was not recognized in Oracle 23c AI, I used Oracle SQL Developer as an alternative dashboard. 
 ![](https://github.com/user-attachments/assets/4476ac68-1a11-4601-85b5-964b3a833b56)
 
3. Issues Encountered and Solutions 
The emctl command was unavailable in Oracle 23c AI.: Used Oracle SQL Developer as an alternative .

4. Conclusion
- Successfully created a PDB with an admin user
- Created and deleted a second PDB for testing
- Verified and documented all results using SQL Developer dashboard

