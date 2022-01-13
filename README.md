# Supagrations
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
| command | description |
|---------|-------------|
| sg:create [migration-name] | create a new migration file in the migrations directory |
| sg:up {N} | apply latest migration; optional int to apply next N migrations |
| sg:down | rollback latest migration; optional int to rollback last N migrations |
| sg:redo | redo latest migration; optional int to redo last N migrations |