
## Installation

Install data-push-nodejs with npm

```bash
  npm install my-project
  cd my-project
```
## API - endpoints - http://localhost:8800

### Account module - CRUD Endpoints

Create Account - http://localhost:8800/accounts/save

Find One Account - http://localhost:8800/accounts/:accountId

Find All Accounts - http://localhost:8800/accounts/getAll

Update Accounts - http://localhost:8800/accounts/update/:accountId

Delete Accounts - http://localhost:8800/accounts/delete/:accountId

### Destination module - CRUD Endpoints

Create Destination  - http://localhost:8800/destinations/save

Find One destinations (accountId in query params) - http://localhost:8800/destinations/:accountId

Find All destinations - http://localhost:8800/destinations/getAll

Update destinations - http://localhost:8800/destinations/update/:destinationsId

Delete destinations - http://localhost:8800/destinations/delete/:destinationsId
