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

### **Introductory guide:**

_As a new user, I want to see a quick introductory guide on the home screen so that I can learn how to use the app._

**Acceptance Criteria:**

1. A pop-up should appear on the user's first interaction, showing the core functions of the app.
2. This pop-up should be accessible throught a help button, in case the user wants to consult it again.

**Priority:** Low.

## Detail Screen

### **Select event:**

_As a user, I want to access detailed information on a selected event so that I can read and/or edit details of any event in a day._

**Acceptance Criteria:**

1. Selecting an event should open detailed information, such as starting time and repeatability.
2. User should be able to edit details.

**Priority:** High.

## Persistent Data

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

## External API

### **Event location:**

_As a user, I want to add a location to an event so that I can plan where should I go during my day._

**Acceptance Criteria:**

1. Google Maps API should be integrated to the system.
2. User should have the option to add a location when editing event details.

**Priority:** Low.

## Settings Menu

### **Access settings:**

_As a user, I want to access a settings menu so that I can adjust preferences at my convenience._

**Acceptance Criteria:**

1. App should have a icon in the top corner that opens a settings menu.

**Priority:** High.

## Settings Screen

### **Notification preferences:**

_As a user, I want to adjust notification preferences so that I only receive alerts relevant to me._

**Acceptance Criteria:**

1. User should be able to turn off different notification categories, like promotional alerts.

**Priority:** High.

### **Dark mode:**

_As a user, I want to be able to enable dark mode so that I can reduce eye strain during nighttime._

**Acceptance Criteria:**

1. User should be able to select between light or dark mode, or set for folowing the system's theme.

**Priority:** Low.

### **Email and password change:**

_As a user, I want to update my email and password on the settings screen so that I can keep my account secure._

**Acceptance Criteria:**

1. User should be able to change the email and password used for log in, as long as a valid email is used.

**Priority:** High.

## Notifications

### **Daily reminder**

_As a user, I want to receive a daily reminder notification so that I don’t forget my tasks_

**Acceptance Criteria:**

1. App should send a push notification at the starting time of the users' routine.

**Priority:** Medium.

### **Event reminder**

_As a user, I want to receive a reminder notification for a specific event so that I don’t forget a task I recently added to my routine_

**Acceptance Criteria:**

1. App should send a push notification at the starting time of an event selected by the user.

**Priority:** Medium.

### **New features**

_As an admin, I want send notifications for relevant new features in the app so that the user can have the opportunity to engage with it._

**Acceptance Criteria:**

1. App should send a push notification when a new feature is implemented.
2. User should be able to turn off this notifications.

**Priority:** Low.
