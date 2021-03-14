# Learning Log


# Format

## DATE, 2021

**Today's Progress**:

**Thoughts**: 

**Link to work**:

**Resources**

----------------------------------------------------------
# 2021

## March 13, 2021 (Day 57 #100DaysOfCode)

**Today's Progress**:
- Completed JavaScript Challenges in Module 4 of the Career Path
- Learned how to build an image carousel with HTML, CSS & vanilla JavaScript

**Link to work**:
- [Image carousel with vanilla JavaScript](https://codepen.io/maelingcodes/pen/ExNMYjp)

----------------------------------------------------------
## March 12, 2021 (Day 56 #100DaysOfCode)

**Today's Progress**:
- Continued JavaScript Challenges in Module 4
    - Started learning how to build a carousel with HTML, CSS & JS

**Thoughts**: 
- If we put position: relative; on the parent element, anything inside of it with position: absolute; will be placed absolutely, relative to that containing unit! - csstricks.com
- You can use the CSS `transform: translateY();` property to get perefect vertical alignment of elements when positioning. This was useful to use when vertically aligning the buttons after using the `top` property to position the buttons on top of the image 

----------------------------------------------------------
## March 11, 2021 (Day 55 #100DaysOfCode)

**Today's Progress**:
- Purchased domain name on namecheap.com for my portfolio/blog site! - maeling.dev
- Continued JavaScript Challenges in Module 4: Created a search bar for a list of items and used the `startsWith()` method and `keyup` event in JS to display items that match the query as you type and hide all non-matches. 

**Thoughts**: 
- I started building the search to find matches in the list using the `includes` method, but realized when I was searching for apples, both apples and pineapples were listed as matches, since technically they both include 'apples'. To be more specific with the match, I decided to go with the `startsWith` method. 

**Link to work**:
- [Search Bar - startsWith() method](https://codepen.io/maelingcodes/pen/BaQveLW)

**Resources**
- [startsWith() method](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/startsWith)

----------------------------------------------------------
## March 10, 2021 (Day 54 #100DaysOfCode)

**Today's Progress**:
- Started JavaScript challenges section in Module 4 and started learning how to build a modal

----------------------------------------------------------
## March 9, 2021 (Day 53 #100DaysOfCode)

**Today's Progress**:
- Spent some practicing how to center an element horizontally and vertically on a screen using flexbox (see codepen link below)

**Thoughts**: 
- Images are inline elements. You can use `text-align: center` to center an image within a `div` element 
- It's good practice to apply focus states whenever applying hover states in CSS 

**Link to work**:
- [CodePen: Centering an element on the screen vertically & horizontally](https://codepen.io/maelingcodes/pen/KKNrqzK)

----------------------------------------------------------
## March 8, 2021 (Day 52 #100DaysOfCode)

**Today's Progress**:
- Completed CSS Fundamentals section in Module 4 
    - Specificity of selectors: element < class < id
    - Compound selectors
    - Font-related properties & how to use Google Fonts
    - Inheritance 
- Practiced recreating a layout from a provided image using HTML & CSS

----------------------------------------------------------

## March 7, 2021 (Day 51 #100DaysOfCode)

**Today's Progress**:
- After studying more CSS Fundamentals, I went back to one of my static site projects (Coding Journey Resources) from a few months ago & revamped the HTML structure & CSS styling with my new understanding! It's looking so much better now & I have a more fluid layout.

----------------------------------------------------------
## March 6, 2021 (Day 50 #100DaysOfCode)

**Today's Progress**:
- Continued CSS Fundamentals section in Module 4 (Scrimba FE Career Path)

----------------------------------------------------------
## March 5, 2021 (Day 49 #100DaysOfCode)

**Today's Progress**:
- Started Module 4 (CSS & JavaScript Fundametals) on the Scrimba FE Career Path. Started the CSS Fundamentals Section with Kevin Powell. 

**Thoughts**: 
- Margin collapsing: If an element has a margin-bottom of 50px & another element under it has a margin-top of 50px, the space between them will be 50px and NOT 100px. Doesn't apply to flexbox/grid layouts. If a child element has a margin-top, it can merge with the parent's margin-top setting, even if parent has no margin value set. This can be fixed by adding padding on the parent to prevent the parent's margin from merging with the child's. In order to better understand this behavior, I made a [CodePen](https://codepen.io/maelingcodes/pen/jOVpgxQ).

----------------------------------------------------------
## March 3, 2021 (Day 48 #100DaysOfCode)

**Today's Progress**:
- Created my first quiz web app with HTML, CSS & vanilla JavaScript! It's a short quiz on commonly used JavaScript methods when dealing with arrays. 

**Link to work**:
[JavaScript Methods Quiz](https://maelingmurphy.github.io/javascript-quiz/)

----------------------------------------------------------

## March 2, 2021 (Day 47 #100DaysOfCode)

**Today's Progress**:
- Completed 'Build a diary app' section in Module 3
    - Accessing elements from the DOM: `document.querySelector`, `document.querySelectorAll`, `document.getElementById`, `document.getElementsByClassName`
    - Creating new DOM elements: `document.createElement()`
    - Appending elements to the DOM: `appendChild()`
    - Using event listeners: `addEventListener`
- Completed Module 3 of Scrimba's Frontend Development Career Path

**Thoughts**: 
- I learned that you can access a global variable declared in a js file in a separate js file as long as the files have been loaded 

**Resources**
1. [JavaScript quiz made by Scrimba community member (Palak)]()https://scrimba.com/scrim/co79a429ba5477f130defdcc7
2. [Access variables from another file](https://stackoverflow.com/questions/3244361/can-i-access-variables-from-another-file)

----------------------------------------------------------
## March 1, 2021 (Day 46 #100DaysOfCode)

**Today's Progress**:
- Started 'Build a diary app' section in Module 3

----------------------------------------------------------
## February 28, 2021 (Day 45 #100DaysOfCode)

**Today's Progress**:
- Finished 'Your personality in emojis' section in Module 3
- Started work on Scrimba's weekly web dev challenge: Building a quiz (HTML, CSS, JS)

**Thoughts**: 
This exercise was very helpful in practicing modifying an array using `push()`, `unshift()`, `pop()`, `shift()` and using event listeners

**Link to work**:
[My Emojis](https://scrimba.com/scrim/co77c4ecca8e218eedeeea94b)

----------------------------------------------------------
## February 26, 2021 (Day 44 #100DaysOfCode)

**Today's Progress**:
- Continued 'Intro to the DOM':
    - Modifying elements
        - Text: `innerHTML` and `textContent` properties 
        - CSS styles: `style`
        - CSS classes: `className` & `classList` properties 
            - `classList.add`
            - `classList.remove`
            - `classList.toggle`
        - Input values: `value` property
    - Creating elements
        - Using `innerHTML` property
        - Using `createElement()`
        - Adding elements to parent:
            - `append()` method
            - `prepend()` method
        - Creating elements with a `for` loop
    - Event listeners 
        - `addEventListener()`
        - `removeEventListener()`

**Link to work**:
[Log & Display Input Values](https://scrimba.com/scrim/cofbc4185a6dab6ac2aa3fc61)

----------------------------------------------------------
## February 25, 2021 (Day 43 #100DaysOfCode)

**Today's Progress**:
- Started 'Intro to the DOM' in Module 3:
    - Ways to select elements from the DOM:
        - `getElementById()`
        - `getElementsByClassName()`
        - `getElementsByTagName()`
        - `querySelector()`
        - `querySelectorAll()`

----------------------------------------------------------
## February 24, 2021 (Day 42 #100DaysOfCode)

**Today's Progress**:
- Won Scrimba's weekly web dev challenge for my two-way unit converter site!! (https://maelingmurphy.github.io/dog-human-age-converter/)
- Continued 'Intro to Functions & Methods':
    - Used `Math.floor()` and `Math.random()` to create a random quote generator
    - Covered methods:
        - `slice()`
        - `push()`
        - `unshift()`
        - `pop()`
        - `shift()`
- Learned how to use `document.createElement()` and `appendChild()` to create a list of items that are taken from input field values.

**Link to work**:
1. [Random quote generator](https://codepen.io/maelingcodes/pen/mdOpwga)
2. [Add items to a list using input field](https://codepen.io/maelingcodes/pen/rNWpjVV)

----------------------------------------------------------
## February 23, 2021 (Day 41 #100DaysOfCode)

**Today's Progress**:
- Finished Scrimba's weekly dev challenge - Dog Age to Human Age Unit Converter (link below)
- Started 'Intro to Functions & Methods' section in Module 3 

**Thoughts**: 
- This was great practice for working with events, event listeners, string conversions, operations w/ floats, CSS flexbox & media queries. 

**Link to work**:
- [Dog Age - Human Age Unit Converter](https://maelingmurphy.github.io/dog-human-age-converter/)

**Resources**
- [Using <span> to create line breaks with CSS](https://stackoverflow.com/questions/2703601/how-to-line-break-from-css-without-using-br)

----------------------------------------------------------
## February 22, 2021 (Day 40 #100DaysOfCode)

**Today's Progress**:
- Finished the 'Intro to Loops' section in Module 3 
- Worked on Scrimba's weekly web dev challenge creating a dog age- human age converter:
    - Function:
        - parseFloat() - parses an argument and returns a floating point number
    - Events:
        - keyup event - input (type = number)
        - change event - select dropdown
    - Methods
        - toString() - converts integer to a string
        - toFixed() - converts 

**Thoughts**:
- Worked on the logic in JS for a 2-way unit converter based on what pops up when you try to convert units via Google search. The logic ended up being a bit more complicated than I had assumed but it's functioning! Now how to refactor this lengthy code!

**Resources**
- [parseFloat()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseFloat)
- [toFixed()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/toFixed)
- [toString() method]()
- [keyup event]()
- [change event]()


----------------------------------------------------------
## February 20, 2021 (Day 39 #100DaysOfCode)

**Today's Progress**:
- Installed node and npm: https://nodejs.org/en/download/
    - check node version: `node -v`
    - check npm version: `npm -v`
- Got the CodeRunner extension running in VSCode so I can now run my .js files and access the output in the console
- Used JavaScript, HTML & CSS to build a pacman-style board in Scrimba Module 3 lesson

**Thoughts**:
- Got some practice with the classList method, which I used to add different classes to HTML elements for styling in CSS based on logic. Used classes to create the walls, pac-dots, pacman & ghosts!

**Link to Work**:
[Pacman board with HTML, CSS & JS](https://scrimba.com/scrim/cod9e43989f6e6e1f87bdb92c)


----------------------------------------------------------
## February 19, 2021 (Day 38 #100DaysOfCode)

**Today's Progress**:
- Installed code runner for Visual Studio Code to be able to see console output from JavaScript code (Doesn't work because I don't have node and npm installed - in progress)
- Worked on Module 3 of Scrimba's Front-End Developer Career Path
    - Completed 'Your first interactive website'
    - Completed 'Intro to JavaScript'

**Thoughts**:
- Enjoyed learning about these concepts in JavaScript
    - variables
    - primitive & complex data types
    - objects
    - comparison operators
- Practiced declaring an object & accessing its properties via dot notation & bracket notation

**Resources**
1. [JavaScript Objects](https://www.w3schools.com/js/js_objects.asp)
2. [How to view JavaScript output in VSCode](https://www.youtube.com/watch?v=X_TVF96Kqcw)

----------------------------------------------------------
## February 18, 2021 (Day 37 #100DaysOfCode)

**Today's Progress**:
- Completed Module 2 of Scrimba's Front-End Developer Career Path
- Started Module 3 - Making Websites interactive 

**Thoughts**: 
- I really enjoyed learning how to use flexbox to create layouts with columns.When you add `display:flex` to a parent element, its direct children become flex items/columns. The parent element becomes the flex container. 

**Link to work**:
- [Scrimba's HTML & CSS Challenge - my scrim](https://scrimba.com/scrim/co2cf47f796f01c91d8b71830)

----------------------------------------------------------
## February 17, 2021 (Day 36 #100DaysofCode)

### Container Gardening Site - [Link to repo](https://github.com/maelingmurphy/Container-Gardening-Site)
**Today's Progress**:
- Used flexbox to style header. Set `display:flex` on parent header element and then set `display:flex` on nav element so menu items would line up horizontally. I then adjusted the `padding-left` property on the nav menu items to get appropriate spacing.

**Thoughts**: 
- Learned about the `list-style-position` CSS property that is used for styling lists. It sets the position of the marker relative to a list (marker for unordered list = bullet(default), marker for ordered list(numbers)). You can set it to `outside` (default) and `inside`.

**Link to Work**:
[Container Gardening Site](https://maelingmurphy.github.io/Container-Gardening-Site/)

**Resources**
 - [list-style-position property for styling lists](https://stackoverflow.com/questions/11556493/second-line-in-li-starts-under-the-bullet-after-css-reset/11556534)

----------------------------------------------------------

## February 16, 2021 (Day 35 #100DaysofCode)

### Container Gardening Site - [Link to repo](https://github.com/maelingmurphy/Container-Gardening-Site)
**Today's Progress**:
- Started working on basic HTML structure for site with incorporation of CSS flexbox for the layout
- Changed default branch from master to main

**Thoughts**: 
- I learned the importance of having to reset browser CSS styles as I was trying to figure out why I was seeing spaces between my block level elements. I'm glad I had a background color applied to them so I could see the spaces that were there due to browswer CSS properties. 

**Resources**
1. [Controlling ratios of flex items along the main axis](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Controlling_Ratios_of_Flex_Items_Along_the_Main_Ax)
2. [Basic concepts of flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
3. [CSS Tools: Reset CSS](https://meyerweb.com/eric/tools/css/reset/)
4. [5 steps to change GitHub default branch from master to main](https://stevenmortimer.com/5-steps-to-change-github-default-branch-from-master-to-main/)

----------------------------------------------------------

## February 14, 2021 (Day 34 #100DaysOfCode)

**Today's Progress**:
- Completed Scrimba's Weekly Dev Challenge and made a hover flip card with HTML & CSS. Used CSS concepts:
    - Pseudo-elements
    - Transform properties 
    - Positioning
    - Flexbox

**Link to work**:
- [Valentine's Day Hover Flip Card](https://scrimba.com/scrim/cof6b4a88beeb7d3943d95e27)


----------------------------------------------------------
## February 13, 2021 (Day 33 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Scrimba's CSS Crash Course:
    - `background-image` property

----------------------------------------------------------
## February 12, 2021 (Day 32 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Scrimba's CSS Crash Course:
    - Block element content wrapping: https://codepen.io/maelingcodes/pen/GRNrRaG

----------------------------------------------------------
## February 11, 2021 (Day 31 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Started Scrimba's CSS Crash Course and covered:
    - CSS syntax: selectors + property-value pairs = CSS rules 
    - Ways of adding CSS to doc (inline, embedded, external stylesheet)
    - Inheritance: Elements inherit properties from their parents (usually applies to type and fonts)
    - Cascade: Declarations that are made lower down in the stylesheet will override earlier declarations 
- Learned how to use `strptime()` to convert a string to a datetime object and `strftime()` to change the format of a datetime object. Applied this to my project by changing the date display format for the Activity and Attendance tables.
- Created custom Jinja template filters to format date-related Jinja template variables within my project 

**Thoughts**: 
- I learned that you can create your own Jinja filters to modify your template variables. I created a custom filter to change the date display format. I had to add the following lines of code to my `__init__.py` file, right under the creation of the Flask app instance.
```python
# Create custom filters to use on Jinja template variables
@app.template_filter()
def datetime_format_filter(value, format='%m-%d-%Y'):
    """Convert a datetime to a different format."""
    return value.strftime(format)

app.jinja_env.filters['datetime_format_filter'] = datetime_format_filter

@app.template_filter()
def string_to_datetime_filter(value):
    """Convert string to datetime object."""
    return datetime.datetime.strptime(value, '%Y-%m-%d')

app.jinja_env.filters['string_to_datetime'] = string_to_datetime_filter
```
To apply the filter to the variable, use pipe `|` within the template variable code block in the html file: `{{ today | datetime_format_filter }}`
You can also chain multiple filters that will be applied to the variable from left to right. This was useful when I needed to first convert a string to a datetime object so I could then change the date format using `strftime()` via the datetime_format_filter: `<td>{{ activity.activity_date | string_to_datetime_filter | datetime_format_filter }}</td>`

**Resources**
1. [Formatting dates - strftime() and strptime() behavior](https://docs.python.org/3/library/datetime.html#strftime-strptime-behavior)
2. [Primer on Jinja templating](https://realpython.com/primer-on-jinja-templating/#custom-filters)
3. [Jinja template filters](https://ttl255.com/jinja2-tutorial-part-4-template-filters/)

----------------------------------------------------------
## February 9, 2021 (Day 30 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Read about Flask routes
- Completed Scrimba's HTML Crash Course and built a mini site with the skills I've reviewed so far:
https://scrimba.com/scrim/co1614f8f9ccb8679bbcf0430

**Resources**
1. [Flask routes](https://hackersandslackers.com/flask-routes/)
2. [Passing functions into flask routes](https://www.reddit.com/r/flask/comments/a31lh0/reusing_functions_for_different_pages/)
3. [Pluggable views - Flask](https://flask.palletsprojects.com/en/1.1.x/views/#pluggable-views)

----------------------------------------------------------

## February 7, 2021 (Day 29 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Continued with the HTML Crash Course section of The Frontend Development Career Path

----------------------------------------------------------
## February 5, 2021 (Day 28 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Learned how to use the `datetime` module and `timedelta` to calculate the week's start and end date based on a given date (current date). Created a repl to illustrate how the basic logic works (see resources).
- Added ability for user to update the data the activity table displays on `index.html` by selecting a date range and student. Wrote the appropriate database queries and logic for displaying the associated data in the table. 

**Thoughts**: 
```python
# This query does not work and yields the error: TypeError: Boolean value of this clause is not defined
activities_currentweek = db.session.query(Activity).filter(Activity.activity_date >= current_week_start and Activity.activity_date <= current_week_end).all()    
```
[This post](https://stackoverflow.com/questions/42681231/sqlalchemy-unexpected-results-when-using-and-and-or) gives a good explanation of why the above doesn't work and helped me to figure out the proper syntax below
```python
activities_currentweek = current_user.activities.filter((Activity.activity_date >= current_week_start) & (Activity.activity_date <= current_week_end)).all()
```

**Resources**
1. [Give start and end of week data based on given date](https://stackoverflow.com/questions/19216334/python-give-start-and-end-of-week-data-from-a-given-date)
2. [Repl - How to calculate start and end dates of a week based on current date](https://repl.it/@maelingmurphy/Date-Ranges-from-Given-Date#main.py)
3. [Filtering on a datetime object](https://stackoverflow.com/questions/51451768/sqlalchemy-querying-with-datetime-columns-to-filter-by-month-day-year/51468737)
4. [Using boolean SQL expressions: and_(), or_(), not_(), etc.](https://stackoverflow.com/questions/42681231/sqlalchemy-unexpected-results-when-using-and-and-or)

----------------------------------------------------------

## February 4, 2021 (Day 27 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Continued with Frontend Development Career Path (Module 2)

----------------------------------------------------------
## February 3, 2021 (Day 26 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Continued with Frontend Development Career Path: Started Module 2
    - HTML elements
    - Basic HTML file structure
    - Headings and paragraphs
    - Strong `<strong>` and emphasis `<em>` inline elements
- Worked on Homeschool Web App:
    - Add activity table to `index.html`
    - Wrote query to select activity data for current date (`today`) in `/index` route
    - Added select dropdown form that will eventually link to queries to show activities based on selection (Today, This Week, Next Week)

**Thoughts**: 
- I've started taking notes for my coding courses in Notion and it's been extremely helpful for organizing my notes and embedding code snippets. It is also a database system, so it's also great for organizing the various resources I've been collecting for future review.
- I ran into an issue where I was trying to test submission in one form and it would display errors in a different form on the same page even though the original form passed validation and I had not clicked the submit button on the different form. I then realized that I had to change the names of the variables attributed to the `SubmitField` so they would be different for both forms (they were previously both named `submit`). Then I updated the conditional statement in the `/index` route that checked for the the name of the submit button passed from the form(input name is passed from WTForms field name) & checked form validation before continuing with further actions. Now validation works correctly for both forms on the `index.html` page. 

```python
# In forms.py

class AddAttendanceForm(FlaskForm):
    """Add attendance form"""
    attendance_date = DateField('Date', format='%Y-%m-%d')
    student = SelectField(u'Student', choices=[])
    submit = SubmitField('Log Attendance')

class DisplayActivitiesForm(FlaskForm):
    """Display activites form"""
    display = SelectField(u'Display', choices=['Today','This Week','Next Week'])
    display_submit = SubmitField('Display')

# In routes.py

# Validation for form
if "submit" in request.form and form2.validate_on_submit():
    # Continue with further steps

# Validation for form
if "display_submit" in request.form and form3.display.validate(form3):
    # Continue with further steps
```

**Resources**
1. [Combining multiple forms in WTForms](https://dev.to/sampart/combining-multiple-forms-in-flask-wtforms-but-validating-independently-cbm)
2. [Flask multiple forms on the same page](https://stackoverflow.com/questions/58122969/flask-multiple-forms-on-the-same-page)
3. [Notion](https://www.notion.so/)
4. [Scrimba's Frontend Development Career Path](https://scrimba.com/learn/frontend)

----------------------------------------------------------
## February 2, 2021 (Day 25 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Started Scrimba's Frontend Development Career Path and completed Module 1.

**Thoughts**: 
- In one of the introductory projects in the Frontend Development Career Path, I was introduced to using CSS custom properties(variables). This is something I need to incorporate in this project's design! CSS custom properties allow you to define a value in one place and then reference it multiple times in other places. 

**Resources**
1. Emojis: [getemoji.com](https://getemoji.com/), [emojipedia.com](https://emojipedia.org/) 
2. [CSS custom properties(variables)](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)
3. [Scrimba's Frontend Development Career Path](https://scrimba.com/learn/frontend)
----------------------------------------------------------

## January 31, 2021 (Day 24 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**: 
- Studied `onclick` event handlers and created a CodePen that shows/hides a box based via onclick event
- Added ability to dismiss Flask flash messages with button `onclick` event

**Link to Work**:
- [Show/Hide a box based on button onclick event](https://codepen.io/maelingcodes/pen/eYBmMQa)

**Resources**
- [How to - Alerts](https://www.w3schools.com/howto/howto_js_alert.asp)
----------------------------------------------------------
## January 30, 2021 (Day 23 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Completed Scrimba's Learn UI Design Fundamentals course
- Added logic to `/attendance` and `/index` routes that checks if attendance record already exists for a student before adding it to the database 

**Links to Work**:
1. [Learn UI Design Fundamentals - The Final Challenge](https://scrimba.com/scrim/co1674fe78bf180844353256c)
2. [Learn UI Design Fundamentals - Design Challenge 4: Visual Hierarchy](https://scrimba.com/scrim/co2c0433387188c01ecbd9341)
3. [Learn UI Design Fundamentals - Design Challenge 3: Color](https://scrimba.com/scrim/co8ec4c2a9b9b25989a37081c)

**Resources**
1. [StyleStage.dev - View how multiple people style one HTML page](https://stylestage.dev/styles/)

----------------------------------------------------------
## January 29, 2021 (Day 22 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Started Scrimba's Learn UI Design Fundamentals course to help me with the design aspect of my web app project

**Thoughts**: 
- Some of the fundamentals to consider for great design:
    - White Space
    - Color
    - Contrast
    - Scale
    - Alignment
    - Typography
    - Visual Hierarchy 
- WCAG has issued contrast guidelines for the visual representation of text and images of text. You can use contrast checking tools to help your projects adhere to these guidelines when designing (e.g. browser plugins, websites, UI design application plugins)

**Resources**
1. [WAVE - Web Accessibility Evaluation Tool](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh/related?hl=en-US)
2. [Contrast Checker - WebAim](https://webaim.org/resources/contrastchecker/) and their [API](https://webaim.org/resources/contrastchecker/?fcolor=EBE6EB&bcolor=1F76C7&api)
3. [Learn UI Design Fundamentals - Free course on Scrimba taught by Gary Simon](https://www.freecodecamp.org/news/learn-ui-design-fundamentals-with-this-free-one-hour-course/)

----------------------------------------------------------
## January 28, 2021 (Day 21 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Added ability for user to remove students and subjects (and their associated activities) from their Profile Edit pag (`profile-edit`)
- Learned how to use datetime module to create variable that holds current date. I had to pass the `today` variable to `index.html` and set it to the value attribute for the `{{ form2.attendance_date }}` field. 
```python
import datetime

today = datetime.date.today()
```
**Thoughts**: 
- I received errors when I removed a student from the database. Since I still had activities trying to show on `log.html` that were associated with that particular student id, the errors I received were SQL-related dealing with a NOT NULL constraint. I then realized I needed to also delete all associated student activities when deleting a student by accessing `student.activities`.
- I was able to get a static data HTML table working with Bootstrap Table with a filter extension that allows me to filter by the data in each column. However, I have not been able to get it to work with the dynamic data inserted via the Jinja template variables that are linked to my database queries. If I do end up getting this to work with my data, I will need to change my activity.status 'Not Completed' variable to 'Incomplete' so it will sort properly in the bootstrap-table. I may come back to trying to add this feature later but I did want to note what external dependencies I had to include to get the static TEST table on `log.html` working for Bootstrap Table - Filter Control:
    - CSS (place in <head> of `base.html`): 
        - `<link rel="stylesheet" href="https://unpkg.com/bootstrap-table@1.18.2/dist/bootstrap-table.min.css">`
    - JS (place right before `</body>` in `base.html`):
        -  `<script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-table/1.10.0/bootstrap-table.js"></script>`
        - `<script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-table/1.9.1/extensions/filter-control/bootstrap-table-filter-control.js"></script>`
**Resources**
1. [The Figma 2021 Crash Course by Example - Gary Simon](https://www.youtube.com/watch?v=Gu1so3pz4bA)
2. [Bootstrap Table Filter Control & Export Example](https://codepen.io/AurelieT/pen/JGxMgo)
3. [Bootstrap Table Options](https://bootstrap-table.com/docs/api/table-options/)
4. [Bootstrap Table - Getting Started](https://bootstrap-table.com/docs/getting-started/introduction/)
5. [datetime - Python docs](https://docs.python.org/3/library/datetime.html)
----------------------------------------------------------
## January 27, 2021 (Day 20 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Updated `/delete` route so activity records can be removed from the db via the delete button on the `log.html` page
- Added flash messaging to `update` route 
- Created user profile page (`profile.html`) that displays user's current list of students and subjects 
- Started working on an edit profile page (`profile-edit.html`) where user can add/remove students and subjects from their account.
    - Added functionality for user to add students and subjects to their account

**Thoughts**: 
- Glad to find out I can display two different FlaskForm classes on one html page. I did this so a user can add a student or a subject on the `profile-edit.html` page. When instantiating the forms in the route (`/profile-edit`), I made sure to have two different variable names for the forms and pass those two names through the render_template function to display the form fields via Jinja template variable names in `profile-edit.html`. 

**Resources**
- [Bootstrap Filter Control Table](https://examples.bootstrap-table.com/#extensions/filter-control.html)

----------------------------------------------------------
## January 26, 2021 (Day 19 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Changed submit button label text to 'Update Activity' on `update.html`: `form.submit.label.text = "Update Activity"`
- Added `/details` route and `details.html` to template files in order to display activity record details 

----------------------------------------------------------
## January 25, 2021 (Day 18 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Added column for a delete button in attendance log table on `attend.html`. Linked to database in `/delete/attendance` route to commit the deletion changes. 
- Linked form data to database in`/update` route so user can update an activity record. User selects activity record on `log.html`, which takes them to `update.html`. They are then presented with a form with the current activity data populating the form. The user can then make changes in the form and upon submission, the changes are updated and committed in the database.
- Added some CSS styling (`display:flex`) to the attendance log form. Will need to add media queries to display as block for smaller viewports

----------------------------------------------------------
## January 24, 2021 (Day 17 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Learned how to pass an object into a WTForms form to be able to autofill certain form fields 
- Learned how to pass URL arguments to Flask routes
- Added `/update` route which takes the activity title as an argument (passed from 'Update' button in table on `log.html`) and displays a form to edit activity details (need to populate with user's data for the specific activity record and link to database in order to commit changes)
- Figured out how to prepopulate data for all fields in the form shown when a user clicks to update their activity record. Form details are populated via the `/update` route and shown on `update.html`.

**Thoughts**: 
- The code below, which links to a WTForms TextAreaField, does NOT show the user's description that was saved to the db. Setting the value in this case does not prepopulate the form with this data from `activity.description`. 
```html
 <div class="form-group">
        {{ form.description.label }}
        {{ form.description(size=500, class_='form-control', value=activity.description) }}
</div>
```
but the code blocks for other WTForm fields (StringField, DateField) work at populating the user data from the db using the following code:
```html
<div class="form-group">
    {{ form.title.label }}
    {{ form.title(size=100, class_='form-control', value=activity.title) }} 
    {% for error in form.title.errors %}
    <span style="color:red;">[{{ error }}]</span>
    {% endfor %}
</div>

<div class="form-group float-item">
    {{ form.activity_date.label }}
    {{ form.activity_date(class_='datepicker form-control', value=activity.activity_date) }}
    {% for error in form.activity_date.errors %}
    <span style="color:red;">[{{ error }}]</span>
    {% endfor %}
</div>
```
- I'm having issues prepopulating my Update Activity form with user data because I cannot get the modal links to pass the activity id to the `/log` route. I think I may be able to avoid some issues by creating a separate `/update` route and view function and remove the modal windows from `log.html`.


**Resources**
1. [Populating WTForms form fields with data](https://stackoverflow.com/questions/42984453/wtforms-populate-form-with-data-if-data-exists)
2. [Passing URL Arguments in Flask Using URL Converter](https://www.youtube.com/watch?v=qYeWemghBxI)
3. [Passing variables into url_for](https://stackoverflow.com/questions/48265877/how-to-access-variables-within-html-template-url-for)
4. [FontAwesome Icon Gallery - Latest Version](https://fontawesome.com/icons?d=gallery)

----------------------------------------------------------
## January 23, 2021 (Day 16 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Displayed attendance records in table in descending order: `attendance_records = current_user.attendance.order_by(Attendance.attendance_date.desc()).all()`
- Diplayed activity records in table in ascending order: `activities = current_user.activities.order_by(Activity.activity_date).all()`
- Worked on 'Update Activity' modal on log.html. Modal window now shows field data associated with the specific activity record, to allow user to update an activity. Still working on how to prepopulate the checkbox if activity has already been completed (linked to WTForms BooleanField object). Still need to pass data to '/update' route to actually add any changes from form data to the database. Also need to learn how to prepopulate the student and subject dropdown fields in the modal window. 

**Resources**
1. [Build a CRUD web app with Python & Flask - Part Two](https://scotch.io/tutorials/build-a-crud-web-app-with-python-and-flask-part-two)
2. [Jinja, Flask and WTForms - how to pass parameters in field?](https://stackoverflow.com/questions/35768370/jinja-flask-and-wtforms-how-to-pass-parameters-in-field)
3. [Template Designer Documentation - Jinja](https://jinja.palletsprojects.com/en/2.11.x/templates/#assignments)
4. [How to change the default width of Bootstrap modal box](https://www.tutorialrepublic.com/faq/how-to-change-the-default-width-of-bootstrap-modal-box.php)
----------------------------------------------------------
## January 22, 2021 (Day 15 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Learned about how to undo changes in my repository with `git checkout`, `git revert` and `git reset`
- Reverted project to its state on 1/20/21
- Added student_id to Activity model and changed student-activity relationship to one-to-many in `models.py`
- Correctly passed student_id and subject_id to activity table when adding a new activity in `/add` route 
- Added `user_id` to `Subject` model. Changed user-subject relationship to one-to-many and removed user_subject helper table
- Used conditional logic to convert Boolean status data from Activity Form to "Completed"(True=1) or "Not Completed"(False=0), which was passed to the activity object in the database for the status field. 
- Learned how to implement FontAwesome icons within buttons and read about best practices for accessibility when using icons 
- Added ability to add attendance data for user's students on `attendance.html`
- Created a table to display all the attendance records associated with a user 

**Thoughts**: 
- I'm not sure what happened, but my `venv` folder disappeared from my project. Had to redo the following to setup my virtual environment:
    - Create a virtual environment: `python3 -m venv venv`
    - Activate virtual environment: source venv/bin/activate
    - Install flask: `pip install flask`
    - Set FLASK_APP environment variable: `export FLASK_APP=journal.py`
    - Install the python-dotenv package: `pip install python-dotenv`
    - Create .flaskenv file with environment variables for flask command (e.g. FLASK_APP=journal.py)
    - Upgrade pip version: `pip install --upgrade pip`
    - Install Flask-WTF: `pip install flask-wtf`
    - Install Flask-SQLAlchemy: `pip install flask-sqlalchemy`
    - Install Flask-Migrate: `pip install flask-migrate`
    - Install Flask-Login: `pip install flask-login`
    - Install Email() validator from WTForms: `pip install email-validator`
- To display headers when you're retrieving results from queries in sqlite terminal: `.headers on`. If you'd like to also display in column format: `.mode column`

**Resources**
1. [Undoing things with Git & GitHub](https://www.youtube.com/watch?v=RIYrfkZjWmA)
2. [Font Awesome Examples](https://fontawesome.com/v3.2.1/examples/)
3. [Accessibility with Icons - FontAwesome](https://fontawesome.com/how-to-use/on-the-web/other-topics/accessibility)
----------------------------------------------------------
## January 21, 2021 (Day 14 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- I am now able to display the current user's list of activities in `/log` view, although all of the associated data is not populated (see 'Thoughts' below)

**Thoughts**: 
- I feel like I've gone in loops today trying to understand how to write queries in Flask-SQLAlchemy. I am trying to understand why my subject and student name data don't show up in my Activity Log table. Now I'm not sure if I should save the subject and student names directly as fields in the Activity model OR if I should try to query the database to save the student and subject ids to the Activity model and then run another query when it's time to display the student and subject names in the Activity log (on `/log` view). I've made changes to my files tonight but I'm not pushing anything (except for my project log) because I probably should start with a clean slate for tomorrow since I'm in such a state of confusion. 
- Activity status type is a a Boolean where (0 = not completed (FALSE), 1 = completed (TRUE))

**Resources**
1. [Debugging Queries in Flask-SQLAlchemy](https://www.youtube.com/watch?v=5puPZ3n06EE)
2. [Query API - SQLAlchemy Docs](https://docs.sqlalchemy.org/en/13/orm/query.html)
3. [Flask-SQLAlchemy with examples](https://pythonbasics.org/flask-sqlalchemy/)
4. [Get list of column names in SQLite](https://stackoverflow.com/questions/685206/how-to-get-a-list-of-column-names/685212)
5. [Nested queries with Sqlalchemy](https://blog.miguelgrinberg.com/post/nested-queries-with-sqlalchemy-orm)

----------------------------------------------------------
## January 20, 2021 (Day 13 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Added string representations of the Student and Subject objects so the names could appear as choices in the the 'Add Activity' form in the `/add` route. 
- Passed 'Add Activity' form data to database. Removed mock objects for Subject and Student choices and replaced with user's student and subject data from their User object in the database.

**Thoughts**: 
- If terminal closes and need to run app, make sure to: Change into correct directory; Activate virtual environment `source venv/bin/activate` ; Export Flask environment variables `export FLASK_APP=journal.py`, `export FLASK_DEBUG=True`; Run the app `flask run`

**Resources**
1. [Python __str__() and __repr__() methods](https://www.journaldev.com/22460/python-str-repr-functions)

----------------------------------------------------------
## January 19, 2021 (Day 12 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Passed 'Add Subject' form data from `index.html` to '/index` route.
- Linked 'Add Subject' form data to database in `/index` route and learned how to insert data into table using a backref from a many-to-many relationship 

**Thoughts**: 
- (Referencing the code in the `\index` route in `routes.py`. I kept getting this error (`TypeError: 'int' object is not iterable`) when I was trying to link the student object with the backref ('admin'). I then realized I needed to append the  `current_user.id` to the admin property of the student object I created. I needed to use the 'admin' backref in this manner because I am dealing with a many-to-many relationship betweent the user and subject tables. 
```python
# The code that gave me the TypeError: 'int' object is not iterable
for name in subject_names:
            subject = Subject(subject_name=name, admins=current_user.id)
            db.session.add(subject)
            db.session.commit()

# The correct way to link the current_user to the student object, via the backref
# 'admin' that was created via the many-to-many relationship between user and subject
# tables
for name in subject_names:
            subject = Subject(subject_name=name)
            subject.admins.append(current_user) # Using backref to associate subject with current user
            db.session.add(subject)
            db.session.commit()
```


----------------------------------------------------------
## January 18, 2021 (Day 11 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Studied the differences between declaring models for one-to-many and many-to-many relationships
- Added 2 helper/association tables (user_subject, student_activity) (required for many-to-many relationships) to `models.py` and updated the models that required the `db.relationship()` function to relate properly to each other. 
- Updated form structure on `index.html` so user can add students and subjects to their profile. 

**Thoughts**: -
- I ran into errors when adding my helper tables and updating my models. I was able to create the migration script, but received an error (`raise ValueError("Constraint must have a name")`) when trying to run `flask db upgrade`. I was able to implement [this solution](https://stackoverflow.com/questions/45527323/flask-sqlalchemy-upgrade-failing-after-updating-models-need-an-explanation-on-h) which required adding a `naming_convention` to my __init__.py file. The solution worked after I deleted my existing database - `app.db`, `migrations/` folder and then ran `flask db init`, `flask db migrate` and finally `flask db upgrade `.
- To turn on debugger when running app,  run `export FLASK_DEBUG=True` in the terminal before running `flask run`

**Resources**
1. [Declaring models - Flask SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/models/)
2. [Creating One-To-Many Relationships in Flask-SQLAlchemy](https://www.youtube.com/watch?v=juPQ04_twtA)
3. [Creating Many-To-Many Relationships in Flask-SQLAlchemy](https://www.youtube.com/watch?v=OvhoYbjtiKc)
----------------------------------------------------------

## January 17, 2021 (Day 10 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Added `Student` and `Subject` database models to `models.py`

**Thoughts**: 
- Realized today that the relationship between my students and activities table is many-to-many. A student can have many activities and an activity can have many students. I need to create an association table to be able to join those two tables together for queries.

**Resources**
1. [Creating Many-To-Many Relationships in Flask-SQLAlchemy](https://www.youtube.com/watch?v=OvhoYbjtiKc)
2.  [Many to Many - SQLAlchemy Docs](https://docs.sqlalchemy.org/en/14/orm/basic_relationships.html#many-to-many)
3. [Many to many relationships in SQLAlchemy models (Flask)](https://www.michaelcho.me/article/many-to-many-relationships-in-sqlalchemy-models-flask)

----------------------------------------------------------
## January 16, 2021 (Day 9 #100DaysofCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Added student number to User database model
- Removed 'Add Student' fields from registration form
- Added 'Add Student(s)' form to index.html and updated the `/index` route so information passed from the form gets added to the database (names added to `student` table associated with user_id, student_number field in `user` table)
- Added conditional statment to index.html so the 'Add Student' section only shows if a user doesn't have a student number saved in the `user` table (e.g. `{% if not current_user.student_number %}`)
- Added CSS styling to Flash messaging by category

**Thoughts**: 
```sqlite
Open a database file in sqlite
sqlite> sqlite3 app.db

View all the tables in app.db
sqlite> .tables

View the schema for all tables in app.db
sqlite> .schema

Delete all rows from a table
sqlite> DELETE FROM <table>;

View all content in a table
sqlite> SELECT * FROM <table>;
```
- Flask `flash()` for flash messaging takes an optional second argument, categories. 

**Resources**
1. [Flashing messages with Flask](https://blog.tecladocode.com/flashing-messages-with-flask/)
2. [Message Flashing](https://flask.palletsprojects.com/en/1.1.x/patterns/flashing/)
----------------------------------------------------------
## January 15, 2021 (Day 8 #100DaysOfCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Figured out how to dynamically add input fields to a form based on a user's select input. I was able to remove and add fields so the field number matched the user's select number. I learned more about how to interact with the DOM using JavaScript.
- Added an app.js file to my project and linked it on `base.html`


**Thoughts**: 
- Ran into issues today trying to figure out how to pass data from dynamically generated fields to the route using WTForms. I had to use a specific naming sequence for my input fields and `request.form.get("<name>")` to be able to access the data in those fields that populated based on the user's input. This is my workaround till I learn something better! 

**Resources**
1. [Dynamically adding HTML form fields based on user's input](https://stackoverflow.com/questions/31988183/dynamically-adding-html-form-fields-based-on-a-number-specified-by-the-user)
2. [Event Listeners on select elements - 1 choice example](https://stackoverflow.com/questions/24875414/addeventlistener-change-and-option-selection)
3. [Event Listeners - change event](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/change_event)
4. [Adding input elements dynamically to form](https://stackoverflow.com/questions/14853779/adding-input-elements-dynamically-to-form#:~:text=If%20you%20want%20to%20dynamically,of%20them%20to%20the%20container.)
5. [Input text object properties](https://www.w3schools.com/jsref/dom_obj_text.asp)
6. [Dynamic Fields WTForms](https://www.rmedgar.com/blog/dynamic-fields-flask-wtf/)

----------------------------------------------------------

## January 14, 2021 (Day 7 #100DaysOfCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Added `RegistrationForm` class to `forms.py`
- Installed `Email()` validator external dependency from WTForms: `$ pip install email-validator`
- Added registration form structure to `register.html`
- Added link to registration page below login form on `login.html`
- Added `/register` view on `routes.py` 
- Added custom messages for WTForms validation errors on `forms.py`

**Thoughts**: 
- When you define a class in Python, you can create class variables and instance variables. A class variable will be shared by all instances and an instance variable is unique to each instance. A good example of this in my project is my `RegistrationForm` class in `forms.py`. 

**Resources**
1. [Python Class and Instance Variables](https://docs.python.org/3/tutorial/classes.html#class-and-instance-variables)
2. [Understanding Class and Instance Variables in Python3](https://www.digitalocean.com/community/tutorials/understanding-class-and-instance-variables-in-python-3)
-  [Chapter 5: User Logins - Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-v-user-logins)
3. [Form Validation with WTForms](https://flask.palletsprojects.com/en/1.1.x/patterns/wtforms/)

----------------------------------------------------------
## January 13, 2021 (Day 6 #100DaysOfCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Added password hashing and verification (added to `app/models.py` via Werkzeug package)
- Added user loader function to `app/models.py`
- Added login functionality via flask-login
- Added logout view
- Added conditional logic for displaying login or logout link in nav bar
- Added login requirement for certain views with login decorators
- Added redirect to 'next' page in login view

**Resources**
-  [Chapter 5: User Logins - Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-v-user-logins)

----------------------------------------------------------

## January 12, 2021 (Day 5 #100DaysOfCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Added email field to 'user' database model
- Added 'login' view to `routes.py`
- Added LoginForm class to `forms.py`
- Created login.html to display login form 
- Added Activity class in `models.py`
- Fixed Alter table errors due to SQLite, followed [these instructions](https://blog.miguelgrinberg.com/post/). Had to make adjustments to database instance in `app/__init__.py`

**Thoughts**: 
 - Learned about the concept of multiple inheritance in Python and how it leads to the ability to use mixins to add different features to a class.
 - You can use a `pass` statement when writing a loop or function in python to serve as a placeholder, since you can't have an empty body. If you left it with an empty body, the interpreter would give an error. 
 - You can apply `index=True` as an attribute to a database model field in order to speed up queries on this column
 ```python
 # Example for the user table in models.py

 class User(db.Model):
    id = db.Column(db.Integer, primary_key=True)
    username = db.Column(db.String(64), index=True, unique=True)
    email = db.Column(db.String(120), index=True, unique=True)
    password_hash = db.Column(db.String(128))
    students = db.relationship('Student', backref='admin', lazy='dynamic')
 ```
 - To view tables you created in sqlite, type `sqlite3 app.db` in the terminal. Then at the `sqlite>` command line, type `.tables`. To see schema for a specific table, type `.schema table`. To see all data in a specific table, type 

**Resources**
1. [Mixins and Python](https://www.ianlewis.org/en/mixins-and-python)
2. [Multiple inheritance in Python](https://www.geeksforgeeks.org/multiple-inheritance-in-python/)
3. [Python Multiple Inheritance](https://www.programiz.com/python-programming/multiple-inheritance)
4. [Making Python classes more modular using mixins](https://www.residentmar.io/2019/07/07/python-mixins.html)
5. [SQLAlchemy Column & Data Types](https://docs.sqlalchemy.org/en/14/core/type_basics.html)
6. [How to Connect to SQLite from Command Line](https://www.a2hosting.com/kb/developer-corner/sqlite/connect-to-sqlite-from-the-command-line)
----------------------------------------------------------

## January 11, 2021 (Day 4 #100DaysOfCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Learned how to view previews of my markdown (.md) files in VSCode. Right-click on code editor tab for file and select 'Open Preview'.
- Completed Chapter 4: Databases in the Flask Mega-Tutorial
- Integrated Flask-SQLAlchemy with my web app! Added User and Student database models in models.py  
- Learned how to create a shell context so you can open up a Python interpreter with the relevant elements from your project, pre-imported. Added `make_shell_context()` function to journal.py

**Thoughts**: 
- When saving datetime information in your database, it is recommended to work with UTC dates and times. This will ensure uniform timestamps regardless of where the users are located. The timestamps will then be converted to the user's local time when they are displayed. - (miguelgrinberg.com)
- Working with Flask-Migrate (Alembic):
    -  `flask db init`: initializes the migration repository 
    - `flask db migrate -m "<optional message>"`: generates the migration script
    - `flask db upgrade`: applies the changes to the database
    - `flask db downgrade`: undoes the last migration 
- Changes to the database are made within the context of a session, which is accessed through `db.session`. Changes that have been added (`db.session.add()`) are not actually committed to the database until `db.session.commit()` is called. `db.session.rollback()` aborts the session and removes any changes stored in it. 
- Database queries:
    - All models have a query attribute which allows you to run database queries
    - Query to return all elements of a specific class called User: User.query.all())
    - Query to return a user whose id = 1: User.query.get(1)
    ```python
    # Query to get all posts written by a user
    u = User.query.get(1)
    posts = u.posts.all()

    # Query to print post author and body for all posts
    posts = Post.query.all()
    for p in posts:
        print(p.id, p.author.username, p.body)

    # Query to get all users in reverse alphabetical order
    User.query.order_by(User.username.desc()).all()
    ```
- SQLAlchemy provides the use of `db.relationship`, which gives you a high-level view of the relationships between tables without having to deal explicitly with foreign keys
- The `flask shell` command helps to set up a Python interpreter with the imports relevant to your application. You can create a "shell context" that names which symbols you want to pre-import. You can write this "shell context" function in the main file used to run the app with an `app.shell_context_processor` decorator. When ready to use, run `flask shell` in terminal BEFORE opening up a Python interpreter. 

**Resources**
1. [Case Styles](https://medium.com/better-programming/string-case-styles-camel-pascal-snake-and-kebab-case-981407998841)
2. [Flask-SQLAlchemy documentation](https://flask-sqlalchemy.palletsprojects.com/en/2.x/)
3. [Declaring models in Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/models/)
4. [Chapter 4: Databases - Flask Mega-Tutorial by Miguel Grinberg](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-iv-database)
----------------------------------------------------------
## January 10, 2021 (Day 3 #100DaysOfCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Created mock objects and control statements to display activity information in table on log.html page until I can start pulling in info from the database. 
- Added new view function for displaying attendance history ('/attendance')
- Worked through Flask Mega-Tutorial (Chapter 2: Templates, Chapter 3: Web Forms)
- Made a dynamic WTForms SelectField with mock `students` and `subjects` object
- Added field validation with error displays and flash messaging 

**Thoughts**: 
- Creating mock objects can be useful when you're working on one part of the application but the other aspects of the system haven't been created yet. 
- Jinja2 is a template engine that comes with the Flask framework. The `render_template()` function takes a template filename and template arguments and then converts the placeholders, indicated by `{{ ... }}` blocks, to actual values. Control statements are given inside `{% ... %}` blocks.
- `GET` requests typically return information to the client(e.g. web browser). `POST` requests typically used when browser submits form data to the server. 
- Using the "with" construct in Flask template: From Miguel Grinberg -  " "with" in this situation is that this is more or less similar to using "with" in regular Python code. Basically what you get is that the variable defined as part of the with declaration can be used anywhere between the "with" and the "endwidth"."
- The `url_for()` function generates URLS, where the argument to url_for() is the endpoint name, which is the name of the view function. 
- You can use `os.urandom(24).hex()` to generate a random key, after importing the `os` library in Python 

**Resources**
1. [Form Validation with WTForms](https://flask.palletsprojects.com/en/1.1.x/patterns/wtforms/?highlight=form)
2. [Using CSRF with FlaskForm](https://flask-wtf.readthedocs.io/en/stable/csrf.html)
3. [The 'with' construct in Flask templates](https://www.reddit.com/r/flask/comments/8rc3oi/what_does_with_construct_do/)
4. [Flask Mega-Tutorial Chapter 2: Templates](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-ii-templates)
5. [Flask Mega-Tutorial Chapter 3: Web Forms](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-iii-web-forms)
6. [Dynamic WTForms SelectField](https://stackoverflow.com/questions/12850605/how-do-i-generate-dynamic-fields-in-wtforms)
7. [Message Flashing in Flask](https://flask.palletsprojects.com/en/1.1.x/patterns/flashing/)
----------------------------------------------------------
## January 9, 2021 (Day 2 #100DaysOfCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Added modal windows for editing an activity and viewing activity details on log.html page 
- Installed Flask-SQLAlchemy via terminal: `pip install flask-sqlalchemy`
- Installed Flask-Migrate via terminal to use with database migration framework, Alembic: `pip install flask-migrate`
- Added Config class to configuration file (config.py) and added if else logic to app.py for choosing which configuration attributes to apply to the Config class. 
- Added SQLALCHEMY configuration variables to config.py file 
- Changed file structure of app. Made the application a package instead of a module. Added routes.py and __init__.py to app/ folder.
- Created a migration repository using Flask-Migrate. Got STUCK because Flask-Migrate was not detecting the table that I created in models.py. Going to walk through the Flask Mega-Tutorial to see if I detect what the problem is. 
    - Completed Chapter 1: Hello World!

**Thoughts**: 
- The 'OS' module in Python provides functions for interacting with the operating system. OS is included in Python's standard utility modules (no need to install externally). `os.path` is a sub-module of OS module and is commonly used for path name manipulation. `os.path.dirname(path)` is a method that gets the directory name from a specified path. `os.path.abspath(path)` is a method that returns the pathname to the path that is passed in as a parameter to this function. 
- It's important to consider the principle of 'separation of concerns' when deciding the location for your app's configuration variables. Instead of putting them in the same file where you create your application, you can create a configuration class in a separate Python module. For my project, I'm creating a configuration class in config.py in the top-level directory. 
- Routes are the different URLS that the app serves to the user. Handlers for the app routes are called view functions. These view functions are mapped to one or more route URLs and serves a specific URL depending on the logic defined in the function. The @app.route decorator creates a relationship between the URL given as an argument and the function (miguelgrinberg.com)
- If your application is a module (e.g. app.py), then the templates folder should be next to that module. If your application is a package (e.g. app/), the templates folder is inside your package
- Flask-Migrate: The `flask db` sub-command is used to manage various database migration scenarios. `flask db init` creates the migration repository. `flask db migrate` creates a migration automatically. 
- Make sure to type `python3` in the terminal BEFORE I try to run Python code in the terminal! Forgetting to do so results in a `...can't read /var/mail/...` error 

**Resources**
1. [Using the aria-labelledby attribute](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-labelledby_attribute)
2. [The Flask Mega-Tutorial - Databases](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-iv-database)
3. [Python classes](https://docs.python.org/3/tutorial/classes.html)
4. [os.path.dirname() method](https://www.geeksforgeeks.org/python-os-path-dirname-method/)
5. [os.path.abspath() method](https://www.geeksforgeeks.org/python-os-path-abspath-method-with-example/)
6. [App Configuration & Web Forms](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-iii-web-forms)
7. [Flask configuration files - the best explanation I've come across so far for setting up config.py](https://pythonise.com/series/learning-flask/flask-configuration-files)
8. [How to set up folder structure for rendering templates](https://flask.palletsprojects.com/en/1.1.x/quickstart/#rendering-templates)
9. [How to add Flask-Migrate to project](https://blog.miguelgrinberg.com/post/how-to-add-flask-migrate-to-an-existing-project)


----------------------------------------------------------
## January 8, 2021 (Day 1 #100DaysOfCode)

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Started the #100DaysOfCode challenge
- Learned how to create a GIF from a screen capture on my laptop using licecap software
- Started building '/log' route and linked to log.html
- Used flexbox to change layout of form fields on 'Add An Activity' page
- Added a 'notes' field to the form on 'Add An Activity' page 
- Added modal window for adding a new activity from the log.html page 

**Thoughts**:
- This [tutorial](https://www.youtube.com/watch?v=XTpLbBJTOM4) was extremely helpful in learning how to use modals with Bootstrap.


**Resources**
1. [GIF Creation Tools](https://webflow.com/blog/5-tools-to-help-you-give-the-gift-of-gifs)
2. [The table HTML element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table) 
3. [Tables - Bootstrap](https://getbootstrap.com/docs/4.0/content/tables/)
4. [Modal - Bootstrap](https://getbootstrap.com/docs/4.0/components/modal/)

----------------------------------------------------------
## January 6, 2021

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Added rest of fields to 'Add an Activity' form on add.html file. Added Bootstrap CSS styling so form is responsive.

**Thoughts**: 
- To run app in development mode, run this in terminal: `export FLASK_ENV=development`
- You can inject HTML in the Jinja-templated form (e.g. to add a class to a field: `{{ form.title(size=100, class_='form-control') }}`)

**Resources**
1. [DatePicker widget with WTForms](https://stackoverflow.com/questions/26057710/datepickerwidget-with-flask-flask-admin-and-wtforms)
2. [Use calendars with DatePicker in Flask WTForms](https://www.youtube.com/watch?v=jAdFZa6KZNE)
3. [WTForms Fields](https://wtforms.readthedocs.io/en/2.3.x/fields/?highlight=html%20attributes)
4. [Passing HTML attributes to Flask form]((https://john.soban.ski/pass-bootstrap-html-attributes-to-flask-wtforms.html))

----------------------------------------------------------
## January 5, 2021

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Installed Flask-WTF to use with creating forms whose input can be validated: `$ pip install flask flask-WTF`
- Installed python-dotenv in order to use .env file to store SECRET_KEY variable: `pip install python-dotenv`
- Started creating form on 'add.html' using FlaskForm 
- Added config files with SECRET_KEY info to enable CSRF protection 

**Thoughts**: 
- WTForms is a Python library used for handling forms. It can be used via the Flask plugin, Flask-WTF
- Routes give instructions on what should be served to the user based on the URL they visit within the app. My routes for this app are defined in my app.py file
- Form classes are Python models that are used to validate the data submitted in forms.
- Jinja templates are used to render the HTML forms that are displayed to the user
- It's common to use CapitazliedWords when naming Python classes (e.g. AddActivity)
- You have to set up a secret key in order to use features like flask-login and CSRF protection. I encountered this error (RuntimeError: A secret key is required to use CSRF.)  when trying to view my form I created using WTForms. 
- It's best to use a separate configuration file for storing the configuration variables that will be applied to the Flask app. 
- Environment variables are stored in the system memory of the device running the app and can be temporarily created via the terminal: (e.g. `$ export SECRET_KEY='o9uaglkiDjro')`. The variable exists as long as you keep the terminal open. To check the variable value, `echo $SECRET_KEY`

**Resources**
1. [Handling Forms in Flask with Flask-WTF](https://hackersandslackers.com/flask-wtforms-forms/)
2. [WTForms Documentation](https://wtforms.readthedocs.io/en/2.3.x/#)
3. [FieldList with SelectField](https://stackoverflow.com/questions/24296834/wtform-fieldlist-with-selectfield-how-do-i-render)
4. [Secret key required to use CSRF](https://stackoverflow.com/questions/47687307/how-do-you-solve-the-error-keyerror-a-secret-key-is-required-to-use-csrf-whe)
5. [Generating SECRET KEY for Flask](https://stackoverflow.com/questions/34902378/where-do-i-get-a-secret-key-for-flask)
6. [Setting up .env file for use with Flask project](https://itnext.io/start-using-env-for-your-flask-project-and-stop-using-environment-variables-for-development-247dc12468be)
7. [Python with Flask Fundamentals](https://www.rithmschool.com/courses/flask-fundamentals/forms-with-wtforms)
8.[Flask Configuration](https://explore-flask.readthedocs.io/en/latest/configuration.html) - helped me set up my 2 config files to provide my SECRET_KEY: one in the root, other in instance folder

----------------------------------------------------------
## January 4, 2020

### Homeschool Journal Site (Flask Web App) [Link to Repo](https://github.com/maelingmurphy/homeschool-journal)
**Today's Progress**:
- Created private repo for project (homeschool-journal)
- Cloned into repo to be able to work on project locally 
- Activate virtual environment: In 'Environments' folder, run `source my_env/bin/activate` in the Terminal. To deactivate the virtual environment, run `deactivate` in the Terminal. 
- Created file main.py in order to run Flask (to run script in Terminal: python3 main.py)
- Created templates folder to store the html files for this project
- Incorporated Bootstrap for navbar structure and styling 
- Added a static folder to house style.css file 
- Started building input form on add.html page for adding an activity 

**Thoughts**: 
- When using `url_for` to link to another template HTML file, it must match the name of the view that renders the specific template file. Essentially, `url_for` links to views. 

**Resources**
1. [SSH Keys for GitHub](https://jdblischak.github.io/2014-09-18-chicago/novice/git/05-sshkeys.html)
2. [Cloning private GitHub repo](https://github.community/t/clone-private-repo/1371/2)
3. [freeCodeCamp - Build a web applicat using Flask](https://www.freecodecamp.org/news/how-to-build-a-web-application-using-flask-and-deploy-it-to-the-cloud-3551c985e492/)
4. [Building a URL to a specific function using url_for()](https://flask.palletsprojects.com/en/0.12.x/quickstart/#url-building)
5. [Flask series](https://dev.to/brunooliveira/flask-series-part-i-4do8)
6. [HTML input type="checkbox"](https://www.w3schools.com/tags/tryit.asp?filename=tryhtml5_input_type_checkbox)
7. [HTML input type="date"](https://www.w3schools.com/tags/att_input_type_date.asp)

----------------------------------------------------------

# 2020

## December 26, 2020
**Today's Progress**:
- :christmas_tree: Completed Day 24 #JavaScriptmas and [published a post linking to all my solutions] (https://dev.to/maelingcodes/a-beginner-s-24-day-journey-with-javascriptmas-83n) for the entire Scrimba #JavaScriptmas code challenge on my dev.to blog. 

**Link to work**: 
https://dev.to/maelingcodes/a-beginner-s-24-day-journey-with-javascriptmas-83n

----------------------------------------------------------

## December 23, 2020
**Today's Progress**:
- :christmas_tree: Completed Day 23 #JavaScriptmas - [Social Media Input](https://twitter.com/maelingcodes/status/1341941621336797184?s=20)

**Resources**
[Text area remaining characters](https://www.mattmorgante.com/technology/textarea-remaining-characters-javascript)

----------------------------------------------------------
## December 22, 2020
**Today's Progress**:
- :christmas_tree: Completed Day 22 #JavaScriptmas - [Extract Matrix Column](https://twitter.com/maelingcodes/status/1341497003625373696?s=20)
- Studied how to submit API requests with Python 

**Thoughts**: 
- I understand much more about how to submit API requests with Python. I was able to successfully consume API data from some of the tracking APIs and quickly realized that I won't be able to get tracking data with them unless I used them to create the the tracking number in the first place as a business sending out packages. At least that's what I'm assuming right now since my requests were successful but the response data was empty when I addeded courier name and tracking number as parameters to my GET request. Time to pivot to another project idea. 

**Resources**
1. [Web Scraping & APIs](https://www.dataquest.io/course/apis-and-scraping/)
2. [Getting Music Data with Last.fm API using Python](https://www.dataquest.io/blog/last-fm-api-python/)


----------------------------------------------------------
## December 21, 2020
**Today's Progress**:
- CS50 Final Project: Started formulating my idea for my CS50 project. I'm thinking of a site that shows you a list of all your packages with their tracking info all on one page. 
- :christmas_tree: Completed Day 21 #JavaScriptmas - [Sum of Two](https://twitter.com/maelingcodes/status/1341190469146034177?s=20)

**Thoughts**: 
- Learned that you can use the 'requests' library in Python for making API calls 
- I spent a lot of time trying to figure out how to extract tracking data using 2 different APIs (Tracking More & AfterShip). I feel like I need a better understanding of how to work with APIs so I will find some resources that take me through the process of working with APIs in Python. 

**Resources**
1. [The Request Context - Flask](https://flask.palletsprojects.com/en/1.1.x/reqcontext/)
2. [Working with Aftership API](https://mixedanalytics.com/knowledge-base/import-aftership-data-to-google-sheets/)
3. [How to use an API with Python](https://rapidapi.com/blog/how-to-use-an-api-with-python/)
4. [Python API Tutorial](https://www.dataquest.io/blog/python-api-tutorial/)


----------------------------------------------------------
## December 20, 2020
**Today's Progress**:
- :christmas_tree: Completed Day 20 #JavaScriptmas - [Domain Type](https://twitter.com/maelingcodes/status/1340725709426352128?s=20) 
- Set up Local IDE in preparation for CS50 Final Project 
    - [uninstall homebrew](https://github.com/homebrew/install#uninstall-homebrew) in Terminal: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall.sh)"`
    - [install homebrew](https://github.com/homebrew/install#uninstall-homebrew) in Terminal: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`
    - intall Git using Homebrew
    - [install Python3 and set up local programming environment on MacOS](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-macos)
    - install flask `python3 -m pip install Flask`
    - [initialize Git repository](https://docs.github.com/en/free-pro-team@latest/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line)
    - run flask app from Terminal export `FLASK_APP=app` `export FLASK_ENV=development` `python3 -m flask run`

**Thoughts**: 
- I learned that 'NANO' and 'VI' are simple text editors you can access from within the Terminal. 
- You can create virtual environments within the Terminal (Create Virtual Environment: `python3.7 -m venv my_env` Activate: `source my_env/bin/activate`  Deactivate: `deactivate`)
- It took a lot of trial and error but I was finally able to set up a local development environment to run Python and Flask! Ran into issues with updating my Git version and getting my system to recognize the update, but I was able to eventually resolve that by making sure that the PATH where the updated version was stored was prioritized over the PATH that the Apple-provided version of Git was stored. 


**Resources**
1. [Git ignore file](https://www.pluralsight.com/guides/how-to-use-gitignore-file)
2. [Creating a simple web app with Python and Flask](https://www.youtube.com/watch?v=cjYxDFsSZio)
3. [Resolving git update issues - still showing old version after update](https://stackoverflow.com/questions/20508136/updated-git-but-still-showing-old-version)
4. [Locating or creating .bashrc](https://askubuntu.com/questions/127056/where-is-bashrc)
5. [Creating new text documents with the Vi editor](https://modulesunraveled.com/command-line-beginners/creating-new-text-documents-vi-editor#:~:text=When%20you're%20in%20%22Command,are%20in%20%22Insert%22%20mode.)
6. [Changing Git version priority](https://modulesunraveled.com/installing-git/updating-git-if-you-have-version-apple-well-official-install)


----------------------------------------------------------
## December 19, 2020
**Today's Progress**:
- :christmas_tree: Completed Day 19 #JavaScriptmas [Alphabet Subsequence](https://twitter.com/maelingcodes/status/1340400995269042176?s=20)


----------------------------------------------------------
## December 18, 2020
**Today's Progress**:
- :christmas_tree: Completed Day 18 #JavaScriptmas [Array Previous Less](https://twitter.com/maelingcodes/status/1340094740944084994?s=20)
- :christmas_tree: Completed Day 15 #Javascriptmas [Carousel](https://twitter.com/maelingcodes/status/1340065065450520576?s=20)



----------------------------------------------------------
## December 17, 2020
**Today's Progress**:
- :christmas_tree: Completed Day 16 #JavaScriptmas - [Insert Dashes](https://twitter.com/maelingcodes/status/1339689243376017415?s=20)
- :christmas_tree: Completed Day 17 #JavaScriptmas - [Different Symbols Naive](https://twitter.com/maelingcodes/status/1340065065450520576?s=20)

**Thoughts**: 
- Received this helpful explanation on the different methods for getting elements from the DOM with JS:
"...The getElementsByClassName() method returns a collection of all elements in the document with the specified class name, as an HTMLCollection object. To use it you need to assign the event listeners such as: next[0].addEventListener. A cleaner way is to use document.querySelector() instead of document.getElementsByClassName(). Since that document.querySelector() returns only one element, which is what you want. The newer querySelector() and querySelectorAll() methods are my go-to methods for DOM access. The were introduced in 2013 in response to the popularity of jQuery at that time." - @galser from Scrimba Discord Chat 

**Resources**
1. [The 'new' keyword in JavaScript](https://stackoverflow.com/questions/1646698/what-is-the-new-keyword-in-javascript)
2. [Template strings](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)


----------------------------------------------------------
## December 16, 2020
**Today's Progress**:
- Finished CS50 Finance Project!!
    - Added the ability for user to add to their cash for the 'personal touch' requirement. 

**Thoughts**: 
Validating the cash input was an interesting task. I ended up using `replace()` for removing potential commas so I could convert the input to a float. I then used regex to search for periods so I could check using `split()` how many numbers were after the decimal place. I created a new route "/add" to run a function that would update the cash in the database and also reflect the changes in the user's overview table on the front-end. 


----------------------------------------------------------
## December 14, 2020
**Today's Progress**:
- :christmas_tree: Completed Day 14 #JavaScriptmas [Finding max absolute difference between any two adjacent elements in an array](https://twitter.com/maelingcodes/status/1338588808317636611?s=20)
- CS50 Finance Project: Worked on "/sell" and "/history" routes:
    - Completed the implementation of sell in such a way that it enables a user to sell shares of a stock (that he or she owns).
        - Require that a user input a stock’s symbol, implemented as a select menu whose name is symbol. Render an apology if the user fails to select a stock or if (somehow, once submitted) the user does not own any shares of that stock.
        - Require that a user input a number of shares, implemented as a text field whose name is shares. Render an apology if the input is not a positive integer or if the user does not own that many shares of the stock.
        - Submit the user’s input via POST to /sell.
    - Complete the implementation of history in such a way that it displays an HTML table summarizing all of a user’s transactions ever, listing row by row each and every buy and every sell.
        - For each row, make clear whether a stock was bought or sold and include the stock’s symbol, the (purchase or sale) price, the number of shares bought or sold, and the date and time at which the transaction occurred.

**Thoughts**: 
- I was having THE hardest time getting the SQL query output that I desired, which involved getting the sum of total shares for each symbol (positive - BUY & negative - SELL values). Someone in the CS50 discord mentioned using `AS` in a query in response to someone else's question and after further research, I found that I could use it to help with my problem! Using 'AS' in a SQL query allows you to create a column alias. Essentially a column alias is a column that exists only for the duration of the query. I used it to create a column alias called 'shares_total' that consisted of the result from `SUM(shares)` across all my transactions grouped by symbol and matched the logged-in user. Here's my SQL query snippet:
```
rows = db.execute("SELECT SUM(shares) AS shares_total, symbol, price, stock_name FROM transactions WHERE users_id = ? GROUP BY symbol", session["user_id"])

```
- I also learned that you have to have some workarounds if you want to refer to a column alias in a WHERE clause. Column aliases can be used in GROUP BY, HAVING or ORDER BY clauses.
- If I want to format my numbers as currency, I can use the `usd` filter in my jinja template (HTML doc). Example: `<td>{{ total_value | usd }}</td>`

**Resources**
1. [MySQL alias for columns](https://www.mysqltutorial.org/mysql-alias/)
2. [Referring to SQL field aliases in the WHERE clause](https://stackoverflow.com/questions/8370114/referring-to-a-column-alias-in-a-where-clause)
3. [How to use select query alias in WHERE clause](https://dba.stackexchange.com/questions/204511/how-to-use-select-queryalias-on-where-clause/204514)
4. [Issues with column aliases](https://dev.mysql.com/doc/refman/8.0/en/problems-with-alias.html)



----------------------------------------------------------
## December 13, 2020
**Today's Progress**:
- :christmas_tree: Completed Day 13 #JavaScriptmas [Removing every kth element from an array](https://twitter.com/maelingcodes/status/1338166720196988933?s=20)
- CS50 Finance Project: Worked on "/index" route:
    - Complete the implementation of index in such a way that it displays an HTML table summarizing, for the user currently logged in, which stocks the user owns, the numbers of shares owned, the CURRENT price of each stock, and the total value of each holding (i.e., shares times CURRENT price)
    - Display the user’s current cash balance along with a grand total (i.e., stocks’ total value plus cash).

**Resources**
1. [filter()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
2. [Preventing SQL injection attacks with Python](https://realpython.com/prevent-python-sql-injection/)
3. [Alter a SQLite Table Using Python](https://pythontic.com/database/sqlite/alter%20table)


----------------------------------------------------------
## December 12, 2020
**Today's Progress**:
- :christmas_tree: Completed Day 12 #JavaScriptmas
- CS50 Finance Project: Worked on "/buy" route:
    - Require that a user input a stock’s symbol, implemented as a text field whose name is symbol.
    - Render an apology if the input is blank or the symbol does not exist (as per the return value of lookup).
    - Require that a user input a number of shares, implemented as a text field whose name is shares. Render an apology if the input is not a positive integer.
    - Submit the user’s input via POST to /buy.
    - Add one or more new tables to finance.db via which to keep track of the purchase. Store enough information so that you know who bought what at what price and when.
    - Render an apology, without completing a purchase, if the user cannot afford the number of shares at the current price.

**Resources**
1. [SQL data types](https://www.w3schools.com/sql/sql_datatypes.asp)
2. [Inserting DATETIME value in SQL database table](https://www.caretit.com/blog/odoo-mobile-dev-3/post/how-insert-datetime-value-in-sqlite-database-36)
3. [SQL UPDATE Statement](https://www.w3schools.com/sql/sql_update.asp)


----------------------------------------------------------
## December 11, 2020
**Today's Progress**:
- :christmas_tree: Completed Day 11 #JavaScriptmas [Avoiding Obstacles](https://twitter.com/maelingcodes/status/1337461459442397185?s=20)
- CS50 Finance Project - worked on "/quote" and "/quoted" routes:
    -  Require that a user input a stock’s symbol, implemented as a text field whose name is symbol.
    - Submit the user’s input via POST to /quote.
    - When a user visits /quote via GET, render one of those templates, inside of which should be an HTML form that submits to /quote via POST.
    - In response to a POST, quote can render that second template, embedding within it one or more values from lookup.

**Resources**
[Getting min or max from an array in JavaScript ](https://medium.com/@vladbezden/how-to-get-min-or-max-of-an-array-in-javascript-1c264ec6e1aa)


----------------------------------------------------------
## December 10, 2020
**Today's Progress**:
- :christmas_tree: Completed Day 10 #JavaScriptmas [Adjacent Elements Products](https://twitter.com/maelingcodes/status/1337113707252428801?s=20)
- Started working on my CS50 Finance Project. Started working on the "/register" route and completed:
    - Created basic html structure for register.html
    - Required that a user input a username, implemented as a text field whose name is username. Render an apology if the user’s input is blank or the username already exists.
    - Required that a user input a password, implemented as a text field whose name is password, and then that same password again, implemented as a text field whose name is confirmation. Render an apology if either input is blank or the passwords do not match.
    - Submitted the user’s input via POST to /register.
    - Used SQL to INSERT the new user into users, storing a hash of the user’s password, not the password itself. Hashed the user’s password with generate_password_hash.

**Resources**
1. [How to store passwords securely using Werkzeug](https://techmonger.github.io/4/secure-passwords-werkzeug/)
2. [Hashing passwords - one way road to security](https://auth0.com/blog/hashing-passwords-one-way-road-to-security/)

----------------------------------------------------------
## December 9, 2020
**Today's Progress**:
- Watched CS50 lectures: 'Databases', 'Finance' in preparation for the CS50 finance project in the web track
- :christmas_tree: Completed Day 9 #JavaScriptmas [Summing Odd Fibonacci Numbers](https://twitter.com/maelingcodes/status/1336895084332199936?s=20)


----------------------------------------------------------
## December 8, 2020
**Today's Progress**:
- :christmas_tree: Completed Day 8 #JavaScriptmas [Roll the Dice](https://twitter.com/maelingcodes/status/1336511941892837377?s=20)

**Thoughts**: 
- I learned that when accessing multiple elements by a common selector with querySelectorAll, you have to loop through all the elements in the list in order to modify its properties (can use a `for...of` loop)
- When using switch cases, remember to `break;` after each case! 

**Resources**
1. [Creating dice faces using CSS grid](https://dev.to/ekeijl/creating-dice-using-css-grid-j4)
2. [Generating random whole numbers in JavaScript](https://stackoverflow.com/questions/1527803/generating-random-whole-numbers-in-javascript-in-a-specific-range)
3. [How to Modify Attributes, Classes and Styles in the DOM](https://www.digitalocean.com/community/tutorials/how-to-modify-attributes-classes-and-styles-in-the-dom)
4. [MDN Web Docs: Document.querySelectorAll](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelectorAll)
5. [Loop Over querySelectorAll Matches](https://css-tricks.com/snippets/javascript/loop-queryselectorall-matches/)
6. [JavaScript switch statement](https://www.w3schools.com/js/js_switch.asp)

----------------------------------------------------------
## December 7, 2020
**Today's Progress**:
- :christmas_tree: Finished Day 7 #JavaScriptmas. [Sum all letters in a given string where vowels = 2 and consonants = 1](https://scrimba.com/learn/adventcalendar/note-at-1-00-coc0f4e26a6d2c62ac9f311e1)
- Watched CS50 video on Flask for dynamically generating web pages 

**Resources**
[Using array reduce() for more than just numbers](https://jrsinclair.com/articles/2019/functional-js-do-more-with-reduce/)

----------------------------------------------------------
## December 6, 2020
**Today's Progress**:
- :christmas_tree: Finished Day 6 #JavaScriptmas. [Sort an array of strings by their length](https://scrimba.com/learn/adventcalendar/note-at-0-54-co8b64e7781ba277f9aa953c3)
- Enabled GitHub pages on my repository to display my [Coding Journey Resources](https://maelingmurphy.github.io/coding-journey-resources-/) site I made for CS50 Homepage.

----------------------------------------------------------
## December 5, 2020
**Today's Progress**: 
- :christmas_tree: Finished Day 5 #JavaScriptmas. [Reverse a given string](https://scrimba.com/learn/adventcalendar/note-at-0-12-co5204d59a743da52d1c040c3)

----------------------------------------------------------
## December 4, 2020
**Today's Progress**:
- :christmas_tree: Finished Day 4 #JavaScriptmas challenge. [Return the century given the year](https://scrimba.com/learn/adventcalendar/note-at-0-05-coce54a1681e7fbb07f775011)

----------------------------------------------------------
## December 3, 2020
**Today's Progress**:
- Finished and submitted my CS50 Homepage project: Coding Journey Resources!!
- :christmas_tree: Finished Day 3 of the #JavaScriptmas Challenge. [Split an array into groups the length of the given size and return them as a two-dimensional array](https://scrimba.com/learn/adventcalendar/note-at-0-12-co5204d59a743da52d1c040c3). 

**Link to work**:
- [My CS50 Homepage GitHub repo: Coding Journey Resources](https://github.com/maelingmurphy/coding-journey-resources-)

**Resources**
1. [Centering text horizontally and vertically within a <div>](https://stackoverflow.com/questions/5703552/how-can-i-center-text-horizontally-and-vertically-inside-a-div-block)
2. [Adding a scroll down anchor button to your website](https://www.solodev.com/blog/web-design/adding-a-scroll-down-anchor-to-your-website.stml)
3. [How to iterate over arrays in JavaScript](https://www.freecodecamp.org/news/javascript-loop-tutorial-how-to-iterate-over-an-array-in-javascript/)

----------------------------------------------------------
## December 2, 2020
**Today's Progress**:
- Continued working on my 'Homepage' project:
    - Learned how to link to an element with an id on a different html page: 
        Example `<a class="dropdown-item" href="languages.html#Python-info">Python</a>`
    - Fixed jQuery interactivity with navbar. I had loaded 2 instances of jquery, which I think was causing the problem. 
- :christmas_tree: Finished Day 2 #JavaScriptmas. [Calculate how long it will take to reach savings threshold given deposit amount and interest rate](https://scrimba.com/learn/adventcalendar/note-at-0-52-cobba432889ba7ce533ae28df).

----------------------------------------------------------
## December 1, 2020
**Today's Progress**: 
- Continued working on my 'Homepage' project:
    - Implemented CSS Grid for my basic content layout on the homepage
    - Used Bootstrap to add a responsive navigation bar at the top of the page
    - Started learning how to implement jQuery to help with showing/hiding multiple divs based on button clicks (onclick)

- :christmas_tree: Completed Day 1 of Scrimba's #JavaScriptmas 24 day challenge. [Calculate the total number of candies to be shared equally amongst a given number of children, given the number of candies](https://scrimba.com/learn/adventcalendar/-javascript-challenge-candies-introduction-cLkqvpcQ)  

**Thoughts**: 
- Need to figure out why jQuery onclick() action for navbar dropdown menu item is working after 2nd click and not 1st.

**Resources**
1. [Using rem in CSS](https://www.sitepoint.com/understanding-and-using-rem-units-in-css/)
2. [HTML5 Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
3. [Grid Critters - Game for learning CSS Grid](https://gridcritters.com/)
4. [Flexbox Zombies - Game for learning CSS Flexbox](https://mastery.games/flexboxzombies/)
5. [CSS Grid Layouts](https://gridbyexample.com/examples/)
6. [How to center in CSS Grid](https://coryrylan.com/blog/how-to-center-in-css-with-css-grid)
7. [Creating a dropdown menu in nav bar](https://www.w3schools.com/howto/howto_css_dropdown_navbar.asp)
8. [Bootstrap Framework](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
9. [Dropdown links with Bootstrap](https://getbootstrap.com/docs/4.5/components/dropdowns/)
10. [Sticky Footer Tips](https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/)
11. [Toggle Hide & Show div elements](https://www.w3schools.com/howto/howto_js_toggle_hide_show.asp)
12. [jQuery slide toggle to show/hide multiple divs](https://wpbeaches.com/use-jquery-slidetoggle-to-show-hide-multiple-rows-or-divs/)
13. [An introduction to jQuery](https://www.digitalocean.com/community/tutorials/an-introduction-to-jquery)
14. [jQuery examples](https://www.freecodecamp.org/news/the-best-jquery-examples/)

----------------------------------------------------------
## November 30, 2020
**Today's Progress**:
- Started building my CS50 Web Track 'Homepage' project, which must include HTML, CSS and JavaScript 
- Created GitHub repo for my project files so I can track changes 

**Link to work**:
[My project GitHub repo](https://github.com/maelingmurphy/coding-journey-resources-.git)

**Resources**
1. [Coolors - Website Color Palette Ideas](https://coolors.co/palettes/trending)
2. [Smooth Scroll Beginner JS Website Project Tutorial](https://www.youtube.com/watch?v=3-2Pj5hxwrw)

----------------------------------------------------------
## November 23, 2020
**Today's Progress**:
- Studied entity relationship diagrams and the use of the 'crow's foot' notation
- Completed 'Movies' problem in CS50 Pset 7

**Resources**
1. [Crow's Foot Notation](https://www.vertabelo.com/blog/crow-s-foot-notation/)
2. [How to JOIN 3 or more tables in SQL](https://learnsql.com/blog/how-to-join-3-tables-or-more-in-sql/)
3. [SQL Keyword Reference](https://www.w3schools.com/sql/sql_groupby.asp)

----------------------------------------------------------
## November 22, 2020
**Today's Progress**:
- Started writing SQL scripts for 'Movies' in CS50 Problem Set 7 

----------------------------------------------------------
## November 16, 2020
**Today's Progress**:
- Started watching CS50 Week 7 SQL Lecture

**Resources**
[2020 CS50 Week 7 SQL Lecture](https://www.youtube.com/watch?v=ZX2T7slE_9I)

----------------------------------------------------------
## November 15, 2020
**Today's Progress**:
- Finished Pset6 DNA program in CS50:
    - Learned how to access and store CSV header names in a separate list with DictReader fieldnames
    - Learned how to create a regex that would match and return to a list consecutive repeats of a substring

**Thoughts**: 
I've made more progress on this DNA program today than I have in all the days since I started working on this problem till now. I know for a fact that taking a break from the problem set and doing the freeCodeCamp 'Scientific Computing with Python Certification' curriculum up to the last Regular Expressions module really helped me to have a better understanding of the basics of the Python language.

**Resources**
1. [Regex101.com: Test regular expressions online](https://regex101.com/)
2. [Non-capturing groups in Python regular expression](https://medium.com/@yeukhon/non-capturing-group-in-pythons-regular-expression-75c4a828a9eb)
3. [How to use a variable inside a regular expression](https://stackoverflow.com/questions/6930982/how-to-use-a-variable-inside-a-regular-expression)
4. [Iterating through DictReader](https://stackoverflow.com/questions/21566437/iterating-through-dictreader)
5. [How to compare dictionaries in Python](https://www.kite.com/python/answers/how-to-compare-dictionaries-in-python)

----------------------------------------------------------
## November 7, 2020
**Today's Progress**:
- Started working on 'Python for Everybody' curriculum via freeCodeCamp

**Resources**
[FREE Python for Everybody Textbook](https://www.py4e.com/book.php)

----------------------------------------------------------
## November 6, 2020
**Today's Progress**:
- Walked through this [tutorial](https://www.youtube.com/watch?v=iy4N5Y3bRvA) to better understand how to use DictReader from the csv module to parse CSV files in Python
- Downloaded Python3 to my Mac OS: https://www.python.org/downloads/
- Downloaded the atom editor: atom.io
- Ran a small python program from my MacOS terminal window
- Started freeCodeCamp's 'Python for Everybody' course to help me better understand the basics of Python programming.  

**Thoughts**: 
- As I'm working through the 'DNA' problem, I realize I need a much better foundational understanding of the csv module and creating dictionaries and accessing their values in Python. Hopefully this will help me in trying to figure out how to pass through the STR values in my program by just reading them in from the fieldnames of the database CSV file, instead of hardcoding them in my program. 

**Resources**
[Python CSV Manipulation | How to read, parse, write CSV file to dictionary | Tutorial](https://www.youtube.com/watch?v=iy4N5Y3bRvA)


----------------------------------------------------------
## November 5, 2020
**Today's Progress**:
- Continued working on 'DNA' in Problem Set 6 of CS50

**Thoughts**: 
You can find the headers ("name" and the STRs) in your DictReader's fieldnames attribute

**Resources**
1. [Regular expression in Python - Python Regex](https://www.guru99.com/python-regular-expressions-complete-tutorial.html#7)
2. [Reading CSV files with csv.DictReader in Python](https://www.youtube.com/watch?v=BBH0asrYSq8)
3. [Example of accessing values in dictionary generated from csv file](https://courses.cs.washington.edu/courses/cse140/13wi/csv-parsing.html)
4. *[Read CSV files in Python with csv.Dictreader](https://www.youtube.com/watch?v=5CEsJkKhS78)


----------------------------------------------------------
## November 4, 2020:
**Today's Progress**:
- Working on 'DNA' in Problem Set 6 of CS50

**Thoughts**: 
- Using Python regex is an option for writing a program to find the longest consecutive substring
- I may be able to use recursion in this program to count the longest successive substrings 

**Resources**
1. [Command line arguments in Python](https://stackabuse.com/command-line-arguments-in-python/)
2. [Reading and writing csv files in Python](https://realpython.com/python-csv/#parsing-csv-files-with-pythons-built-in-csv-library)
3. [Working with files in Python](https://realpython.com/working-with-files-in-python/)
4. [Reading and writing files in Python](https://realpython.com/working-with-files-in-python/)
5. [Python for loops](https://www.w3schools.com/python/python_for_loops.asp)
6. [Check if Python string contains a substring](https://www.afternerd.com/blog/)
python-string-contains/)
7. [Searching substring appearing successively](https://stackoverflow.com/questions/58551480/finding-the-most-amount-of-times-a-substring-appears-successively-in-a-string/58551521#58551521)
8. [Maximum consecutive substring occurrence](https://www.geeksforgeeks.org/python-maximum-consecutive-substring-occurrence/)
9. [Recursively finding longest successive substring occurences](https://stackoverflow.com/questions/64621500/how-to-count-consecutive-occurrences-of-a-substring-in-a-main-string-in-python)
10. [Counting consecutive substring in a string in python 3](https://stackoverflow.com/questions/61131768/how-to-count-consecutive-substring-in-a-string-in-python-3)

----------------------------------------------------------
## November 3, 2020:

**Today's Progress**:
- Completed 'Readability' in Problem Set 6 of CS50

----------------------------------------------------------
## October 18, 2020
**Today's Progress**:
- Started Problem Set 6 of Week 6 CS50: Completed 'Mario (Less)'. Completed 'Cash'


----------------------------------------------------------
## September 28, 2020
**Today's Progress**:
- Continued watching CS50 Week 6 'Shorts' on Python

----------------------------------------------------------
## September 27, 2020
**Today's Progress**:
- Continued watching CS50 Week 6 'Shorts' on Python

----------------------------------------------------------
## September 21, 2020
**Today's Progress**:
- Continued with CS50 week 6 lecture on Python
- Started watching CS50 Week 6 'Shorts' on Python

----------------------------------------------------------

## July 20, 2020
**Today's Progress**:
- Continued with CS50 week 6 lecture on Python

----------------------------------------------------------
## July 1, 2020
**Today's Progress**:
- Continued with CS50 week 6 lecture on Python

----------------------------------------------------------
## June 30, 2020
**Today's Progress**:
- Started Week 6 of CS50, focusing on Python

----------------------------------------------------------

## June 28, 2020
**Today's Progress**:
- Sucessfully submitted my 'speller' program to conclude week 5 of CS50

**Thoughts**: 
This problem set really helped me to better understand the use of pointers and how to construct hash tables. I can more clearly see how hash tables can improve insertion and search time when compared to arrays or linked lists on their own. 

**Resources**
- [CS50 Pset 5 'Speller'](https://cs50.harvard.edu/x/2020/psets/5/speller/)

----------------------------------------------------------
## June 27, 2020
**Today's Progress**:
- Completed the hash function portion of the 'Speller' challenge in pset 5 of CS50

**Resources**
1. [Hash function algorithms](https://www.partow.net/programming/hashfunctions/#AvailableHashFunctions)
2. More [hash functions](http://www.cse.yorku.ca/~oz/hash.html)

----------------------------------------------------------
## April 10, 2020
**Today's Progress**:
- Finished 'recover' to complete pset 4 in CS50
- Successfully submitted my 'recover' program to conclude week 4 of CS50

**Thoughts**:
This problem set really helped me to understand how to create new files and open/close, read and write to them in C. Understanding what `fread()` returns a function helped me to write conditions that allowed me to read the entire memory card file and start retrieving JPEG data based upon the unique header info JPEGs have in their first 4 bytes.   

**Resources**
[Reading data from a file using fread()](https://www.educative.io/edpresso/c-reading-data-from-a-file-using-fread)

----------------------------------------------------------
## April 8, 2020
**Today's Progress**:
- Started working on the 'recover' problem in pset 4 in CS50

**Resources**
1. [File Input/Output (I/O) in C Programming](https://beginnersbook.com/2014/01/c-file-io/)
2. [Using typedef in C](https://www.tutorialspoint.com/cprogramming/c_typedef.htm)
3. [Reading from files in C](https://www.udemy.com/blog/fread-c/)

----------------------------------------------------------
## April 2, 2020
**Today's Progress**:
- Finished coding the blur filter for pset 4 in CS50
- Successfully submited my filter program for pset 4 in CS50

**Thoughts**: I was stuck on how to implement the logic for some `if` statements in one of my `for` loops and was surprised at how much things began to make more sense once I started explaining my thought process out loud! I really do need a rubber duck for my desk lol! 

----------------------------------------------------------
## March 31, 2020
**Today's Progress**:
- Continued working on blur filter for pset 4 in CS50

**Thoughts**: Drawing a 3x3 box and identifying which pixels would need to be counted for the average for each pixel in the box definitely helped me start to visualize how to approach this problem. 

----------------------------------------------------------
## March 30, 2020
**Today's Progress**:
- Successfully programmed grayscale filter for problem set 4 in CS50
- Successfully programmed sepia filter for pset 4 in CS50
- Successfully programmed reflect filter for pset 4 in CS50
- Started working on blur filter for pset 4 in CS50

**Thoughts**: 
I love to use photo editing tools so it was really exciting to start to understand how algorithms are used to apply various photo effects and to code my own photo filters!

**Resources**
[Various grayscale algorithms](https://tannerhelland.com/2011/10/01/grayscale-image-algorithm-vb6.html)

----------------------------------------------------------
## March 25, 2020
**Today's Progress**:
- Reviewed the objective for the filter challenge in problem set 4 in CS50


----------------------------------------------------------
## March 24, 2020
**Today's Progress**:
- Studied file pointers: `fopen()`, `fclose()`, `fgetc()`, `fputc()`, `fread()`, `fwrite()` in C 


----------------------------------------------------------
## March 21, 2020
**Today's Progress**:
- Studied call stacks in C


----------------------------------------------------------
## March 17, 2020
**Today's Progress**:
- Studied dynamic memory allocation in C


----------------------------------------------------------
## March 16, 2020
**Today's Progress**:
- Studied pointers in C

----------------------------------------------------------
## March 12, 2020
**Today's Progress**:
- Started reviewing CS50 Week 4 Shorts: Hexadecimal numbers 

**Thoughts**: 
Memory addresses are expressed in hexadecimal in C and a '0x' prefix is used to denote hexadecimal numbers so they are distinguishable from other base number systems. 


----------------------------------------------------------
## March 5, 2020
**Today's Progress**:
- Learned about pointers and the scanf() function in C on Sololearn

----------------------------------------------------------
## March 4, 2020
**Today's Progress**:
- Reviewed the pseudocode, big-O and big-omega for various sorting and search algorithms:
    - Sort - selection, bubble, insertion, merge
    - Search - linear, binary 

**Resources**
1. [Linear Search](https://www.youtube.com/watch?v=TwsgCHYmbbA)
2. [Binary Search](https://www.youtube.com/watch?v=T98PIp4omUA)
3. [Bubble Sort](https://www.youtube.com/watch?v=RT-hUXUWQ2I)
4. [Selection Sort](https://www.youtube.com/watch?v=3hH8kTHFw2A)
5. [Insertion Sort](https://www.youtube.com/watch?v=O0VbBkUvriI)
6. [Recursion](https://www.youtube.com/watch?v=mz6tAJMVmfM)
7. [Merge Sort](https://www.youtube.com/watch?v=Ns7tGNbtvV4)
8. [Algorithms Summary](https://www.youtube.com/watch?v=ktWL3nN38ZA)

----------------------------------------------------------
## March 2, 2020
**Today's Progress**:
- Finished coding my program for the 'runoff' challenge in pset3 and submitted it successfully! 

**Thoughts**: I realized today that the reason I was having problems with some of my functions were because of not understanding how return statements should be used within functions. 

**Resources**
- [Return statements in C](https://www.geeksforgeeks.org/return-statement-in-c-cpp-with-examples/)

----------------------------------------------------------
## March 1, 2020 
**Today's Progress**:
- Continuing work on 'runoff' problem in pset 3 CS50


----------------------------------------------------------
## February 26, 2020
**Today's Progress**:
- More work with nested for loops while coding the next function needed for my 'runoff' program for pset 3 in CS50
- Learned how to use break statements to terminate the inner loop in order to force the execution of the next iteration of the outer loop

**Resources**
- [Nested loops] (http://eecs.oregonstate.edu/ecampus-video/CS161/template/chapter_5/nested.html)

----------------------------------------------------------
## February 25, 2020
**Today's Progress**:
- Continued work on the 'runoff' problem in pset3 for CS50. Completed the voter() function which updates the voters preference array with each voter's candidate preference ranking. 

**Thoughts**: Nested for loops have started to make more sense to me as I used them to create a function to update my voter preferences array.

**Resources**
1. [Multidimensional arrays in C](https://www.tutorialspoint.com/cprogramming/c_multi_dimensional_arrays.htm)
2. [2D arrays in C] (https://beginnersbook.com/2014/01/2d-arrays-in-c-example/)

----------------------------------------------------------
## February 10, 2020 
**Today's Progress**:
- Started CS50 Week 3 Lecture on Algorithms

----------------------------------------------------------
## February 7, 2020
**Today's Progress**:
- Completed the 'Caesar' problem in pset2 CS50 and successfully submitted the entire problem set 2! 

----------------------------------------------------------
## February 6, 2020
**Today's Progress**:
- Reviewed C concepts in Sololearn

----------------------------------------------------------

## February 5, 2020
**Today's Progress**:
- Worked on the 'Caesar' problem in pset2 CS50.

----------------------------------------------------------
## February 4, 2020
**Today's Progress**:
- Read about blockchain technology and some of the programming languages used in development.

----------------------------------------------------------
## February 3, 2020
**Today's Progress**:
- Did some reading about blockchain technology 

----------------------------------------------------------
## February 2, 2020
**Today's Progress**:
- Started working on the 'Caesar' problem in problem set 2 of CS50. This problem involves writing a program that converts plaintext to ciphertext, using a user-defined key based on non-negative integers. 

**Resources**
1. [Command Line Arguments in C](https://www.geeksforgeeks.org/command-line-arguments-in-c-cpp/)
2. [<ctype.h> functions useful for testing and mapping characters](https://www.tutorialspoint.com/c_standard_library/ctype_h.htm)
----------------------------------------------------------
## February 1, 2020
**Today's Progress**:
- Completed and submitted the 'readability' program for problem set 2 in CS50

**Thoughts**:
In solving this coding challenge, I learned the importance of making sure I was working with the right data types so my Coleman-Liau equation yielded accurate values. For example, using `float` instead of `int`, gave me more accuracy in my values to be used in the final equation since dividing two `int`s could lead to truncation of values, ultimately leading to a final incorrectly computed value. 

**Resources**
- [CS50 Problem Set 2](https://cs50.harvard.edu/x/2020/psets/2/)
----------------------------------------------------------
## January 31, 2020
**Today's Progress**:
1. Made major progress in the 'readability' problem in Problem Set 2 of CS50. Learned how to build functions in C that count the words, letters and sentences of a user's string input. 

**Resources**
1. [Creating Functions in C](https://www.youtube.com/watch?v=DbR-0GfnQOs)
2. [Calling Functions in C](https://www.youtube.com/watch?v=_0Lp3utEEcs) 
----------------------------------------------------------
## January 30, 2020
**Thoughts**: I didn't do any coding today but I did think about whether I should change my learning approach and only focus on one curriculum and only move on to the next once I complete it. I think I will just focus on CS50 moving forward since C is a brand new language for me. 

----------------------------------------------------------
## January 29, 2020
**Today's Progress**: 
- Worked on problem set 2 in CS50. Worked on creating a function that counts the number of letters in a string of text that the user inputs.

**Resources**
- [CS50 Problem Set 2](https://cs50.harvard.edu/x/2020/psets/2/)
----------------------------------------------------------
## January 28, 2020
**Today's Progress**:
- Reviewed nested if & switch statements and logical operators in C  on the Sololearn app.

**Resources**
- [Sololearn C Tutorial](https://www.sololearn.com/Course/C/)
----------------------------------------------------------
## January 27, 2020
**Today's Progress**:
- Started building my 'readability' program in C for #CS50 problem set 2. 

**Thoughts**:
It's an interesting problem incorporating the Coleman-Liau formula to assign a grade level to an input of sample text.

**Resources**
- [CS50 Problem Set 2](https://cs50.harvard.edu/x/2020/psets/2/)

----------------------------------------------------------
## January 26, 2020
**Today's Progress**:
- Reviewed conditionals & loops in C #sololearn

**Resources**
- [Sololearn C Tutorial](https://www.sololearn.com/Course/C/)
----------------------------------------------------------
## January 25, 2020
**Today's Progress**:
- Finished the 'Basic Concepts' section in the C tutorial on the Sololearn app. 

**Resources**
- [Sololearn C Tutorial](https://www.sololearn.com/Course/C/)
----------------------------------------------------------
## January 24, 2020
**Today's Progress**: 
1. Listened to some of the 'Shorts' videos for Week 2 of CS50, focusing on writing functions in C
2. Worked on my Tribute page project for freeCodeCamp. 

**Thoughts**: I have some video embeds on my page so I'm trying to understand and implement these CSS tricks for making iframes responsive 

**Link to work**:
[My 'Build a Tribute Page' Project Github Repo](https://github.com/maelingmurphy/Katherine-Dunham-FCC-Tribute-Page)

**Resources**
1. [Styling a navigation bar using CSS via w3schools.com]https://www.w3schools.com/css/css_navbar.asp
2. [Responsive iframes via CSS Tricks](https://css-tricks.com/responsive-iframes/)
3. (https://www.w3docs.com/snippets/css/how-to-create-a-responsive-iframe-with-css.html)
4. [YT Tutorial](https://www.youtube.com/watch?v=QG7JQkeaJy4)
----------------------------------------------------------
## January 23, 2020
**Today's Progress**:
- Finished watching lecture 2 of #cs50 about arrays in C.

**Thoughts**:
Also learned about type casting, where you can convert one data type into another, e.g. converting an int to a float.

**Resources**
- [CS50 Lecture 2 - Arrays](https://cs50.harvard.edu/x/2020/weeks/2/)
----------------------------------------------------------
## January 22, 2020
**Today's Progress**:
1. Started watching Lecture 2 in the CS50 course - Arrays
2. Started reading 'Computational Fairy Tales' by Jeremy Kubica t

**Thoughts**: I'm really enjoying this book as it's helping to integrate programming concepts in an interesting and entertaining way!

**Resources**
1. [CS50 Lecture 2 - Arrays](https://cs50.harvard.edu/x/2020/weeks/2/)
2. ['Computational Fairy Tales' by Jeremy Kubica](https://amzn.to/319wNIk)- Amazon affiliate link 

----------------------------------------------------------
## January 21, 2020
**Today's Progress**: 
- Finished & submitted Problem Set 1 for CS50!

**Thoughts**: 
I had been stumped on how to solve the Mario problem for a few days. After reviewing the video shorts for Lecture 1 and receiving a one sentence tip on being careful where to insert the `printf("\n")` for printing a new line, it all started to click today! In fact, I surprised myself and was able to solve the second problem (calculating the fewest number of coins needed to give someone change using quarters, dimes, nickels and pennies) in problem set 1 in less than 30 minutes! 

**Resources**
1. [CS50 Week 1 - Problem Set 1](https://cs50.harvard.edu/x/2020/psets/1/)
2. [Mario Problem Set 1 Walkthrough]https://www.youtube.com/watch?v=EGWRG5e1O2s&feature=youtu.be
----------------------------------------------------------
## January 20, 2020
**Today's Progress**:
- Continued working on the 'Mario - less comfortable' problem in CS50 Problem Set 1

**Thoughts**:
It can be frustrating to break down the steps and know what you want the computer to do but not know how to frame it in the right language. I'll get there though!

**Resources**
- [CS50 Week 1 - Problem Set 1](https://cs50.harvard.edu/x/2020/psets/1/)
----------------------------------------------------------
## January 19, 2020
**Today's Progress**:
1. Started working through problem set 1 of CS50 - Trying to output a pyramid of right-aligned hashes of a height determined by user input. 

**Thoughts**:
I can output a square of hashes of a certain integer input, but how to get the hashes to decrease by row...that is the question. Going back to my pseudocode!

**Resources**
- [CS50 Week 1 - Problem Set 1](https://cs50.harvard.edu/x/2020/psets/1/)
----------------------------------------------------------
## January 18, 2020
**Today's Progress**:
1. Studied more basic concepts of C on Sololearn today - Data types and input/outputs.

**Thoughts**: 
I want to review up to conditionals, loops and functions so I can start on week 1 #cs50 homework!

**Resources**
- [Sololearn C Tutorial](https://www.sololearn.com/Course/C/)
----------------------------------------------------------
## January 17, 2020
**Today's Progress**:
1. Reviewed intro to C concepts using Sololearn
2. Did a bit of HTML form coding to modify a 
Mailchimp embedded form on client's site to set up an automation sequence based on which page of the site a client subscribes from.

**Resources**
- [Sololearn C Tutorial](https://www.sololearn.com/Course/C/)

----------------------------------------------------------
## January 16, 2020
**Today's Progress**:
##### Continued freeCodeCamp's 'Responsive Web Design Projects' - 'Build a Tribute Page' project
- Worked on site's layout using CSS grid and flexbox

**Thoughts**: I found some helpful resources today that explained how I could use CSS grid and flexbox together to create responsive layouts. 

**Link to work**:
[My 'Build a Tribute Page' Project Github Repo](https://github.com/maelingmurphy/Katherine-Dunham-FCC-Tribute-Page)

**Resources**
1. [freeCodeCamp 'Build a Tribute Page' project guidelines](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-tribute-page) 
2. [Realizing common layouts using CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Realizing_common_layouts_using_CSS_Grid_Layout) - via MDN web docs
3. [CSS grid website layout examples](https://www.quackit.com/css/grid/examples/css_grid_website_layout_examples.cfm) - via Quackit

----------------------------------------------------------
## January 15, 2020
**Today's Progress**:
##### Continued freeCodeCamp's 'Responsive Web Design Projects' - 'Build a Tribute Page' project
- Worked on my site layout using CSS Grid

**Thoughts**: I'm looking into nested grids and how to use flex within a CSS grid layout. I feel like I'm working with some sort of weird jigsaw puzzle right now lol.

**Link to work**:
[My 'Build a Tribute Page' Project Github Repo](https://github.com/maelingmurphy/Katherine-Dunham-FCC-Tribute-Page)

**Resources**
1. [freeCodeCamp 'Build a Tribute Page' project guidelines](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-tribute-page) 
2. [Creating nested CSS grids](https://www.quackit.com/css/grid/tutorial/create_a_nested_grid.cfm)
3. [Realizing common layouts using CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Realizing_common_layouts_using_CSS_Grid_Layout)
4. [Sample CSS Grid Layouts](https://www.quackit.com/html/html_editors/scratchpad/preview.cfm?example=/html/templates/grid/_inc/inc_css_grid_layout_template_7.cfm)

----------------------------------------------------------
## January 14, 2020
**Today's Progress**: 
##### Continued freeCodeCamp's 'Responsive Web Design Projects' - 'Build a Tribute Page' project
1. Outlined the content for my tribute page with a rough wireframe
2. Started writing semantic HTML for the site structure and content

**Thoughts**: I challenged myself to use VS Code and Git for version control while working on this site. I'm actually starting to feel a flow when updating my files using Git in the terminal! 

**Link to work**:
[My 'Build a Tribute Page' Project Github Repo](https://github.com/maelingmurphy/Katherine-Dunham-FCC-Tribute-Page)

**Resources**
1. [freeCodeCamp 'Build a Tribute Page' project guidelines](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-tribute-page) 

----------------------------------------------------------
## January 13, 2020
**Today's Progress**: 
##### Continued Harvard's CS50 Introduction to Computer Science course on EdX
- Watched Week 1 lecture of #CS50 - 'C' and started learning how to program in C!
##### Started freeCodeCamp's 'Responsive Web Design Projects' - 'Build a Tribute Page' project 
- Started planning my topic for the 'Build a Tribute Page' project

**Thoughts**: The CS50's instructor's  description of the info feeling like drinking from a firehose...accurate 😆

**Resources**
1. [CS50 Week 1](https://cs50.harvard.edu/x/2020/weeks/1/)
2. [freeCodeCamp 'Build a Tribute Page' project guidelines](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-tribute-page) 
----------------------------------------------------------

## January 12, 2020

**Today's Progress**: 
##### Completed 'CSS Grid' within freeCodeCamp's 'Responsive Web Design Certification'

**Thoughts**: It looks like there is a lot of flexibility when working with CSS Grid. There are so many different properties and ways to tweak the values for a very specific and responsive layout it seems. 

**Resources**
1. [CSS Grid](https://www.freecodecamp.org/learn/responsive-web-design/css-grid/) via freeCodeCamp
2. [Additional info on CSS Grids](https://alligator.io/css/css-grid-layout-fr-unit/) via alligator.io
3. This article includes a [breakdown on how `auto` and `fr` work when used together](https://www.rawkblog.com/2018/03/css-grid-understanding-grid-gap-and-fr-vs-auto-units/) to set values using CSS Grid. `fr` takes priority over `auto` when they are used together. 
----------------------------------------------------------

## January 11, 2020
**Today's Progress**: 
- Read through an interesting article series titled 'How to Become A Developer' on dev.to. 

**Thoughts**: I had a full day today and didn't get to code, but I am excited about the info I gathered from the articles I read today. The 4th article in the series has some book recommendations covering programming culture that I look forward to checking out. 

**Resources**
1. ['How to Become a Developer'](https://dev.to/codemouse92/how-to-become-a-developer-part-1-coding-skills-5fen) series on dev.to by Jason C. McDonald 

----------------------------------------------------------
## January 10, 2020 
**Today's Progress**: 
##### Completed 'CSS Flexbox' within freeCodeCamp's 'Responsive Web Design Certification'

##### Started the 'CSS Grids' track within freeCodeCamp's 'Responsive Web Design Certification'

**Resources**
1. [CSS Flexbox](https://www.freecodecamp.org/learn/responsive-web-design/css-flexbox/) via freeCodecamp
2. [CSS Grid](https://www.freecodecamp.org/learn/responsive-web-design/css-grid/) via freeCodeCamp 
----------------------------------------------------------
## January 9, 2020 
**Today's Progress**: 
##### Completed 'Responsive Web Design Principles' within freeCodeCamp's 'Responsive Web Design Certification'
##### Started 'The Front End' track within The Odin Project's 'Full Stack Ruby on Rails' curriculum
- Reviewed HTML & CSS basics by building a local webpage 
##### Started 'CSS Flexbox' track within freeCodeCamp's 'Responsive Web Design Certification'
- Created a codepen so I could get better grasp the CSS Flexbox concepts 
**Thoughts**: Flexbox seems to work so much better than using the `float` property that I learned about briefly several years ago. 

**Link to work**:
1. [CSS Flexbox Examples - Codepen](https://codepen.io/msgrad08/pen/OJPvarJ)

**Resources**
1. [freeCodeCamp CSS Flexbox](https://www.freecodecamp.org/learn/responsive-web-design/css-flexbox/)
2. [HTML & CSS Basics - htmldog.com](https://www.htmldog.com/guides/)
3. [Front End Track - The Odin Project](https://www.theodinproject.com/courses/web-development-101/lessons/introduction-to-the-front-end)

----------------------------------------------------------
## January 8, 2020
**Today's Progress**:

##### Completed the 'Applied Visual Design' track within freeCodeCamp's 'Responsive Web Design Certification'

##### Completed the 'Applied Accessibility' track within freeCodeCamp's 'Responsive Web Design Certification'

**Thoughts**: I really enjoyed learning how to tailor CSS animations using `@keyframes` and other properties like `animation-timing-function`, `cubic-bezier`, `animation-duration` and `animation-iteration-count` . I was a little familiar with some of the animation concepts from my days of tinkering with animations in After Effects, so it was cool to see it translate over to CSS! In the Applied Accessibility section, it was great to learn about how to make more mindful html structuring and overall design decisions to improve web accessibility for all who use it.

**Resources**
1. freeCodeCamp [CSS animations](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/learn-how-bezier-curves-work), [Applied Accessibility](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/)


----------------------------------------------------------
## January 7, 2020 
**Today's Progress**:
- Created a new repo (this one!) to log my #100daysofcode progress & resource links
- Created a new repo to document [my self-directed learning path](https://github.com/maelingmurphy/My-Learning-Path)
- Started learning the markdown for the GitHub platform

##### Continued Harvard's CS50 Introduction to Computer Science course on EdX
- Completed and submitted my Scratch project for Problem Set 0 

**Thoughts**: I am seriously excited about learning how to use Git and GitHub! I actually started my GitHub account several years ago but never really took too much time to work with it. I can't even believe that I'm creating my own log files on here now. Ah, the simple things lol! I really enjoyed using Scratch to start to help my brain wrap around concepts like events, conditions and variables. This project was especially fun because my 4yr old helped me with it by choosing the sprites, background and he even recorded a sound effect for the ball hitting the bat!


**Link to work**:
1. [Moving Baseball Game - A Scratch Project](https://scratch.mit.edu/projects/357107366)

**Resources**
1. [GitHub Guide - Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
2. [CS50 - Intro to Computer Science](https://www.edx.org/course/cs50s-introduction-to-computer-science)
----------------------------------------------------------
## January 6, 2020 
**Today's Progress**:
##### Continued on the 'Applied Visual Design' track within freeCodeCamp's 'Responsive Web Design Certification'
- Learned about how to use CSS pseudo-elements to create shapes
- Learned how to use `@keyframes` to create CSS animations
- Built and shared my first codepen! 

**Thoughts**: I had recently been admiring some web design work where I noticed they were able to place these graphical elements around images using just code. When I inspected the code, I saw these `::before` and `::after` elements not knowing yet that they were pseudo-elements. This tutorial came right on time so I could better understand how pseudo-elements work! 

**Link to work**:
1. [CSS Color-Changing Heart - Codepen](https://codepen.io/msgrad08/pen/MWYrzNX) 

**Resources**
1. freeCodeCamp 'Applied Visual Design' - [CSS shapes & pseudoelements](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/create-a-more-complex-shape-using-css-and-html), [CSS Animations](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/learn-how-the-css-keyframes-and-animation-properties-work)

----------------------------------------------------------
## January 5, 2020
**Today's Progress**:
##### Continued on the 'Web Development 101' track within The Odin Project's 'Full Stack Ruby on Rails' curriculum 
- Deployed test rails app to Heroku 
- Practiced Git commands

##### Continued on the 'Applied Visual Design' track within freeCodeCamp's 'Responsive Web Design Certification'
- Learned CSS transform properties 
- Styled a Mailchimp embedded form using CSS

**Thoughts**: I had never used Git before this challenge so it was great to go through resources that really explained why distributed version control systems like Git are necessary. I have a better working knowledge of a file's potential journey in the Git process: 1) Working Copy 2) Staging Area & 3) Local Repository and the git commands used for these different stages.  

**Link to work**:
1. [Test Rails App](https://quiet-brushlands-51994.herokuapp.com/)

**Resources**
1. [The Odin Project 'Web Development 101' - PROJECT: YOUR FIRST RAILS APPLICATION](https://www.theodinproject.com/courses/web-development-101/lessons/your-first-rails-application)
2. [The Odin Project 'Web Development 101' - GIT BASICS](https://www.theodinproject.com/courses/web-development-101/lessons/git-basics)
----------------------------------------------------------

## January 4, 2020 
**Today's Progress**:
##### Started Harvard's CS50 Introduction to Computer Science course on EdX
- Watched Week 0's lecture
- Started building my project in Scratch for Problem Set 0

**Thoughts**: It was fascinating to learn how computers can trasnmit so many different forms of electronic media using just 0s and 1s! I now know how to represent integers using just 0s and 1s. I also loved getting started on my project using Scratch, a block-based programming language made by MIT. My 4yr old saw how much fun I was having on Scratch that he came over and asked if he could help me with the project! I also learned that they have Scratch Jr. for kids, so I can't wait to download that for him! 

**Resources**
1. [CS50 Course on EdX](https://www.edx.org/course/cs50s-introduction-to-computer-science)
2. [Scratch](https://scratch.mit.edu/)
3. [Scratch Jr.](https://www.scratchjr.org/)

----------------------------------------------------------
## January 3, 2020 
**Today's Progress**:
##### Continued on the 'Web Development 101' track within The Odin Project's 'Full Stack Ruby on Rails' curriculum 
- Installed Ruby on Rails & pushed first test rails app to my Github repo using Git! 

##### Continued on the 'Applied Visual Design' track within freeCodeCamp's 'Responsive Web Design Certification'
- Worked on adjusting elements'colors using hsl( ) w/ CSS. HSL= Hue, Saturation, Lightness 

**Thoughts**: Installing Ruby on Rails today gave me more practice in reading error messages and installing other programs via the CLI that it needed to run successfully. 

**Link to work**:
1. [My repo for my test rails app](https://github.com/maelingmurphy/my_first_rails_app)

**Resources**
1. [The Odin Project 'Web Development 101' - PROJECT: YOUR FIRST RAILS APPLICATION](https://www.theodinproject.com/courses/web-development-101/lessons/your-first-rails-application)
2. [freeCodeCamp 'Applied Visual Design' - hsl ( )](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/adjust-the-hue-of-a-color)

----------------------------------------------------------
## January 2, 2020 
**Today's Progress**: 
##### Continued on the 'Web Development 101' track within The Odin Project's 'Full Stack Ruby on Rails' curriculum 
- Used the command line to install Ruby, Git
- Used the command line to connect to Github account 

##### Continued on the 'Applied Visual Design' track within freeCodeCamp's 'Responsive Web Design Certification'
- Worked on CSS positioning and floats 

**Thoughts**: I ran into some difficulties installing Ruby during the installation of Xcode. Apparently, I had a previous version of Xcode on my system that wasn't fully removed after I had dragged the app to the trash (noob move). Thankfully, I was able to find some advice on StackOverflow on how to fully remove Xcode from my system so I could proceed with a fresh installation of Xcode. It was a little frustrating, but gave me some practice on reading error messages and navigating my folders using the command line! 

**Resources**
1. [freeCodeCamp 'Applied Visual Design' - CSS Positioning](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/change-an-elements-relative-position)
2. [freeCodeCamp 'Applied Visual Design' - CSS Floats](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/push-elements-left-or-right-with-the-float-property)
3. [The Odin Project 'Web Development 101' - Installing Ruby](https://www.theodinproject.com/courses/web-development-101/lessons/installing-ruby)
4. [The Odin Project 'Web Development 101' - Setting Up Git](https://www.theodinproject.com/courses/web-development-101/lessons/setting-up-git)
5. [StackOverflow post for uninstalling Xcode](https://stackoverflow.com/questions/31011062/how-to-completely-uninstall-xcode-and-clear-all-settings)
6. [Helpful post on Xcode installation](https://wilsonmar.github.io/xcode/#XCodeInstall)

----------------------------------------------------------
## January 1, 2020
- Decided to not enroll in a coding bootcamp and instead pursue a self-directed path to becoming a software engineer

----------------------------------------------------------
# 2019
----------------------------------------------------------

## December 31, 2019 
- Accepted to the Flatiron Part-Time Online Software Engineering program (chose not to do the program)
- Completed the 21 day Career Karma Challenge 

----------------------------------------------------------
## December 30, 2019 
- Accepted to Kenzie Academy Software Engineering program (chose not to do the program)

----------------------------------------------------------

## December 23, 2019 
- Applied to Kenzie Academy Software Engineering program 

----------------------------------------------------------

## December 19, 2019 
- Applied to Flatiron ‘Online Software Engineering’ program

----------------------------------------------------------

## December 17, 2019
- Started [The Odin Project Full Stack Ruby on Rails Track](https://www.theodinproject.com/tracks/1) 


----------------------------------------------------------

## December 15, 2019 
- Published my [first post about my coding journey](https://www.maelingmurphy.com/2019/12/15/my-coding-journey-a-progresslog/) on my blog!


----------------------------------------------------------

## December 13, 2019  
- Started the [Responsive Web Design Certification on freeCodeCamp](https://www.freecodecamp.org/learn) 
- Started [Flatiron's free coding bootcamp prep course on Learn.co](https://flatironschool.com/free-courses/coding-bootcamp-prep#overview)

----------------------------------------------------------

## December 11, 2019  
- Started the [Career Karma #21dayCkChallenge](https://careerkarma.com/21-day-ck-challenge/?p=7)

----------------------------------------------------------
