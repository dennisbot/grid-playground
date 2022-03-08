In order to easily setup this example:

1. Use vscode.
2. Install this plugin:
https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer
3. __Ctrl+Shift+P__ then write: 'Open Settings (JSON)', without quotes (it will autocomplete), then, select it.
4. Inside `settings.json` Add this entry:
`{"liveServer.settings.root": "/src"}` src can change per project (or even be empty or not present at all in this config file), this sample project uses `/src` as the baseUrl. (default value is `/` same as root folder).
5. __Ctrl+Shift+P__ then write: 'live server: open with live server', without quotes (it will autocomplete), then, select it, a local server with `/src` as root will pop up (e.g.: http://127.0.0.1:8080/grid-2.html).
6. Go to terminal (in vscode hit alt to show up the menu bar, then click to `View` menu option, then click to `Terminal` sub-item menu option).
7. Make sure that your current project folder show up in the Terminal's prompt, execute `npm i` to install sass (described in the `package.json` file).
8. Finally, in the same Terminal location, execute one of the scripts, in this case:
`npm run sass-dev` to enable sass in watch mode so that the browser will update automatically.