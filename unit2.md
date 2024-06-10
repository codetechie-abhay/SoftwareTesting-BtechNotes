# UNIT-II: Types of Testing and Test Processes 🧪🔍

## Key Concepts

### 1. **Testing Activities and Levels**
- **Activities**:
  - **Planning**: Testing activities ke scope, approach, resources, aur schedule ko define karna.
  - **Designing**: Detailed test cases aur procedures ko create karna based on requirements.
  - **Executing**: Tests run karna aur outcomes ko record karna.
  - **Reporting**: Test results aur jo defects mile unko document karna.

### 2. **Levels of Testing**
1. **Unit Testing**: 
   - **Kya Hota Hai**: Yeh process individual components ya modules ko test karne ka hai.
   - **Kaise**: Har ek function ya feature ko alag-alag test kiya jata hai.
   - **Udaharan**: Calculator app mein ek function jaise addition ko test karna.
2. **Integration Testing**: 
   - **Kya Hota Hai**: Isme application ke alag-alag parts ko ek saath test kiya jata hai.
   - **Kaise**: Calculation aur history features ko ek saath test kiya ja sakta hai.
   - **Udaharan**: Calculator app mein calculation aur history features ko saath mein test karna.
3. **System Testing**: 
   - **Kya Hota Hai**: Is level mein pure system ko test kiya jata hai.
   - **Kaise**: Pura application functionality, usability, aur performance ko test kiya jata hai.
   - **Udaharan**: Calculator app ke saare features ko, jaise ki calculations, memory usage, aur UI, ko test karna.
4. **Acceptance Testing**: 
   - **Kya Hota Hai**: Isme real-world environment mein end-users dwara system ko test kiya jata hai.
   - **Kaise**: End-users actual scenarios aur use cases ko simulate karte hain.
   - **Udaharan**: Real users ke dwara calculator app ko use karke calculations aur usability ko test karna.

🔍 **Example**:
- **Unit Testing**: Calculator app mein ek specific function, jaise ki 'Add' function, ko test karna.
- **Integration Testing**: Calculation aur history features ko ek saath test karke dekha jata hai ki kya calculations sahi hote hain aur history properly update hoti hai.
- **System Testing**: Pura calculator app ko test karke dekha jata hai ki saare features properly kaam kar rahe hain, UI acchi hai, aur koi performance issues nahi hain.
- **Acceptance Testing**: Real users ke dwara calculator app ko use karke dekha jata hai ki kya wo asani se calculations kar sakte hain aur kya UI intuitive hai.

## Testing Techniques

### 3. **White-Box and Black-Box Testing ⚫⚪**
- **White-Box Testing**:
  - **Definition**: Internal structures ya workings of an application ko test karna.
  - **Focus**: Code, paths, branches, conditions.
  - **Techniques**: Code coverage, path testing, loop testing.
  - **Example**: Ek sorting function ke logic ko test karna taaki ensure ho sake ki ye har condition mein sahi sort kar raha hai.
- **Black-Box Testing**:
  - **Definition**: Application ki functionality ko test karna bina internal structures ya workings ko jane hue.
  - **Focus**: Inputs aur outputs.
  - **Techniques**: Equivalence partitioning, boundary value analysis, decision table testing.
  - **Example**: Login functionality ko test karna by providing various inputs (valid, invalid, edge cases) taaki ensure ho sake ki ye expected tarike se behave kar raha hai.

### 4. **White-Box Testing Techniques**
- **Code Coverage**: Kitna percentage code execute hua hai during testing. For example, agar ek sorting function mein code coverage 80% hai, toh yeh indicate karta hai ki 80% code lines test ki gayi hain aur baki 20% abhi bache hain. 📊
- **Path Testing**: Sabhi possible paths ya flows ko test karna. For example, agar ek function mein do branches hain, jaise if aur else, toh path testing mein har branch ka flow test kiya jata hai. 🛤️
- **Loop Testing**: Loops ko test karna. Loop ko zero, ek, aur multiple times execute kiya jata hai. For example, agar ek loop mein code hai jo 5 baar chalta hai, toh loop testing mein isse 0, 1, aur 5 baar execute kiya jata hai. 🔄

