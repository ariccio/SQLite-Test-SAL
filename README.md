# SQLite-Test-SAL
I'm toying with the use of SAL in a large, and well tested system (SQLite)

I intend for this to eventually be a drop-in "replacement" for SQLite, for users of SQLite, to errors in their own usage of the SQLite API. By carefully annotating the API, I've enabled `/analyze` to detect insidious bugs in API misuse.
