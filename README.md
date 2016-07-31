# JavaScript lab 1

In this lab, you'll write some more JavaScript.

Start by downloading the code, either by cloning or by opening
up a zip file that you've emailed to yourself:

```
cd ~/Desktop
git clone https://github.com/meet-projects/y2-js-lab2
```

In the terminal, run the code to set up Python (you need this because the web server
is a flask app):

```
wget http://tinyurl.com/MEETpythonY2
source MEETpythonY2
```

Now, run the web server. Make sure you use `cd` to move to the
`y2-js-lab2` folder first!

```
python web_app.py
```

Open up the Chromium web browser (not Firefox) and navigate to
http://127.0.0.1:5000 .

## Exercise 1

Look through `templates/index.html` to find the IDs and classes of the
different `div`s in the page.

Open the JavaScript console with Ctrl+Shift+J. Using http://coolors.co/,
jQuery selectors, and the `.css()` method, give the webpage a temporary
makeover. Show your result to a TA or instructor before continuing. *We
won't check you off unless you pick a reasonable color scheme!*

## Exercise 2

Open `static/js/script.js`. Notice that just like in the last lab, all
JavaScript code goes inside `$(document).ready(function() {`.

Add code so that when you click on the picture, the main text background color
changes. Make sure you pick a reasonable color so that the text is readable!

