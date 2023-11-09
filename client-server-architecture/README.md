# ![[Intro to Full Stack Development] - Client/Server Architecture](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to define client/server architecture. 

## Client/server architecture

![Client/server architecture cycle](./assets/originals/client-server-architecture.png)

tktk hunter -- please make this prettier.  Also, I prefer a server icon that looks something like this: https://i.imgur.com/YqZANRo.png.  I feel it drives home the point that a server is just computer hooked up to the internet.

The terms *client* and *server* can refer to both a **physical device** (computer, tablet, phone, etc.) and to a **software process**. For example:

- A laptop computer could be thought of as a client, if it is being used to access the internet.  Within that laptop, the web browser (e.g. Chrome, Firefox, etc) that is being used could be thought of as a software client.  It will make requests for information from a server.
- A server, from the perspective of a software process, is an application who's job it is to respond to client requests for information.  These applications will be running on a computer somewhere that is turned on and connected to the internet.  In this situation, that computer can also be thought of as a server.

In the client and server architecture, clients make requests for information from servers. Servers then reply to requests with a response containing the requested information.  Here's an example:

1. A user navigates to a website in their browser (the browser is the client).
2. The browser sends a request to the website's server, asking for the HTML code for the website.
3. The server processes the request and sends the HTML code back to the browser.
4. The browser displays the website to the user.