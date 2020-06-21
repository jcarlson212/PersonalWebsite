# Project 0 (Harvard CS50 Web)

Web Programming with Python and JavaScript

For this project, I made a website that includes basic information about me, math flash cards, a blog, my resume, and a projects page. I used bootstrap, html, scss, css, and javascript in this project. 

## Index.html

This file is essentially the home page of my website. It contains a short paragraph about me, a picture of me, and a picture of a math meme. Users can use this page to navigate to any of the other pages. The navigation bar I styled myself so that it shrinks when users have a screen of 1000px or smaller (changes the flex direction to column).

## mystyle.scss

This contains all of the styling needed for the other pages (that does not use bootstrap). The styling of the navigation, paragraphs, and tables were the main things styled here. Also, colors are here (with variables for some).

## mystyle.css

This is the actual css file the scss file creates. To create it, I just run "sass --watch mystyle.scss:mystyle.css" in the terminal in my project directory

## flashCards.html

This page contains math flash cards that flip when clicked to reveal definitions / theorems. It uses the bootstrap grid model. I was able to make the back of flash cards scrollable without the scrollbar showing.

## resume.html

This page loads my resume and displays it.

## blog.html

This page contains posts I make about random things. It includes a single post about GDP of wealthy countrys vs poor countries.

## projects.html

This page contains a list of projects I have made with links. 
