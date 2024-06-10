# UNIT-I: Introduction to Software Quality and Testing 🧪💻

## Key Concepts

### 1. **Software Quality**
- **Definition**: Software quality ka matlab hai software kitna achha kaam kar raha hai aur user ki expectations ko pura kar raha hai.
- **Attributes**:
  - **Functionality**: Software woh sab kuch kar raha hai jo usse karna chahiye?
  - **Reliability**: Software har baar ek jaisa kaam kar raha hai?
  - **Usability**: Software use karne mein kitna aasan hai?
  - **Efficiency**: Software resources ko kitna achhe se use kar raha hai?
  - **Maintainability**: Software ko update aur modify karna kitna aasan hai?
  - **Portability**: Software different platforms par kitna asaani se chal sakta hai?
- **Example**: Ek mobile banking app jo smoothly run hoti hai, secure hai, user-friendly hai, aur different devices aur operating systems par kaam karti hai.

### 2. **Role of Testing**
- **Purpose**: Defects ko identify karna, software quality ensure karna, aur ye verify karna ki software user ki requirements ko pura kar raha hai.
- **Goals**:
  - **Detect Defects**: Bugs ko dhoondhna aur fix karna.
  - **Ensure Quality**: Confirm karna ki software quality standards aur requirements ko meet kar raha hai.
  - **Prevent Defects**: Testing ka use karke development process ko improve karna aur future defects ko prevent karna.
- **Example**: Ek naye e-commerce website par tests run karna taaki ensure ho sake ki ye user data ko securely handle karti hai, transactions correctly process karti hai, aur accha user experience deti hai.

# Verification vs. Validation (V&V) 🧪✔️

## **Verification** (Kya hum product sahi tarike se bana rahe hain?)

### Purpose
- **Verification**: Ensure karna ki software correctly develop ho raha hai aur specified requirements aur design specifications ko meet kar raha hai.

### Techniques
1. **Inspections**: Detailed examination of documents, design, code, etc., taaki errors ya improvement areas ko find kiya ja sake.
   - **Example**: Ek software design document ko review karna taaki ensure ho sake ki sabhi specified requirements sahi se cover aur implement ho rahe hain.
2. **Reviews**: Systematic assessment of software taaki issues identify ho sake, peers ya experts ke dwara.
   - **Example**: Code ka peer review karna taaki check kiya ja sake ki coding standards follow ho rahe hain aur koi logical errors nahi hain.
3. **Walkthroughs**: Step-by-step presentation by the author of the document ya code taaki feedback aur errors find kiya ja sake.
   - **Example**: Developer apne naye feature implementation ko team ko explain karta hai, aur sab milke potential issues ya improvements ko find karte hain.

### Example Scenario
Maan lo aap ek naye online shopping feature ko develop kar rahe ho e-commerce site ke liye. Verification phase ke dauraan:
- **Inspections**: Aap design document inspect karoge taaki ensure ho sake ki sabhi zaroori user requirements jaise items add karna, cart dekhna, aur checkout karna included hain.
- **Reviews**: Aap developers ki team se code review karwaoge taaki ensure ho sake ki code company ke coding standards ko follow kar raha hai aur logically sound hai.
- **Walkthroughs**: Lead developer naye shopping cart feature ko team ko present karta hai, explain karta hai kaise implement kiya, aur team feedback provide karti hai.

## **Validation** (Kya hum sahi product bana rahe hain?)

### Purpose
- **Validation**: Ensure karna ki software user needs aur requirements ko meet kar raha hai, yani ki final product end-user ke expectations ko fulfill kar raha hai.

### Techniques
1. **Testing**: Software ko execute karna taaki defects find kiye ja sake aur ensure ho sake ki requirements meet ho rahe hain.
   - **Example**: Naye shopping cart feature par various test cases run karna taaki ensure ho sake ki ye different conditions mein correctly kaam kar raha hai, jaise items add karna, remove karna, aur checkout karna.
