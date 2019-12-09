# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200 My Answer:
```
Could not get any response
There was an error connecting to 200.
Why this might have happened:
The server couldn't send a response:
Ensure that the backend is working properly
Self-signed SSL certificates are being blocked:
Fix this by turning off 'SSL certificate verification' in Settings > General
Proxy configured incorrectly
Ensure that proxy is configured correctly in Settings > Proxy
Request timeout:
Change request timeout in Settings > General
```
2. 301 My Answer :
```
Could not get any response
There was an error connecting to 301.
Why this might have happened:
The server couldn't send a response:
Ensure that the backend is working properly
Self-signed SSL certificates are being blocked:
Fix this by turning off 'SSL certificate verification' in Settings > General
Proxy configured incorrectly
Ensure that proxy is configured correctly in Settings > Proxy
Request timeout:
Change request timeout in Settings > General
```
3. 400 My Answer :
```
Could not get any response
There was an error connecting to 400.
Why this might have happened:
The server couldn't send a response:
Ensure that the backend is working properly
Self-signed SSL certificates are being blocked:
Fix this by turning off 'SSL certificate verification' in Settings > General
Proxy configured incorrectly
Ensure that proxy is configured correctly in Settings > Proxy
Request timeout:
Change request timeout in Settings > General
```
4. 401 My Answer:
```
Could not get any response
There was an error connecting to 401.
Why this might have happened:
The server couldn't send a response:
Ensure that the backend is working properly
Self-signed SSL certificates are being blocked:
Fix this by turning off 'SSL certificate verification' in Settings > General
Proxy configured incorrectly
Ensure that proxy is configured correctly in Settings > Proxy
Request timeout:
Change request timeout in Settings > General
```
5. 403
```
Could not get any response
There was an error connecting to 403.
Why this might have happened:
The server couldn't send a response:
Ensure that the backend is working properly
Self-signed SSL certificates are being blocked:
Fix this by turning off 'SSL certificate verification' in Settings > General
Proxy configured incorrectly
Ensure that proxy is configured correctly in Settings > Proxy
Request timeout:
Change request timeout in Settings > General
```
6. 404
```
Could not get any response
There was an error connecting to 404.
Why this might have happened:
The server couldn't send a response:
Ensure that the backend is working properly
Self-signed SSL certificates are being blocked:
Fix this by turning off 'SSL certificate verification' in Settings > General
Proxy configured incorrectly
Ensure that proxy is configured correctly in Settings > Proxy
Request timeout:
Change request timeout in Settings > General
```
7. 418 My Answer:
```
Could not get any response
There was an error connecting to 418.
Why this might have happened:
The server couldn't send a response:
Ensure that the backend is working properly
Self-signed SSL certificates are being blocked:
Fix this by turning off 'SSL certificate verification' in Settings > General
Proxy configured incorrectly
Ensure that proxy is configured correctly in Settings > Proxy
Request timeout:
Change request timeout in Settings > General
```
8. 500 My Answer:
```
Could not get any response
There was an error connecting to 500.
Why this might have happened:
The server couldn't send a response:
Ensure that the backend is working properly
Self-signed SSL certificates are being blocked:
Fix this by turning off 'SSL certificate verification' in Settings > General
Proxy configured incorrectly
Ensure that proxy is configured correctly in Settings > Proxy
Request timeout:
Change request timeout in Settings > General
```


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat


