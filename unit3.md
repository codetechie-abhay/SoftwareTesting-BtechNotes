
---
# UNIT-III: System Integration Testing & Test Design 🔌🔍

## Topics:

### 1. 📚 Concept of Integration Testing
**Integration Testing** ka matlab hai alag-alag modules ya components ko saath me test karna taaki ensure ho sake ki wo sahi se saath kaam kar rahe hain.

🔹 **Example:** 
Socho tumhare paas ek shopping app hai jisme ek payment module aur ek shipping module hai. Integration testing yeh check karega ki payment module sahi se shipping module ke saath communicate kar raha hai ya nahi, jaise payment ke baad order status update ho raha hai ya nahi.

### 2. 🔗 Different Types of Interfaces and Interface Errors
**Interfaces** woh points hote hain jahan do systems ya components milte hain aur interact karte hain. **Interface errors** tab hote hain jab in interactions me koi issue aata hai.

🔹 **Example:** 
Humare shopping app me, ek interface error tab ho sakta hai jab payment module galat data format shipping module ko bhej de, jisse wo crash ho jaye.

### 3. ⚖️ Granularity of System Integration Testing
**Granularity** ka matlab hai testing ka level of detail. Yeh fine-grained (chote parts test karna) ya coarse-grained (bade parts test karna) ho sakta hai.

🔹 **Example:**
Fine-grained testing me hum sirf payment gateway aur cart system ka interaction test kar sakte hain. Coarse-grained testing me hum poore order process ko test karte hain, jisme payment se lekar delivery tak sab kuch aata hai.

### 4. 🛠️ System Integration Techniques
**System Integration Techniques** wo tarike hain jinse hum different modules ko integrate aur test karte hain.

🔹 **Example:**
Humare shopping app me hum bottom-up integration use kar sakte hain, jisme pehle hum lowest level modules (jaise individual functions) ko integrate karte hain, fir higher level modules ko.

### 5. 📝 Test Plan for System Integration
**Test Plan** ek document hota hai jo batata hai ki integration testing kaise ki jayegi. Isme objectives, scope, test items, resources, schedule, aur test cases include hote hain.

🔹 **Example:**
Humare shopping app ke liye test plan me yeh define hoga ki kaunse modules test karne hain, kis order me test karne hain, kya expected outcomes hain, aur kis time frame me testing complete hogi.

### 6. 🛒 Off-the-Shelf Component Testing
**Off-the-Shelf (OTS) components** wo components hote hain jo pre-made hote hain aur market me available hote hain. Inki testing ensure karti hai ki yeh humare system ke saath compatible hain.

🔹 **Example:**
Agar humare shopping app me hum ek third-party payment gateway use kar rahe hain, to hume ensure karna hoga ki yeh gateway humare app ke saath sahi se integrate ho raha hai aur kaam kar raha hai.

### 7. 🧪 System Test Categories
**System Test Categories** different types of tests ko define karti hain jo system pe perform kiye jate hain, jaise functionality testing, performance testing, security testing, etc.

🔹 **Example:**
Humare shopping app ke liye:
- **🔍 Functionality Testing:** Saare features sahi se kaam kar rahe hain ya nahi.
- **⚡ Performance Testing:** App heavy load me kaise perform karta hai.
- **🔒 Security Testing:** Vulnerabilities check karenge.

## 🛒 Comprehensive Example: Shopping App Integration Testing

Ab ek comprehensive example dekhte hain jis se sab concepts clear ho jayein.

### Scenario:
Tum ek shopping app develop kar rahe ho jisme teen main modules hain: **User Account**, **Payment**, aur **Shipping**.

1. **Concept of Integration Testing:**
   - **Testing Goal:** Ensure karo ki jab user payment kare, to payment module sahi se user account aur shipping module ko update kare.
   
2. **Different Types of Interfaces and Interface Errors:**
   - **Interface Example:** Payment module aur shipping module ka interaction.
   - **Possible Error:** Agar payment module ne galat order ID shipping module ko bhej di, to shipping details update nahi hongi.
   
3. **Granularity of System Integration Testing:**
   - **Fine-Grained Testing:** Test karo ki payment confirmation function sahi se shipping update function ko call kar raha hai.
   - **Coarse-Grained Testing:** Pura order process test karo, jisme user login se lekar payment aur shipping tak sab include ho.
   
4. **System Integration Techniques:**
   - **Bottom-Up Integration:** Pehle payment gateway aur database functions integrate karo, fir user interface aur finally pura system.
   
5. **Test Plan for System Integration:**
   - **Plan Example:** Define karo ki pehle user login aur account verification test hoga, fir payment processing aur end me shipping update.
   
6. **Off-the-Shelf Component Testing:**
   - **Example:** Third-party payment gateway (jaise PayPal) ko integrate karte waqt ensure karo ki saari functionalities sahi se kaam kar rahi hain.
   
7. **System Test Categories:**
   - **Functionality Testing:** Check karo ki user login, payment processing, aur shipping update sahi se ho rahe hain.
   - **Performance Testing:** Test karo ki jab ek hi time me bahut saare users payment kar rahe hain to system slow to nahi ho raha.
   - **Security Testing:** Ensure karo ki payment information secure hai aur vulnerabilities nahi hain.

