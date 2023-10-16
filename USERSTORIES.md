# USER STORY 1
**AS A** General user of smart schedule,
**I WANT TO** login and logout and link my academic calendar to the app
**NO LATER THAN** December 1st.

**ACCEPTANCE CRITERIA:**

- **GIVEN** login info, **IT NEEDS TO** save when I login.
- **GIVEN** a calendar, **IT NEEDS TO** be saved and preloaded when I login.
- **GIVEN** my school's Calendar, **WHEN** I link it to smart schedule, **IT WILL** link and display accordingly.

# USER STORY 2
**AS A** highschooler,
**I WANT TO** import my class schedule into the app,
**SO THAT** I can view all my classes and assignments in one place.

**ACCEPTANCE CRITERIA:**

- **GIVEN** my class schedule, **WHEN** I import it into the app, **IT WILL** display all my classes and their timings.
- **GIVEN** assignments, **WHEN** I add them to the app, **IT WILL** show them on the corresponding dates.

# USER STORY 3
**AS A** college student,
**I WANT TO** set reminders for assignments based on their importance,
**SO THAT** I can effectively prioritize and manage my workload.

**ACCEPTANCE CRITERIA:**

- **GIVEN** an assignment's importance level, **WHEN** I add it to the app, **IT WILL** allow me to set reminders based on its importance.
- **GIVEN** multiple assignments with different importance levels, **WHEN** I view my reminders, **IT WILL** display them in order of importance.
- **GIVEN** the completion of an assignment, **WHEN** I mark it as completed, **IT WILL** remove the associated reminder.

# USER STORY 4
**AS A** parent of a high school student,
**I WANT TO** receive notifications about my child's upcoming assignments and test dates,
**SO THAT** I can provide necessary support and encouragement.

**ACCEPTANCE CRITERIA:**

- **GIVEN** my child's class schedule and assignments, **WHEN** they are added to the app, **IT WILL** notify me of upcoming assignments and test dates.
- **GIVEN** the ability to customize notification preferences, **WHEN** I configure them, **IT WILL** send notifications as per my preferences.
- **GIVEN** the completion of an assignment or test, **WHEN** my child marks it as completed, **IT WILL** send a notification to inform me about their progress.

# USER STORY 5

**AS A** developer,
**I WANT TO** create an API for accessing metric data produced by users,
**SO THAT** I can analyze and monitor the application's performance.

**ACCEPTANCE CRITERIA:**

- **GIVEN** a request to access metric data, **WHEN** it is made via the API, **IT WILL** authenticate the user.
- **GIVEN** user-submitted metric data, **WHEN** it is received, **IT WILL** be stored in a structured database.
- **GIVEN** the need to query metric data, **WHEN** I make a request to the API, **IT WILL** support filtering and sorting options.
- **GIVEN** different user roles (Admin, User), **WHEN** they access the API, **IT WILL** grant or restrict access to metric data accordingly.
- **GIVEN** a request for metric data, **WHEN** it is processed, **IT WILL** return the data in JSON or XML format.
- **GIVEN** developers' need to understand the API, **WHEN** they consult the documentation, **IT WILL** provide comprehensive information about endpoints and data formats.
- **GIVEN** potential errors in data access, **WHEN** they occur, **IT WILL** handle them gracefully with clear error messages.
- **GIVEN** potential system loads, **WHEN** data is retrieved, **IT WILL** ensure the API can scale effectively.
- **GIVEN** the completion of an API update, **WHEN** data access methods change, **IT WILL** maintain backward compatibility.
- **GIVEN** data retrieval performance, **WHEN** accessing metric data, **IT WILL** meet acceptable response time benchmarks.
- **GIVEN** data access authorization, **WHEN** handling metric data, **IT WILL** regularly review and update access controls for security.
