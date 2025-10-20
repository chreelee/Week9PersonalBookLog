# Week9PersonalBookLog

For week 9, the project I decided on was to create a personal book log that will allow a reader to log their books, details, and ratings into a database. This database will hold all of the entered book information and will be searchable by varying criteria including rating, genre, and author.

The planner table can be found in the docx Word file found in this repository.

|Week|Concept|Feature|Goal|Acceptance Criteria|Evidence in README.md|Test Plan|
|----|-------|-------|----|-------------------|---------------------|---------|
|10|Modeling|Create Book entity and Statistics page|App can create books and display statistics page|[ ] book table displayed [ ] table sortable and searchable[ ] statistics page displays|Implemented code, README write-up, screenshots as needed|Run migration, test database tables exist|
|11|Separations of Concerns / DI|Add ISortingService to sort by criteria of rating and genre, Add Statistics page that will aggregate information|Move logic out of controller into a service|[ ] service registered in DI[ ] controller uses constructor injection [ ] criteria are displayed correctly|Implemented code, README write-up, screenshots as needed|Call endpoint, verify criteria view is shown correctly|
|12|CRUD|Add create/edit/update forms for Books|User can add, edit, and delete books|[ ] form displays [ ] validation message shows [ ] changes saved to DB|Implemented code, README write-up, screenshots as needed|Add new book, edit, delete, and confirm each DB update|
|13|Diagnostics|Add /healthz endpoint|App reports if Book DB is reachable|[ ] Healthy when DB is up[ ] Unhealthy when DB is down|Implemented code, README write-up, screenshots as needed|Stop database and text /healthz|
|14|Logging|Log every book entity and its changes|Record structured logs for book updates and criteria view requests|[ ] log message created[ ] log contains ID of book and DB request or change|Implemented code, README write-up, screenshots as needed|Perform CRUD actions and check log output|
|15|Stored Procedures|Call stored procedures of ‘library’ summary (displays total stats)|Show a summary of # of books, pages read, authors read|[ ] SP executes [ ] result summary displays|Implemented code, README write-up, screenshots as needed|Run SP in app and DB and compare results|
|16|Deployment|Deploy app to Azure App Service|Make app accessible in cloud with production settings|[ ] App Service created [ ] App builds and runs in Azure[ ] /healthz reachable [ ] one functional path works|Implemented code, README write-up, screenshots as needed|Visit public URL, confirm health endpoint and one page loads|
