## Design of a Flask Application to Teach Mountain Climbing

### HTML Files

- **index.html**: This file will serve as the landing page of the website. It will contain basic information about the website, such as a description of the content and links to other pages.
- **lessons.html**: This file will contain the main content of the website, which are the mountain climbing lessons. It will be organized into sections, with each section covering a specific aspect of mountain climbing (e.g., gear, techniques, safety).
- **about.html**: This file will provide information about the author of the website and their qualifications in mountain climbing.
- **contact.html**: This file will provide a form for visitors to contact the author if they have any questions or feedback.

### Routes

- **@app.route('/')**: This route will map to the index.html file. It will be the main entry point for the website.
- **@app.route('/lessons')**: This route will map to the lessons.html file. It will display the mountain climbing lessons.
- **@app.route('/about')**: This route will map to the about.html file. It will display information about the author.
- **@app.route('/contact')**: This route will map to the contact.html file. It will display a form for visitors to contact the author.
- **@app.route('/submit-form', methods=['POST'])**: This route will handle the submission of the form on the contact.html page. It will process the data entered by the visitor and send it to the author's email address.