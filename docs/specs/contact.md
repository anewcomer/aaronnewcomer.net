# Contact Section (#contact)

Section heading: **Contact**  
Subheading: *Help me help you.*

Contact Form Fields:
- **Your Name** (required, input#name)
- **Your Email** (required, input#email)
- **Your Phone** (optional, input#phone)
- **Your Message** (required, textarea#message)

Form action: [Formspree endpoint](https://formspree.io/f/mjkgqayq)  
Method: POST  
Data type: JSON

Validation:
- Uses jqBootstrapValidation for all fields
- Prevents form submission if validation fails
- Only visible fields are validated

Submission:
- On success: shows a green success alert and resets the form
- On error: shows a red error alert with the user's first name and resets the form
- Alerts are shown in the #success div
- Success message: "Your message has been sent."
- Error message: "Sorry [First Name], it seems that my mail server is not responding. Please try again later!"

Other behaviors:
- Clicking on the name field clears the #success message
- Tab navigation for form tabs is supported

Button: **Send Message** (type=submit, class="btn btn-xl")

Dependencies:
- jQuery
- jqBootstrapValidation

To recreate:
- Use a form with the above fields and IDs
- Add jqBootstrapValidation to inputs and textarea
- Use AJAX POST to Formspree endpoint with name, email, phone, and message as data
- Display success/error messages in a #success div
- Reset the form after submission (success or error)
