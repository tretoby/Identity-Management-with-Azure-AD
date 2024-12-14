# **Identity Management with Microsoft Entra ID: A Secure User Access Solution**

## **Project Overview**
In this project, I implemented a secure identity and access management system using **Microsoft Entra ID**. This showcases my ability to configure and manage user identities, secure resource access, and implement advanced identity protection mechanisms. The project highlights various real-world identity management tasks and security strategies.

---

## **Implementation Steps**

### **Step 1: Create a Tenant**
Navigate to **Entra ID** and create a new tenant.

![Create Tenant](https://github.com/user-attachments/assets/db24075a-429e-4918-b23d-267856eae4aa)

---

### **Step 2: Add Users to Entra ID**
Add multiple users to the tenant for testing purposes.

![Add Users](https://github.com/user-attachments/assets/650816da-c3d5-4df6-aeef-80a49095e64d)

#### Users Created:
1. Michael Jordan  
2. LeBron James  
3. Kobe Bryant  
4. Dwyane Wade  
5. Tracy McGrady  

![Users Created](https://github.com/user-attachments/assets/4dc0cd17-5e51-4739-ae81-97b5a0f99e7a)

---

### **Step 3: Group Management**
After creating the users, add them to a group and assign administrative privileges.

![Create Group](https://github.com/user-attachments/assets/1f9782ec-f6d0-485f-9276-e6e5fdf5bc1d)  
![Select Users](https://github.com/user-attachments/assets/36e4c77e-abb6-4e6e-9622-5ee9d181b15d)  
![Group Created](https://github.com/user-attachments/assets/962a77f7-c3e2-4127-baa8-c26a9874d93f)

---

### **Step 4: Assign Administrative Roles**
Assign **User Administrator** roles to Michael Jordan.

![Assign Role](https://github.com/user-attachments/assets/fe2c1e60-cb41-40d0-85fa-3197febeb314)

---

### **Step 5: Validate User Role Management**
Sign in as Michael Jordan to verify if he can manage other users successfully.

![Role Validation](https://github.com/user-attachments/assets/164a6067-6263-4126-bf5a-c01d0eedec07)

---

### **Step 6: Enable Self-Service Password Reset (SSPR)**
Enable **Self-Service Password Reset (SSPR)** for all users.

- Navigate to **Entra ID > Password Reset > Enable All**.

![Enable Password Reset](https://github.com/user-attachments/assets/c72be892-b1a1-4769-a500-00c41c16c2e8)

- Configure **Email Authentication Methods**.

![Email Authentication](https://github.com/user-attachments/assets/6df17a7c-5089-48bc-9e8e-b433d0f9ec2b)

#### Test the SSPR Functionality:
1. Log in as LeBron James and select "Forgot Password."  
   ![Forgot Password](https://github.com/user-attachments/assets/83dbdce8-b019-4979-8436-aafccaa9b685)  

2. Send a verification email to the alternate email.  
   ![Send Verification Email](https://github.com/user-attachments/assets/26239a9b-7505-4138-97ca-465edd846132)

3. Enter the new password and confirm the reset.  
   ![Password Reset Confirmation](https://github.com/user-attachments/assets/e3b2734d-1fcb-4b45-8413-cf5697ebe170)

---

### **Step 7: Implement Conditional Access**
Navigate to **Entra ID > Security > Conditional Access** to implement policies.

![Conditional Access](https://github.com/user-attachments/assets/2df4e2f5-54a5-4736-82a6-927020c7e192)

#### Policy Created:
- Block access to users outside the United States to enhance security.

![Block Access](https://github.com/user-attachments/assets/f9542c82-2779-44d0-8de1-3a8bac06c04e)

Validate that the conditional access policy is applied.

![Policy Validation](https://github.com/user-attachments/assets/80803410-b2a8-40fb-a220-d17b90f6fff0)

---

## **Conclusion**
This project demonstrates my ability to:
- Configure secure user access through **Microsoft Entra ID**.
- Manage identity roles and groups.
- Implement self-service password resets.
- Enforce advanced conditional access policies.






 























