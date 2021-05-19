# Code Review 

A code review is important for a developer to have their code looked at by another team member when they have finished the task. Another developer may be able to spot an error or area of code that could have been done more efficiently. Code reviews are super benefical in large companies to keep all code aligned with the existing code style guidelines, error free, fulfilling requirements. Code is often covered by unit tests that will do most of the error checking, but carrying out a code review after testing has been done can be great for picking up on things that the system missed. Although developers across a team may have designated tasks to carry out, by checking each others code when complete allows the reviewer to get to know all aspects of the project.

# _Code Review Checklist_

![image](https://i2.wp.com/d331tpl5vusgqa.cloudfront.net/wp-content/uploads/2015/08/Code-Review-Checklist.png?ssl=1)

When reviewing code, it is important to keep a checklist of different aspects of the code to look out for:

**1. Best Coding Practices**
    To follow best coding practices it is important to look out for:
- No Hard Coding
- Use of Constants where possible
- Use Frameworks where possible
- Efficient use of if/else statements
- Informative comments

**2. Usability**
    Is the User Interface easy to use? Is the User well informed?
    It is important for the code to not only solve the problem, but it must also be easy for a user to navigate.
    
**3. Code Formatting**  
- Remove unnecessacary commenting
- Use autoalign tools
- No whitespaces
- No empty lines of code
- Not exceed 30 methods per class where possible

**4. Maintainability**  
- Readability, the code should be self explanatory (e.g. variable names say what they do/are for)
- Testability, easy to test.
- Configurability, keep values such as database values in place no changes need to be made to the code in the event of a change in the data

**5. Reusability** 
- No repitition in code
- Generic functions and classes used where possible
- Reusable services and functions used where possible

**6. Security** 
Is the data protected with code security? Insecure code invites security vulnerabilities to the system. It is important for the developer and the reviewer to put themselves in the shoes of someone trying to get into the system.

**7. Speed & Performance** 
How quickly does the code run? The user expects quick reponses from the application so therefore it is important to get rid of any redundant code, unnecassary API calls, and inefficient database queries.
The system should use caching and asynchronous processing where possible to speed up the performance.

**8. Patterns**
Has the team already defined a pattern necessary to carry out the task? Most large bodies of work follow a style guide to keep everybody's code in line, so therefore new code should align with it.

**9. Test Coverage**
Have all edge cases passed the test? The system may be passing tests that actually should be failing. Tests should follow all of the same rules as listed above. When code is updated, tests should be updated also.