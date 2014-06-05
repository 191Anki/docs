# Software Design Document
Team Anki

Dillon Gee, Jazmynn-Jade Daos, Kyla Lamontagne, Vamsi Koduru, Wilbur Chen

## What programming languages will you use?
+ Ruby
+ JavaScript
+ HTML
+ CSS
+ SQL

## What frameworks will you use?
+ Ruby on Rails

## What other libraries or dependencies will you use?
+ Sublime Text
+ Any other library or dependencies that provides desired functionality

## Will you use different languages, frameworks, and/or libraries/dependencies for different parts of your application?
+ JavaScript, HTML and CSS languages will be used to develop the AnkiShare website application
+ Ruby on Rails will be the framework used to develop AnkiShare
+ SQL will be used to setup and maintain the website�s database
+ Sublime Text will be used as our main text editor

## What is your overall architecture?
+ MVC

## What data will you need to store?
+ User account information: usernames, passwords
+ Flashcard decks in .apkg format
+ Flashcard edits

+  Deck class/category name organization structure
+ User activity log: username, timestamps, action

## What is your database design (or other data storage scheme)?
+ MySQL

## What are the other parts of your software?

<b>Model:</b>
+ Decks
 + Methods: Download, Upload, Change Privacy Settings, Sync with central database
 + Attributes: Number of cards, tags, sub decks, master decks
+ Accounts
 + Users
 + Moderators
+ Flash Card
+ Attributes: Rate, Edit, Remove, Deck Position
+ Controllers:
 + Redundancy Algorithm:<br>
&nbsp;&nbsp;&nbsp;Methods: Run every time central deck is updated
 + Tagging System:<br>
&nbsp;&nbsp;&nbsp;Methods: Dropdown list of pre-set tags, corresponding to course title
 + View Cards:<br>
&nbsp;&nbsp;&nbsp;Methods: View All, Filter view, Search
 + Accounts:<br>
&nbsp;&nbsp;&nbsp;Methods: Log-in, Log-out, Sync, Share, Download, Edit

<b>View:</b>
+ Web browser interface
