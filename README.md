# SQL_INJECTION TESTING AND SECURING DATABASE

## MANUAL CHECKS

**THIS IS AN ERROR RETURNED AFTER USING THE MANUAL AUTHENTICATION FILE TO CHECK WHETHER A DATABASE IS SECURE**

![alt text](https://github.com/taylorhelene/SQL_injection_testing_and_protection/blob/main/image/sqlresult.png)

**THIS MEANS THE DATABASE IS NOT SECURE**

## TOOL CHECKS

-**STEP 1**

You need OWASP WebGoat listening on port 8080. You also need either OWASP Zap or Burp Suite properly configured with your Web Browser.

-**STEP 2**

Download Sqlmap.
Sqlmap an open source penetration testing tool.
Navigate to its folder on cmd
Run Sqlmap.py sqlmap –wizard
Run your post and get queries that can cause a security risk

![alt text](https://github.com/taylorhelene/SQL_injection_testing_and_protection/blob/main/image/sqlmap.png)

## TOOL CHECKS

Use netsparker
