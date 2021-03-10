# Heroku Buildpack for Metabase

Due to Heroku's ephemeral file system we need to download client's SSL keys before running the app.

Java Keystore would be an option, but we don't have experience with this tool
