Download Link: https://assignmentchef.com/product/solved-tuffytravel-project-guide-cpsc-121-milestone-1-8
<br>
<h1><span style="font-weight: 400;">Learning objectives</span></h1>

<ol>

 <li style="font-weight: 400;"><span style="font-weight: 400;">Design and implement software that makes appropriate use of fundamental programming constructs and data structures (e.g., expressions, conditions, loops, functions, primitive data types, arrays).</span></li>

 <li style="font-weight: 400;"><span style="font-weight: 400;">Design and implement software that makes appropriate use of object-oriented concepts (e.g., classes, objects, methods, composition, inheritance, abstract classes, polymorphism).</span></li>

 <li style="font-weight: 400;"><span style="font-weight: 400;">Design and implement software that makes appropriate use of advanced programming concepts (e.g., recursion, pointers, memory allocation, STL, file input/output, exception handling).</span></li>

 <li style="font-weight: 400;"><span style="font-weight: 400;">Demonstrate proper use of encapsulation and decoupling.</span></li>

 <li style="font-weight: 400;"><span style="font-weight: 400;">Demonstrate proper use of coding standards.</span></li>

 <li style="font-weight: 400;"><span style="font-weight: 400;">Write appropriate inline comments to help other developers understand and reuse code.</span></li>

 <li style="font-weight: 400;"><span style="font-weight: 400;">Demonstrate the ability to utilize IDEs to optimize software development.</span></li>

</ol>

<h1><span style="font-weight: 400;">Project specifications</span></h1>

<span style="font-weight: 400;">The goal of this project is to develop a travel planning application. Users will use a menu-based command-line interface to interact with the software. Its major features are the creation of travel routes, adding routes to a travel schedule, and saving and loading routes into text files. </span>




<span style="font-weight: 400;">The software should be designed using the object-oriented programming paradigm so that the code can easily be modified, extended, and scaled by other developers. It is equally important to provide sufficient internal documentation to help other developers understand the code and encourage them to contribute to its development.</span>




<span style="font-weight: 400;">The software will be delivered in incremental versions or milestones over the course of the semester. Descriptions of the eight milestones are presented below, but technical details will be provided in your GitHub repositories for each milestone. The deadlines listed for each milestone may change depending on the class’ progress. In such cases, I will announce changes in class and/or through Piazza.</span>

<h1><span style="font-weight: 400;">Grading</span></h1>

<span style="font-weight: 400;">Each milestone will be graded separately using the same lab exercise checking stages, but with an additional reflection component. Your final project grade is the average of all your milestone grades.</span>




<b>Stage 1. Compilation (5%) </b><span style="font-weight: 400;">will be assessed by checking whether your code compiles correctly assuming you put in sufficient effort in solving the problem. Minimal code or code that does not attempt to solve the problem will not get a compilation grade.</span>




<b>Stage 2. Functionality (40%) </b><span style="font-weight: 400;">will be assessed by checking how much of the unit tests defined for the problem were passed by your solution. Unlike lab exercises, you will only have access to some test cases via the unit tests. You will need to think of other test cases and make sure that your program addresses them properly. My graders and I will use an instructor’s set of unit tests that we expect your programs to pass.</span>




<b>Stage 3. Design (40%)</b><span style="font-weight: 400;"> will be assessed by checking whether your code uses the appropriate constructs for solving the problem. Code that runs correctly does not guarantee a high grade. An example of bad code design is using a brute force approach like manually printing out every number from one to 100 instead of using a loop.</span>




