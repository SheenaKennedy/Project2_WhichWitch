## This project is for a website called **"WhichWitch”**. 

It’s purpose is to provide users a quiz of personal questions 
to discover the type of witch they may be. After users receive their result
they are provided with a brief description expanding on their result 
and a number of related gallery images sourced from Pinterest, 
as well as a few resources if they’d like to learn more about their result. 

They will also have the option to see all possible results from the quiz, 
to see if a different witch type reflects their interests more closely.
After receiving their quiz result, users have the option to sign up for 
an account which will store their result and any other '“favorited”' results
they select for Window.localStorage to remember for future visits.

### Site Purpose:
WhichWitch’s purpose to help guide potential baby Witches 
to identify and explore varying areas/types of witchcraft that may speak 
to them more strongly than the standard stereotype of the crone with the 
pointy hat that lives alone with 50 cats and cooks up lizard guts in a 
cauldron. 
Finding the key to their witch type, will open the door for baby Witches 
to the great world of real magic that surrounds all of us, if they learn
to become aware of it.

### User Goals: 
Users of this site may be anyone, of any age, region, gender, 
background or religion. Witchcraft is not a religion, but a conscious relationship 
with the Earth around us. Users with an interest in witchcraft who may not know much 
about the different types of witches or may need help figuring out what type(s) 
speak to them, will gain knowledge and direction from their quiz result. 

### Site Owner Goal: 
To gauge present interest in witchcraft, 
for future offers and services in that market. 
As well as a resource of good will, 
helping those in the early stages of feeling drawn to witchcraft 
but unsure about what it is and if it's right for them.

### Technologies Used:
HTML
CSS
JavaScript

### Outsourced Bootstrap Framework 
from Start Bootstrap, architecture theme '"Grayscale"'
HTML repo: https://github.com/StartBootstrap/startbootstrap-grayscale.git

### Code referenced for quiz construction, Sitepoint.com and SimpleStepsCode.com
HTML: htts://www.sitepoint.com/simple-javascript-quiz/
HTML: https://simplestepscode.com/javascript-quiz-tutorial/

### Other sources used:
Images sourced from Pinterest
Descriptions of types taken from various websites, included with 
external reference links to open a new tab

### The information architecture for this site:
1. starts from the Landing page
that displays the h1 Title heading of the website name, 
a background image of a door and key hole, 
and an HTML button that users can click to '"unlock"' the progression of the site flow.

2. After clicking the '"unlock"' button, users are taken to the Welcome page.
This page includes a new background image of inside a cottage,
a h2 and h3 to welcome the user, 
another subheading h2 and paragraph of text to explain what this site is about, 
what value it provides the user, 
a description of the quiz, and why the user would want to this information.
At the bottom of the page, below all the paragraph text, there is a button 
the user can click to take them to the next page which is the quiz itself.

3. The quiz will display all questions on one page, 
using radio buttons to select their answer to each question.
The quiz is coded in a way that requires user input, 
or the quiz will not advance to the result page. 
This way it guarantees the quiz is properly complete and no questions are mistakenly skipped.
At the bottom of this page there is a '"see my results"' button 
that users can click to take them to the results page.

4. After the user has completed the quiz questions correctly
and clicked the '"see my results"' button, they will be taken to the Results page.
Here they will receive in an h2 their witch type, 
a brief description in a paragraph, and an image sourced from Pinterest that relates to their type.
Each image used includes a reference link if the user clicks the image or link, 
which will take them to Pinterest where they can find other similar images. 
Each image also contains descriptive alt text, should the image not load properly, 
or for read-aloud computer options that assists the visually impaired.
They will also have a '"remember me"' heart button option to store their result 
in Window.localStorage for any future visits to this site.
There is also a '"see all results"' button at the bottom that will take the user
to the next page and final page.

5. The '"see all results"' page will include all the 10 possible results from the quiz, 
displayed in a gallery type format, with alternating paragraph and image display for each type.
Each type will be stated in h3 heading, followed by paragraph text below, 
and a relevant image displayed adjacent to the description. Each image will carry their 
own reference link and related alt text.
Each type will also have a heart button that a '"remember me"' user can favorite any other 
types they may relate to or feel an interest in, to be stored in Window.localStorage 
for future reference alongside their quiz typre result.
At the bottom there will also be a brief unordered list of other witch types that the user 
can choose to explore and research on their own, outside of the parameters of this quiz site.
There will also be a separate list of recommended resources to learning more about witchcraft and witch types.
At present this list includes a handful of books that I personally have read. 
But depending on future growth and interest in this site from users, 
(as seen internally on the backend side as the number of visits to the site) this list may change 
offering potential for honest endorsements from other third-party representatives 
to link to their own website for mutual benefit of all, including users wanting to know more. 

Overall: the architecture I chose for this site did not follow the usual
navigation menu of a home, about, contact and sign-up template because 
I imagined this site to be more like a PBS public education resource, 
rather than a specific company or business owner seeking to draw in interest
for a paid service, and dividing information the user may want first on
separate hyperlink pages. So because I don't want WhichWitch to inherently
sell anything via this site at any foreseeable time, I thought it most effective
to arrange the information flow from page to page more like a story,
taking the user from one page to the next, no skipping around. As a reader might
read a new book they just started, or as a reader re-visiting a book they've already finished,
it is logical to always start from the beginning. 
So I designed the site architecture to flow in this way.
The only direction the user can go is forward or backward. 
There are no hyperlinks to go from the landing page to the result page, or see all results page.
(With the exception that a previous user had selected the '"remember me"' button 
which will bring them straight to their results page.)
This is intentional, as I believe any user that would revisit the page having not previously
clicked the button to store their results is coming back to retake the quiz again.
(If a previous '"remember me"' user wishes to retake the quiz they can easily delete their localStorage
and start again as a new user; or they can click the '"see all results"' button from their result page.)

And in keeping with a book, an automated heading and footer does carry over 
from the first page'/'welcome page, through all the rest of the pages that follow.

The only exception to the one-way flow of a story book is that
after a user has received their witch type, they have the option 
to click a '"remember me"' button. Which will store their result in Windows.localStorage
for any future visits to this site (either they'd forgotten their type, 
want to read more about their type, want to take the quiz again, 
show the site and their result to any of their friends,
or would like to revisit the '"see all results"' page)


