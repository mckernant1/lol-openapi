# Lol OpenApi
A league of legends esports API.

Spring backend: https://github.com/mckernant1/lol-api-service

Documentation: https://mckernant1.github.io/lol-openapi/

[![Dashboard](https://img.shields.io/static/v1?label=AWS&message=Dashboard&color=green)](https://cloudwatch.amazonaws.com/dashboard.html?dashboard=Lol-Esports-Api-V2&context=eyJSIjoidXMtZWFzdC0xIiwiRCI6ImN3LWRiLTY1MzUyODg3Mzk1MSIsIlUiOiJ1cy1lYXN0LTFfWWdlV3dsS0tGIiwiQyI6Ijc4OHJ1bGIzdDNvaTc3dTJjbGhoOTlzbGNpIiwiSSI6InVzLWVhc3QtMTozZTFmYmM5Yi05MDZmLTQ5ZjQtOWFkYy0xZmE1OTJkNjk1YjkiLCJPIjoiYXJuOmF3czppYW06OjY1MzUyODg3Mzk1MTpyb2xlL3NlcnZpY2Utcm9sZS9DV0RCU2hhcmluZy1QdWJsaWNSZWFkT25seUFjY2Vzcy1YWDNITURQRyIsIk0iOiJQdWJsaWMifQ==)


## Authorization

Url: `https://v2-api.lol-esports.mckernant1.com`

## Platforms

### Java

![Version](https://badgen.net/maven/v/metadata-url/https/mvn.mckernant1.com/release/com/github/mckernant1/lol/esports-api/maven-metadata.xml)


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
implementation("com.github.mckernant1.lol:esports-api:0.0.9")
```



### Curl

```bash
curl https://v2-api.lol-esports.mckernant1.com/leagues
```
