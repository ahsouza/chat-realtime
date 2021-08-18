In the integrated terminal, run the following command to install LibMan:

```sh
dotnet tool install -g Microsoft.Web.LibraryManager.Cli
```

Run the following command to get the SignalR client library by using LibMan

```sh
libman install @microsoft/signalr@latest -p unpkg -d wwwroot/js/signalr --files dist/browser/signalr.js --files dist/browser/signalr.min.js
```

The output looks like the following example:

```sh
wwwroot/js/signalr/dist/browser/signalr.js written to disk
wwwroot/js/signalr/dist/browser/signalr.min.js written to disk
Installed library "@microsoft/signalr@latest" to "wwwroot/js/signalr"
```