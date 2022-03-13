# Lol OpenApi
A league of legends esports API

Documentation: https://mckernant1.github.io/lol-openapi/

[![Dashboard](https://img.shields.io/static/v1?label=AWS&message=Dashboard&color=green)](https://cloudwatch.amazonaws.com/dashboard.html?dashboard=Lol-Esports-API&context=eyJSIjoidXMtZWFzdC0xIiwiRCI6ImN3LWRiLTY1MzUyODg3Mzk1MSIsIlUiOiJ1cy1lYXN0LTFfWWdlV3dsS0tGIiwiQyI6Ijc4OHJ1bGIzdDNvaTc3dTJjbGhoOTlzbGNpIiwiSSI6InVzLWVhc3QtMTpiMWEzODM2My1mYjA5LTQzYmYtYTQyYi0yNTkyYWM0OTQ4YzUiLCJPIjoiYXJuOmF3czppYW06OjY1MzUyODg3Mzk1MTpyb2xlL3NlcnZpY2Utcm9sZS9DV0RCU2hhcmluZy1QdWJsaWNSZWFkT25seUFjY2Vzcy1JOE5RVldYVCIsIk0iOiJQdWJsaWMifQ==)


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
