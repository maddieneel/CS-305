# CS-305

# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
My client, Artemis Financial, is a financial consulting company that develops financial plans for savings, retirement, investments, and insurance for their customers. They requested for Global Rain, my company, to identify any security vulnerability in their current software. These vulnerabilities were then reported in the Vulnerability Assessment Report.

# What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I felt that I recorded the vulnerabilities shown in the dependency check well - I kept all necessary information yet summarized it for better readability. It is important to have software security and to code securely because one small defect could likely result in a failure of a project. These failures could range from the program doing incorrect or unnecessary steps and/or be a vantage point from an outside attacker.

# What about the process of working through the vulnerability assessment did you find challenging or helpful?
I, thankfully, did not find the vulnerability assessment challenging. Although when interpreting the client’s needs, it was not stated if there were any international transactions and I had to make an educated guess. Due to the assumption, it may have been recorded differently from another programmer.

# How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
To add layers of security, we ran the route to enable check sum and compared the given and expected data from the API. As another level of security, we attached a self-signed certificate to ensure secure communications. In multiple instances, we completed a code review to identify any security vulnerabilities. First we tested using the dependency check tool and compared it to one without the refactored code, then we manually reviewed the code to catch any remaining errors. In future projects, I will continue to do in-depth testing to assess any vulnerabilities throughout the development stage as well as after.

# How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
Before refactoring the code, I ran a dependency check and recorded what vulnerabilities were shown. After I refactored the code to align with Artemis Financials’ needs, I ran another dependency check. When comparing these two reports, I was able to determine that I did not add any additional vulnerabilities.

# What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
One of the resources I will continue to use within my career and future assignments is maven dependency check. I felt it was helpful to not only reference the NVD database, but look at third party vendors and how they have fixed the issue.

# Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
From this assignment I would want to showcase the organization of information, how I am able to understand requirements, and how I’m willing to continuously search for ways to improve and/or fix errors in the future.
