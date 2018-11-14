### SDE coding challenge

Here you are! We're happy that you're interested in working for Quantum Inventions! 
To get a better idea of your current skills, we'd like you to complete a coding challenge - build a web app to display and update resources (e.g - users). 
The actual requirements are listed further down, but here are the general tech requirements:
- Make sure your app is runnable on Windows, Mac OS X and Linux
- Do not include any paid software dependencies
- Include instructions for setting up and running your application
- Containerized app is a plus

### Mock APIs 

Simulate API like behaviour using following approach -
* You can use API mock service: https://reqres.in/. Visit the site for more details.

### Description 

Develop a web application which can support following functionalities:
- Build a **Login** page which takes username and password
- After successful login, go to page where users are listed down
- Use *delayed response* of 5seconds to show a loader icon on a popup
- The users **List** page should have following 
	- A Search and Sort feature to filter desired item
  - A Tabular view to show each items divided by rows
  - Add Pagination support. Each page should have maximum 4 items to show.
- The individual rows of resources in the list, should have following
	- It should contain following details _atleast_ : user profile image/ avatar, first name, last name
	- Each row should have option to **Edit** the item, or **Delete** the item from the list
	- On click of **Edit**
		- A collapsable section should open (e.g - Accordion)
		- Section should contain editable form to edit first name and last name
		- *Form specifications*
			- Required fields: First Name, Last Name
			- Pattern: 
				* Names should not contain any digit or special charchter
				* Names must start with capital case (e.g - John)
				* First and last name should **not** be multi-word input (e.g: A valid `first name` attribute should not look like `John Doe`)
		- Once updated, the row should reflect the change
	- On click of **Delete**
		- The item should be deleted from the list of users
- On click of **Logout** button, the user should return to login page	
- If users try to navigate to a route which does not exists, show a custom error message on a modal and 
provide option to go back to main page


**Complete the assignment as you would do for the real-life production environment.**
> Write your code in Javascript(ES6 Preferred), AngularJS or React


### What we're looking for
- Showing your work through your **commit history**
- Polish
- Holistic understanding of all components of web development
- Pride in craftsmanship

### What we care about
- Architecture:
    - How clean and reasonable is the separation between modules?
- Clarity: 
    - Does the README clearly and concisely explain the problem and solution? 
    - Are technical tradeoffs explained?
    - Explanation of design principles and best practices followed
- Code quality: 
    - Is the code simple, easy to understand, and maintainable?
    - Are there any code smells or other red flags? 
    - Is the coding style consistent with the language's guidelines? 
    - Is it consistent throughout the codebase?
    - Are negative scenarios handled?
- Testing:
    - Quality of unit tests
    - Adequacy and coverage of tests
- Correctness: 
    - Are there any gaps?
    - Does the README explain what the gaps are and the reasons?

Please submit your work by sending us a link to a GitHub repo with your code.
