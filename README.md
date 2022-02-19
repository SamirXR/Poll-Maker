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

then Add a Variable and it'll be helpful for admin to Reset the Poll

```ADMIN_KEY= 4455```

Choose a Key that you Desire/Prefer


 <a href="https://discord.gg/P9gGZaXWGR">
    <img src="https://discordapp.com/api/guilds/913750761924591666/widget.png?style=shield" alt="Discord Server">
  </a>

___________________________________________________________________________________________________________
