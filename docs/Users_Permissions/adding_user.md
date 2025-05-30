# Adding Users

Users can be added by the System Manager. To add users go to:

`Home > Users and Permissions > User`

**There are two main types of users:**

**Website users:** Customers, Suppliers, Students, etc., who have access only to the portal and not to any modules. 

**System Users:** People using software in the Company with access to modules, company data, etc.

Under User, a lot of info can be entered. For the sake of usability, the information entered for web users is minimal: First Name and Email.

An Email address is the unique key (ID) identifying the Users.

**1. How to Create a New User** 
1. Go to the User list, click on New.
2. Add an Email address and name of the user.
3. Save.

  ![Add User Details](../Images/add-user-details.png)

Details like Username and Language can also be changed.

**2. Features** 

**2.1 Setting Roles**
After saving, you will see a list of roles and checkboxes next to them. Just check the roles you want the user to have and save the document. The roles have pre-defined permissions, to know more about roles, click here. You can set Role profiles to use as a template which selects multiple roles together.

![Setting Roles](../Images/user-2.png)


**2.2 More Information** 
More information about the employee can be set from this section:

* Gender
* Phone
* Mobile No
* Birth Date
* Location
* Interests
* Bio
* Banner Image

Ticking on 'Mute Sounds' will mute sounds that play on interacting with documents. The user may need to do a Settings > Reload for the changes to take place.

**2.3 Change Password**

* **Set New Password:** As a System Manager, you can set a new password for the user if it needs to be changed.
* **Send Password Update Notification:** Send an email notification to the user that their password has been changed.
* **Log out from all devices while changing Password:** When changing the user's password, this logs out the user from PC and any mobile device they may have logged into.

**2.4 Document Follow** 
With this option you can follow various documents in the system and get email notifications when they are updated. Know more here.

**2.5 Email Settings**

* **Send Notifications for Email threads:** The user will get notifications for Email conversations that take place in document types like Opportunities.
* **Send Me A Copy of Outgoing Emails:** Sends the user a copy of the emails they send. This is useful for keeping track if the email got sent.
* **Allowed In Mentions:** Allow this user's name to appear in thread conversations so that they can be mentioned using '@'.
* **Email Signature:** Adding an email signature here will set it as default for all outgoing emails for the user. This is different from a footer which is set from the Company master.

**2.6 Email Inbox** 

Subscribe the user to different mailing lists of your company from this section. Add a new row and select the mailing list to assign this user. For example, mailing lists can be jobs, support, sales, etc. To know more about Email Inbox, click here.

**2.7 Allow Module Access** 
Users will have access to all modules for which they have role-based access. If you want to restrict access of certain modules for this user, un-check the modules from this list.

  ![Module Access](../Images/user-3.png)

**2.7.1 Module Profiles**

Role Profiles act as a template to store and select access to multiple modules. This Role Profile can then be assigned to a User. For example, HR Users will have access to multiple modules like HR, Payroll, etc. Role Profiles are useful to provide access to multiple modules at once when adding multiple users.

  ![Module Profile](../Images/module-profile.png)

**2.8 Security Settings**

* **Simultaneous Sessions:** Simultaneous login sessions the user is allowed. You can use the same set of credentials for multiple users by allowing more sessions. This can be restricted from System Settings globally. For cloud account, the total number of simultaneous sessions cannot exceed the total number of subscribed users.
* **User Type:** If the user has any role checked other than Customer, Supplier, Patient, or Student they automatically become a System User. This field is read-only.
* **Login After, Login Before:** If you wish to give the user access to the system only between office hours, or during weekends, specify it here. For example, if office hours are from 10 am to 6 pm, set the Login After, Login Before hours as 10:00 and 18:00.
* **Restrict IP:** Restrict user login to the IPs specified here. This can be used so that the user can log in only from office computers. Multiple IPs can be added separated by commas.
This section also shows other details like Last Login, Last IP, and Last Active time for the user.

**2.9 Third Party Authentication** 
This will allow users to use Facebook, Google, or GitHub to log in. To use this feature, signup for a developer account with Facebook, Google, GitHub, etc. Create an app on their console, specify an app name, the originating URL and callback URL, copy the client ID and client secret info here to start using.

For more details, go to this page.

**2.10 API Access** 
You can generate API Secret keys from this section using the Generate Keys button. This can be used to access your account's data from another application, for example, an offline POS system.

**2.11 After saving** 
After saving a user, these buttons will be seen on the dashboard area of the User master.

  ![User dashboard buttons](../Images/user-after-save.png)

**Permissions**

* **Set User Permissions:** Will take you to the User Permissions page of Bruce from where you can restrict Bruce's access to documents.
* **View Permitted Documents:** Will take you to the 'Permitted Documents For User' report for this user. Here you can see which documents does Bruce have access to. For example, on selected Sales Order, the list of Sales Orders Bruce has access to will be displayed.

**Password** 

* **Reset Password:** An email with instructions to reset the user's password will be sent to the user's Email Account.
* **Reset OTP Secret:** Reset OTP Secret for logging in via Two Factor Authentication.
Create User Email will let you create an Email Account for the user based on the email entered in the User master.

