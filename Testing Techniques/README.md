# Testing Techniques
Functional Testing (Black Box Testing)
- This type of testing checks whether the application behaves as per the defined specifications and requirements.

Non Functional Testing (White Box Testing)
- This type of testing checks the non-functional aspects (i.e., performance, usability, reliability, etc.) of a software application.

## Functional Testing
- Unit Testing
    - validate the functionality of a unit or component, involves testing the smallest parts of an application in isolation
- Integration Testing
    - While component can pass individually, integration testing focuses on the interactions between integrated units to ensure their functionalities as a group
- System Testing
    - Tests the complete system to ensure it meets the specified requirements, also referred to as end-to-end testing
- Regression Testing
    - To ensure that new code changes have not adversely affected existing functionalities and no new issues were introduced in the process of fixing other problems
- User Acceptance Testing (UAT)
    - The final stage of any software development or change request lifecycle before go-live. UAT meaning the final stage of any development process to determine that the software does what it was designed to do in real-world situations 
- Smoke Testing
    - A preliminary test that checks the basic functionality of an application
- Sanity Testing
    - Usually occur after smoke testing. Checks specific functionalities for errors after a change has been made to the code


## Non Functional Testing
- Performance Testing
- Load Testing
- Stress Testing
- Usability testing
- Reliability Testing
- Security Testing
- Recovery Testing


## Positive Testing vs Negative Testing
Positive Testing
- Positive testing involves testing an application with valid input data to ensure it behaves as expected. The main goal is to confirm that a software application provides the expected output when fed valid conditions.

Negative Testing
- Negative testing involves testing an application with invalid input data. The objective is to ensure the application can gracefully handle unexpected or erroneous conditions without crashing or producing unhandled exceptions.

Comprehensive coverage
- While positive testing often misses edge cases, negative testing ensures that all possibilities are explored, giving you a well-rounded quality assurance process.

The following basic techniques are used to verify positive and negative test cases
- Equivalence Partitioning
    - This software testing approach creates test cases keeping border values in mind. When the input data is used inside the boundary value constraints, this is referred to as positive testing. This is known as negative testing when the input data is chosen outside the boundary value restrictions.
- Boundary Value Analysis
    - This software testing method divides input data into numerous sections. Testers must verify the values of each partition at least once. Partitions with valid values are used in positive testing, and negative testing uses partitions with wrong values.
