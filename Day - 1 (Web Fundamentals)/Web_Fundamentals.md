# Web Fundamentals:

Every Website Have Two Parts:

## Frontend Development:

**HTML:** It is a markup language and it is use to struture the the web page.

**CSS:** It is cascading style sheet whic is used for styling the webpage.

**JavaSrcipt:** It is programming language which add functionality and behaviour in the webpages.

### Real Life Example:

A building have structure and we can color it to look beautiful and add functionality like esclator, etc.

## Backend Development:

## How Internet Works:

**The Internet:** It is long piece of wire which is spread all under the ocean and it connected one computer to another. 

- When client search the website then the browser send the message to ISP (Internet Service Provider) 
- ISP srely this message to DNS (Domain Name System), it is phonebook which search the IP of the websites.
- After searching it send message back toh the client.

**Search IP Addresses:** <a href="https://www.nslookup.io/">nslook.io</a>

**Subraine Cable:**  <a href="https://www.submarinecablemap.com/">Submarine Cable Map</a>


## How Website Works:

Let's Type Thi URL In the browser:

http://www.abc.com : This is URL (Uniform Resource Locator) and it is way to locate resources on the internet. Resources can images, audio, video, etc...

Now Browser involves two pices here:

![Client And Server](https://cdn.ttgtmedia.com/rms/onlineimages/client_and_server_requests_and_responses-f_mobile.png)

The client send request to server and server send the resoruces or response to client.

This message is formatted based on the HTTP And HTTPs Protocol. It is used to communicate between client and server.

HTTP; It is a plain textual language for communicating.

HTTPs: HTTP + encryption.

- Example:

**Request Messge:**(HTTP Request)

GET /index.html HTTP/1.1

Host: www.abc.com

Accept-Language: en-us

**Response Message:**(HTTP Response)

HTTP/1.1 200 OK

Date: 24 October 2024 16:26

Content-Type: text/html

..........HTML Document..........

![HTTP Request And Response](https://www3.ntu.edu.sg/home/ehchua/programming/webprogramming/images/HTTP_Steps.png)


## DOM

Document Object Model: It repersents the objects or elements in our HTML document.

This elements are: paragraphs, images, fonts and other stuffs.

For each resources the browser sends seperate HTTP request to the server to fetch that resource.

Many requests send it parallel for fast execution.

![DOM](https://www.freecodecamp.org/news/content/images/2021/09/Document.jpg)

## Inspecting HTTP Request And Response:

- Open the inspect, by right click on the web page and select inspect. Shortcut Key(Ctrl + Shift + i).

- Now go to network.

- Press the refresh button.

- Now these all are the HTTP request that chrome send toh the google.

- There are total request left bottom corner with total size in Kb or Mb.

- You filter the requests and also get more details about that request by click on that request.

![HTTP Requests](Images/HTTP%20Requests.png)


## Validating Web Pages:

Copy Address Link And Paste It To Browser:

For HTML: <a href="validator.w3.org">HTML Validator</a>

For CSS: <a href="jigsaw.23.org/css-validator/">CSS Validator</a>



