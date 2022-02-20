# Lol OpenApi
A league of legends esports API


## Authorization

Url: `https://api.lol-esports.mckernant1.com`
Public Api Key: `CO6gm83RDj3U7LW2uFqKx41n0S834zFi4V7o2fKL`

## Platforms

### Java
Add maven to repositories
```
repositories {
    mavenCentral()
    jcenter()
    maven {
        url = uri("http://mckernant1-mvn.s3-website-us-west-2.amazonaws.com/release")
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
