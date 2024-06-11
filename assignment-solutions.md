### 1. Levels of Testing:
- **Objective:** Ensure the software works correctly. 🛠️
- **Levels:**
  - Unit Testing: Testing a single component in isolation.
    - *Example:* Testing a function that adds two numbers.
  - Integration Testing: Testing how units work together.
    - *Example:* Testing the interaction between a login module and a database.
  - System Testing: Testing the entire system as a whole.
    - *Example:* Testing an e-commerce website to ensure all features work together.
  - Acceptance Testing: Testing if the software meets user requirements.
    - *Example:* Users testing a new mobile app to ensure it meets their needs.
- **Who Tests:** Developers do unit testing, testers do integration and system testing, users or clients do acceptance testing.

### 2. Minimizing Coupling:
- **Objective:** Reduce dependencies between units. 🧩
- **Steps:**
  1. Identify Dependencies.
  2. Encapsulate Components.
  3. Use Interfaces.
- **Coupling Types:** Ranges from loose coupling (best) to tight coupling (worst).
  - *Example:* Loose coupling: Modules communicate through interfaces; tight coupling: Direct method calls between modules.

### 3. Top-down vs Bottom-up Integration Testing:
- **Top-down:** Starts testing from the top module. 🚀
- **Bottom-up:** Tests from the smallest units. 🐞
- **Comparison:** Top-down tests high-level functionality first, while bottom-up tests low-level functionality first.
  - *Example:* Top-down: Testing the UI first, then integrating backend services. Bottom-up: Testing database operations, then integrating with backend logic.

### 4. Debugging:
- **Objective:** Identify and fix errors in the code. 🔍
- **Techniques:** 
  1. Print Statements: Adding statements to track program flow.
    - *Example:* Adding print statements to track the value of variables in a loop.
  2. Debugger Tools: Using tools to step through code and inspect variables.
    - *Example:* Setting breakpoints in code and inspecting variable values during runtime.


## Q5. Popular Debugging Approaches

Debugging is the process of identifying and fixing errors or bugs in software. There are several popular approaches to debugging:

### 1. Print Statement Debugging:
This approach involves strategically placing print statements (or log statements) in the code to output variable values, messages, or control flow information during execution. Developers can use these print statements to trace the flow of the program and identify the source of errors.

**Example:** In a Python program, you can insert print statements to display the values of variables at different stages of execution:
```python
def divide(a, b):
    print("Dividing", a, "by", b)
    result = a / b
    print("Result:", result)
    return result
```

### 2. Debugger Tools:
Debugger tools are software programs that allow developers to pause the execution of their code, inspect variables, step through the code line by line, set breakpoints, and analyze the program's behavior in detail. This approach is more systematic and powerful compared to print statement debugging.

**Example:** Visual Studio Code, PyCharm, and Eclipse are popular IDEs with built-in debugger tools that provide features such as step-through execution, variable inspection, and call stack analysis.

### 3. Rubber Duck Debugging:
This unconventional approach involves explaining the code and the problem to an inanimate object, such as a rubber duck. By verbalizing the problem and walking through the code line by line, developers often gain new insights and can identify the root cause of the issue.

**Example:** A developer encounters a bug while writing code for a sorting algorithm. They explain the code and the problem to a rubber duck on their desk, and in the process of verbalizing their thoughts, they realize they forgot to handle edge cases.

Each of these debugging approaches has its advantages and is used in different scenarios based on the complexity of the problem, the developer's preference, and the available tools.
standing. Let me know if you need further modifications!

### 6. Short Notes:
- **Coverage Analysis Tools:** Check code coverage during testing. 📊
  - *Example:* Code coverage tool showing which lines of code are tested.
- **Performance Testing Tools:** Evaluate system performance. ⚡
  - *Example:* Load testing tool simulating thousands of users accessing a website.
- **Functional/Regression Testing Tools:** Automate testing of functions and regression tests. ✔️
  - *Example:* Selenium for automating web application testing.

### 7. Differentiation:
- **Integration vs System Testing:** Integration tests interaction between units; system tests the whole system. 🔄
- **System vs Acceptance Testing:** System tests system functionality; acceptance tests user requirements. ✅
- **Unit vs Integration Testing:** Unit tests individual units; integration tests interaction between units. 🧩
- **Testing vs Debugging:** Testing verifies functionality; debugging finds and fixes errors. 🔍

