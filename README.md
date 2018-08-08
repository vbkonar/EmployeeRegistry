# EmployeeRegistry

This GUI, on the client, provides :

    1) A way for a “manager” (student) to enter the SSN of a manager (like Borg, or any other manager),
    and the SQL Query would check if indeed that SSN matches a manager’s SSN. If the test is OK,
    then the manager can input the employee information. If the SSN does not match a manager’s
    SSN, then print that the SSN does not correspond to a manager and then stop.

    2) Next the manager must be able to insert a new employee into the COMPANY database.

    3) For the new employee, the manager should be asked to enter the employee information
    according to the EMPLOYEE table attributes, and then to enter one or more projects to which the
    employee is assigned, and to verify that the total number of hours does not exceed 40 hours total.
    Ideally, the GUI should interact with the manager to ensure that the employee does not work more
    than 40 hours over all the projects assigned. The employee can work up to but should not exceed
    40 hours for all the assigned projects.

    4) Use a two-box checkbox, if possible, to have the manager enter whether the new employee has
    dependents. If NO is checked, then no dependents are entered, and if YES is checked, the
    manager is to be prompted to enter the attributes associated with one or more dependents.

    5) Finally, once the new employee information, including projects and dependents, has been
    entered, the database tables are updated, and then a report is printed and presented to the
    employee. The students should print the report as part of their project submission.
    Screen-shots of the interaction should be included. 
    
 We use java Swing API and jdbc implement the above problem.

