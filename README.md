# FancyPants

#### The purpose of this exercise is to start a discussion for interviewing purposes.  The exercise should only take a short amount of time, but it should be completed with care.  

#### Depending on the type of job you are applying for, you may complete this exercise in any programming language that makes sense (e.g. C#, Java & Spring Boot, SQL (PL/SQL or T/SQL), Delphi, C++, Bash, etc.).

### The process is as follows:
1. Sign into GitHub - creating an account if necessary.
1. Create a fork of this repository
1. Using the "Application Specification" (found below), please create an application, and any test routines, that completely fulfills the requirements found in the Application Specification
    + How you output each number (for the requirement below) is up to you and will be dependant on what technology you are using (e.g. web page vs. console application)
    + The application you create should reflect the position you are applying for (e.g. a web solution for a web position, web service/console app for a C# position, sql script for sql dev, etc)
1. Zip your source code solution with a password, commit it to the repository and submit it as a pull-request
    + Title the pull request (replace [YourName] with your actual first and last name): [YourName] - FancyPants Submission
    + Don't submit your source code to the repository - just include it in the zip file.  Only submit the password protected zip file in the PR.
    + If something happens and you are unable to create a pull-request, send your zip file to my email address (below)
1. Email the password for your zip file to: chris.deluca[at]transactcampus.com 
    + Have the subject of your email be (replace [YourName] with your actual first and last name): [YourName] - FancyPants Submission
    + If I don't have a current copy of your resume, please include that as well.
1. If you have questions about the exercise, please contact me (chris.deluca[at]transactcampus.com) and not the recruiters working with HR

### Application Specification
+ Primary requirement: Produce a program or script that does the following:
    + Prompts for (or accepts) 4 input values which should all be positive integers
    + The input variables are to be *specifically* named: Low, High, A, B
    + Output each number on it's own line (in ascending order) from Low to High (including endpoints)
        + However, when the current value is evenly divisible by A, produce the output of “Fancy” instead of the number
        + When the current value is evenly divisible by B, produce the output of “Pants” instead of the number
        + When the current value is evenly divisible by A and also evenly divisible by B, produce the output “FancyPants” instead of the number
    + Note any place where you had to deviate from the instructions due to programming language constraints
+ Secondary requirements:
    + The application should be re-runnable without any noticeable negative impacts  
    + The application should be considered "production quality" and reflect that level of attention to detail
    + Please include any test routines used to prove your solution works