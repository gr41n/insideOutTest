# insideOutTest
Tool to automate the process of testing what traffic and data can get from inside of the network, out. 


This is a personal project for me to learn some more Python skillz so keep in mind that there may be much better/faster ways to accomplish some of the features of this tool. For example, this will scan all 65535 ports on a server which is quite slow in Python. I may change this script in the future to do something differently. 

Feature Goals:
- External Port Scan
- External Application Scan (to test application inspection)
- Data Loss Scan (send sensitive files over various methods like web and email...sensitive files will contain PII and such to test  detection)
- Category Scan (test to see what websites are blocked within the network...keep in mind that this probably won't work too well with organizations that have user defined web blocking set up)

Improvement suggestions and feedback is welcome!
