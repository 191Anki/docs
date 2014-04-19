# Software Design Document
## What programming languages will you use?
+ Python
+ HTML
+ CSS
+ JavaScript
+ SQL
+ PHP

## What frameworks will you use?
+ CakePHP

## What other libraries or dependencies will you use?
+ Any library that provides desired functionality

## Will you use different languages, frameworks, and/or libraries/dependencies for different parts of your application?
+ Python will be used for the Anki while the website will utilize the HTML, CSS, JavaScript, PHP, and CakePHP framework. Both Anki and the server will use SQL to database the flashcards

## What is your overall architecture?
+ MVC

## What data will you need to store?
+ User account information: usernames, passwords
+ Flashcard decks (.apkg format)
+ Flashcard/deck edits

## What is your database design (or other data storage scheme)?
+ MySQL

## What are the other parts of your software?

<b>Model:</b>
+ Decks
 + Methods: Download, Upload, Change Privacy Settings, Sync with central database. 
 + Attributes: Number of cards, tags, sub decks, master decks
+ Accounts
 + Privileges
+ Flash Card
+ Attributes: Rate, Edit, Remove, Deck Position
+ Controllers:
 + Redundancy Algorithm:<br>
&nbsp;&nbsp;&nbsp;Methods: Run every time central deck is updated.
 + Best Card Algorithm:<br>
&nbsp;&nbsp;&nbsp;Methods: TBD. Upvote/Downvote system v.s. # of stars rating system. 
 + Tagging System:<br>
&nbsp;&nbsp;&nbsp;Methods: Dropdown list of pre-set tags, corresponding to course title.
 + View Cards:<br>
&nbsp;&nbsp;&nbsp;Methods: View All, Filter view, Search
 + Accounts:<br>
&nbsp;&nbsp;&nbsp;Methods: Log-in, Log-out, Sync, Share, Download, Edit

<b>View:</b>
+ Web browser interface
    


