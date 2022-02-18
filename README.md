# Poll Maker  : )

A poll built with Chart.js and powered by Node.js with a SQLite database.






FOR ADMIN (POLL MAKER)

- Go to `Index.hbs`

Then edit line `132` As Your desired Poll


```
<div class="poll-form">
<p>What do you like coding most? </p>
```



- Then move to `Sqlite.js`

Then edit line `40` As your desired Poll inputs

```
await db.run(
"INSERT INTO Choices (language, picks) VALUES ('HTML', 0), ('JavaScript', 0), ('CSS', 0)"
);
```

- Then Move to `.Env`

then E









*After that Setup Admin secret/Password for Resetting the poll*