# Book Excercise - JAVA

## How to submit your code assignment

1. Fork the project from GitHub.
2. Make your forked project to **private** 
3. Add member of **ibmq2c** in **Manage Access**,  from Current Setting tab -> Manager access -> Invite a Collaborator -> lookup for **ibmq2c** -> add  **ibmq2c** to thi repository.
4. Complete your code and documentation in the forked project.
5. Create a new plain text file in the root folder of the forked project. And make the file name in the format of "your full name", e.g. **Mark Leon**.
6. Notify the code assignment is done or you can contact your employer to notify the same (we would be regularly checking the repo for any checkins).

## Code assignment details

Imagine you are the software engineer who is going to design and develop a small application. The application is to provide 2 Restful APIs for Book.

The application has 1 domain model named "**Book**" The domain model is Book, which has below minimal information,

- Attribute to act as the unique identifier of a Book
- Attribute to show what the book is or what the book is about. This attribute is able to be understood by the human and has some meaning, for example, it is not a random number.

You can make the decision about the names and data type of above attributes.

Here is technical requirement for the application.

- Use **Spring framework**, you can consider to use Spring MVC or Spring Boot. If you choose to use Spring MVC, you need to provide the embedded web server to run your application alone without external web server (hints: for example, by using Jetty or Tomcat Maven plugin).
- The building tool is Maven 3 or preferably Gradle 4.
- 1 API with HTTP method POST to handle the new entry of Book or update the existing Book information. The HTTP request and response are in JSON format.
- 1 API with HTTP method GET to get the Book information by its unique identifier. The HTTP response is in JSON format.
- You need to have error handling and provide the meaningful error message and status.
- There is no database or external file storage required in this application. You shall not have the function with any kinds of database or storage, e.g. MySQL, H2, Postgresql, or MongoDB.
- Your code shall not be broke in a very simple test.
- It is no need to have complex code structure of the application, but the code shall be clear and able to be understood. The code also shall follow the Java coding standard.
- Consider having appropriate documentation in README.md and Javadoc.
- In the README.md, you need to complete the steps and commands section to show how to run your application, please keep it short and get to the point.
- In the README.md, you need to complete the test commands section by using `curl` to simulate the request for your 2 APIs. You need to provide the payload of the response.
- You need to provide the unit test.

Please keep your implementation simple. It is no need to over design and over development. But the code shall be able to show your basic understanding of the design and development knowledge with MVC and Spring framework.

You can assume your implementation can be completed in 8 hours. Normally, it could be completed in 2 to 6 hours.

## Steps and commands to run the application

You can append to the existing README.md file the steps to run the application

## API testing commands

Append your test endpoint details
