# RACEDAY_PART3
Add InitialCreate migration for the Part 2 schema
Add Azure.Storage.Blobs package and AzureStorage settings
Add IFileStorage and AzureBlobFileStorage service
Add image validation rules (type, size, file signature)
Add BannerBlob / ProfilePictureBlob columns and Enrolment status + migration
Add event banner upload endpoint
Add profile picture upload endpoint
Make event browsing public and add search/type/distance filters
Add GET /api/events/mine with enrolment totals
Add enrolment status endpoint and Pending default
Add totalFinishers to results
Add API tests for blob uploads, status, filters and finisher totals
Create RaceDay.Web MVC project and solution file
Add typed API client, session handler and friendly error mapping
Add session-based login, register and logout
Add RequireRole filter and role-based navigation
Add RaceDay Bootstrap theme, layout and shared partials
Add participant pages: events home with filters, event details + enrol
Add My Enrolments, My Results and Profile pages
Add organiser dashboard and event management (create/edit/delete + banner)
Add categories, enrolments and results entry pages
Add Dockerfiles, docker-compose, MVC tests, CI update and README
