# Supagrations 
***UNDER DEVELOPMENT 
node-pg-migrate boilerplate app for supabase

## Getting Started
#### Setup the project
1. Create a project directory and cd into it:
`mkdir supabaseDBApp && cd supabaseDBApp`
2. install dependencies:
`yarn install`
3. create a file called .env and copy the contents of example.env into it.
4. Copy the database connection string from the supabase console and update the DATABASE_URL in the .env file.
`DATABASE_URL=[paste your connection string here]`

#### commands
Commands to be run from project root like so:
`yarn [command] [args]`
| command | description |
|---------|-------------|
| sg:create [migration-name] | create a new migration file in the migrations directory |
| sg:up {N} | runs all up migrations from the current state; optional int to run next N migrations |
| sg:down {N} | rollback latest migration; optional int to rollback last N migrations |
| sg:redo {N} | redo latest migration; optional int to redo last N migrations |
| sg:downall | rollback all migrations |