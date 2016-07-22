## Web Files


This code assumes your server for ES is on localhost.  For that to work properly, you need to allow CORS in your ES config yaml file.

````
  http.cors.enabled: true
  http.cors.allow-origin: "*"
````

Start it up after adding that.

You can use `python -m SimpleHTTPServer 8001` in the web directory and then open "localhost:8001".

The UI is not pretty -- it's meant to be a non-trivial example with few queries and some aggregation + details.   It should allow you to refine how you want your query (and maybe indexing) to work in your final design, as you play with it.

