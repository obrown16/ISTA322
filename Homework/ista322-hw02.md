## Oscar Brown
## 4/04/2018
## Read chapter 2, pages 11 – 50 in the Pro ASP.NET MVC 5 book

## Answer the discussion questions in writing for chapter 2.

1. Describe what a controller does in the MVC design pattern.
A controller handles incoming request. It's just C# classes that usually inherits from System.Web.MVc.Controller, the framework's built-in controller base class.
Control is the traffic cop.
2. What is the ASP.NET MVC convention in naming controllers? What does HomeController.cs do?
controller names always ends with control.

3. What is the name of the routing configuration file? Where is it located?
RouteConfig.cs located in the AppStart folder.

4. What is Razor? How does Razor treat an expression beginning with the at symbol (@)?
Razor is a view engine that processes the contents of views and produces HTML that is sent to the browser. The @ tells razor that this is the code that needs to be executed. Reads the C# code and produces HTML.

5. How do View methods work?
runs a method on a specific view as opposed to simply printing to the browser.

6. What is the purpose of MVC models?
contains all the core functionality of whatever you are doing. Contains properties and objects.

7. What is a strongly typed view and why do we use strongly typed views? pg 29
A strongly typed view is intended to render a specific domain type. 

8. What is the purpose of setting a start page URL?
To help make the browser requrest a URL based on the view being currently edited.

9. Describe the differences between HTTP GET and HTTP POST.
POST request method requests that a web server accept the data enclosed in the body of the request message. HTTP GET request method retrieves information from the server.


10. Describe the two approaches to validation in web applications.
Can do client side or server side validation. Disadvantage client side it can be spoofed. Advantage

11. What is the role of Cascading Style Sheets (CSS) in web development?
simple design language intended to simplify the process of making web pages presentable. CSS handles the look and feel part of a web page. 