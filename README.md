# Student Management - Node.js + MySQL

## Local
1. Install Node.js and MySQL.
2. Run database.sql in MySQL.
3. Run `npm install`.
4. Set DB_HOST, DB_PORT, DB_USER, DB_PASSWORD, DB_NAME (or use local defaults).
5. Run `npm start`.
6. Open http://localhost:3000

## Render
Render Web Service does not automatically provide a local MySQL database. Use a cloud-accessible MySQL provider, then add DB_HOST, DB_PORT, DB_USER, DB_PASSWORD, DB_NAME as Render environment variables.
Build command: `npm install`
Start command: `npm start`

After Save Student, Node.js inserts into MySQL and reloads the table. Refreshing the page keeps the record because it is stored in MySQL.
