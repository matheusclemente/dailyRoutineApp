# DailyRoutine User Story

## Login/Registration Screen

### **Application registration:**
_As a new user, I want to register with a username, email and password, so that I can create an account and access the app features._

**Acceptance Criteria:**
1. System should verify if the email is valid.
2. Email should be unique to each acccount.

**Priority:** High.

### **Application login:**
_As a user, I want to login using my email and password, so that I can access my account and track my routine._

**Acceptance Criteria:**
1. User should be able to login with a registered email and valid password.
2. Text in password field should be hidden.
3. Logged user should be redirected to home screen.

**Priority:** High.

### **Error feedback on signup and login:**
_As a user, I want to receive a message if I enter the wrong username or password, so that I know my login attempt was unsuccessful._

**Acceptance Criteria:**
1. System should show an error messagem if no email or password is entered. 
2. System should show an error messagem if an invalid email or password is entered.

**Priority:** High.

### **Store user data:**
_As a user, I want to stay logged in between sessions, so that I don't need to enter my account information every session._

**Acceptance Criteria:**
1. User details should be saved in local storage.

**Priority:** Medium.