2. **User Acceptance Testing (UAT)**: End-users software ko test karte hain taaki ensure ho sake ki ye unki needs aur requirements ko meet kar raha hai before live jana.
   - **Example**: Shopping cart feature ke beta testing ko conduct karna taaki end-users se feedback mila ja sake aur ensure ho sake ki software intended tarike se function kar raha hai.

### Example Scenario
Jab software ka development complete ho jata hai, validation phase ke dauraan:
- **Testing**: Various scenarios aur conditions ko test karke ensure kiya jata hai ki software correctly kaam kar raha hai. Jaise shopping cart feature ke liye, items ko add, remove, aur checkout karke dekha jata hai ki sab kuch expected tarike se kaam kar raha hai.
- **User Acceptance Testing (UAT)**: Actual end-users naye shopping cart feature ko use karke feedback dete hain. Yeh ensure karta hai ki software real-world environment mein user expectations ko meet kar raha hai.

## Summary
- **Verification**: Ensure karta hai ki software correct tarike se develop ho raha hai (kya hum product sahi tarike se bana rahe hain?).
- **Validation**: Ensure karta hai ki software user needs ko meet kar raha hai (kya hum sahi product bana rahe hain?).


### 5. **Testing Activities and Levels**
- **Activities**:
  - **Planning**: Testing activities ke scope, approach, resources, aur schedule ko define karna.
  - **Designing**: Detailed test cases aur procedures ko create karna based on requirements.
  - **Executing**: Tests run karna aur outcomes ko record karna.
  - **Reporting**: Test results aur jo defects mile unko document karna.


  ## 📊 **Levels of Testing:**

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

### 6. **White-Box and Black-Box Testing ⚫⚪**
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

**Techniques**:

- **White-Box Testing Techniques**:
  - **Code Coverage**: Yeh technique check karta hai ki kitna percentage code execute hua hai during testing. Agar sabhi lines of code test nahi hote, toh kuch bugs chhup jaate hain. For example, agar ek sorting function mein code coverage 80% hai, toh yeh indicate karta hai ki 80% code lines test ki gayi hain aur baki 20% abhi bache hain. 📊
  - **Path Testing**: Is technique mein sabhi possible paths ya flows ko test kiya jata hai. Har ek path ko at least ek baar execute karna important hota hai. For example, agar ek function mein do branches hain, jaise if aur else, toh path testing mein har branch ka flow test kiya jata hai. 🛤️
  - **Loop Testing**: Yeh technique loops ko test karne ke liye use hoti hai. Loop ko zero, ek, aur multiple times execute kiya jata hai. For example, agar ek loop mein code hai jo 5 baar chalta hai, toh loop testing mein isse 0, 1, aur 5 baar execute kiya jata hai. 🔄

- **Black-Box Testing Techniques**:
  - **Equivalence Partitioning**: Is technique mein input ranges ko classes mein divide kiya jata hai aur phir har class ke ek representative value ka use kiya jata hai testing ke liye. For example, agar ek input field ki range 1 se 100 hai, toh hum ise teen classes mein divide kar sakte hain: 1-33, 34-66, aur 67-100. 🧩
  - **Boundary Value Analysis**: Yeh technique input ki boundaries ko test karta hai, jaise ki minimum aur maximum values. Hum typically input ke minimum, maximum, aur inke beech ke values ko test karte hain. For example, agar ek input field ki range 1 se 100 hai, toh hum test karenge 1, 100, aur 2-99 ke beech ke values ko. 🚧
  - **Decision Table Testing**: Is technique mein different input combinations ke liye test cases banaye jaate hain. Har possible combination ko cover karna important hota hai. For example, agar ek application mein ek function hai jo inputs ke basis par decisions leta hai, toh hum different inputs ke combinations ke liye test cases create karenge. 📝


### 7. **Test Case Selection**
- **Sources of Information**:
  - **Requirements Documents**: Detailed descriptions ki software kya karna chahiye.
  - **User Stories**: Brief statements of desired functionality from the user's perspective.
  - **Design Documents**: Technical specifications detailing ki software kaise banaya jana chahiye.
