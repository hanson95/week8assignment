# week8assignment
Week 8 assignment

Challenge 1- User enumeration
Site:Green
Vulnerability:
When you try to login with a known username the font is bold. When you login with a fake user name the login font is non bolded.
This is a vulnerability because a hacker will know if he has correctly accessed a real account.
https://imgur.com/a/pVYlo

Challenge 2-IDOR
Site:blue
Vulnerability:
Using the id in the url you can access other users in the database by changing the value. All of the users on the page are able to be
accessed but when you increase the id to 10 and 11 you have access to users that are not on the users list. A hacker could use this to 
access some users personal data and exploit it.
Gif:
https://imgur.com/a/80SVI

Challenge 3- SQL injection
Site:blue
vulnerability:
In the url you can inject SQL code into the id field by converting the SQL into html. This is a vulnerability because once a hacker can have access to the database. He might
get personal information or even delete tables and data. 
Gif:
https://imgur.com/a/OcrF8

Challenge 4-XSS
site:Green
In the feedback page, you can insert a script into the comment box and when you log into the page and check the feedback section
the script will activate. This could be a vulnerability since a hacker could inject harmful scripts into sites.
Gif:
https://imgur.com/a/t5mLz

challenge 5-CSRF
site: Red
vulnerability:
you can create an html file that you can run that will submit a POST request and update a users information or create a new user.
Gif:
https://imgur.com/a/TI7Pd

challenge 6-Session Hijacking
site:Red
Vulnerability:
The sessionID is not secure and once you login to the red site, you'll have access to the blue site. So if there is sensitive information in the blue site
you can have access to it. 
Gif:
https://imgur.com/a/5b8VS
