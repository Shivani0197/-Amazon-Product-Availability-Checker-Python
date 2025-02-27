Amazon-Product-Availability-Checker-Python
As we know Python is a multi-purpose language and widely used for scripting. Its usage is not just limited to solve complex calculations but also to automate daily life task. Let’s say we want to track any Amazon product availability and grab the deal when the product availability changes and inform the user of availability through email. It will be a great fun to write a Python script for this.
Note: Install the required libraries (as per the code) before running the script. Also, note if the product is not available currently then no email will be sent to user. Asin Id should be provided by the user for the product he wants to keep track of.
Working of each module used: 
-> requests: Used to make HTTP get and post requests 
-> time: Used to find current time, wait, sleep 
-> schedule: Used to schedule a function to run again after intervals. It is similar to “setInterval” functionality in JavaScript. 
-> smptlib: Used to send email using Python.
Level up your coding with DSA Python in 90 days! Master key algorithms, solve complex problems, and prepare for top tech interviews. Join the Three 90 Challenge—complete 90% of the course in 90 days and earn a 90% refund. Start your Python DSA journey today!
