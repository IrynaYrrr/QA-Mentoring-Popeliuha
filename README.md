# QA-Mentoring-Popeliuha
This repository contains a set of practical software testing exercises completed as part of the training with Popeliuha. It includes work with test cases, bug reports, API, SQL, and other aspects of QA.


Manual Course Program

Playlist of videos that will help you complete these tasks:
1.	Create a Trello board with columns: To Do, In Progress, Done. Create a card (task) in it and add a checklist, deadline, and attachment. Take a screenshot of the board and submit it for review.

2.	Choose a website that you will test in all the following lessons. It must be an online store. Write a 25-point checklist.
	•	Do not test login and registration, but test the cart and product operations.
	•	Do not forget to use negative checks (entering unexpected text, different symbols, etc.).

3.	At work, daily stand-ups are held. Answer 3 questions about work/study:
     a) What did you do yesterday?
     b) What are you doing today?
     c) Do you have any blockers? If so, what are they?

4.	Write a checklist for testing the payment card input form (Card number: 16 digits, Expiration date in MM/YY format, CVV code: 3 digits).

5.	Write 10 test cases in TestRail for your chosen website.
	•	Place them in 2 test suites with logical names.
	•	Do not forget about screenshots in test cases.
	•	Submit the result in PDF format and attach it to Google Docs.

6.	Create a test report from your test cases.
	•	Submit the result in PDF format and attach it to Google Docs.

7.	On the website https://exe.ua/ua/ find 5 bugs and create bug reports in Jira.
	•	Submit screenshots of bug reports.

8.	When a user uploads a document as an avatar, there is no error message.
	•	Create a bug report for this issue.

9.	Find at least 8 bugs and write the titles of the bug reports you would create.

10.	There is a registration form in a web application with the fields: First name, Last name, Username, Password, Repeat password, and a Register button.

	•	Create a checklist with the following requirements:
    a) First name and Last name must contain only Latin or Cyrillic letters. The only allowed special character is a hyphen (e.g., “Anna-Maria”).
    b) Username may consist of Latin letters and numbers. Special characters are not allowed.
    c) Password must be from 10 to 20 characters, contain at least 1 number, 1 uppercase letter, and 1 special character. Only English letters are allowed (non-English characters are not accepted).
    d) The Repeat Password field must be completely identical to the Password field. Case-sensitive (e.g., “paSSword” and “PassWord” are different passwords).

11.	Describe how you would test a flashlight or a kettle at different testing levels in the format Level - Test Name.

12.	Describe how you would test your website at different testing levels in the format Level - Test Name, writing 1 test per level.

13.	Evaluate all your previous tasks using Fibonacci numbers (at your discretion).

	•	Maximum score is 21. The more difficult the task, the higher the number.
	•	Submit the result as a Trello screenshot or Google Sheet.
	•	Tasks MAY have the same estimate (e.g., 2 tasks with a score of 5 is acceptable).

14.	Test your website using all known types of testing (excluding levels) in the format Type - Test Name, one test per type.

15.	Although testers are not required to write requirements, in the absence of project documentation, they may have  to.

	•	Write 10 functional requirements for the website from task 2.

16.	Write 2 tests for your website with valid and invalid data, using:
    a) Equivalence Partitioning
    b) Boundary Value Analysis
    c) Pairwise Testing
    d) Error Guessing
17.	Test an input field that accepts integer values from 18 to 99 (inclusive) using Boundary Value Analysis and Equivalence Partitioning.

18.	Create a decision table for one feature of your website.

	•	Submit the result as a Google Docs link.

19.	Create a state transition diagram for one feature of your website.

	•	Submit the result as a Google Docs link.

20.	Create a use case diagram for your website.

	•	Submit the result as a Google Docs link.

21.	Write User Stories based on your use case diagram.

	•	Each story must consist of 3 parts:
	•	“As a [type of user], I want to [action], so that [goal].”

22.	Requirement Analysis:

	•	Using your previously written Requirements, User Stories, Checklist, and Test Cases, create a Traceability Matrix.
	•	Submit the result as a Google Sheet.

23.	It’s time for Sprint Planning!

	•	Imagine that next week is your sprint.
	•	Choose tasks from this list that you will complete next week and estimate them in hours.
	•	Try to complete the plan, but if you don’t, it’s not critical.
	•	Submit your planned tasks and estimates.