- **Example**: Login feature ke liye test cases create karna based on user stories jo describe karti hain ki different users login process ke sath kaise interact karenge.

### 8. **Test Planning and Design**
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

### 9. **Monitoring and Measuring Test Execution 📈**
- **Monitoring**:
  - **Definition**: Testing activities ke progress ko track karna aur ensure karna ki ye schedule par hain.
  - **Tools**: Test management software (e.g., JIRA, TestRail).
  - **Example**: Dashboard use karke real-time mein passed, failed, aur pending test cases ko monitor karna.
- **Measuring**:
  - **Definition**: Test results aur metrics ko analyze karna taaki testing ki quality aur effectiveness ko evaluate kiya ja sake.
  - **Metrics**: Defect density, test coverage, pass/fail rates.
  - **Example**: Module ke defects per mile number ko analyze karna taaki areas identify ho sake jo zyada attention chahiye.

### 10. **Test Tools and Automation 🤖**
- **Test Tools**:
  - **Definition**: Software applications jo testing processes mein madad karti hain.
  - **Types**: Test management tools, defect tracking tools, automation tools.
  - **Example**: Automated browser testing ke liye Selenium use karna.
- **Automation**:
  - **Definition**: Repetitive tests ko automatically perform karne ke liye scripts likhna.
  - **Benefits**: Time save hota hai, accuracy badhti hai, aur frequent testing allow karta hai.
  - **Example**: Web application ke login tests ko automate karna taaki ensure ho sake ki deployment ke baad consistent behavior ho.

## UNIT Testing: Concept and Types

### 11. **UNIT Testing**
- **Concept**: Individual components ya modules of a software application ko test karna taaki ensure ho sake ki ye sahi se kaam kar rahe hain.
  - **Static UNIT Testing**:
    - **Definition**: Code ko review karna bina execute kiye hue.
    - **Techniques**: Code inspections, reviews, walkthroughs.
    - **Example**: Code review session conduct karna taaki logical errors ko function mein find kiya ja sake.
  - **Dynamic UNIT Testing**:
    - **Definition**: Code ko execute karna aur uske behavior ko expected outcomes ke sath verify karna.
    - **Techniques**: Test cases run karna aur outputs ko check karna.
    - **Example**: Test cases run karna taaki check kiya ja sake ki function correctly sum of two numbers calculate kar raha hai.
### 12. **Defect Prevention**
- **Methods**:
  - **Code Reviews**: Regularly code review karna taaki issues early stage mein hi catch ho jaye.
  - **Pair Programming**: Do developers ek sath ek workstation par kaam karte hain.
  - **Static Analysis Tools**: Tools jo bina code execute kiye potential errors ko analyze karti hain.
- **Example**: Static analysis tools like SonarQube use karna taaki potential code quality issues identify kiya ja sake before wo defects ban jaye.

### 13. **Mutation Testing 🧬**
- **Concept**: Software code mein chhoti modifications (mutations) karna taaki check kiya ja sake ki existing test cases changes ko detect kar sakti hain ya nahi.
- **Purpose**: Ensure karna ki test cases robust hain aur errors ko catch kar sakti hain.
- **Example**: Code mein conditional statement ko change karna (e.g., `==` to `!=`) taaki dekha ja sake ki test cases fail ho rahe hain ya nahi, indicating ki wo correctly error ko detect kar rahe hain.

### 14. **Debugging 🐞**
- **Process**:
  - **Identify the Bug**: Code mein error locate karna.
  - **Analyze the Bug**: Error ka cause aur impact samajhna.
  - **Remove the Bug**: Code fix karna taaki error eliminate ho jaye.
  - **Test the Fix**: Verify karna ki fix kaam kar raha hai aur naya issue introduce nahi ho raha.
- **Example**: Debugger use karke code step by step chalana aur ek null pointer exception fix karna jo application crash kar raha hai.

---

📚 **Happy Learning and Testing!** 🧑‍💻✨
