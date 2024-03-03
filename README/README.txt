(From top to bottom)
CODE FUNCTIONALITY INCLUDED FOR ALL PAGES
-<!DOCTYPE html>, for making a html workspace
-<html lang="en"> and <meta charset="UTF-8", language English and format 
-<link>, For my head favicon
-<linK>, this links in the CSS stylesheet 
-<title>, Name of website that is shown in tab
-<nav> <ul>, the navigation system that links between the 3 pages and creates a nav bar at top
-<div class=container>, whole page put in a flexbox
-<footer> <p> <a>, My name and a clickable image for contacting me through email
 
Home page
-introduces the user to me and who I am
-A central hub for accessing all the content
-Picture of me and what I do
CODE FUNCTIONALITY HOMEPAGE
-<div class=main>, creates a flexbox where the flexbox's main and sub-section go
-<div class=picture>, splits the screen where the flexbox for the img
-<div class=sub-section>, container flexbox for the text beside the img
-<img>, image of me
-<p>, 1 paragraph about myself and 1 paragraph about CS background
-<ul> <a>, for listing 3 of my various hobbies and links to something that is related to the subject
-<div class="center">, centers to middle of page

ME page 
-Includes things I want to highlight about myself
-A place where you can see what I like as well as things i've done
-Video of me skiing (personal touch)
CODE FUNCTIONALITY ME PAGE
-<ol>, list of things I want to highlight about myself
-<ul>, examples of each of the highlights
-<li class="ordered-me" id="education-list"> <ol id="me-list-wrap">, for creating the grid with the list
-<video>, Skiing video of me
-<form> <label> <input>, creates a form for users for questions about me

Project page
-Introduces the user to things i've worked on
-shows some part of my creativity, ingenuity and skills
-Looks at current and past works
CODE FUNCTIONALITY PROJECTS PAGE
-<table> <ol>, for listing current and past projects and creates a table
-<p> <a> <img>, breif explanation of keyboard project and a link to buy parts for beginners as well as a image of one i've built
-<p> <img>, explanation of building computer project and image of proccess of building my computer 
-<p> <iframe>, breif explanation of coding project and youtube reference video to the project

CSS Stylesheet
-for adding attributes to the webpages
-color, background, font, borders
CODE FUNCTIONALITY CSS STYLESHEET
*{}, adds requested background and white text to mostly all of web pages
div[class~="contain"]{}, For making whole page a flex box
.nav{}, for making the navigation bar at tops of pages
.main{}, used for home page and used to create a flexbox for the img
.sub-section{}, used for the text on the right of img
#block a{}, Used for the "blocks" for the navigation bar
li a:hover, #block a:hover, a:hover{}, used for black outline when hovering links
img, video, iframe{}, for borders around the respective elements
ul li{}, removes bullet points for lists
ol > li::first-line{}, first line of organized lists are formatted
h2{}, all heading formatted 
.ordered-me{}, needed for grid
#me-list-wrap{}, For creating the grid
#education-list{} #work-list{} #strengths-list{} #sports-list{}, for setting configuration in the grid
p + p{}, adding emphasis to text that is on project page
th, td{}, adding border around table cells
h2 ~ p{}, centers paragraphs underneath important headings
table, .center{}, used for centering specific things
input, textarea{}, changes colours for form elements
th{}, making text headings underlined and pop out

REFERENCES
-For traveling link(HOME PAGE - line 42): Global Affairs Canada. 2023. Home. (January 2023). Retrieved February 7, 2023 from https://travel.gc.ca/
-For spikeball link(HOME PAGE - line 44): Spikeball Store. Spikeball. Retrieved February 7, 2023 from https://spikeball.com/
-For skiing link(HOME PAGE - line 46): Sunshine Village Ski Resort in Banff Alberta. Sunshine Village. Retrieved February 7, 2023 from https://www.skibanff.com/
-For gmail image: Anon. Gmail logo(ALL PAGES - homepage line 52). Retrieved February 7, 2023 from https://1000logos.net/gmail-logo/
-For youtube video(PROJECT PAGE - lines 53-58): Anon. 2020. Java - Easy Currency Converter Program in Java ( Tutorial ), YouTube.
-Zybooks
-Dalhousie university 2023 1170 winter