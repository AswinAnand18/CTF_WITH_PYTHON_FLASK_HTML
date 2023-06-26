# CTF_WITH_PYTHON_FLASK_HTML
Developing a Capture the Flag (CTF) project in Python can be an exciting way to enhance your programming and cybersecurity skills. A CTF project typically involves creating challenges or puzzles that require participants to solve them by finding vulnerabilities, exploiting systems, or analyzing code
In this example, we use the Flask web framework to create a simple CTF login challenge. The project consists of two files: app.py and index.html.

The Python code in app.py defines a Flask application with two routes. The '/' route renders the index.html template when accessing the root URL. The '/login' route handles the form submission and checks if the provided credentials match the expected ones. If the credentials are correct, the server responds with the flag; otherwise, it returns an "Invalid credentials" message.

The HTML code in index.html creates a login form with two input fields for username and password. The form's action is set to /login, which corresponds to the route defined in app.py.

To run this CTF project, you need to install Flask by executing pip install flask in your Python environment. Save the Python code in a file named app.py and the HTML code in index.html. Then, execute python app.py in the terminal to start the Flask development server.

Participants can access the CTF challenge by navigating to http://localhost:5000 in their web browser. They will see a login form and need to find the correct username and password combination to obtain the flag.

Keep in mind that this is a simple example, and you can expand on it by adding more complex challenges, such as cryptographic puzzles, reverse engineering tasks, or network-based challenges.
