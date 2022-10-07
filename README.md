# angular-9-Demo app
 
 
# npm install and then ng serve --port 4400
Access the web application using http://localhost:4400
It should redirect you to the login page ..click on register then create a new account.
After login, you should see Home, Users, Logout menu buttons into the header there.
 
FYI.. We are using a fake backend provider using the localStorage for apis and data.
You may see the apis in "app/_services/account.service.ts"
But the actual BE api logic in "app/_helpers/fake-backend.ts"
 
 
## 1. UI Task:-
a.) Please add a new button as "My Profile" into the header just before the Logout button.
b.) It should redirect us to the new My Profile page.
c.) My Profile page should have First Name, Last Name, Username, Password fields.
d.) Currently logged in user details should be auto populated.
e.) It should have a submit button to save the details.
- First Name, Last name fields are mandatory.
- Username field should be disabled.
- Password field is non mandatory, If it is not supplied then it should not overwrite the password value.
But should overwrite if provided.
 
## 2. Update profile api logic Task.
f.) We already have an "update" api in account service. You can use that to update My profile details.
But please add a logic to update the details in "updateUser" function into the " app/_helpers/fake-backend.ts"