### 8. Outline of a Test Plan Document:
- **Introduction:** Overview of the software being tested. 📄
- **Test Items:** Components to be tested. 🧪
- **Features to be Tested:** Specific features to be tested. ✅
- **Approach:** Testing methodologies and techniques. 🛠️
- **Pass/Fail Criteria:** Criteria for determining test success or failure. ✔️❌
- **Suspension Criteria:** Conditions under which testing may be suspended. ⚠️
- **Resumption Requirements:** Conditions for resuming testing. 🔄
- **Test Deliverables:** Documentation and reports to be produced. 📝
- **Testing Tasks:** Specific tasks to be performed during testing. 📋
- **Environmental Needs:** Software and hardware requirements. 💻
- **Responsibilities:** Roles and responsibilities of testing team members. 👨‍💼👩‍💼
- **Schedule:** Timeline for testing activities. ⏰
- **Risks and Contingencies:** Potential risks and mitigation strategies. ⚠️🛡️
- **Approvals:** Sign-offs and approvals required. ✍️

### 9. Most Popular Level of Testing:
- **System Testing:** It tests the entire system as a whole, ensuring it meets requirements and functions correctly. 🔄🌐

### 10. Most Popular Integration Testing Approach:
- **Top-down Integration Testing:** It starts with the high-level modules and gradually integrates lower-level modules. 🚀🧩

### 11. Path Testing:
- **Objective:** Tests all possible paths in the software. 🛤️
- **Steps:** Identify paths, create test cases for each path, execute test cases. 🧪✔️

### 12. Metrics:
- **Quality of Source Code:** Measures code readability, maintainability, and efficiency. 📊📈
- **Source Code Coverage:** Measures the percentage of code covered by tests. 🧩✔️
- **Test Case Defect Density:** Number of defects found per test case. 🐞📉
- **Review Efficiency:** Measures effectiveness of code reviews. 🔄👁️

### 13. Failure Intensity Calculation:
- **Present Failure Intensity:** Remains at 10 failures/CPU hour. 🔢
- **After 50 CPU Hours:** 10 failures/CPU hour. 🔢
- **After 100 CPU Hours:** 5 failures/CPU hour. 🔢

### 14. Software Reliability:
- **MTBF (Mean Time Between Failures):** Average time between failures. 🕰️
- **MTTF (Mean Time To Failure):** Average time until a failure occurs. 🕰️
- **Failure Intensity:** Rate of occurrence of failures. 🔢
- **Failures Experienced:** Number of failures within a specific time. 🔢

### 16. Advantages of Automated Test Data Generation:
- **Efficiency:** Faster than manual generation. ⚡
- **Accuracy:** Less prone to human error. 🎯
- **Consistency:** Generates consistent test data. ↔️

### 17. Random Testing:
- **Objective:** Tests software with randomly generated inputs. 🎲
- **Popularity:** Efficient for finding unexpected bugs. 👾

### 18. Short Notes:
- **Mutation:** Modifies code to create variants for testing. 🧬
- **One-point Crossover:** Genetic algorithm operator for combining genetic material. ↔️
- **Two-point Crossover:** Another genetic algorithm operator for combining genetic material. ↔️↔️
- **Fitness Function:** Determines how close a solution is to the desired result in evolutionary algorithms. 💪🎯
---

# 2. 📚 Assignment 

**Date:** 31/05/2024-03/06/2024 (Submission Date)

## Q1. What is a use case? How is it different from a use case diagram? What are the components of a use case diagram? 

### Use Case:
Use case ek scenario ya example hota hai jismein system aur user ka interaction dikhaya jata hai. Yeh batata hai ki user kis tarah se system ko use karega.

### Use Case Diagram:
Use case diagram ek visual representation hoti hai jo system ke use cases aur users (actors) ke beech ke interactions ko dikhati hai.

### Components of a Use Case Diagram:
1. **Actors** 🎭 - Jo system ko use karte hain (e.g., users, other systems)
2. **Use Cases** 📄 - System ke functions ya features
3. **System Boundary** 🔲 - System ki limits ko define karta hai
4. **Relationships** 🔗 - Actors aur use cases ke beech ka interaction (e.g., associations, generalizations)

## Q2. How do we write use cases? Describe the basic and alternative flows in a use case. Discuss.

### Writing Use Cases:
1. **Use Case Name** - Clear aur descriptive naam.
2. **Actors** - Kon kon interact karega.
3. **Preconditions** - Kya conditions pehle se honi chahiye.
4. **Basic Flow** - Normal sequence of steps user follow karta hai.
5. **Alternative Flow** - Agar kuch galat ho jaye toh steps.
6. **Postconditions** - Kya result hona chahiye.

