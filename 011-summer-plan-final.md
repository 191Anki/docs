# Summer Plan Draft
Team Anki<br>
Dillon Gee, Jazmynn Daos, Kyla Lamontagne, Vamsi Koduru, Wilbur Chen

## Assessment
<b>What did we deliver at the end of spring quarter?</b><br>
Basic AnkiShare.com website build with a homepage login and upload/download pages for users. Users are able to register for an account, login, logout, upload files, and delete and download any of the uploaded files. 

Functional Requirements:
+ Users can register for an account, login, and logout.
+ Users can upload only apkg files to the system.
+ Users can delete files from the system.
+ Users can download files from the system.
+ The upload/download page automatically refreshes with an updated download list once a user uploads a file.

Nonfunctional Requirements:
+ Website access is restricted to registered users only.
+ System notifies user about any actions (i.e. "You are now logged in as...").
+ File uploads are restricted to apkg files only.
+ Avaiable download files appear as a list of links of uploaded files.

<b>Feedback from sponsors:</b><br>
Are satisfied with the spring MVP delivery, but would like the team to implement deck category integration as soon as possible so that all uploaded deck files are organized better.<br>

<b>What functional and nonfunctional requirements remain to be met for the final product?</b><br>
Functional Requirements:
+ Decks will be organized by categories.
+ Users can view the contents of a deck (overview of all the individual cards).
+ Users can view an individual card of a deck.
+ Users can edit a card's content (front, back, tags) and the new card will be added to an "edits" database for moderator review.
+ Users can edit a card's tags and the original card's tags will be edited.
+ Implement moderators.
+ Moderators will create communal decks for every category.
+ Moderators can delete cards from the communal database (all original and edited cards).
+ Moderators can approve and disapprove card edits.
+ Moderators can add/delete cards from communal decks.
+ System will recognize similar/duplicate/redundant cards.
+ Main database will automatically update with any changes (add approved new cards for edited cards, update tags of original cards, add new cards that were uploaded).

Nonfunctional Requirements:
+ Regular user and moderator user interfaces will be different, access-wise.
+ Website will be user-friendly.
+ Website design and aesthetics will be simple and clean.
+ System will display errors to the user when appropriate (i.e. invalid user, wrong password, upload error, etc.)


<b>What other work do we need to do deliver the final product?</b>
+ All team members need to continue brushing up on our Ruby, Javascript, HTML, and CSS coding skills.
+ We also need to conduct user testing to get feedback from users.
+ Continue meeting with our sponsors to receive their feedback and to update them on our progress throughout the summer and fall.

<b>Are there some requirements for the final product that are not yet clear?</b><br>
Need to clarify the role of moderators and what functionality will be available to them.<br>

<b>What is the most important work to do to make progress on delivering the final product?</b><br>
Advancing our Ruby, JavaScript, HTML, and CSS skills as a whole team.

<b>What skills are needed to do this work?</b><br>
Ruby, JavaScript, HTML, and CSS.<br>

<b>Who in the team has these skills? Who does not?</b>
+ Ruby: All team members, but still basic.
+ JavaScript: Dillon and Vamsi (some). <i>Jazmynn, Kyla, and Wilbur have no experience</i>
+ HTML: All team members, but still basic.
+ CSS: All team members, but still basic.

<b>How can those on our team without these skills get them?</b><br>
Continue reading tutorials, watching videos, etc. on Ruby, JavaScript, HTML, and CSS.

## Timeline
<b>SUMMER</b><br>
Touch Ups: Jazmynn, Wilbur | New Features: Dillon, Vamsi | Floater: Kyla<br>
Research means "trying to implement as best as we can"; Research tasks ARE NOT gauranteed to be finished; these tasks are more "trial" tests and runs so that we can hit the ground running in the Fall
+ <b>[1] 6/15-6/21:</b><br>
[TU] Learn and get familiar with current build of the website<br>
[NF] Implement moderator user accounts<br>
[NF] Set up development project for future builds<br>
[NF] Research: Attempt to figure out how to read .apkg and .file files
+ <b>[2] 6/22-6/28:</b><br>
[TU] Remove "Delete" feature for now<br>
[TU] Fix login bugs<br>
[TU] Start implementing category organization<br>
[NF] Buffer Week for research tasks
+ <b>[3] 6/29-7/5:</b><br>
[TUNF] Set up server via gnu screen (so it keeps running)<br>
[TU] Finish implementing category organization<br>
[NF] Research: Attempt to implement Anki importer, View Deck, Individual Card, and coverflow for deck overview
+ <b>[4] 7/6-7/12:</b><br>
[TU] Create email account for discount user testing feedback (ankishareucifeedback@gmail.com)<br>
[TU] Buffer Week<br>
[TU] Soft Summer Deployment Phase 1.0 7/12<br>
[NF] Buffer Week for research tasks
+ <b>[5] 7/13-7/19:</b><br>
[TU] Respond to discount user testing<br>
[NF] Research: Attempt to implement Edit Card and Edit Tags
+ <b>[6] 7/20-7/26:</b><br>
[TU] Respond to discount user testing<br>
[NF] Buffer Week for research tasks
+ <b>[7] 7/27-8/2:</b><br>
[TU] Respond to discount user testing<br>
[NF] Buffer Week for research tasks
+ <b>[8] 8/3-8/6:</b><br>
[TUNF] Create documentation; Make final adjustments<br>
[TUNF] Prepare for last Hard Summer Deployment Phase 1.1 8/6<br>
[TU] Respond to discount user testing<br>
[NF] Buffer Week for research tasks
+ <b>[ ] 8/7-9/30:</b><br>
NOTE: NO Hard deadlines for the rest of summer<br>
[TUNF] Continue learning Ruby, JavaScript, HTML, and CSS<br>
[TU] Respond to discount user testing<br>
[NF] Buffer Week for research tasks<br>

<b>FALL</b><br>
All tasks are a team effort.
+ <b>[0] 10/1-10/4:</b><br>
(nothing)
+ <b>[1] 10/5-10/11:</b><br>
Start implementing View Deck and Individual Card
+ <b>[2] 10/12-10/18:</b><br>
Finish implementing View Deck and Individual Card<br>
Start implementing Edit Card and Edit Tags
+ <b>[3] 10/19-10/25:</b><br>
Finish implementing Edit Card and Edit Tags<br>
Start implementing Communal Deck (moderator side) per category level
+ <b>[4] 10/26-11/1:</b><br>
Continue implementing Communal Deck (moderator side) per category level
+ <b>[5] 11/2-11/8:</b><br>
Finish implementing Communal Deck (moderator side) per category level<br>
Start implementing Communal Deck (regular user side) per category level
+ <b>[6] 11/9-11/15:</b><br>
Finish implementing Communal Deck (regular user side) per category level
+ <b>[7] 11/16-11/22:</b><br>
Buffer Week<br>
Conduct formal user testing
+ <b>[8] 11/23-11/29:</b><br>
Conduct formal user testing<br>
Respond to feedback from user testing<br>
Work on website aesthetics
+ <b>[9] 11/30-12/6:</b><br>
Conduct formal user testing<br>
Respond to feedback from user testing
<br>Work on website aesthetics
+ <b>[10] 12/7-12/13:</b><br>
Make final adjustments<br>
Prepare for Final Deployment Phase 2.0
