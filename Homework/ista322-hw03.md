## Oscar Brown
## 4/10/2018
## Read chapter 3, pages 51 – 66 in the Pro ASP.NET MVC 5 book

1. The book states, “Interactions with an MVC application follow a natural cycle of user actions and view
updates, where the view is assumed to be stateless.” What does it mean for the view to be stateless?
It doesn't have memory. Every interaction between user and webserver is that either transmission is one way. ex. sandbox

2. The book identifies two kinds of models. Briefly describe each of them. pg 52
View models, which just represent data being transferred between views and controllers. Domain models, which contains the data in a business as well as operations, transformations, and rules for manipulating that data.

3. Give an example of separation of concerns from your own life experience. This should be a simple,
everyday example.
ex. types of transportation ground, water, and air vehicles all have different function. One cannot do all or won't work well. ex. Army branches such as Infantry, Armor, and Field Artillery all perform different functions.

4. What is a view engine? pg 53
The component responsible for processing a view in order to generate a response for the browser. Takes input and produces output.

5. The book notes that the three-tier structure, or n-tier model, is “the most widely used pattern for
business applications.” Why do you think that this is true? An answer like, “Because it works well,”
is not a sufficient answer to this question.


6. This question requires some outside research. When we study UWP, you will see that the UWP design
pattern is the Model-View-ViewModel (MVVM). What is the difference between MVC and MVVM
that makes the first good for ASP.NET MVC and the second good for UWP?
In the MVVM there is no controller, the model and the view work hand in hand.

7. Describe the two parts of the dependency injection (DI) design pattern. pg 58
First part is to remove any dependencies on concrete classes from my component. Second is to inject the dependencies declared by the class when you create instances of it. 
ex. IDog duke = new Husky();

8. Give an example of loose coupling from your own life experience. This should be a simple, everyday
example. Loose means your not tied to any implementation. ex. leasing a car as oppose to buying it. 


9. What are the two types of testing discussed in the book? pg 60
Unit testing a way to specify and verify the behavior of individual classes. And integration testing,does the same but for multiple components working together, up o an including the entire Web application.

10. What are the seven steps of the test driven development (TDD) workflow, as stated in the book? pg 64
1) Determine that you need to add a new feature or method to your application
2) Write the test that will validate the behavior of the new feature when it is written
3) Run the test and get a red light.
4) Write the code that implement s the new feature
5) Run the test again and corret the code until you get a green light
6) Refactor the code if required. For example , reoganize the statements, rename the variables, and so on
7) Run the test to confirm that your changes have anot changed the behavior of ayour additions

Notes of the day:
High cohesion
Low coupling parts are interchangable.