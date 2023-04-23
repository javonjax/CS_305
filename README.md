
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
    Artemis Financial wants to modernize their operations. As a crucial part of the success of their custom software, they also want to use the most current and effective software security. Artemis Financial has a public web interface. They are seeking my expertise about how to protect their client data and financial information
    
    
What part of the vulnerability assessment was challenging or helpful to you?
    I had trouble understanding what marked a false positive. Eventually I came to the conclusion that once dependencies are fully up to date, vulnerabilities may still exist because the dependency provider has updated the dependency. Sometimes we need to just live with these types of vulnerabilities as a developer.
    
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
    For this project I implemented a check sum using an algorithm cipher and also used a self signed certificate to increase security. In the future I would probably perform similar techniques as the ones I used when wokring on these projects. Manually scanning the code to find obvious areas that need security improvements would probably be my first step.
    
    
How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
    I performed multiple manual test runs as I was coding to ensure that things were function as planned. After I finished refactoring the code, I performed a final test and also ran a dependency check. I compared the results of the dependency checks before and after refactoring the code to confirm that no new vulnerabilities were introduced when I implemented changes. 
    
What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
    The Iron Clad Java textbook that we used as a resource throughout the course will be something that I refer to frequently in the future. The book taught me a lot about concepts that I only had a rough understanding of before this course. I have also been watching YouTube tutorials to get more comfortable with how Spring Boot functions since it seems to be popular in the industry. 
    
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
    I think showing that I understand how Spring Boot works and that I am comfortable running a dependency check would be important for showing my comfort level with software security. I also think the analysis of the dependencies and potential fixes shows I have an understand of how to safe implement Maven dependencies.
