Information Gathering

  1. Retrieve and Analyze the robot.txt files by using a tool called GNU Wget.

  2.Examine the version of software.database Details, the error technical component, bugs by the error codes by requesting invalid pages.

  3.Implement the techniques such as DNS inverse queries, DNS zone Transfers, web based DNS Searches.

  4.Perform Directory style Searching and vulnerability scanning, Probe for URLs, using tools such as NMAP and Nessus.

  5.Identify the Entry point of the application using OWSAP ZAP, Burb Proxy, TemperIE, WebscarabTemper Data.

  6.By using traditional Fingerprint Tool such as Nmap,Amap, perform TCP/ICMP  ansd service Fingerprinting.

  7 .By Requesting Common File Extension such as .ASP, .EXE, .HTML, .PHP ,Test for recognized file types/Extensions/Directories.

  8.Examine the Sources code From the Accessing Pages of the Application front end.

Authentication Testing

  1.Check if it is possible to “reuse” the session after Logout.also check if the application automatically logs out a user has idle for    a certain amount of time.

  2.Check whether any sensitive information  Remain Stored stored in browser cache.

  3.Check and try to Reset the password, by social engineering crack secretive questions and guessing.

  4.check if the “Remember my password” Mechanism is implemented by checking the HTML code of the login page.

  5.Check if the hardware devices directly communicate and independently with authentication infrastructure using additional      communication channel.

  6. Test CAPTCHA for authentication vulnerabilities presented or not.

  7.Check whether any weak security questions/Answer are presented.

Authorization Testing

Test the Role and Privilege Manipulation to Access the Resources.
2.Test For Path Traversal by Performing input Vector Enumeration and analyze the input validation functions presented in the web application.

3.Test for cookie and parameter Tempering using web spider tools.

4.Test for HTTP Request Tempering and check whether gain illegal access to reserved resources.

Configuration  Management Testing

1.Check directory and File Enumeration review server and application Documentation. also, check the infrastructure and application admin interfaces.

2.Analyze the Web server banner and Performing network scanning.

3.Check and verify the presence of old Documentation and Backup and referenced files such as sources codes, passwords, installation paths.

4.check and identify the ports associated with the SSL/TLS services using NMAP and NESSUS.

5.Review OPTIONS HTTP method using Netcat and Telnet.

6. Test for HTTP methods and XST for credentials of legitimate users.

7.Perform application configuration management test to review the information of the source code, log files and default Error Codes.

Session Management Testing

1.Check the URL’s in the Restricted area to Test for Cross sight Request Forgery.

2.Test for Exposed Session variables by inspecting Encryption and reuse of session token, Proxies and caching, GET&POST.

3.Collect sufficient number of cookie samples and analyze the cookie sample algorithm and forge a valid Cookie in order to perform an Attack.

4.Test the cookie attribute using intercept proxies such as Burb Proxy, OWASP ZAP, or traffic intercept proxies such as Temper Data .

5.Test the session Fixation, to avoid seal user session.(session Hijacking )

Data Validation Testing

1.Performing Sources code Analyze for javascript Coding Errors.

2. Perform Union Query SQL injection testing, standard SQL injection Testing, blind  SQL querY Testing, using tools such as sqlninja,sqldumper,sql power injucter .etc.

3.Analyze the HTML Code,Test for stored XSS,leverage stored XSS,using tools such as XSS proxy,Backframe,Burb,XSS Assistant.

4.Perform LDAP injection testing for sensitive information about users and hosts.

5.Perform IMAP/SMTP injection Testing for Access the Backend Mail server.

6.Perform XPATH Injection Testing for Accessing the confidential information

7.Perfrom XML injection testing to know information about XML Structure .

8.Perform Code injection testing to identify input validation Error .

9.Perform Buffer Overflow testing for Stack and heap memory information and application control flow.

10.Test for HTTP Splitting and smuggling for cookies and HTTP redirect information .

Denial of Service Testing

1.Send Any Large number of Requests that perform database operations and observe any Slowdown and  New Error Messages.

2.Perform manual source code analysis and submit a range of input varying lengths to the applications

3.Test for SQL wildcard attacks for application information testing.

4.Test for User specifies object allocation whether a maximum number of object that application can handle.

5.Enter Extreme Large number of the input field that used by the application as a Loop counter.

6.Use a script to automatically submit an extremely long value for sever can be logged the request.
