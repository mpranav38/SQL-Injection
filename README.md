Overview

SQL injection is a code injection technique that exploits the vulnerabilities in the interface between web
applications and database servers. The vulnerability is present when user’s inputs are not correctly checked
within the web applications before being sent to the back-end database servers.
Many web applications take inputs from users, and then use these inputs to construct SQL queries, so
they can get information from the database. Web applications also use SQL queries to store information in
the database. These are common practices in the development of web applications. When SQL queries are
not carefully constructed, SQL injection vulnerabilities can occur. SQL injection is one of the most common
attacks on web applications.

In this lab, we have created a web application that is vulnerable to the SQL injection attack. Our web
application includes the common mistakes made by many web developers. Students’ goal is to find ways to
exploit the SQL injection vulnerabilities, demonstrate the damage that can be achieved by the attack, and
master the techniques that can help defend against such type of attacks. This lab covers the following topics:
• SQL statement: SELECT and UPDATE statements
• SQL injection
• Prepared statement

Lab Environment.
This lab has been tested on the pre-built Ubuntu 16.04 VM, which can be downloaded from the SEED
website.
We have developed a web application for this lab. The folder where the application is installed and the
URL to access this web application are described in the following:
• URL: http://www.SEEDLabSQLInjection.com
• Folder: /var/www/SQLInjection/
The above URL is is only accessible from inside of the virtual machine
