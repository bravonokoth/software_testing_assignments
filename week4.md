## Differences Between Black-Box and White-Box Testing
** Black-box and white-box testing differ mainly in what the tester knows about the system’s internal workings.

** Black-Box Testing – The tester has no knowledge of the internal code or structure. They only focus on inputs and expected outputs.

## Example: Checking if the login page works by entering various usernames and passwords without knowing the backend code.

** White-Box Testing – The tester knows the internal structure and writes tests based on the code’s logic and flow.

## Example: Writing tests that specifically execute each branch of an if...else statement to ensure complete code coverage.

** Key difference: Black-box = tests behavior, White-box = tests internal logic.

## Equivalence Partitioning (EP)

   Equivalence Partitioning is a test case reduction technique where input data is divided into partitions (groups) that should behave the same way.
   From each group, only one representative value is tested.

## Example: If a form accepts ages 18–60, the partitions could be:

    Valid: 18–60

    Invalid: Less than 18

    Invalid: Greater than 60

    Instead of testing every number, the tester chooses one value from each group (e.g., 20, 15, 65).

    Benefit: Reduces the number of test cases while maintaining coverage.

    Boundary Value Analysis (BVA)
   
 ## Boundary Value Analysis focuses on testing values at the edges of input ranges because bugs often occur at boundaries.

    Example: For an age input of 18–60:

    Test values: 17 (just below), 18 (minimum), 60 (maximum), 61 (just above).

    Significance: Helps detect off-by-one errors and boundary-related defects.

##  Decision Tables in Black-Box Testing
    
    Decision tables are a structured way to represent complex business rules.
    They show conditions and their corresponding actions in a tabular format, ensuring that all possible combinations are covered.

    Example: A discount policy might depend on:

    Membership status (Yes/No)

    Purchase amount (> Ksh100 / ≤ Ksh100)

    The decision table ensures the tester checks all scenarios (member + high amount, non-member + low amount, etc.).

Use: Helps in testing systems with multiple conditional rules.

##  State Transition Testing
    State transition testing checks how a system behaves when changing from one state to another based on events or inputs.

Example: 
An ATM:

    State 1: Card inserted → Enter PIN (moves to State 2)

    State 2: Correct PIN → Select Transaction (moves to State 3)

    State 3: Transaction processed → Card ejected (back to State 1)

    Real-world use: Testing workflows like authentication systems, vending machines, and online booking systems.

    
