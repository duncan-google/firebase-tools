- Re-added a dialog to let users know TLS is being provisioned in App Hosting. (#7595)
- Improved Firebase Data Connect postgres security by granting fine grained SQL privileges to the users the need it. (#7578)
- Removed `dataconnect:sql:migrate` command hard dependency on 'roles/cloudsql.admin'. (#7578)
- Added support for setting the encryption configuration of restored firestore databases. (#7483)
- Added support for `VERIFY_AND_CHANGE_EMAIL` events in the Auth emulator. (#7618)
- Added the `appdistribution:group:list` and `appdistribution:testers:list` commands.
- Update supported range for Angular framework. (#7418)
- Fix (Angular 17+) temporary change the PORT in Angular server.ts (#6651)
