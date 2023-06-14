# Test Project

### Before you start:

All documentation you will need regarding the Marketo specific requirements can be found in following links. The general documentation of Gulp & SASS are included as well.
1. https://docs.marketo.com/display/public/DOCS/Create+a+Guided+Landing+Page+Template
2. https://developers.marketo.com/javascript-api/forms/api-reference/
3. https://developers.marketo.com/rest-api/assets/forms/examples/
4. https://gulpjs.com/docs/en/getting-started/quick-start/
5. https://sass-lang.com/documentation  

Note that we use a version of Gulp-SASS for this project and Gulp runs all tasks and dependencies.


**If you do not yet have access to the Marketo Sandbox Instance please let your LeadFabric contact know**

### Requirements:

- Create your own branch containing your first and last name
- The project requires dependencies, those are missing. Install Gulp, install the dependencies and compile the project using the 'gulp' command.
- Add SASS/SCSS style & Marketo form to recreate the [design](/app/img/brief.png) provided in the [img folder](/app/img), all other assets can be found in [this folder](/app/img) as well.
- Make H1 & H2 titles editable in Marketo.
- Make banner "button" editable. Both text and href.
- Embed Marketo form to the landing page which can be found here: https://engage-lon.marketo.com/?munchkinId=275-OTA-175#/classic/FO1571B2
- Make a small javascript that prefills your first name, last name and email address in the Marketo form in the script file. Not inline in the HTML. Use the MarketoForms2 JS Library.
- Remove the 'dist' folder from the .gitignore file, stage & commit your changes and let your contact within LeadFabric know you're done, including a link to your fork/branch or create a pull request.

**Bonus:**
- Add a boolean that shows/hide the H2 title and make it hidden by default.
- Modify the styling to make it responsive through mobile-first strategy. You can find a media-queries mixin in the 'mixins' folder.


**Approximate values are fine! Do not lose time by nitpicking colors, font sizes, paddings, border radius, ... in reality these are received through brand guideline files or existing assets**. 

Good luck!
