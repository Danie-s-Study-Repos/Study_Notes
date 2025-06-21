# API 

## HOW TO MAKE AN API CALL

```html
https://api.openweathermap.org/data/3.0/onecall?
lat={lat}&lon={lon}&exclude={part}&appid={API key}
```

`?=>QUERY AND STARTS QUERY PARAMETERS`

`& STARTS A QUERY SUBDOMAIN`

##  Parameters start after base URL, start with a / and have a / for each parameter

## Anatomy of URL

1. PROTOCOL

- HTTPS

2. SUBDOMAIN

- WWW
  
3. ROOT DOMAIN

- NAME

4. TOP LEVEL DOMAIN

- .COM

5. SUBDIRECTORY

- /NAME
  - STARTS PATH

6. SLUG

- STARTS AFTER 2ND / 
  
## making a widget  
'''javascript
  
    async function()

    try{
    cost response = await fetch("https://api);
    if (!response.ok) {
        throw new Error
    }
    catch (error)
    console.log("oh NO!!")
}};
```