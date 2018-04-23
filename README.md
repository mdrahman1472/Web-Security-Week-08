# Web-Security-Week-08
### Hour Spent 14 hours

# Blue
#### Vulnerability 1: SQL Injection
<img src="https://i.imgur.com/1CC2iQy.gif" width="800">
Entering this sql injection at the end of url as following ?id=1' OR 1=1'-- gives "Database query failed" in blue. However, in red and green sections it just redirect which indicates Blue has SQL Injection vulnerability.


#### Vulnerability 2:Session Hijacking/Fixation
<img src="https://i.imgur.com/tMAz7Qs.gif" width="800">
Login into first website from one browser and got the session id. Accessing this site from different browser and change the session id that we got from first one, shows loged in

# Green
#### Vulnerability 1:Username Enumeration
<img src="https://i.imgur.com/5lWNQxf.gif" width="800">
Used two different class for correct and incorrect user name. It used class name as "failture" for correct and "failed" for incorrect user name


#### Vulnerability 2:Cross-Site Scripting
<img src="https://i.imgur.com/zbgWDL3.gif" width="800">
Entering alert script code on feedback


# Red
#### Vulnerability 1:Insecure Direct Object Reference
<img src="https://i.imgur.com/pwBcPbr.gif" width="800">
Changing id to 10 and 11 gives two person's information that can't be found in Salesperson section in Red but in Blue and Green section entering id as 10 or 11 redirect to Find a Salesperson page


#### Vulnerability 2: Cross-Site Request Forgery
<img src="https://i.imgur.com/TFdNLr5.gif" width="800">
Changing csrf_token still allow to edit on Red section but not in Blue and Green


# Bonus Objective 2: Build on Objective #4 (Cross-Site Scripting)
<img src="https://i.imgur.com/ZqBgBbB.gif" width="800">
using <script>document.location="https://www.nytimes.com"</script> on feedback allow to redirect to nytiimes.com when check feedback
