# Assignment_Tracker
The motivation behind building this project came from realizing the "need" for it during the third semester of my engineering studies. We receive assignment details for our course on the ELMS portal of IGDTUW. However, every time we want to access it, we have to log in again and navigate through numerous webpages to finally find the relevant assignment updates. To solve this problem, I started working on this project. I explored various documentations about web scraping and eventually developed a solution using BeautifulSoup and the Requests library in Python.

Project Overview:
This is a menu-driven program that performs the following tasks:
-Login Credentials: The user provides login credentials to the program.
-Session Management: A common session is started to maintain the login session throughout subsequent requests.
-Check Updates: The check_updates function extracts assignments and checks if any new assignments have been posted by comparing them with previously posted assignments stored in a text file.
-Extract Assignment Details: The extract_assignment_details function scrapes necessary information such as submission status, grading status, due date, time remaining, and last modified date for an assignment based on the user's choice and displays it to the user.
Submit URL: The get_submit_url function provides a direct link to the submission page of a particular assignment.