<b>Stage 4. Readability (10%)</b><span style="font-weight: 400;"> will be assessed by checking whether your code passess the style and format check, as well as how well it follows the proper naming conventions, and provides sufficient internal documentation for complex code. Documentation is often an art, but Google’s style guide is a good starting point (</span><a href="https://google.github.io/styleguide/cppguide.html"><span style="font-weight: 400;">https://google.github.io/styleguide/cppguide.html</span></a><span style="font-weight: 400;">). Coding styles will be discussed in class and shown in our code samples.</span>

<h2><b>Reflection (5%)</b><span style="font-weight: 400;"> will be assessed by checking whether you appropriately accomplished the reflection form. The form will ask you to provide information about your submission such as a description of your program, the test cases that you identified, and a discussion about the issues you encountered while developing your program.</span></h2>

<h2><span style="font-weight: 400;">Milestone 1</span></h2>

<i><span style="font-weight: 400;">Deadline: September 20, 11:59 pm</span></i>




<span style="font-weight: 400;">Create a program that asks the user to input three bus departure times. The system should also ask the user to provide the name of the route to make it easy to distinguish. It should also ask the passenger what time they want to leave. Use conditions to identify the bus route that the passenger should take if they want to leave by the time they specified.</span>

<h2><span style="font-weight: 400;">Milestone 2</span></h2>

<i><span style="font-weight: 400;">Deadline: October 11, 11:59 pm</span></i>




<span style="font-weight: 400;">Design and implement a </span><b>Route</b><span style="font-weight: 400;"> object that will store the name of the route, its departure time and its arrival time. For example, the 57 Brea Mall – State College-Nutwood route has a departure time of 9:45am and arrival time of 9:56am. Create a </span><i><span style="font-weight: 400;">display</span></i><span style="font-weight: 400;"> member function that will print on screen the name of the route, its departure time and arrival time.</span>




<span style="font-weight: 400;">Create a function called </span><i><span style="font-weight: 400;">create_route</span></i><span style="font-weight: 400;"> that asks the user to provide the name of the route, the departure time, and the arrival time. Use the information provided by the user to create a </span><b>Route</b><span style="font-weight: 400;"> object and return it.</span>




<span style="font-weight: 400;">Modify your Milestone 1 program so that it calls the </span><i><span style="font-weight: 400;">create_route</span></i><span style="font-weight: 400;"> function to instantiate three </span><b>Route</b><span style="font-weight: 400;"> objects. Use the accessors and mutators of each </span><b>Route </b><span style="font-weight: 400;">object to figure out which one will allow the passenger to leave by the time they specified. Call the selected </span><b>Routes</b><span style="font-weight: 400;"> object’s </span><i><span style="font-weight: 400;">display</span></i><span style="font-weight: 400;"> member function to show the information on screen.</span>




<span style="font-weight: 400;">The code should be organized so that class and function prototypes are placed in header files (.hpp) while their implementations are placed in source files (.cpp)</span>

<h2><span style="font-weight: 400;">Milestone 3</span></h2>

<i><span style="font-weight: 400;">Deadline: October 21, 11:59 pm</span></i>




<span style="font-weight: 400;">Create a menu-based interface that allows the user to add routes, display all routes, and exit the program. Specifically, the user presses either R to create routes, D to display the routes, or X to exit.</span>




<span style="font-weight: 400;">Create an array of </span><b>Route</b><span style="font-weight: 400;"> objects in the </span><i><span style="font-weight: 400;">main</span></i><span style="font-weight: 400;"> function. Whenever the user adds a route, call the </span><i><span style="font-weight: 400;">create_route</span></i><span style="font-weight: 400;"> function to instantiate a </span><b>Route</b><span style="font-weight: 400;"> object and store it on the first available space in the array.</span>




<span style="font-weight: 400;">Create a </span><i><span style="font-weight: 400;">display_routes</span></i><span style="font-weight: 400;"> function that accepts the array and its size as a parameter, then displays information about each </span><b>Route</b><span style="font-weight: 400;"> object in the array. Take note that you can also call each </span><b>Route</b><span style="font-weight: 400;"> object’s </span><i><span style="font-weight: 400;">display</span></i><span style="font-weight: 400;"> function instead of its accessor and mutator functions. The </span><i><span style="font-weight: 400;">display_routes</span></i><span style="font-weight: 400;"> function should be called whenever the user asks to display routes.</span>

<h2><span style="font-weight: 400;">Milestone 4</span></h2>

<i><span style="font-weight: 400;">Deadline: November 4, 11:59 pm</span></i>




<span style="font-weight: 400;">Update the menu to allow the user to find the route they should take given their time to leave. Specifically, F to find a route.</span>




<span style="font-weight: 400;">Create a </span><i><span style="font-weight: 400;">find_route</span></i><span style="font-weight: 400;"> function that accepts the </span><b>Route</b><span style="font-weight: 400;"> object array, its size, and the time to leave. The function should return the appropriate </span><b>Route</b><span style="font-weight: 400;"> object whose departure time is closest to the user’s time to leave. The route’s departure time should only be equal to or after the passenger’s given time.</span>




<span style="font-weight: 400;">When F is selected on the menu, it should ask the user to provide their time to leave and call the </span><i><span style="font-weight: 400;">find_route</span></i><span style="font-weight: 400;"> function with the appropriate parameter values.</span>

<h2><span style="font-weight: 400;">Milestone 5</span></h2>

<i><span style="font-weight: 400;">Deadline: November 22, 11:59 pm</span></i>




<span style="font-weight: 400;">Update the menu-based interface to also allow the user to save and load routes. Specifically, S to save all added routes and L to load a route file.</span>




<span style="font-weight: 400;">Create a </span><i><span style="font-weight: 400;">save_routes</span></i><span style="font-weight: 400;"> function that accepts the array, its size, and a file name. The function should save each element of the array into a file named according to the file name parameter.</span>




<span style="font-weight: 400;">Create a </span><i><span style="font-weight: 400;">load_routes</span></i><span style="font-weight: 400;"> function that accepts tha array, a size reference, and a file name. The function should open the appropriate file using the file name parameter and update the size reference according to the data in the file. Take note that the reference is linked to the size variable in the </span><i><span style="font-weight: 400;">main</span></i><span style="font-weight: 400;"> function that tracks the total number of </span><b>Route</b><span style="font-weight: 400;"> objects in the array. Instantiate the appropriate </span><b>Route</b><span style="font-weight: 400;"> objects based on the file and store them in the given array.</span>




<span style="font-weight: 400;">The </span><i><span style="font-weight: 400;">save_routes</span></i><span style="font-weight: 400;"> and </span><i><span style="font-weight: 400;">load_routes</span></i><span style="font-weight: 400;"> functions should be called with the appropriate parameter values when the user requests to save or load the routes through the menu. Make sure that the functionality for adding and displaying bus routes continue to work for this Milestone.</span>

<h2><span style="font-weight: 400;">Milestone 6</span></h2>

<i><span style="font-weight: 400;">Deadline: December 6, 11:59 pm</span></i>




<span style="font-weight: 400;">Refactor your code so that it uses an object-oriented design. Refactor is a term that refers to restructuring existing code so that it follows a different design but retains the initial code’s behavior. Specifically, you need to create a </span><b>RouteManager</b><span style="font-weight: 400;"> object that will contain all the </span><b>Route</b><span style="font-weight: 400;"> objects added by the user. The functions created from previous Milestones will be refactored into member functions in the appropriate classes. As a result, codes that call the refactored functions will now use the </span><b>RouteManager</b><span style="font-weight: 400;"> and </span><b>Route</b><span style="font-weight: 400;"> objects’ member functions.</span>




<span style="font-weight: 400;">Specifically, the </span><b>RouteManager</b><span style="font-weight: 400;"> object should now contain the array of </span><b>Route</b><span style="font-weight: 400;"> objects and the variable that keeps track of the number of objects in the array. It should also now contain the refactored </span><i><span style="font-weight: 400;">create_route</span></i><span style="font-weight: 400;">, </span><i><span style="font-weight: 400;">add_route</span></i><span style="font-weight: 400;">, </span><i><span style="font-weight: 400;">display_routes</span></i><span style="font-weight: 400;">, </span><i><span style="font-weight: 400;">find_routes</span></i><span style="font-weight: 400;">, </span><i><span style="font-weight: 400;">save_routes</span></i><span style="font-weight: 400;">, and </span><i><span style="font-weight: 400;">load_routes</span></i><span style="font-weight: 400;"> member functions. Take note that these member functions should use the class’ member variables instead of requiring parameters.</span>




<span style="font-weight: 400;">The menu should be updated to use objects and call their appropriate member functions.</span>

<h2><span style="font-weight: 400;">Milestone 7</span></h2>

<i><span style="font-weight: 400;">Deadline: December 19, 11:59 pm</span></i>




<span style="font-weight: 400;">Add a new route type called </span><b>CheckedRoute</b><span style="font-weight: 400;">. In addition to information stored in a </span><b>Route</b><span style="font-weight: 400;"> object, this new route type also keeps track of the number of hours the passenger needs to arrive before the departure time. In airlines for example, users would need to arrive at least an hour before a domestic flight and three hours before an international flight. A possible </span><b>CheckedRoute</b><span style="font-weight: 400;"> object might be a Delta flight from LAX – ATL whose time for take off is 6:35am, arrival time is 11:01am, and passengers are required to arrive 1 hour before the flight. </span>




<span style="font-weight: 400;">Create a </span><i><span style="font-weight: 400;">create_checked_route</span></i><span style="font-weight: 400;"> member function in the </span><b>RouteManager</b><span style="font-weight: 400;"> class that asks the user to provide all necessary values and return a </span><b>CheckedRoute</b><span style="font-weight: 400;"> object using those values.</span>




<span style="font-weight: 400;">Apply inheritance and polymorphism so that </span><b>Route</b><span style="font-weight: 400;"> and </span><b>CheckedRoute</b><span style="font-weight: 400;"> objects can be stored in the same array inside the </span><b>RouteManager</b><span style="font-weight: 400;">. The other functionalities such as adding, displaying, finding, saving, and loading routes should still work as expected.</span>




<span style="font-weight: 400;">Update the menu to create a checked route when the user presses C. Call the </span><i><span style="font-weight: 400;">create_checked_route</span></i><span style="font-weight: 400;"> function and pass all necessary parameter values.</span>

<h2><span style="font-weight: 400;">Milestone 8 (Extra credit)</span></h2>

<i><span style="font-weight: 400;">Deadline: December 19, 11:59 pm</span></i>




<span style="font-weight: 400;">Create another </span><b>Route</b><span style="font-weight: 400;"> type called </span><b>ConnectionRoute</b><span style="font-weight: 400;">. It is a special type of </span><b>Route</b><span style="font-weight: 400;"> that stores the name of a source route and destination route that are names of other routes. Take for example the case when the user needs to walk after they take a bus to the airport. A </span><b>ConnectionRoute</b><span style="font-weight: 400;"> might require the passenger to walk from the source route, LAX Terminal 1 stop, to the destination route, the LAX airport, that departs at 12:33pm and arrives at 12:34pm.</span>




<span style="font-weight: 400;">Create a </span><i><span style="font-weight: 400;">create_connection_route</span></i><span style="font-weight: 400;"> member function in the </span><b>RouteManager</b><span style="font-weight: 400;"> class that asks the user to provide all necessary values and return a </span><b>ConnectionRoute</b><span style="font-weight: 400;"> object using those values.</span>




<span style="font-weight: 400;">Apply inheritance and polymorphism so that </span><b>Route</b><span style="font-weight: 400;">, </span><b>CheckedRoute</b><span style="font-weight: 400;">,</span> <span style="font-weight: 400;">and </span><b>ConnectionRoute</b><span style="font-weight: 400;"> objects can be stored in the same array inside the </span><b>RouteManager</b><span style="font-weight: 400;">. The other functionalities such as adding, displaying, finding, saving, and loading routes should still work as expected.</span>




<span style="font-weight: 400;">Update the menu to create a connection route when the user presses T. Call the </span><i><span style="font-weight: 400;">create_connection_route</span></i><span style="font-weight: 400;"> function and pass all necessary parameter values.</span>