Software Requirements Specification (SRS)
Corrected Requirements
Requirement 1: User Interface

ID: R1

Description: The system shall provide a navigation menu on every page with clearly labeled buttons that allow users to access all main features within three clicks.

Rationale: Ensures the system is user-friendly and easy to navigate.

Testable: Verify that all main features are accessible within three clicks from any page.
Requirement 2: Student Records Security

ID: R2

Description: The system shall store all student records in an encrypted database and ensure that only authenticated users can access the records.

Rationale: Protects sensitive student information from unauthorized access.

Testable: Attempt to access student records without authentication and verify access is denied; check that stored records are encrypted.

Requirement 3: System Performance

ID: R3

Description: The system shall load any page within 3 seconds when accessed with a standard 10 Mbps internet connection.

Rationale: Ensures quick response time and improves user experience.

Testable: Measure page load time under standard network conditions; must be ≤ 3 seconds.

Requirement 4: User Registration

ID: R4

Description: The system shall allow a new user to register by providing a unique email and password.

Rationale: Enables users to create accounts securely.

Testable: Attempt to register with a unique email and verify account creation.

Requirement 5: User Login

ID: R5

Description: The system shall allow registered users to log in using their email and password.

Rationale: Ensures only authenticated users can access the system.

Testable: Attempt login with valid and invalid credentials and verify access.

Requirement 6: Profile Management

ID: R6

Description: The system shall allow logged-in users to update their personal information, including name, contact number, and profile picture.

Rationale: Provides flexibility for users to maintain accurate information.

Testable: Update profile data and verify changes are saved correctly.

Requirement 7: Notifications

ID: R7

Description: The system shall send an email notification to users within 1 minute whenever a new assignment is added or a grade is updated.

Rationale: Keeps users informed about important events promptly.

Testable: Add a new assignment or grade and verify email is received within 1 minute.