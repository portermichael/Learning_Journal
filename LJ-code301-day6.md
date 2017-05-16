# LJ Code 301 - Day 5

Today we learned about AJAX and JSON in lecture. AJAX is a means to send and receive data from a server/localhost. When we send data it is in a string, so we have to run JSON.stringify on our object. When we receive data we must parse it with JSON.parse to get an object back.

REST refers to GET, POST, PUT/PATCH and DELETE commands. I didn't know that's what it meant. RESTful must refer to using these commands properly with your code. Minimizing commands and being safe.

We diagrammed how a user contacts a website. The user first reaches the DNS, which sends the actual website ip address. I guess first they check their cache to see if they have the website, before going to the DNS. With the ip address, they can reach the server and query/receive data through the controller. There may be many variations of DNS handling as the load varies and it sends you to different sites. Although the DNS sends an ip address, the user handles it automatically without any input. We can use traceroute urltowebsite or ping towebsite to see our own route or ping.

An http request requires a URL, method and headers. We get back a status code, headers and the body/content of page. AJAX was created out of a need to reduce user wait times on websites.

We can use:
```
$.ajax({
    properties: "property value"
  })
```

to send and ajax request. Some important properties are url, method, success, error, and complete. We can also use $.get and $.getJSON. They function the same, except $.getJSON is clearer and easier to read. We also learned about let and const. These both function in their own blocks only. We can keep the namespace cleaner with these. const is a constant, so once it's value is assigned it cannot change or an error gets thrown.

I also improved my portfolio a bit. There are no bugs in it that I can tell, although I should choose an image to use as the hero image. The project of the day consisted of implementing AJAX requests on a local file. We then processed this object accordingly.
