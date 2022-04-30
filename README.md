# Okta Event Hook User Transfer

A Node.js application written to receive Event Hooks from Okta to sync new user profiles to a database. 


## Your Project

The Event Hook will be verified and post content to the /UserTransfer endpoint.

Upon the triggering event, the application will request additional information from Okta using the API key you've created.

The user will then be pushed to a SQLite Database.

A JSON object containing all users can be viewed at the /getUsers endpoint.


On the back-end,

- your app starts at `server.js`
- add frameworks and packages in `package.json`
- safely store app secrets in `.env` (nobody can see this but you and people you invite)

Click `Show` in the header to see your app live. Updates to your code will instantly deploy.


## Made by [Glitch](https://glitch.com/)

**Glitch** is the friendly community where you'll build the app of your dreams. Glitch lets you instantly create, remix, edit, and host an app, bot or site, and you can invite collaborators or helpers to simultaneously edit code with you.

Find out more [about Glitch](https://glitch.com/about).

( ᵔ ᴥ ᵔ )