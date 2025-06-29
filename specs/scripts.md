# Scripts Section

- jQuery (CDN: //code.jquery.com/jquery-1.11.1.min.js)
- Bootstrap JS (CDN: //maxcdn.bootstrapcdn.com/bootstrap/3.3.4/js/bootstrap.min.js)
- Plugin JS: jquery-easing, classie.js, cbpAnimatedHeader.js
- Contact form JS: jqBootstrapValidation.js, contact_me.js
- Custom JS: agency.js

## Contact Form Scripts

- **jqBootstrapValidation.js**: Adds validation to all visible input and textarea fields in the contact form. Prevents submission if validation fails.
- **contact_me.js**: Handles AJAX form submission to Formspree endpoint. On success, displays a green success alert and resets the form. On error, displays a red error alert and resets the form. Success/error messages are shown in the #success div. Clicking the name field clears the #success message. Uses field IDs: #name, #email, #phone, #message.
- Form action: https://formspree.io/f/mjkgqayq (POST, JSON)
- Button: Send Message (type=submit, class="btn btn-xl")

## Google Analytics

- Uses Universal Analytics (analytics.js)
- Tracking ID: UA-53669200-2
- Loads analytics.js from //www.google-analytics.com/analytics.js
- Initializes with:
  - ga('create', 'UA-53669200-2', 'auto');
  - ga('send', 'pageview');
- Script is loaded asynchronously
- Full snippet:

```html
<script type="text/javascript">
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
      (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
      m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
  ga('create', 'UA-53669200-2', 'auto');
  ga('send', 'pageview');
</script>
```
