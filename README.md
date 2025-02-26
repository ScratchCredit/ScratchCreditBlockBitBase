[/balance/\<user> example]: https://blockbit.yippymishy.com/balance/yippymishy
# ScratchCredit
All the server and API code for ScratchCredit, a (pretend) currency on Scratch!

# Files
**main.py** - Creates a thread for the API and a thread for the server.\
**server.py** - All of the main server code is in this file. It handles transactions, saving and returning peoples' balances, and anything else related to the Scratch project. There are a decent number of comments there to help you understand it.\
**api.py** - All of the code for the API (a Flask app) is here.
**admins.txt** - A list of all the admins, users who have extra permissions (one username per line)

### templates
**index.html** - The main page of the API

### secrets
**session_id.txt** - Put your Scratch session ID here

# API Docs
**/balance/\<user>** - returns the specified user's balance [[Example with yippymishy][/balance/\<user> example]]
