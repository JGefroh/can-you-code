# can-you-code
A collection of potential technical interview challenges to determine whether an interviewee can code.

# Purpose
The purpose is to see if junior-level interview candidates can develop software. From my experience, whiteboard brain teasers and challenges aren't indicative of this. Take-home projects have their own share of problems (lack of time, no control, etc.)

### Challenge Criteria
1. Short challenges - 10-30 minutes.
2. End result is code.

# Challenges
1. Create an active directory search base parser.  
The challenge is to create a method that takes an email address and creates a naive search base for an AD login.  
For example, `joseph.gefroh@gmail.com` would output `DC=gmail,DC=com`. `example@subdomain.domain.com` would output `DC=subdomain,DC=domain,DC=com`.  
Extra points if they create tests.

2. [The Number Game](https://gist.github.com/JGefroh/111fc6ca61db239ddd54)  
The challenge is to refactor this code and make it cleaner and better.
