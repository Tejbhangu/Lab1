# 2 Thigns that I learned n form the quiz questions

1. Is the following code Synchronous and Asynchronous?


    ```js
    var food = fs.readFile('food.txt', 'utf8', function(err, food){
      if (err) {
        console.log(err);
      } else {
        console.log(food);
      }
    });
    ```
    
    ## Answer: asynchronous because it uses a callback function

1. What does .listen(8080) refers to?

    ```js
    var http = require('http');
    http.createServer(function (request, response) 
    {
        response.writeHead(200, {'Content-Type': 'text/plain'}); 
        response.end('Hello World\n');
    }).listen(8080);
    
    ## Answer: .listen(8080) refers to Port number
    
# 2 Questions I still have are...

  * What Node stands for?
  * Is the whole course based on JavaScript?
  
  
1. ![Instaltion successful](./lab1/screenshot.PNG)

