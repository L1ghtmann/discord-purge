# discord-purge

Remove all of your messages from a given Discord guild (server) or a DM (direct message) channel.

## How to install:

### npm

	$ npm install

### yarn

	$ yarn

## How to use:

	$ node index.js

And follow the on-screen instructions.

## How to get the token (Firefox):

1. Log into your Discord account in the browser (https://discordapp.com/login).
2. Open the developer tools (press: Ctrl + Shift + I [on PCs] or Command + Shift + I [on Macs]).
3. Open the Network tab.
4. Filter for "/api" (may need to refresh the page for them to appear).
5. Select the [200] status entry with "library" in its 'File'.
6. Open the headers tab on the right-hand side.
7. Your token is the value for the "Authorization" key under the 'Request Headers' heading.

