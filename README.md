Title: My Static Website with Form Handling

Overview:
This project is a simple static website with a Go server that handles form submissions. The website allows users to fill out a form with their name and address and submit it to the server. Upon submission, the server processes the form data and displays the submitted name and address.

Functionality:
1. Static Website:
   - The project includes a static website with two pages: "index.html" and "form.html."
   - The "index.html" page serves as the homepage and provides a basic greeting message.
   - The "form.html" page contains a form with fields for entering the user's name and address and a "submit" button.

2. Form Handling:
   - The Go server is set up to handle form submissions from the "form.html" page.
   - When a user fills out the form and clicks the "submit" button, the data is sent to the server.

3. Form Data Processing:
   - The Go server uses the "formHandler" function to process the form data.
   - Upon receiving the form data, the server parses it to extract the values of the "name" and "address" fields.

4. Displaying Submitted Data:
   - After processing the form data, the server responds with a "Post request successful" message to the client (web browser).
   - The server then displays the submitted name and address on the same page.
   - The user can see their submitted data displayed below the form after submission.

5. Page Routing:
   - The server uses the "helloHandler" function to handle requests to the "/hello" endpoint.
   - When a user visits "localhost:8088/hello" in their web browser, the server responds with a "hello!!!" message.

Usage:
To run the project, ensure you have Go installed on your system. Follow these steps:

1. Clone the repository from GitHub.
2. Open a terminal or command prompt and navigate to the project directory.
3. Run the Go server using the following command:
   ```bash
   go run main.go
   ```
4. The server will start on port 8088. You can access the static website by opening a web browser and visiting "http://localhost:8088."
5. On the homepage, you will see a greeting message.
6. Click on the "Submit" button after filling out the form with your name and address.
7. The server will process the form data and display a "Post request successful" message along with your submitted name and address.

Note:
This project is intended for educational purposes and serves as a basic example of handling form submissions with a Go server. It can be expanded and enhanced to include more features like data validation, database integration, or additional form fields based on specific requirements. Feel free to modify and build upon it according to your needs.
