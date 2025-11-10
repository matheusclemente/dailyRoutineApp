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

## Home Screen

### **Overview:**

_As a user, I want to view an overview of my data on the home screen so that I can quickly monitor my day._

**Acceptance Criteria:**

1. Home screen should show a list of the events for the day in chronological order.
2. User should be able to mark completed events.

**Priority:** High.

### **Introductory Guide:**

_As a new user, I want to see a quick introductory guide on the home screen so that I can learn how to use the app._

**Acceptance Criteria:**

1. A pop-up should appear on the user's first interaction, showing the core functions of the app.
2. This pop-up should be accessible throught a help button, in case the user wants to consult it again.

**Priority:** Low.

## Detail Screen

### **Select Event:**

_As a user, I want to access detailed information on a selected event so that I can read and/or edit details of any event in a day._

**Acceptance Criteria:**

1. Selecting an event should open detailed information, such as starting time and repeatability.
2. User should be able to edit details.

**Priority:** High.

## Integrate Persistent Data

### **Store user data:**

_As a user, I want to stay logged in between sessions, so that I don't need to enter my account information every session._

**Acceptance Criteria:**

1. User details should be saved in local storage.

**Priority:** Medium.

### **Store user preferences:**

_As a user, I want to save my preferences such as dark mode so that the app remembers my settings._

**Acceptance Criteria:**

1. User preferences should be saved in local storage.

**Priority:** Medium.
