# nodejs-urlModule

The URL module splits up a web address into readable parts.
To include the URL module, use the require() method:
`var url = require('url'); `

### url.parse() :

Parse an address with the url.parse() method, and it will return a URL object with each part of the address as properties

after we store the arsed url in a variable we can access the separate section with folloing (host,pathname,search,query)
and go deeper like query.name etc.

#### required installation :

[nodejs](https://nodejs.org)

#### how to use:

- install the repo in your computer
- run node demo-url.js to get an example of url and how to split it to its part
- run node index.js to see how to use it on serving fles requested by clients.
  here is tow links to check it it working right :

1. http://localhost:8080/summer.html
2. http://localhost:8080/winter.html
