# CS-305
Repository for class projects

# Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
For this project, the client was Artemis Financial, a financial insitute that handle banking and investment services for their customers. 
The company had given us their program they intended to use, but wanted us to review it and find any vulnerabilites that needed to be adressed prior
to be released. 

# What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
After finding the vulnerabilites, I think I did well at giving my personal recommendations of how they could improve and secure the program, to 
avoid these vulnerabilites. It is important to code securely because this will help reduce vulnerabilites in a program and reduce the ways that 
attackers may exploit the program and secure sensitive inforamtion. software security improves a companies well-being in multiple aspects. It will
reduce the amount of exploits used on them, in which will increase the trust of hteir clients. It will also help keep sensitive and crucial information secure, 
whether that be trade secrets or client information.

# Which part of the vulnerability assessment was challenging or helpful to you?
I really liked using the Maven dependency check. This tool was very helpful in finding known vulnerabilites that may be present in your code, without having to do
extensive research for every aspect of the code. 

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased layers of security by adding hashing encryption to the codebase, to secure the private information. I also added the use of secure https 
communications to the project. 

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To do this, I made sure to use quality code as to not introduce new vulnerabilites into the project. And to be sure of this, I did a maven dependency check 
and reviewed the report to confirm that no new vulnerabilites were added in my refactored code. 

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
In this course, there was a lot that I learned that could be utilized in future projects. For example, usiong the secure software flow diagram 
was a helpful tool to look back at, in order ot make sure I was implementing the various secure coding best practices. I also liked using encryption algorithms
and hash functions. I think this will be helpful in ensuring future projects have secure data even if vulnerabilites are found that allows attackers to siphon it from the system.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
From this assignment, I could show future employers my ability to identify vulnerabilities, by running a dependency check and assessing how we may fix them. I can also
show them how I implemented a hash function into the program. 
