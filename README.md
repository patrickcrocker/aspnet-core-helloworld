# ASP.NET Core Hello World

A simple ASP.NET Core web application for the [ASP.NET Core buildpack][].

## Push to Cloud Foundry

```
cf push -b https://github.com/cloudfoundry-community/dotnet-core-buildpack.git
```

## Run the app locally

1. Install ASP.NET Core by following the [Getting Started][] instructions
+ Clone this app
+ cd into the app directory and then `src/dotnetstarter`
+ Run `dotnet restore`
+ Run `dotnet run`
+ Access the running app in a browser at [http://localhost:5000](http://localhost:5000)

[Getting Started]: http://docs.asp.net/en/latest/getting-started/index.html
[ASP.NET Core buildpack]: https://github.com/cloudfoundry-incubator/dotnet-core-buildpack