# Part Two

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and a snippet of the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact
```
https://catfact.ninja/breeds?
{
    "current_page": 1,
    "data": [
        {
            "breed": "Abyssinian",
            "country": "Ethiopia",
            "origin": "Natural/Standard",
            "coat": "Short",
            "pattern": "Ticked"
        },
        {
            "breed": "Aegean",
            "country": "Greece",
            "origin": "Natural/Standard",
            "coat": "Semi-long",
            "pattern": "Bi- or tri-colored"
        },
        {
            "breed": "American Curl",
            "country": "United States",
            "origin": "Mutation",
            "coat": "Short/Long",
            "pattern": "All"
        },
        {
            "breed": "American Bobtail",
            "country": "United States",
            "origin": "Mutation",
            "coat": "Short/Long",
            "pattern": "All"
        },
        {
            "breed": "American Shorthair",
            "country": "United States",
            "origin": "Natural",
            "coat": "Short",
            "pattern": "All but colorpoint"
        },
        {
            "breed": "American Wirehair",
            "country": "United States",
            "origin": "Mutation",
            "coat": "Rex",
            "pattern": "All but colorpoint"
        },
        {
            "breed": "Arabian Mau",
            "country": "Arabian Peninsula",
            "origin": "Natural",
            "coat": "Short",
            "pattern": ""
        },
        {
            "breed": "Australian Mist",
            "country": "Australia",
            "origin": "Crossbreed",
            "coat": "Short",
            "pattern": "Spotted and Classic tabby"
        },
        {
            "breed": "Asian",
            "country": "developed in the United Kingdom (founding stock from Asia)",
            "origin": "",
            "coat": "Short",
            "pattern": "Evenly solid"
        },
        {
            "breed": "Asian Semi-longhair",
            "country": "United Kingdom",
            "origin": "Crossbreed",
            "coat": "Semi-long",
            "pattern": "Solid"
        },
        {
            "breed": "Balinese",
            "country": "developed in the United States (founding stock from Thailand)",
            "origin": "Crossbreed",
            "coat": "Long",
            "pattern": "Colorpoint"
        },
        {
            "breed": "Bambino",
            "country": "United States",
            "origin": "Crossbreed",
            "coat": "Hairless/Furry down",
            "pattern": ""
        },
        {
            "breed": "Bengal",
            "country": "developed in the United States (founding stock from Asia)",
            "origin": "Hybrid",
            "coat": "Short",
            "pattern": "Spotted/Marbled"
        },
        {
            "breed": "Birman",
            "country": "developed in France (founding stock from Burma)",
            "origin": "Natural",
            "coat": "Semi Long",
            "pattern": "Colorpoint"
        },
        {
            "breed": "Bombay",
            "country": "developed in the United States (founding stock from Asia)",
            "origin": "Crossbred",
            "coat": "Short",
            "pattern": "Solid"
        },
        {
            "breed": "Brazilian Shorthair",
            "country": "Brazil",
            "origin": "Natural",
            "coat": "Short",
            "pattern": "All"
        },
        {
            "breed": "British Semi-longhair",
            "country": "United Kingdom",
            "origin": "",
            "coat": "Medium",
            "pattern": "All"
        },
        {
            "breed": "British Shorthair",
            "country": "United Kingdom",
            "origin": "Natural",
            "coat": "Short",
            "pattern": "All"
        },
        {
            "breed": "British Longhair",
            "country": "United Kingdom",
            "origin": "",
            "coat": "Long",
            "pattern": ""
        },
        {
            "breed": "Burmese",
            "country": "Burma and Thailand",
            "origin": "Natural",
            "coat": "Short",
            "pattern": "Solid"
        },
        {
            "breed": "Burmilla",
            "country": "United Kingdom",
            "origin": "Crossbreed",
            "coat": "Short/Long",
            "pattern": ""
        },
        {
            "breed": "California Spangled",
            "country": "United States",
            "origin": "Crossbreed",
            "coat": "Short",
            "pattern": "Spotted"
        },
        {
            "breed": "Chantilly-Tiffany",
            "country": "United States",
            "origin": "",
            "coat": "",
            "pattern": ""
        },
        {
            "breed": "Chartreux",
            "country": "France",
            "origin": "Natural",
            "coat": "Short",
            "pattern": "Solid"
        },
        {
            "breed": "Chausie",
            "country": "France",
            "origin": "Hybrid",
            "coat": "Short",
            "pattern": "Ticked"
        }
    ],
    "first_page_url": "https://catfact.ninja/breeds?page=1",
    "from": 1,
    "last_page": 4,
    "last_page_url": "https://catfact.ninja/breeds?page=4",
    "next_page_url": "https://catfact.ninja/breeds?page=2",
    "path": "https://catfact.ninja/breeds",
    "per_page": 25,
    "prev_page_url": null,
    "to": 25,
    "total": 98
}

```
1. A list of 150 random users in English.
1. All the repos on Github with Pursuit their name
1. All the JavaScript repos on Github with Pursuit in their name
1. All the Swift repos on Github with Pursuit in their name
1. A list of all Pokemon
1. A list of all items in Fortnite
1. A list of all Game of Thrones Episodes.
1. A list of all songs with "Love" in the title.
1. All information about Petyr Baelish from the Game of Thrones books
1. All the movies Leonardo Dicaprio has acted in


hi
