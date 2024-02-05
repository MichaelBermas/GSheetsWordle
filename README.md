# GSheetsWordle
A replication of the game Wordle by Josh Wardle, but in Google Sheets, using only native Google Sheets functions and Google Apps Script's JavaScript extension.

### Main Game Sheet Link
Link: docs.google.com/spreadsheets/d/15_xCGjMbIXxvAzwTbQfwSGTXJk6dWpb4PeUSckIq3Jk/edit#gid=0  
This link contains the user-facing sheet where the player will start games, and input guesses.

### Backend Sheet Link
Link: https://docs.google.com/spreadsheets/d/1tUfWsYh2KUPUJhkqa5g2OavW-FKmaMEJ16PbeqHcXZE/edit#gid=0  
This link contains the sheet's backend, where the word database and the word to be guessed for each game instance can be found. This is joined to the main game sheet link through the **SpreadsheetApp.openbyiD()** method.
