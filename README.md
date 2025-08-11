# Software_testing_assignments
The link for all software testing assignments


## WEEK TWO

## Different Types of Software Testing and Their Significance
Software testing can be compared to a health check-up for software before it is released. Each type of testing plays a specific role — like different doctors focusing on different parts of a patient’s health.

** Unit Testing – Checks individual components of the software in isolation, ensuring each part works as intended.

** Integration Testing – Verifies that different components interact correctly when combined.

** System Testing – Evaluates the entire application as a complete product to ensure it functions properly in a production-like environment.

** Acceptance Testing – Confirms that the software meets the end user’s requirements and expectations.

**Significance:
  Testing allows a team to identify and fix bugs, performance issues, or security risks early, reducing the cost and effort required later in development.


## Functional vs Non-Functional Testing
** Functional testing focuses on what the software does, while non-functional testing focuses on how well it performs.


** Functional Testing – Ensures the software’s features work according to requirements. For example:

** Can a user log in with correct credentials?

** Does the “Search” button return the correct results?

** Non-Functional Testing – Measures the software’s performance, usability, and reliability. For example:

## How fast does a page load?

  Can the system handle heavy traffic?

  In short: Functional = What it does, Non-functional = How well it does it.

  | **Aspect**  | **Unit Testing** 🧩                                                     | **Integration Testing** 🔗                                                       |
| ----------- | ----------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| **Scope**   | Tests small, individual pieces of code (functions, classes, or modules) | Tests the interaction between multiple components                                |
| **Purpose** | Ensures each component works correctly on its own                       | Ensures combined components work correctly together                              |
| **Example** | Checking if a “calculateTotal()” function returns the correct sum       | Checking if “calculateTotal()” works properly when linked with “applyDiscount()” |

## System Testing & Acceptance Testing
** System Testing – Tests the complete application in an environment similar to production to ensure all features work together.

** Acceptance Testing – Conducted to determine whether the software meets the agreed requirements before it is released to users.

## Role in quality:

** System Testing ensures the product is fully functional and stable.

** Acceptance Testing ensures the product is ready and approved for use.


## Common Types of Non-Functional Testing
   These tests evaluate the quality attributes of a system:

**  Performance Testing – Measures speed and responsiveness under expected load.

** Load Testing – Checks behavior under a specific volume of users or transactions.

** Stress Testing – Pushes the system beyond normal limits to see how it recovers.

** Security Testing – Identifies vulnerabilities to protect against cyberattacks.

** Usability Testing – Ensures the system is intuitive and easy for users.

** Compatibility Testing – Verifies operation across different devices, browsers, and operating systems.

## WEEK THREE

## Concept and Importance of Static Testing

** Static testing is a method of evaluating software without actually running the code. Instead, the focus is on examining and reviewing requirements, design documents, or source code to find errors early in the development process.

## It is important because it:

** Detects defects before the software is executed, which saves time and cost.

** Ensures coding standards and guidelines are followed.

** Improves the quality of both the code and documentation.

** Example: A developer reviews another team member’s code for potential logic mistakes or security flaws before the program is tested dynamically.

## Walkthroughs, Technical Reviews, and Inspections
   These are formal approaches within static testing, each with a different level of depth and structure:

** Walkthrough – An informal review where the author of a document or code explains it to peers to gather feedback. Purpose: Share understanding and get suggestions.

** Technical Review – A more formal process where technical experts examine code or documents to identify defects and suggest improvements, often guided by a checklist.

** Inspection – The most formal type, with defined roles (author, moderator, reviewers, recorder) and structured steps to detect defects in detail. Often used for critical software components.

## Role of Static Analysis Tools

** Static analysis tools automatically scan code without running it to detect:

** Syntax errors

** Security vulnerabilities

** Performance issues

** Violations of coding standards

** These tools help developers identify problems early, reduce human error in manual reviews, and ensure consistency across the project.

## Key Benefits of Using Static Analysis Tools

  Using these tools provides several advantages:

** Early Bug Detection – Issues are caught before testing or deployment.

** Improved Code Quality – Helps enforce coding standards and best practices.

** Time and Cost Savings – Reduces the need for extensive rework later.

** Security Enhancement – Flags potential vulnerabilities before they become threats.

## Popular Static Analysis Tools and Their Features
  
   Some widely used tools include:

** SonarQube – Detects code smells, bugs, and security vulnerabilities; supports multiple languages.

** ESLint – Popular in JavaScript projects; enforces coding style and catches syntax issues.

** Pylint – Checks Python code for errors, style violations, and best practices.

** Checkstyle – Ensures Java code adheres to coding standards.

Fortify Static Code Analyzer – Focuses on identifying security vulnerabilities in code.
Consistent Reviews – Maintains uniform quality across the development team.
