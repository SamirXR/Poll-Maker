# Poll Maker  : )

A poll built with Chart.js and powered by Node.js with a SQLite database.






FOR ADMIN (POLL MAKER)

- Go to





















1. Add a link to `src/pages/index.hbs` after the form, which will send a query parameter to the server script:

```
<p>
 <a href="/?results=true">Show results</a>
</p>
```

2. Extend the `server.js` `GET` endpoint `/` to send a flag if the user requested the results:

```
// User requested results
params.results = request.query.results;
```

Click the __Show results__ link to see the results without voting!

_Tip: If you just cleared the log, make sure you vote again so that there are some results to show._ 🙈
