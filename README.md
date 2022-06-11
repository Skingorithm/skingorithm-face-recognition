# API Face Recognition Skingorithm

-   Endpoint : `/skingorithm/predict`
-   HTTP Method : `POST`
-   Request Headers :
    -   Accept : `application/json`
-   Request Body :

```json
{
    "input": <base64 string face photo>
}
```

-   Request Header :
    -   Accept : `application/json`
-   Response Body (Success) :

```json
{
    {
    "output": {
        "acne": 99.92,
        "average": 93.97,
        "bspot": 100.0,
        "peye": 81.84,
        "wrinkle": 94.11
    },
    "success": true
}
}
```

-   Response Body (Fail) :

```json
{
    {
    "output": [],
    "success": false
}
}
```
