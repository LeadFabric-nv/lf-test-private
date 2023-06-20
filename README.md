# Test Project

### Before you start:

All documentation you will need for this test can be found in following links, this test will focus on your ability to adapt to a new environment.
The general documentation of Gulp & SASS are included as well.

1. https://docs.marketo.com/display/public/DOCS/Create+a+Guided+Landing+Page+Template
2. https://developers.marketo.com/javascript-api/forms/api-reference/
3. https://developers.marketo.com/rest-api/assets/forms/examples/
4. https://gulpjs.com/docs/en/getting-started/quick-start/
5. https://sass-lang.com/documentation  

Note that we use a version of Gulp-SASS for this project and Gulp runs all tasks and dependencies.

**Approximate values are fine! Do not lose time by nitpicking colors, font sizes, paddings, border radius, ... in reality these are received through brand guideline files or existing assets**. 

**If you do not yet have access to the Marketo Sandbox Instance please let your LeadFabric contact know**

### Requirements:

- The project requires dependencies, those are missing. Install Gulp, install the dependencies and compile the project using the 'gulp' command. The gulpfile is already configured.
- Add SASS style & Marketo form to recreate the [design](/app/img/brief.png) provided in the [img folder](/app/img), all other assets can be found in [this folder](/app/img) as well.
- Make H1 & H2 titles editable in according to the Marketo syntax.
- Make banner "button" editable. Both text and href, according to the Marketo syntax.
- Embed Marketo form to the landing page using the snippet below:
```
<script src="https://275-OTA-175.mktoweb.com/js/forms2/js/forms2.min.js"></script> <form id="mktoForm_1571"></form> <script>MktoForms2.loadForm("https://275-OTA-175.mktoweb.com", "275-OTA-175", 1571);</script>
```
- Make a small javascript that prefills your first name, last name and email address in the Marketo form in the script file. Not inline in the HTML. Use the MarketoForms2 JS Library.
- Remove the 'dist' folder from the .gitignore file, stage & commit your changes and let your contact within LeadFabric know you're done, including a link to your fork/branch or create a pull request.


Good luck!
