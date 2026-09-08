# Noura Requirements

## Functional Requirements

### Authentication
- FR-01: The system shall allow a new user to create an account using email and password.
- FR-02: The system shall allow registered users to log in.
- FR-03: The system shall allow users to log out.
- FR-04: The system shall allow users to request a password reset.
- FR-05: The system shall prevent unauthenticated users from accessing protected pages.

### Quran Tracker
- FR-06: The system shall display a 30-day Quran reading plan consisting of 30 Juz.
- FR-07: The user shall be able to mark a Juz as completed.
- FR-08: The user shall be able to undo a completed Juz.
- FR-09: The system shall save Quran progress for the logged-in user.
- FR-10: The system shall calculate completed Juz.
- FR-11: The system shall calculate remaining Juz.
- FR-12: The system shall calculate Quran completion percentage.

### Duas & Adhkar
- FR-13: The user shall be able to create a custom category.
- FR-14: The user shall be able to rename a category.
- FR-15: The user shall be able to delete a category.
- FR-16: The user shall be able to add an entry to a category.
- FR-17: The user shall be able to classify an entry as Dua or Dhikr.
- FR-18: The user shall be able to edit an existing entry.
- FR-19: The user shall be able to delete an entry.
- FR-20: The user shall be able to search saved entries.

### Dashboard
- FR-21: The Dashboard shall display Quran completion percentage.
- FR-22: The Dashboard shall display completed and remaining Juz.
- FR-23: The Dashboard shall display one Quran progress chart.

### User Data
- FR-24: The system shall store each user's data separately.
- FR-25: The system shall load the user's saved data after login.
- FR-26: The system shall prevent one user from reading or modifying another user's data.

## Non-Functional Requirements

- NFR-01: The application should be simple and easy to understand.
- NFR-02: The application shall work on desktop, tablet, and mobile devices.
- NFR-03: Normal pages should load and respond without unnecessary delay.
- NFR-04: Users shall only be able to access their own private data.
- NFR-05: Passwords shall be handled by the authentication provider and not stored manually by Noura.
- NFR-06: Saved Quran progress, Duas, and Adhkar shall remain available after logout and login.
- NFR-07: The application should handle failed requests without crashing.
- NFR-08: The application shall display understandable error messages.
- NFR-09: Important form fields shall have labels and keyboard-accessible controls.
- NFR-10: The code shall be organized into reusable and understandable components.
- NFR-11: The beta application should work on modern browsers such as Chrome and Edge.
- NFR-12: Personal Quran progress, Duas, and Adhkar shall not be publicly visible.
