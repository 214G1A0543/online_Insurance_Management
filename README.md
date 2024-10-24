**Admin and Customer functionalities** for insurance management system.


This project is an Insurance Management System where both admin and customers have different roles and functionalities. The admin manages policies and customer queries, while customers can apply for policies and track their status.

### Admin Functionalities:
1. **Admin Account Creation:**
   - Admin can create an account using the `createsuperuser` command provided by Django. Once created, the admin can log in to access the admin dashboard.

2. **Customer Management:**
   - Admin can view a list of all registered customers.
   - Admin has the authority to update or delete customer accounts if necessary.

3. **Policy Category Management:**
   - Admin can view, add, update, and delete policy categories such as Life, Health, Motor, and Travel.

4. **Policy Management:**
   - Admin can view, add, update, and delete insurance policies within the system.

5. **Policy Holder Management:**
   - Admin can view the total number of policyholders.
   - Admin can filter policyholders by status: approved policyholders and disapproved policyholders.

6. **Policy Approval:**
   - When a customer applies for a policy, the application enters a pending state.
   - Admin can review and approve or disapprove policies applied for by customers.

7. **Customer Queries:**
   - Admin can view and respond to questions asked by customers.

### Customer Functionalities:
1. **Account Creation:**
   - Customers can create accounts without requiring approval from the admin.
   - After successful registration, they can log in to access their dashboard.

2. **View Policies:**
   - After logging in, customers can view all available insurance policies added by the admin.

3. **Apply for Policies:**
   - If a customer is interested in any policy, they can apply for it.
   - Once applied, the policy application enters a pending state until reviewed and approved by the admin.

4. **Check Policy Status:**
   - Customers can check the status of their applied policies in the **History** section, where the status will be updated based on the admin’s approval or disapproval.

5. **Ask Questions:**
   - Customers can ask questions to the admin regarding policies or other matters. These questions will be visible to the admin for responses.
.
