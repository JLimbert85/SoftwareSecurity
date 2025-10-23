# SoftwareSecurity

## Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a fincancial consulting company that develops financial plans for its clients. The company uses a custom software that has a public web interface. They are worried about software security and have asked us to consult on how to protect their clients data and financial information in their software.

## What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
When vulnerabilities were found I think I did well on researching them and providing feedback and steps to help mitigate the vulnerabilities. It is safe to assume that any piece of code that is run on the internet will have hackers trying to break it. Coding securely and making sure to mitigate vulnerabiliities and protect sensitive data is crucial. Software security is very valuable to a company's well being. Being hacked and leaking customer information can be very damaging to a company's reputation and can lead to a loss of customers they may never get back. 

## Which part of the vulnerability assessment was challenging or helpful to you?
Doing the static analysis of the dependencies was the most challenging. The dependency check tool gives a lot of information that is useful but it took awhile to figure out how to read and understand it.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased the security by ensuring the web interface is using SSL encryption to transmit data. I also created a hashing function to generate a checksum to verify data that is sent. In the future I will use the dependency check tool for static analysis as I found it very useful. I will also continue to manually review code to check for vulnerabilities. This will guide the steps I take to secure software.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After refactoring the code I reran the static analysis looking for any new vulnerabilities. I also tested the code to ensure the web interface was using SSL and that the checksum ahshing worked correctly.

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The dependency check tool was very helpful for static testing. This is a tool I will continue to use in the future when doing security analysis.

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show them the report I created identifying the vulnerabilities in the code and the steps I recommend taking to mitigate the vulnerabilities. This will demonstrate my understanding of software security and the ability to research vulnerabilities.
