# Lol OpenApi
A league of legends esports API.
Requests may take up to 20 seconds to respond

Documentation: https://mckernant1.github.io/lol-openapi/

[![Dashboard](https://img.shields.io/static/v1?label=AWS&message=Dashboard&color=green)](https://cloudwatch.amazonaws.com/dashboard.html?dashboard=Lol-Esports-Api-Operations&context=eyJSIjoidXMtZWFzdC0xIiwiRCI6ImN3LWRiLTY1MzUyODg3Mzk1MSIsIlUiOiJ1cy1lYXN0LTFfWWdlV3dsS0tGIiwiQyI6Ijc4OHJ1bGIzdDNvaTc3dTJjbGhoOTlzbGNpIiwiSSI6InVzLWVhc3QtMTphYThiMWIxZC05NGI4LTQ2MDktYTRlOS0xMzU4NDlmMmRmMmIiLCJNIjoiUHVibGljIn0%3D)


## Authorization

Url: `https://api.lol-esports.mckernant1.com`

Public Api Key: `CO6gm83RDj3U7LW2uFqKx41n0S834zFi4V7o2fKL`

## Platforms

### Java
Add maven to repositories
```build.gradle.kts
repositories {
    mavenCentral()
    jcenter()
    maven {
        url = uri("https://mvn.mckernant1.com/release")
    }
}
```

Add dependency on esports-api
```
implementation("com.github.mckernant1.lol:esports-api:0.0.1")
```



### Curl

```bash
curl -H "X-API-KEY: CO6gm83RDj3U7LW2uFqKx41n0S834zFi4V7o2fKL" https://api.lol-esports.mckernant1.com/leagues
```
