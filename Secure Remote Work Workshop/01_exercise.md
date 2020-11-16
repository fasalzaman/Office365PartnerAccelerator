## Exercise 1 : Enable cloud or hybrid Identity 

Since we don't have any on-premise infrastructure, we will continue with Cloud identity only.

Now login to Microsoft 365 Admin Center https://admin.microsoft.com/ using the credentials provided in the environment details page. 

You are the having **Global Administrator** privilege on the Tenant and an Office 365 License to access various Apps.

Microsoft 365 Admin Centre will look like this :

<kbd>![](images/msac.jpg)</kbd>

Now lets try accessing teams for this user.

Open Teams online https://teams.microsoft.com/go# and sign-in using the credentials provided in the lab environment details page.

<kbd>![](images/teams.jpg)</kbd>

### Task 1 : Add a new user user with license assigned

Select **Active Users** under **User** tab to see all the active users in this tenant.

<kbd>![](images/activeusers.jpg)</kbd>

To add a new user, Click on **Add a User** button.

<kbd>![](images/adduser.jpg)</kbd>

In the Basics window that appear, provide the required details and click on **Next** 

<kbd>![](images/userbasic.jpg)</kbd>

In the Product License window, Select **Assign User a Product license** and check the box near Microsoft 365 E5 license. Then, Click on **Next**.

In the optional window setting that appear, click on **Next**.

<kbd>![](images/useroptional.jpg)</kbd>

In the next wind Click on **Finish adding** to create a new user 

<kbd>![](images/usercreate.jpg)</kbd>

https://docs.microsoft.com/en-us/microsoft-365/admin/add-users/add-users?view=o365-worldwide

Now you have 2 user, 1 with Global Admin privilege on the Tenant and another one with "No administrator" access.
We will be using the user account with Global Admin privilege (Lab User) for configuring Teams setting.

### Task 2 : Get Teams Ready for New User

Open Teams online https://teams.microsoft.com/go# and sign-in using new user's credentials.

<kbd>![](images/teams.jpg)</kbd>

Now you have teams ready for 2 users.
