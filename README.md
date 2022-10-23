# CS-360-T1198-22EW1

Q1) Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

A1) The application had the goal of being a weight tracking application. This application required a function to login and create accounts, and allow for users to add weight and date information. This information was to be added, edited, and deleted by the user. The application would also allow the user to input their goal weight and send them a SMS when their goal was reached. If the permission to send SMS was not given to the application, it would still function. The information available for the user to add, edit, and delete were specific to that user; and users could not see information for other users.

Q2) What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

A2) The two primary screens were the login screen and the data activity screen. The login screen was simply to get users authenticated, where the data activity screen contained the display for user weights, and included options to add, edit, and delete weights. And another option to edit the goal weight. Each option could have been designed to function on the same screen, or have a new screen for each option. For simplicity, this application was designed for each function (add weight, edit weight, delete weight, edit goal) was given it's own screen. I used the data activity screen as the 'hub' and each function was routed to from the buttons on this screen, and routed back to this screen when that activity was completed or canceled. This keeps the screens simple and easy to understand. 

Q3) How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

A3) My application was coded after the design and UI/screen flow were deteremined. This made designing the code relatively simple, since the purpose was already determined. In the future I would use a similar technique, but create test code and UI at the same time. As throughout the project, the code needed to be rewritten a few times and the UI changed slightly to improve it's function. 

Q4) How did you test to ensure your code was functional? Why is this process important and what did it reveal?

A4) I originally wrote the code in it's entirity prior to testing. This was a mistake, as there were multiple errors that needed to be resolved. I started again using a more appropriate technique of coding each function individually and testing to ensure it worked as intended prior to moving on. It is important to test your code and test the UI function to ensure the application actually works, and works as intended. For example, I forgot to test my cancel buttons until near the end of the project and found that I had not included the appropriate references to those buttons which caused an error. If this testing was not completed, the application could have been launched with significant flaws which result in time wasted trying to fix them. Users would also lose a lot of trust in the application and could move on to a more competitive application which meets their needs.

Q5) Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

A5) During the design and development process, I was struggling with the primary database functions displaying properly. I inovated by looking into the functions further and taking some approaches I was not as familiar with. This made the database a little easier to work with and by adjusting the view and making use of a 'refresh' function, I was able to verify that the information was both being added and displaying properly.

Q6) In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

A6) I had the best experience creating the login function and allowing for new accounts to be created quickly. This screen is simple and easy to understand, and new accounts are created with a single checkbox. In the future, I would have the view change slightly and add a second password box that the user must fill to confirm their password prior to account creation. 
