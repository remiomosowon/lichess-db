# lichess DB

This code exports lichess game database in a standard PGN format.

Files are available on [https://database.lichess.org](https://database.lichess.org).

Use them to do great things. Please share the results!

## Usage

```
# export Jan 2016 games to lichess_db_2016-01.pgn"
sbt "run 2016-01"

# export Jan 2016 games to custom_file.pgn"
sbt "run 2016-01 custom_file.pgn"
```
