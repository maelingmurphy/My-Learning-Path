# Learning Log


# Format

##
**Today's Progress**:
**Thoughts**: 
**Link to work**:
**Resources**

----------------------------------------------------------
# 2020

## December 26, 2020
**Today's Progress**:
- Completed Day 24 #JavaScriptmas and [published a post linking to all my solutions] (https://dev.to/maelingcodes/a-beginner-s-24-day-journey-with-javascriptmas-83n) for the entire Scrimba #JavaScriptmas code challenge on my dev.to blog. 

**Link to work**: 
https://dev.to/maelingcodes/a-beginner-s-24-day-journey-with-javascriptmas-83n

----------------------------------------------------------

## December 23, 2020
**Today's Progress**:
- Completed Day 23 #JavaScriptmas - [Social Media Input](https://twitter.com/maelingcodes/status/1341941621336797184?s=20)

**Resources**
[Text area remaining characters](https://www.mattmorgante.com/technology/textarea-remaining-characters-javascript)

----------------------------------------------------------
## December 22, 2020
**Today's Progress**:
- Completed Day 22 #JavaScriptmas - [Extract Matrix Column](https://twitter.com/maelingcodes/status/1341497003625373696?s=20)
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
- Completed Day 21 #JavaScriptmas - [Sum of Two](https://twitter.com/maelingcodes/status/1341190469146034177?s=20)

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
- Completed Day 20 #JavaScriptmas - [Domain Type](https://twitter.com/maelingcodes/status/1340725709426352128?s=20) 
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
- Completed Day 19 #JavaScriptmas [Alphabet Subsequence](https://twitter.com/maelingcodes/status/1340400995269042176?s=20)


----------------------------------------------------------
## December 18, 2020
**Today's Progress**:
- Completed Day 18 #JavaScriptmas [Array Previous Less](https://twitter.com/maelingcodes/status/1340094740944084994?s=20)
- Completed Day 15 #Javascriptmas [Carousel](https://twitter.com/maelingcodes/status/1340065065450520576?s=20)



----------------------------------------------------------
## December 17, 2020
**Today's Progress**:
- Completed Day 16 #JavaScriptmas - [Insert Dashes](https://twitter.com/maelingcodes/status/1339689243376017415?s=20)
- Completed Day 17 #JavaScriptmas - [Different Symbols Naive](https://twitter.com/maelingcodes/status/1340065065450520576?s=20)

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
- Completed Day 14 #JavaScriptmas [Finding max absolute difference between any two adjacent elements in an array](https://twitter.com/maelingcodes/status/1338588808317636611?s=20)
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
- Completed Day 13 #JavaScriptmas [Removing every kth element from an array](https://twitter.com/maelingcodes/status/1338166720196988933?s=20)
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
- Completed Day 12 #JavaScriptmas
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
