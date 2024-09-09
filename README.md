# E-Wallet-Management-System-PEGA


**Concepts covered in this projects are**
1. Case Lifecycle 
2. Alternate Flows-Optional Action 
3. Routing 
4. SLA 
5. Multi-step form 
6. Controlling the case workflow 
7. Adding fields to a case type 
8. Correspondence 
9. Manipulating case data 
10. Calculating case Values 
11. Validating case data 
12. Work Parties 
13. Reports 
14. Integration

**The process for E-Wallet Management System is as following:**
a. Accept the customer information via digital form 
b. Customer needs to add his/her bank details to any transaction. 
c. Once he/she adds the bank details we need to verify him with OTP. 
d. Once verification is done, now the customer can able to perform digital transaction using 
mobile number. 
e. While performing transaction, we are going to verify it using OTP. 
f. Before performing the transaction internally, it should check whether balance is available 
or not. 
g. If available balance is less than the transaction amount, the transaction should fail by 
showing available balance is less. 
h. After transactions is done we need to provide some info regarding the previous or 
current transaction information.

**Case Lifecycle for the E-Wallet Management System**
This case type has multiple stages  
 
1. Login 
2. Create Account 
3. Begin Transaction 
4. Add Bank Details 
5. Payment 
6. Transaction History 
 
**Login**: When the customer/User is already registered with our application they can directly Login 
using Username and Password. 
 
**Create Account**: If the Customer/User is new to the application they can register to the 
application by giving personal details, add Id proof and address proof.  
 
**Start transaction**: Customer/User must select the type of transaction what they want to perform. 

**Add Bank Details**: User can able to add bank details by providing the information like Bank name, 
Account number 

**Payment**: User need to enter the mobile number to whom he /she wants to send amount. While 
sending the amount we need to authenticate with a valid PIN number provided at the time of 
registration. On successful completion of the transaction the details need to be added into the 
Local Data source.  
 
**Transaction History**: The user can able to view the transactions based on Current month, 
Previous month, All transactions and based on mobile number. 