### Basic Flow:
Yeh wo steps hain jo usually follow hote hain jab sab kuch thik chal raha ho.

### Alternative Flow:
Yeh wo steps hain jo tab follow hote hain jab kuch galat ho jaye ya koi exception aa jaye.

## Q3. Design a problem statement for library management system and generate the following:

### Problem Statement:
Ek library management system design karna hai jo books ko issue, return aur manage kar sake. Users (students, staff) books ko search, borrow aur return kar sakte hain.

### (i) Use Cases:
1. **Make Reservation** 🔖
2. **Remove Reservation** 🗑️
3. **Lend Item** 📚
4. **Return Item** 🔄
5. **Add Title** ➕
6. **Remove/Update Title** 📝🗑️
7. **Add Item** ➕
8. **Remove Item** 🗑️
9. **Add Borrower** 🆕
10. **Remove/Update Borrower** 📝🗑️
11. **Maintenance** 🛠️

### (ii) Use Case Diagram:
![Use Case Diagram](https://www.startertutorials.com/uml/wp-content/uploads/2013/10/LMS-Use-Case-Diagram.jpg)

### (iii) Basic and Alternative Flows in Use Cases:
**Lend Item - Basic Flow:**
1. Borrower requests to lend an item.
2. Librarian checks the availability of the item.
3. If available, the librarian lends the item to the borrower.
4. System updates the database to reflect the lending status.

**Lend Item - Alternative Flow:**
1. If the item is not available, the system shows a message.
2. Borrower may choose to make a reservation for the item.

### (iv) Test Cases from Use Cases:
1. **Test Case 1:** Verify making a reservation for a book.
2. **Test Case 2:** Verify the process of lending an item.
3. **Test Case 3:** Verify the return item process.
4. **Test Case 4:** Verify adding a new title.
5. **Test Case 5:** Verify removing or updating a title.
6. **Test Case 6:** Verify adding a new borrower.
7. **Test Case 7:** Verify removing or updating a borrower.


## Q4. What are various strategies for data validity? Discuss with the help of an example.

### Strategies for Data Validity:
1. **Input Validation** - Input data ko entry point pe hi check karna.
2. **Data Cleansing** - Incorrect ya redundant data ko remove ya correct karna.
3. **Consistency Checks** - System me data consistency ensure karna.

### Detailed Examples:

#### 1. Input Validation:
Input validation ka matlab hai ki data entry ke waqt hi data ko validate karna, taki incorrect data system me enter na ho sake. Yahaan kuch examples diye gaye hain:

**Example: Email Validation**

- **Format Check:** Ensure email address correct format me ho. E.g., `user@example.com`
  - Input pattern check karne ke liye Regular Expressions (regex) use kar sakte hain.
  - Example Regex: `^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$`
  
  ```python
  import re

  def validate_email(email):
      regex = r'^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$'
      return bool(re.match(regex, email))

  email = "user@example.com"
  print(validate_email(email))  # Output: True
  ```

#### 2. Data Cleansing:
Data cleansing ka matlab hai incorrect, incomplete, ya redundant data ko identify karna aur usse correct karna ya remove karna. Yahaan kuch examples diye gaye hain:

**Example 1: Removing Duplicates**

- **Identify Duplicates:** Duplicate records ko identify karna aur remove karna.
  
  ```python
  data = ["user1@example.com", "user2@example.com", "user1@example.com"]
  unique_data = list(set(data))
  print(unique_data)  # Output: ['user1@example.com', 'user2@example.com']
  ```

**Example 2: Correcting Errors**

- **Fixing Typos:** Common typos ko correct karna, jaise email domain me spelling mistake.
  
  ```python
  data = ["user1@exmaple.com", "user2@example.com"]
  corrected_data = [email.replace("exmaple.com", "example.com") for email in data]
  print(corrected_data)  # Output: ['user1@example.com', 'user2@example.com']
  ```

#### 3. Consistency Checks:
Consistency checks ensure karte hain ki data across different parts of the system consistent hai. Yahaan kuch examples diye gaye hain:

**Example: Ensuring Consistent User Information**

- **Cross-System Consistency:** Ensure user information (e.g., email, phone number) across different databases consistent hai.
  
  ```python
  # Example pseudo-code to check consistency between two systems
  system1_data = {"user1": "user@example.com"}
  system2_data = {"user1": "user@example.com"}

  def check_consistency(data1, data2):
      return data1 == data2

  print(check_consistency(system1_data, system2_data))  # Output: True

## Q5. What are the guidelines for generating the validity checks? Explain with the help of an example.

### Guidelines:
1. **Define Rules** - Set clear validation rules (e.g., email format).
2. **Automate Checks** - Use automated tools to enforce rules.
3. **Regular Audits** - Conduct regular data audits.

### Example:
For email validation, use regex to ensure the format is correct.

## Q6. Why should we do database testing? Write some advantages and applications of database testing.

### Database Testing:
Database testing ensure karta hai ki data sahi tarah se store, retrieve aur manage ho raha hai.

### Advantages:
1. **Data Integrity** - Ensure data consistency.
2. **Performance** - Optimize query performance.
3. **Security** - Identify vulnerabilities.

### Applications:
1. **Banking Systems** - Ensure transactions are processed correctly.
2. **E-commerce** - Validate order and inventory data.

## Q7. Write the problem statement for library management system. Design test cases for various operations using database testing.

### Problem Statement:
Ek library management system develop karna hai jo books ko efficiently manage kar sake.

### Test Cases:
1. **Test Case 1:** Verify book addition to the database.
2. **Test Case 2:** Verify book issue and return operations.
3. **Test Case 3:** Check user registration and authentication.

## Q8.

### (a) What is regression testing? Discuss various categories of selective re-test problem.

### Regression Testing:
Regression testing ensure karta hai ki naye changes ke baad bhi purane functionalities theek se kaam kar rahe hain.

### Categories of Selective Re-Test:
## Categories of Selective Re-Test:

Selective re-testing ka matlab hai ki specific test cases ko select karna jo system changes ke baad run karne chahiye, instead of retesting the entire system. Yeh approach time aur resources bachati hai. Yahaan kuch categories of selective re-test aur unke examples diye gaye hain:

### 1. **Retest-All Tests**
Yeh approach simplest hai. Isme sare test cases retest kiye jate hain jo change se affected ho sakte hain. Yeh ensure karta hai ki system fully tested hai.

**Example:**
- Agar ek library management system me naya feature add kiya gaya hai jo book reservations se related hai, to purane test cases jo book reservations se related hain, unhe retest kiya jata hai.

### 2. **Retest-Risk-Based Tests**
Is approach me un test cases ko select kiya jata hai jo high-risk areas ko cover karte hain. Yeh high-risk areas wo hote hain jahan errors hone ki possibility zyada hoti hai ya jahan critical functionalities hain.

**Example:**
- Agar ek e-commerce website me payment gateway update kiya gaya hai, to high-risk test cases wo honge jo payment processing aur transaction integrity se related hain. In test cases ko retest kiya jayega.

### 3. **Retest-Priority Based Tests**
Is approach me test cases ko priority ke basis pe retest kiya jata hai. High-priority test cases ko pehle execute kiya jata hai.

**Example:**
- Agar ek banking application me funds transfer module me change kiya gaya hai, to high-priority test cases wo honge jo funds transfer functionalities ko cover karte hain. Inhe pehle retest kiya jayega.

### 4. **Retest-Regression Tests**
Isme un test cases ko retest kiya jata hai jo regression suite ka part hote hain. Regression tests ensure karte hain ki naye changes se existing functionalities me koi bug na aaye.

**Example:**
- Agar ek software me naya report generation feature add kiya gaya hai, to regression tests un functionalities ko test karenge jo report generation ke alawa hain, taki ensure kiya ja sake ki naye feature se purani functionalities break na ho.

### 5. **Retest-Impact Analysis Based Tests**
Is approach me impact analysis kiya jata hai aur un test cases ko retest kiya jata hai jo impacted areas se related hote hain. Yeh approach highly efficient hai kyunki yeh accurately identify karta hai ki kaunse areas changes se affected hain.

**Example:**
- Agar ek hospital management system me patient record module update kiya gaya hai, to impact analysis identify karega ki kaunse functionalities directly ya indirectly is module se linked hain, aur unhe retest kiya jayega.

### Summary:
Selective re-testing categories alag-alag strategies provide karti hain jo specific scenarios me best suited hoti hain. Yeh ensure karti hain ki changes ke baad system effectively aur efficiently test ho sake, without wasting unnecessary time aur resources.


### (b) Discuss an algorithm for the prioritization of test cases.

Test case prioritization algorithm ka matlab hai ki test cases ko execute karne ke order ko define karna based on certain criteria, taki testing process more effective aur efficient ho. Yahaan ek simple algorithm discuss kiya gaya hai jo risk-based prioritization pe focus karta hai:

#### Algorithm: Risk-Based Test Case Prioritization

1. **Identify Test Cases:**
   - Sabhi available test cases ki list banayein.
   - Example: Test cases for a library management system.
     - TC1: Add new book
     - TC2: Remove book
     - TC3: Issue book to member
     - TC4: Return book
     - TC5: Generate report

2. **Assign Risk Levels:**
   - Har test case ko risk level assign karein based on impact aur likelihood of failure.
   - Example: High, Medium, Low
     - TC1: Medium
     - TC2: High
     - TC3: High
     - TC4: Medium
     - TC5: Low

3. **Calculate Priority Scores:**
   - Risk score aur other factors (e.g., customer priority, recent changes) ko consider karke priority score calculate karein.
   - Formula: `Priority Score = (Risk Level * Weight1) + (Change Impact * Weight2) + (Customer Priority * Weight3)`
   - Example weights: Risk Level = 5, Change Impact = 3, Customer Priority = 2

4. **Sort Test Cases:**
   - Test cases ko priority score ke descending order me sort karein.
   - Example:
     - TC3: Priority Score = (5 * High) + (3 * High) + (2 * Medium) = 5*3 + 3*3 + 2*2 = 15 + 9 + 4 = 28
     - TC2: Priority Score = 5*3 + 3*Medium + 2*Medium = 15 + 6 + 4 = 25
     - TC4: Priority Score = 5*Medium + 3*Low + 2*Medium = 10 + 3 + 4 = 17
     - TC1: Priority Score = 5*Medium + 3*Low + 2*Low = 10 + 3 + 2 = 15
     - TC5: Priority Score = 5*Low + 3*Low + 2*Low = 5 + 3 + 2 = 10

5. **Execute Test Cases:**
   - Sorted order ke according test cases ko execute karein.
   - Order of execution: TC3, TC2, TC4, TC1, TC5

### Example:

Let's consider a simplified version of this algorithm with the following test cases:

- **TC1:** Add new book (Medium Risk, Medium Change Impact, Low Customer Priority)
- **TC2:** Remove book (High Risk, Medium Change Impact, Medium Customer Priority)
- **TC3:** Issue book to member (High Risk, High Change Impact, High Customer Priority)
- **TC4:** Return book (Medium Risk, Low Change Impact, Medium Customer Priority)
- **TC5:** Generate report (Low Risk, Low Change Impact, Low Customer Priority)

#### Assigning Risk Levels:
- TC1: Medium (2)
- TC2: High (3)
- TC3: High (3)
- TC4: Medium (2)
- TC5: Low (1)

#### Calculating Priority Scores:
Using the formula:
- **Weights:** Risk Level = 5, Change Impact = 3, Customer Priority = 2

1. **TC1:** 
   - Priority Score = (5 * 2) + (3 * 2) + (2 * 1) = 10 + 6 + 2 = 18
2. **TC2:** 
   - Priority Score = (5 * 3) + (3 * 2) + (2 * 2) = 15 + 6 + 4 = 25
3. **TC3:** 
   - Priority Score = (5 * 3) + (3 * 3) + (2 * 3) = 15 + 9 + 6 = 30
4. **TC4:** 
   - Priority Score = (5 * 2) + (3 * 1) + (2 * 2) = 10 + 3 + 4 = 17
5. **TC5:** 
   - Priority Score = (5 * 1) + (3 * 1) + (2 * 1) = 5 + 3 + 2 = 10

#### Sorted Test Cases by Priority Score:
1. TC3: 30
2. TC2: 25
3. TC1: 18
4. TC4: 17
5. TC5: 10

#### Execution Order:
- TC3
- TC2
- TC1
- TC4
- TC5

### Summary:
Yeh algorithm test cases ko prioritize karta hai based on risk, change impact, aur customer priority, taki testing process zyada effective aur efficient ho. Is process ko follow karke testing team ensure kar sakti hai ki sabse important aur high-risk areas pehle test kiye jayein, minimizing the risk of critical bugs in the system.

## Q9. What are the factors responsible for requirement changes? How are the requirements traced?

### Factors Responsible for Requirement Changes:

1. **Customer Feedback:**
   - Customer se directly feedback milne par changes zaroori ho jate hain.
   - **Example:** Ek e-commerce website ke users ne complain kiya ki checkout process complicated hai, to checkout process ko simplify karne ke liye requirements change kiye jayenge.

2. **Market Conditions:**
   - Market trends aur competitive pressure ke wajah se bhi requirements change hote hain.
   - **Example:** Agar market me naye payment methods popular ho rahe hain, to e-commerce website ko naye payment options integrate karne padenge.

3. **Technological Advances:**
   - Nayi technologies introduce hone par bhi requirements change kiye jate hain.
   - **Example:** Mobile app development me nayi framework release hone par, existing app ko us framework me migrate karna ho sakta hai.

4. **Regulatory Changes:**
   - Government regulations aur compliance requirements ke changes ke wajah se bhi requirements change karne padte hain.
   - **Example:** Data privacy laws (like GDPR) change hone par, software ko new regulations ke according update karna padta hai.

5. **Business Process Changes:**
   - Business operations aur processes me changes hone par bhi requirements update karne padte hain.
   - **Example:** Agar ek company apna CRM system upgrade karti hai, to naye process ke according software requirements bhi change karne padte hain.

6. **Stakeholder Input:**
   - Different stakeholders (e.g., managers, developers) ke inputs aur suggestions ke basis pe bhi requirements change hote hain.
   - **Example:** Developers suggest karte hain ki kuch features performance issues create kar rahe hain, to un features ko optimize karne ke liye requirements change hote hain.

### How are Requirements Traced?

Requirements tracing ka matlab hai ki requirements ko track karna throughout the project lifecycle, taki ensure kiya ja sake ki sabhi requirements meet ho rahe hain. Yeh ek systematic approach hai jo changes aur updates ko manage karne me help karta hai.

### Tracing Process:

1. **Requirement Identification:**
   - Har requirement ko unique ID assign kiya jata hai.
   - **Example:** `REQ-001: User login functionality`

2. **Requirement Documentation:**
   - Sabhi requirements ko detail me document kiya jata hai.
   - **Example:** `REQ-001: Users should be able to log in using their email and password.`

3. **Traceability Matrix:**
   - Traceability matrix create kiya jata hai jo requirements ko different project artifacts (like design documents, test cases) se link karta hai.
   - **Example:**
     | Requirement ID | Design Document | Test Case ID |
     |----------------|-----------------|--------------|
     | REQ-001        | DesignDoc-001   | TC-001       |
     | REQ-002        | DesignDoc-002   | TC-002       |

4. **Bi-Directional Traceability:**
   - Requirements ka traceability ensure karta hai ki requirements se related sabhi components (design, code, test cases) easily traceable ho.
   - **Example:**
     - Forward Traceability: Requirements se design aur code tak track karna.
     - Backward Traceability: Code aur test cases se original requirements tak track karna.

5. **Regular Reviews:**
   - Regular reviews aur audits conduct kiye jate hain to ensure ki sabhi requirements properly tracked aur implemented ho rahe hain.
   - **Example:** Monthly review meetings jaha requirements status aur traceability check kiya jata hai.

### Example Scenario:

Consider kariye ek project jisme ek online bookstore develop kiya ja raha hai. Initial requirements me book search functionality include thi. Lekin, project ke midway me, customers ne feedback diya ki advanced search options (like filtering by genre, author) ki zaroorat hai. Is feedback ko accommodate karne ke liye requirements change kiye gaye.

- **Original Requirement:** `REQ-005: Basic book search by title`
- **Updated Requirement:** `REQ-005: Advanced book search with filters by genre, author, publication year`

#### Tracing the Change:

1. **Requirement Update:**
   - Requirement document update kiya gaya to include new filters.

2. **Traceability Matrix Update:**
   - Updated matrix:
     | Requirement ID | Design Document | Test Case ID |
     |----------------|-----------------|--------------|
     | REQ-005        | DesignDoc-003   | TC-005       |
     | REQ-005        | DesignDoc-004   | TC-006       |

3. **Impact Analysis:**
   - Design aur test cases ko review kiya gaya to ensure ki updated requirements meet ho rahe hain.
   - New test cases likhe gaye to test advanced search functionality.

### Summary:
Requirement changes ke liye multiple factors responsible hote hain jaise customer feedback, market conditions, technological advances, etc. Requirement tracing ek systematic approach hai jo ensure karta hai ki changes effectively manage ho sake aur sabhi requirements project lifecycle me meet ho sake.




### Q10. Explaining Regression Testing Process in Simple Language

Regression testing is like 🔄 rechecking your work after making changes to ensure everything still works as expected. Here are the steps:

1. **Identify Test Cases**: 🎯 First, you need to figure out which parts of your project need testing. For example, if you're updating an e-commerce website's checkout process, you'd focus on testing the checkout page.

2. **Select Test Cases**: 📝 Once you know what to test, choose specific test cases that cover those areas. These test cases should represent typical scenarios and edge cases. For our e-commerce website, test cases might include scenarios like a successful purchase, a failed payment, and a checkout with a discount code.

3. **Prioritize Test Cases**: ⏰ Some test cases are more critical than others. Prioritize them based on importance and potential impact if they fail. For instance, a failed payment scenario might be more critical than testing the discount code functionality.

4. **Execute Test Cases**: ▶️ Now, run the selected test cases on the modified code. This checks if the changes introduced any new issues or broke existing functionality. For our example, we would run tests on the updated checkout process to ensure that customers can still complete their purchases smoothly.

5. **Compare Results**: 📊 Compare the results of the current tests with the expected results. Any discrepancies indicate potential problems that need fixing. If a test that previously passed now fails, it suggests that the recent changes might have caused a regression.

6. **Report and Track Issues**: 🚨 If any issues are found, report them to the development team. Make sure to track these issues until they are resolved. This ensures that problems are addressed promptly and effectively, maintaining the quality of the software.

The Most Important Step:
Every step in regression testing is crucial, but if we have to pick one, it would be **Identifying Test Cases**. Why? Because if you miss identifying the right areas to test, or if you overlook changes that need testing, your whole regression testing process could be flawed. Identifying the right test cases ensures thorough coverage and helps maintain the quality of the software.

## Q11. What are selective re-test techniques? How are they different from the 'retest all'?

### Selective Re-test:
Sirf kuch specific tests ko run karna jo impacted ho sakte hain.

### Retest All:
Sabhi tests ko dobara run karna.

## Q12.

### (a) Discuss the priority category schemes for the prioritization of test cases.

1. **Critical** - High impact, frequent use.
2. **Major** - Medium impact, occasional use.
3. **Minor** - Low impact, rare use.

### (b) What is the role of risk matrix for the reduction of test cases?

Risk matrix help karta hai prioritize karne me by identifying high-risk areas.

## Q13. How is risk analysis used in testing? How can we prioritize test cases using risk factor?

### Risk Analysis:
Identify karna high-risk areas ko jo sabse zyada impact kar sakte hain system ko.

### Prioritization:
Use risk matrix to assign priorities and select high-risk test cases.



### Risk Matrix:
Risk matrix ek tool hai jo risks ko assess karta hai based on impact and likelihood.

### Assigning Thresholds:
Define high, medium, and low thresholds based on potential impact and frequency.

### General vs. Version Specific Prioritization:
**General** - Test cases prioritized based on overall impact.
**Version Specific** - Test cases prioritized based on changes in the specific version.

### Example:
High-risk areas identified in the new release should be tested first (Version Specific).


**Risk Matrix kya hai?**
Risk matrix ek tarah ka chart hai jo humein bataata hai ki project mein kis tarah ke risks hain aur unka kya asar ho sakta hai. Socho, jaise tum apne ghar ka kaam kar rahe ho aur tumhe lagta hai ki electricity chali jayegi. Toh tum kuch cheezein karoge jaise candles aur torches ready rakho, taaki agar light chali gayi toh tum phir bhi kaam kar sako. Yeh wahi tarah ka kaam karti hai. Ismein hum different types ke risks ko identify karte hain aur unka asar dekhte hain.

**Thresholds aur Priority Categories kya hain?**
Thresholds matlab hai ek limit ya seema. Hum project mein alag alag tarah ke risks ko dekhte hain aur unko decide karte hain ki woh kitne important hain. Jaise ki, ek choti si baarish se road par accident ho sakta hai, lekin ek bada toofan aane par badi mushkil ho sakti hai. Usi tarah, ek choti si galti project mein minor problem create kar sakti hai, lekin badi galti project ko poora khatam bhi kar sakti hai.

**Example se samjhein:**
Socho, tum apna naya phone use kar rahe ho. Ab tumhe pata chalta hai ki phone ka screen bahut fragile hai. Toh tum extra dhyaan se rakho ge ki screen toot na jaaye. Yeh hai tumhara risk matrix. Ab agar tum screen ko zyada jor se dabao, toh screen toot sakti hai. Yeh hai risk ka asar. Aur agar screen toot jaati hai, toh phone use karna mushkil ho jaayega. Yeh hai impact.

**General vs. Version-Specific Test Case Prioritization:**
General test case prioritization mein hum overall dekhte hain ki kaunse test cases project ke liye sabse zyada zaroori hain. Lekin version-specific test case prioritization mein hum ek specific version ke liye dekhte hain ki kaunse test cases sabse important hain. Jaise ki, ek naya update aaya hai phone ke software mein, toh usmein kuch naye features aaye honge. Usi update ke liye hum test cases ko prioritize karenge.

**8. Important Differnces:**

   - **Alpha Testing vs Beta Testing:**
     - **Alpha Testing:**
       - 🧪 Aapke internal team dvaara product ki quality check ki jaati hai.
       - Udaharan: Ek naya shiksha software ko shikshakon se test kiya jaata hai.

     - **Beta Testing:**
       - 🌍 Bahar ke logon se product ki practicality ka pata lagaya jaata hai.
       - Udaharan: Ek naya mobile app launch se pehle beta testers ke saath share kiya jaata hai.

   - **Development Testing vs Regression Testing:**
     - **Development Testing:**
       - 🚧 Naye code ko early stage mein check kiya jaata hai.
       - Udaharan: Unit tests code ke alag-alag parts ko check karte hain.

     - **Regression Testing:**
       - 🔁 Code ke changes ko test kar ke dekha jaata hai ki koi naya bug to nahi aaya.
       - Udaharan: Ek bug ko fix karne ke baad regression testing kiya jaata hai.

   - **Fault vs Bug vs Failure:**
     - **Fault:**
       - ⚠️ Code mein ek problem ya mistake hoti hai.
       - Udaharan: Null pointer exception ka hona code mein ek fault hai.

     - **Bug:**
       - 🐞 Fault ka result hota hai jo code execute karte waqt aata hai.
       - Udaharan: Kisi button par click karne par kuch nahi ho raha, yeh ek bug hai.

     - **Failure:**
       - ❌ Jab software user ko expected result nahi deta.
       - Udaharan: Online shopping website crash ho jaati hai jab log sabse zyada online shopping kar rahe hote hain.

   - **Verification vs Validation:**
     - **Verification:**
       - ✅ Check kiya jaata hai ki software specifications ke according bana hai ya nahi.
       - Udaharan: Login page sahi usernames aur passwords ko accept kar rahi hai ya nahi, yeh verify kiya jaata hai.

     - **Validation:**
       - 🎯 Dekha jaata hai ki software user ke needs aur expectations ko meet kar raha hai ya nahi.
       - Udaharan: User interface design user-friendly hai ya nahi, yeh validate kiya jaata hai.

   - **Static vs Dynamic Testing:**
     - **Static Testing:**
       - 📝 Code aur documentation ko bina execution ke analyze kiya jaata hai.
       - Udaharan: Code reviews aur walkthroughs syntax errors aur design flaws ko identify karne ke liye kiye jaate hain.

     - **Dynamic Testing:**
       - 🔄 Code ko execute karke uski functionality ko validate kiya jaata hai.
       - Udaharan: Test cases chalakar yeh verify kiya jaata hai ki software alag-alag conditions mein sahi se kaam karta hai.

   - **Program vs Software:**
     - **Program:**
       - 🖥️ Ek particular task ko perform karne ke liye ek executable file ya application.
       - Udaharan: Microsoft Word ek program hai jo word processing tasks ke liye istemal hota hai.

     - **Software:**
       - 📦 Programs, data, aur documentation ka ek collection jo ek saath kaam karta hai.
       - Udaharan: Microsoft Office Suite mein kai saare programs jaise ki Word, Excel, aur PowerPoint hote hain.

   - **Test Case vs Test Suite:**
     - **Test Case:**
       - 🧪 Ek specific scenario ya condition jo software component ki functionality ko validate karta hai.
       - Udaharan: Ek test case jo yeh verify karta hai ki login page sahi credentials ko accept karta hai ya nahi.

     - **Test Suite:**
       - 📋 Ek collection of test cases jo execute aur report ke liye ek saath group kiya gaya hota hai.
       - Udaharan: Ek regression test suite jo yeh ensure karta hai ki recent changes ne koi new defects nahi introduce kiye hain.

   - **Deliverable vs Milestones:**
     - **Deliverable:**
       - 📦 Ek tangible ya intangible product ya service jo client ya stakeholders ko diya jaata hai.
       - Udaharan: Aakhri software application jo customer ko diya jaata hai, ek deliverable hai.

     - **Milestones:**
       - 🎉 Project timeline mein important points jo kisi phase ki completion ya goal ki achievement ko indicate karte hain.
       - Udaharan: Kisi project ke design phase ki completion ek milestone hai jo project ki poora hone ki disha mein progress ko darshata hai.
---