24.	Create a JSON file containing an array of 4 elements on any topic.

	•	Submit the result as a screenshot or the text of the file.

25.	Download Fiddler and make all requests from Petstore for User (except creating an array and list) and Store.

	•	Submit the result as screenshots.

26.	Download Postman and make all requests from Petstore for User (except creating an array and list) and Store.

	•	Submit the result as screenshots.

27.	Add tests in Postman to verify that:

	•	The request returns 200/404.
	•	The response body contains the correct username in one of the requests.
	•	Submit the result as a screenshot.

28.	Write a checklist for 3 requests from User (Petstore Swagger):
     a) POST /user
     b) GET /user/{username}
     c) GET /user/login
29.	Create and populate database tables with relationships:

	•	Universities (Id, UniName, City)
	•	Faculties (Id, Name, UniversityId)
	•	Groups (Id, GroupNumber, FacultyId)
	•	Students (Id, Name, Surname, Age, GroupId)
	•	Ensure one student is named “Ivan.”
	•	Submit the result as a screenshot.

30.	Write SQL queries:

	•	Select all fields from Universities.
	•	Select only names and surnames of students.
	•	Select only students named “Ivan.”
	•	Select only groups where the number is greater than 300.
	•	Select only universities containing “U” in their name.
	•	Submit the result as a screenshot.

31.	Sort the Students table alphabetically and in reverse order.

	•	Submit the result as a screenshot.

32.	Write a JOIN query combining the Students and Groups tables.

	•	Submit the result as a screenshot.

33.	Write SQL queries (without MySQL) to:

	•	Retrieve the phone number and address of user “Muzik.”
	•	Select users whose names end with “A.”
	•	Retrieve users with orders over 2000 UAH.
	•	Count the number of orders.
	•	Calculate the total sum of all orders.

34. Write the following SQL queries (Do not use MySQL):

a) There is an imaginary table Workers (id, name, hireDate (hire date), profession). Retrieve all Testers from the Workers table, sorted by hire date.
b) Retrieve the 5 most recently hired Testers from the Workers table.


35. Open DevTools in the Network tab on any website, perform some actions until a GET request is sent.
	•	Take a screenshot and highlight the parts of the API request (request URL, method, status code, headers, body if available) and label them.


36. Create an XML file containing an array of 4 elements on any topic.
	•	One tag must have 2 attributes simultaneously.
	•	There must be 1 self-closing tag.


37. Open the website https://friends.in.ua/serialdruzi/ and find the following elements using XPath:
	•	This image will help you understand the tasks. The task letter is placed next to the row for which you need to find XPath.
a) The title: “СЕРІАЛ ДРУЗІ ВСІ СЕЗОНИ УКРАЇНСЬКОЮ МОВОЮ ОНЛАЙН”
b) The parent of the result from task “a” using the word parent.
c) The parent of the result from task “b” using an attribute.
d) This element using 2 attributes.
e) Answer the question: What can be used to replace the name of any tag?


38. Create 5 automated tests in Selenium IDE
	•	Submit a screenshot where all tests have passed.


39. Create a Git repository and push any file.
	•	Submit the result as a screenshot from the SourceTree program.


40. Create a branch in Git, push changes, and merge them into the main branch.
	•	Submit the result as a screenshot from the SourceTree program.


41. Push a commit and revert it.
	•	Submit 2 screenshots:
	•	One showing the changes in the first commit.
	•	One showing the reverted commit in SourceTree.


42. Create a resume.
	•	Avoid using templates if possible.
	•	Upload your photo, city, and whether you are considering remote work.
	•	List your main skills and technologies in order of priority for the project.
	•	All types of test documentation (test cases, etc.) should be listed separately. Do not generalize them under “test documentation”.
	•	Submit the result in PDF or DOC format with a link to Google Drive.


43. Create a portfolio on GitHub.
	•	Add the following:
	•	Test cases
	•	Checklists (all)
	•	Bug reports
	•	Testing types usage
	•	Test design techniques
	•	Database work (screenshots)
	•	API testing (screenshots)
	•	Resume

🚫 Do NOT add: Testing levels, testing of airplanes, XML and JSON, Selenium, or anything else not mentioned above.


44. Retrospective time!

Instead of evaluating a sprint, we evaluate learning in this practical course. Answer 3 questions:
a) What went well?
b) What can be improved?
c) How can it be improved?