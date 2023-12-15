
# Golang Server

Golang Server is a simple web server implemented in Go that serves static files and handles basic form submissions. The project includes an example of serving static HTML files and processing form data.

## Project Structure

The project is structured as follows:

- **main.go:** Entry point of the application. Initializes the server, defines request handlers for serving static files and processing form submissions.

- **static/form.html:** HTML file containing a simple form with fields for name and address.

- **static/index.html:** HTML file for the static homepage.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/golang-server.git
   cd golang-server
   ```

2. **Run the Application:**
   ```bash
   go run main.go
   ```
   The application will start on port `8080` by default.

3. **Access the Static Homepage:**
   Open your web browser and visit [http://localhost:8080](http://localhost:8080) to access the static homepage.

4. **Access the Form Page:**
   Open your web browser and visit [http://localhost:8080/form](http://localhost:8080/form) to access the form page.

5. **Submit Form:**
   Fill in the form fields and submit to see the form data being processed.

## Project Features

### Serving Static Files

- The server serves static HTML files from the `./static` directory.

### Form Submission

- The server handles form submissions from the `/form` endpoint.
- Access the form page at [http://localhost:8080/form](http://localhost:8080/form).
- Enter values in the form and submit to see the data processed.

## Dependencies

- None (Standard Go libraries only).
