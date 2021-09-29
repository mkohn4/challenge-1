# Code Refactor Starter Code
Changes Made:
- update title
- change <div class="search-engine-optimization"> to an id
- change CSS for the sections to be one css style set of rules
    - add comments for hero section in css
    - change classes for hero section to hero-styles
    - update css for each hero style section to be using the same CSS and replace existing
- Update img attributes with alt text and remove </img> tag to replace with just /> ending
- add p {font-size: 16px;} to the body attribute
- move a attribute to .header a for now to make header links white
- create new section for hero-content css in comments and move all css for content section into it
- add benefit section for CSS
- consolidate benefits css to benefit-item class and replace all other references in CSS for benefit-lead and others to benefit-item - remove extraneous styles code
- update HTML to match
- add html comments


Acceptance Criteria: 
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title



Grading Requirements
This challenge is graded based on the following criteria:

Technical Acceptance Criteria: 40%
Satisfies all of the preceding acceptance criteria plus the following code improvements:

Application's links all function correctly.

Application's CSS selectors and properties are consolidated and organized to follow semantic structure.

Application's CSS file is properly commented.

Deployment: 32%
Application deployed at live URL.

Application loads with no errors.

Application GitHub URL submitted.

GitHub repository that contains application code.

Application Quality: 15%
Application resembles (at least 90%) screenshots provided in challenge instructions.
Repository Quality: 13%
Repository has a unique name.

Repository follows best practices for file structure and naming conventions.

Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

Repository contains multiple descriptive commit messages.

Repository contains quality README file with description, screenshot, and link to deployed application.

