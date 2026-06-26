## Vytvoření aplikace: ##

dotnet new sln -n MiBa.ReactSpa

backend
dotnet new webapi -n MiBa.ReactSpa.Server

front end - přímo react
npm create vite@latest MiBa.ReactSpa.Client -- --template react-ts

přidání do projektu:
dotnet sln add MiBa.ReactSpa.Server/MiBa.ReactSpa.Server.csproj

společný start
přidání skriptu do package.json - viz skript dev-all - moc nefunguje

propojení proxy
přidání adresy do vite.config.ts
