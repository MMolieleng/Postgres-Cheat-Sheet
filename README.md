# Postgres-Cheat-Sheet
My Postgres Cheatsheet


## Installation
Visit this 10 minutes video if you are a mac user
 - (Watch the video here) https://www.youtube.com/watch?v=wTqosS71Dc4&ab_channel=Prisma

# Running the server
- Open postgres app
- Click on start

## Connecting to the server
The below command will request for user's password
```sql
psql -U <username> -h <host>
```

## Show databases
Option 1 - Short version
```psql
\l
```

Option 2 - The full function name
```psql
\list
```

# Connecting to the database
- Open the terminal
```sql
psgl postgres://user@localhost:5432/database
```

