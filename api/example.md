FORMAT: 1A

# Mainflux Core API
API document for Mainflux Core

# /device
This is our [resource](http://www.w3.org/TR/di-gloss/#def-resource). It is
defined by its
[URI](http://www.w3.org/TR/di-gloss/#def-uniform-resource-identifier) or, more
precisely, by its [URI Template](http://tools.ietf.org/html/rfc6570).

This resource has no actions specified but we will fix that soon.

## GET
Here we define an action using the `GET` [HTTP request method](http://www.w3schools.com/tags/ref_httpmethods.asp) for our resource `/message`.

As with every good action it should return a
[response](http://www.w3.org/TR/di-gloss/#def-http-response). A response always
bears a status code. Code 200 is great as it means all is green. Responding
with some data can be a great idea as well so let's add a plain text message to
our response.

+ Response 200 (text/plain)

        Hello World!

## PUT
OK, let's add another action. This time to put new data to our resource
(essentially an update action). We will need to send something in a
[request](http://www.w3.org/TR/di-gloss/#def-http-request) and then send a
response back confirming the posting was a success (_HTTP Status Code 204 ~
Resource updated successfully, no content is returned_).

+ Request (text/plain)

        All your base are belong to us.

+ Response 204


# /channel
This is our [resource](http://www.w3.org/TR/di-gloss/#def-resource). It is
defined by its
[URI](http://www.w3.org/TR/di-gloss/#def-uniform-resource-identifier) or, more
precisely, by its [URI Template](http://tools.ietf.org/html/rfc6570).

This resource has no actions specified but we will fix that soon.

## GET
Here we define an action using the `GET` [HTTP request method](http://www.w3schools.com/tags/ref_httpmethods.asp) for our resource `/message`.

As with every good action it should return a
[response](http://www.w3.org/TR/di-gloss/#def-http-response). A response always
bears a status code. Code 200 is great as it means all is green. Responding
with some data can be a great idea as well so let's add a plain text message to
our response.

+ Response 200 (text/plain)

        Hello World!

## PUT
OK, let's add another action. This time to put new data to our resource
(essentially an update action). We will need to send something in a
[request](http://www.w3.org/TR/di-gloss/#def-http-request) and then send a
response back confirming the posting was a success (_HTTP Status Code 204 ~
Resource updated successfully, no content is returned_).

+ Request (text/plain)

        All your base are belong to us.

+ Response 204