### 5. **Black-Box Testing Techniques**
- **Equivalence Partitioning**: Input ranges ko classes mein divide karna aur har class ke ek representative value ka use karna testing ke liye. For example, agar ek input field ki range 1 se 100 hai, toh hum ise teen classes mein divide kar sakte hain: 1-33, 34-66, aur 67-100. 🧩
- **Boundary Value Analysis**: Input ki boundaries ko test karna, jaise ki minimum aur maximum values. For example, agar ek input field ki range 1 se 100 hai, toh hum test karenge 1, 100, aur 2-99 ke beech ke values ko. 🚧
- **Decision Table Testing**: Different input combinations ke liye test cases banana. For example, agar ek application mein ek function hai jo inputs ke basis par decisions leta hai, toh hum different inputs ke combinations ke liye test cases create karenge. 📝

### 6. **Test Case Selection**
- **Sources of Information**:
  - **Requirements Documents**: Detailed descriptions ki software kya karna chahiye.
  - **User Stories**: Brief statements of desired functionality from the user's perspective.
  - **Design Documents**: Technical specifications detailing ki software kaise banaya jana chahiye.
- **Example**: Login feature ke liye test cases create karna based on user stories jo describe karti hain ki different users login process ke sath kaise interact karenge.

### 7. **Test Planning and Design**
- **Test Planning**:
  - **Scope**: Kya test kiya jayega aur kya nahi kiya jayega.
  - **Objectives**: Testing ka aim kya hai.
  - **Resources**: Log, tools, aur materials jo testing ke liye chahiye.
  - **Schedule**: Testing activities ka timeline.
  - **Example**: Planning involve karta hai timelines aur resources define karna taaki ek naye feature ko e-commerce application mein test kiya ja sake.
- **Test Design**:
  - **Detailed Test Cases**: Specific inputs, execution conditions, aur expected results.
  - **Test Procedures**: Har test case ko execute karne ke steps.
  - **Example**: Login feature ke liye specific test steps likhna, including various input scenarios aur expected outcomes.

### 8. **Monitoring and Measuring Test Execution 📈**
- **Monitoring**:
  - **Definition**: Testing activities ke progress ko track karna aur ensure karna ki ye schedule par hain.
  - **Tools**: Test management software (e.g., JIRA, TestRail).
  - **Example**: Dashboard use karke real-time mein passed, failed, aur pending test cases ko monitor karna.
- **Measuring**:
  - **Definition**: Test results aur metrics ko analyze karna taaki testing ki quality aur effectiveness ko evaluate kiya ja sake.
  - **Metrics**: Defect density, test coverage, pass/fail rates.
  - **Example**: Module ke defects per mile number ko analyze karna taaki areas identify ho sake jo zyada attention chahiye.

### 9. **Test Tools and Automation 🤖**
- **Test Tools**:
  - **Definition**: Software applications jo testing processes mein madad karti hain.
  - **Types**: Test management tools, defect tracking tools, automation tools.
  - **Example**: Automated browser testing ke liye Selenium use karna.
- **Automation**:
  - **Definition**: Repetitive tests ko automatically perform karne ke liye scripts likhna.
  - **Benefits**: Time save hota hai, accuracy badhti hai, aur frequent testing allow karta hai.
  - **Example**: Web application ke login tests ko automate karna taaki ensure ho sake ki deployment ke baad consistent behavior ho.

## Unit Testing: Concept and Types

### 10. **Unit Testing**
- **Concept**: Individual components ya modules of a software application ko test karna taaki ensure ho sake ki ye sahi se kaam kar rahe hain.
  - **Static Unit Testing**:
    - **Definition**: Code ko review karna bina execute kiye hue.
    - **Techniques**: Code inspections, reviews, walkthroughs.
    - **Example**: Code review session conduct karna taaki logical errors ko function mein find kiya ja sake.
  - **Dynamic Unit Testing**:
    - **Definition**: Code ko execute karna aur uske behavior ko expected outcomes ke sath verify karna.
    - **Techniques**: Test cases run karna aur outputs ko check karna.
    - **Example**: Test cases run karna taaki check kiya ja sake ki function correctly sum of two numbers calculate kar raha hai.

### 11. **Defect Prevention**
- **Methods**:
  - **Code Reviews**: Regularly
