## Instructions:
Fork and clone this repo.  Then submit a pull request with all of the bad answers deleted and only the correct answers showing.

#### 1.  Which browser does Node share a runtime with?
* A) V8

#### 2.  Which of the following code in a js file will include a core module named 'fs' ?   

* D) require('fs')


#### 3.  The below code is an attempt to run a simple Node.js server. The server fails to start. Without seeing the server error message, what can you fix in the code to make the server run ?

```
var http = require('http');

function showTime(req, res) {
  res.setHeader("Content-Type", "text/plain");
  res.statusCode = 404;
  res.write("<h1>Hello</h1> citizen, if you are here");
  res.end();
};

var server = http.createServer(res);

http.listen(8000, function() {
	console.log("I'm listening on port 8000...")
});

```

* H) change *text/plain* to *text/html*

###4. Consider the following code from boxes.js , which is required by another file.  What **DATA TYPE** type will be returned from module.exports in this file?
```
var boxes = ["cardboard", "plastic", "metal"]

module.exports = function(){
  return boxes;
}

```



* D) none of the above


###5. What do we mean when we say that Node has a non-blocking IO model ?  (free response) . Give an example from class if you can remember it, or any other example of how this can work.

non-blocking is another way of saying asychronous. you can change something in the page without having to reload the entire page...
