# Readme - FanFare Films


## Site Owner Goal
Site Owner also owns a cinema - FanFare Films. Site Owner is looking for a website that firstly allows online bookings - for classic films that users can find details about on the website itself. These should be prominent and eye catching.
Secondly - a voting system which allows returning users to vote for their next chosen classic, in order to drive repeat custom.

The motivation is to draw custom and revenue to the venue, by facilitating online bookings and establishing interactivity from the end users. Make them feel invested.

The films are the focus, instead of the venue. The venue is merely the site, the draw is the films.


## User Stories
These will be brief touchpoints of what the user is looking for from this site. The full walkthrough is later in the readme of the entire completed journey.

### User A - New Customer
- A new customer will want to know what they can watch at this cinema.
- A new customer will want details of the film to aid in selection.
- Price, runtime, days and times that the film shows.
- Ability to book chosen film at chosen times.
- Confirmation that booking as been successful.
- Location of the cinema. Parking.
- Details of snacks availability and policy.

### User B - Returning Customer
- Returning customer will also want to see the schedule, film details.
- Ability to book film.
- Confirmation of film booking.
- Ability to vote for upcoming film from selection - details of said films.


## Pages
  
### Home Page
Eye catching hero image followed by a consistent call to action. Leading on a journey through - Home --> Book --> Vote --> About Us --> Home

This is followed by a short description of what they are looking at - location, theme and what how they can interact and participate

Then the schedule is prominent as the main information focus, calls to action eye catching for more details

### Bookings
Primary function is a booking page to capture details, allowing the user to select their choice.

Users arrive here after wanting to 'see more' from the schedule.

They are presented with film details and the ability to select their day and time to book. There is a prominent imdb logo so they can see reviews if they want to also.

### Voting
After you book you are encouraged to go and vote, there is a reminder on the homepage text also, along with about.

This is the call for return custom, giving users a choice in what they can see. There is also a selection box should none of the current votes take their fancy.

### About
Here the users find more about us, our drive for films and our encouragement for them to join us in it. 

The personal writing leads to people (ideally) being more invested, feeling like they are being written to individually to try to drive repeat custom from film enthusiasts, like the site creators.

## Design Decisions

### General design:
Grey/black and white was chosen for two reasons - one as it gives a nice clean feel (in my opinion) and doesn't detract from the feel of the black and white films on show. Bright, brash colours would have done so I believe.

The calls to action are the exception here - green throughout due to it not being shocking, whilst invoking a positive feel.

The boostrap cards are also used throughout the project. This is to make the website have a consistent feel throughout, complementing the black/white design choice. In addition, the cards are excellent responsive tools and allow the information to remain presentable regardless of device.


### Book Page:
This page went through several iterations, primarily on how the booking system itself would be represented in this project. Initially, the day was selected via click button (which would remain highlighted), then the clicked time button would pass through the information and also act as 'submit'

This was deemed as an inferior design due to the ability to make misclicks and accidentally submit a booking. The dropdowns were chosen after this as a safer option, complemented by a call to action in keeping with the other calls to action across the site.

### Vote page:
Center alignment was the main decision made here - left alignment as before looked messy due to the lack of images. Finding license allowed images for big classic movies was a struggle so design aesthetic was amended whilst keeping the same feel.
This decision then lead to a liking for centre alignment, so it was adopted throughout the site. 
It was felt that it kept the user eyes focused down from the centre aligned hero text, flowing down the page.

Getting everything centered then changed the margin design - additional styling was needed to bring the right spacing in between the elements - code commented where this is applicable for future explanation.

After the midpoint meeting, i was introduced to a better way of looking for royalty-free images and managed to locate images for each of the six films here - vastly improving the feel of the page.

### About page:
This page was originally going to be a section at the top of the main page. Instead it was swapped for a brief overview of how the process works and moved to its own page to be more in-depth.

The reasoning for this was not wanting to detract from the film schedule any more than necessary. This is the main draw of the site.

The bulk of the information is presented here for those wanting more details on the site story and it also incorporates an interactive map which should cut out any questions about location.

### Code:
The code has been commented into general sections throughout, however I have chosen to add additional comments to book.html and vote.html due to them having large blocks of code within each card element. 
The comments split this a little making it easier to read along with highlighting where changes can be targeted if needed.

### Wireframes:
See images below for initial design ideas on mobile and desktop. Note that it was originally intended to be a one-page site however a multi-page made much more sense when going through the user stories.


#### Desktop
![image](https://user-images.githubusercontent.com/61311614/90532565-4eed1080-e16f-11ea-8dbd-bfcf3a6e4090.png)



![image](https://user-images.githubusercontent.com/61311614/90532627-5f9d8680-e16f-11ea-87b5-bb74a430f5d3.png)



![image](https://user-images.githubusercontent.com/61311614/90532650-688e5800-e16f-11ea-9e36-89338d210f89.png)



#### Mobile
![image](https://user-images.githubusercontent.com/61311614/90532512-409ef480-e16f-11ea-8c7e-ebebe482cd11.png)



![image](https://user-images.githubusercontent.com/61311614/90532546-498fc600-e16f-11ea-82d3-0bbcc67c56cc.png)



## Technologies used
- Repl.it - this was the chosen development platform.
- Bootstrap for card framework, container code - used throughout for rich content and responsive behaviour.
- GitHub - utilised for cloud backups and project progression.
- GitHub Pages - an aspect of github, used to deploy the finalised product.
- Balsamiq - used to create wireframe ideas of how the website should look and function.

## Deployment procedure
-Github pages utilised for deployment - process as follows:
-Navigate to https://github.com/WrightDanG/FanFareFilms/
-Settings, scroll down to Github pages
-Select the master branch, root directory and click deploy.
-Site is hosted at https://wrightdang.github.io/FanFareFilms/

On the first navigation, a 404 error was presented. Manually navigating to https://wrightdang.github.io/FanFareFilms/index.html resolved this and the website remained stable after that.

Code was locally viewed and edited via repl.it.

## Attributation
- Header and Nav from Code Institute Love Running Project.

- Hero Image -  Home https://www.pexels.com/photo/abstract-analog-art-camera-390089/

- Hero Image - Booking
https://www.pexels.com/photo/multi-colored-chairs-in-row-257385/

- Hero image - Vote
https://www.pexels.com/photo/person-dropping-paper-on-box-1550337/

- Hero image - About
https://www.pexels.com/photo/board-cinema-cinematography-clapper-board-274937/

- The Big Sleep image
https://pixabay.com/photos/humphrey-bogart-lauren-bacall-619157/

- Angel and the Badman Image
https://pixabay.com/photos/john-wayne-gail-russell-actor-394468/

- Detour image
https://pixabay.com/photos/ann-savage-tom-neal-actress-actor-394472/

- Prisoner of Zenda image
https://pixabay.com/photos/ronald-colman-madeleine-carroll-403399/

- Citizen Kane image https://commons.wikimedia.org/wiki/File:Citizen-Kane-Cotten-Welles-Sloane-Sanford.jpg

- The Maltese Falcon image
https://commons.wikimedia.org/wiki/File:Maltese-Falcon-Tell-the-Truth-1941.jpg

- Treasures of the Sierra Madre image
https://commons.wikimedia.org/wiki/File:Humphrey_Bogart_Walter_Huston_The_Treasure_of_the_Sierra_Madre_Still.jpg

- Dark Passage image
https://pl.wikipedia.org/wiki/Plik:Dark_Passage_1947_Lobby_Card_1.jpg

- Casablanca image
https://www.flickr.com/photos/72006245@N05/6506075403
Creative commons licence located on a page link there which follows through to:
https://creativecommons.org/licenses/by/2.0/

- The Great Dictator image
https://www.flickr.com/photos/tom-margie/1535376771
Creative commons licence located on a page link there which follows through to:
https://creativecommons.org/licenses/by/2.0/

- Assistance on name and value for form button submission on book page:
https://stackoverflow.com/questions/37973455/pass-additional-data-with-submit-button 

- Assistance on how to jump to a specific part of another page - namely the bookings section of book.html for this project:
https://stackoverflow.com/questions/17687328/getting-a-link-to-go-to-a-specific-section-on-another-page

- Readme screenshot information guide found here: https://medium.com/@justynagolawska/how-to-easily-add-screenshots-into-your-readme-file-on-github-d806a01d6ffd


## Desirable features to add:
Date validation - currently using this week/next week. Calendar dropdown with valid dates available. Would be linked to a database of upcoming.
Likely would go with something such as: https://bootstrap-datepicker.readthedocs.io/en/latest/
Or:
https://formvalidation.io/guide/getting-started 
This one has some useful built in abilities to only specify a certain date range.

Requires additional knowledge of JS and Jquery, though appears achievable. Carepoints would include ensuring past bookings are not possible and only future bookings that fall on appropriate scheduled days.

Going forward, repeat custom would be best served in implementing a user database and an emailer which would alert users to new films and specifically new films that they have actively voted for.


Bootstrap appears to have many elements that generally do not conform to the accessibility contrast guidelines. In this project, this is reflected in the btn-success that are used across the site. 

This is addressed in several places, for example:
https://getbootstrap.com/docs/4.0/getting-started/accessibility/#overview-and-limitations

and 

https://github.com/twbs/bootstrap/issues/25126

In discussion with my mentor, it was decided to acknowledge this here for now but make no changes. Moving forward it would be a preference to use colours and functions that met appropriate standards for contrast throughout.


## Testing

### Between-page links

#### Top Nav Bar 
Index - All functioning to each page
Book - All functioning to each page
Vote - All functioning to each page
About - All functioning to each page

#### Fanfare Films logo
Index - Leads to index.html
Book - Leads to index.html
Vote - Leads to index.html
About - Leads to index.html

#### Hero links
Index - Leads to book.html
Book - Leads to vote.html
Vote - Leads to about.html
About - Leads to index.html

#### 'See More' Links - located on index.html
The Big Sleep - Leads to book.html, bookings section
Angel and the Badman - Leads to book.html, bookings section
Detour - Leads to book.html, bookings section
The Prisoner of Zenda - Leads to book.html, bookings section

#### 'What we do' links - located on about.html
'Book Now' button on Step 1 - Leads to book.html
'Vote' button on Step 2 - Leads to vote.html
'Schedule' button on Step 3 - Leads to the schedule cards on index.html

#### Map on about.html
Map shows 123 Nottingham Road.
Map can be moved and Scrolled
'Directions' and 'view larger map' links are functionality

#### Footer address link
Index - Clicking '123 Nottingham Road' takes you to the map in about.html
Book - Clicking '123 Nottingham Road' takes you to the map in about.html
Vote - Clicking '123 Nottingham Road' takes you to the map in about.html
About - Clicking '123 Nottingham Road' takes you to the map in about.html

#### Footer Social Links
Index - Facebook, Instagram and Twitter all go to their respective home pages. 
Book - Facebook, Instagram and Twitter all go to their respective home pages. 
Vote - Facebook, Instagram and Twitter all go to their respective home pages. 
About - Facebook, Instagram and Twitter all go to their respective home pages. 


### Server submissions

#### 'Book' Links - located on book.html
The Big Sleep - Leads to 'Congratulations' page.
-'Choose a day' unclickable.
-Date Values represented on 'Congratulations' page
-Time values represented on 'Congratulations' page
-Times reflective of described times in 'showings this week'

Angel and the Badman - Leads to 'Congratulations' page.
-'Choose a day' unclickable.
-Date Values represented on 'Congratulations' page
-Time values represented on 'Congratulations' page
-Times reflective of described times in 'showings this week'

Detour - Leads to 'Congratulations' page.
-'Choose a day' unclickable.
-Date Values represented on 'Congratulations' page
-Time values represented on 'Congratulations' page
-Times reflective of described times in 'showings this week'

The Prisoner of Zenda - Leads to 'Congratulations' page.
-'Choose a day' unclickable.
-Date Values represented on 'Congratulations' page
-Time values represented on 'Congratulations' page
-Times reflective of described times in 'showings this week'


#### 'Vote' links, located on vote.html

Citizen Kane - Leads to 'Congratulations' page with appropriate content.

The Maltese Falcon - Leads to 'Congratulations' page with appropriate content.

Casablanca - Leads to 'Congratulations' page with appropriate content.

The Treasure of the Sierra Madre - Leads to 'Congratulations' page with appropriate content.

Dark Passage - Leads to 'Congratulations' page with appropriate content.

The Great Dictator - Leads to 'Congratulations' page with appropriate content.


#### 'Suggestion Box', located on vote.html
Movie input is reflected on 'Congratulations' page.
Movie Year input is reflected on 'Congratulations' page.


### IMDB Links

#### Book.html

The Big Sleep - Leads to the appropriate imdb page.

Angel and the Badman - Leads to the appropriate imdb page.

Detour - Leads to the appropriate imdb page.

the Prisoner of Zenda - Leads to the appropriate imdb page.


#### Vote.html

Citizen Kane - Leads to the appropriate imdb page.

The Maltese Falcon - Leads to the appropriate imdb page.

Casablanca - Leads to the appropriate imdb page.

The Treasure of the Sierra Madre - Leads to the appropriate imdb page.

Dark Passage - Leads to the appropriate imdb page.

The Great Dictator - Leads to the appropriate imdb page.


### Responsiveness

In testing, a problem arose when loaded onto a Galaxy Note 9 and turned sideways. 

The problem was identified as the jumbotron header text clipping through the navbar, primarily when the display was wide but short.

This was rectified by the addition of a media query CSS style which reduces the jumbotron text side on smaller screens, followed by removing it entirely on screens that are particularly short and particularly wide.

Otherwise, the cards responsively move and rearrange to suit screen size and are appropriate for both larger and smaller devices.

This has been tested using the following settings on Firefox Developer Tools:
Galaxy S9/S9+
iPad
iPhone 6/7/8
iPhone 6/7/8 Plus
iPhone X/XS
Kindle Fire HDX

### UX and screenreader compatibility
The following website was used to assess compatibility with screenreaders
https://wave.webaim.org/ 

#### Initial findings

##### Index.html

- Document language was missing in the head html

- The social links in the footer of the pages did not have accompanying description

- h2 was accidentally skipped, index.html featured a h1 and a h3

- The program detected the 'See More' buttons as redundant, since they are next to one another and going to the same location.

- Contrast between font and background colours did not meet standards

##### Book.html

- Labels were not present on the form dropdowns

- The imdb links did not have accompanying description

- Contrast remains an issue on this page.

##### Similar issues were located through vote.html and about.html



#### Improvements

- Amended the text colour from #777777 to #595959 in order to meet contrast requirements.

- Amended the opacity for the hero image cover from 0.5 to 0.6, in order to meet contrast requirements.

- Added 'aria-label' labels to all of the elements that were identified as requiring additional information, such as the dropdowns on book.html and the imdb links. The new labels describe the function of the menu or button.

- Decided that h2 was more appropriate for the heading (since it shouldnt trump the logo) and ensured that they descend through h3 and h4 going onwards. 

### Browsers

The below browsers have had the website opened, navigated through and confirmed to be functional:
-Firefox
-Chrome
-Microsoft Edge

### Testing that GitHub pages matches development version.
It was observed that the github pages version of the website took 10-15 minutes to reflect the development changes after a deployment.

Aside from that, the final github version matches the development version that is hosted on Repl.it.

### W3C and Jigsaw validation
It was identified that several of the dropdown items in book.html required amending in order to pass correctly through the W3C validator. Originally a size attribute was added, which did fix the validator issue but prevented the dropdown animation.

The size elements were then replaced with an empty value on the first dropdown item (the disabled item asking you to make a selection). This retained functionality and kept a pass for the validator.

It was also identified that the Jigsaw validator has serious issues with much of the bootstrap built-in CSS. It was instead validated by input, instead of via URL and the remainder of the CSS was rated to pass.
  


## User story walkthroughs

Decided to move the IMDB details to the front page and the book option to 'more'. This gives return users a more accessible intro to the information they seek immediately as they visit the page.

On mentor advice, most of the information has been transferred from the home page to encourage people to click through to Book. Keep the schedule on home with a teaser of information and then the meat of the content right before they confirm their booking.

Throughout the site, cards have been utilised to present the groups of information. These are fully responsive so rearrange to neatly present the information to the user, regardless of device size.

### User A - New Customer

Immediately on visiting, the customer is presented with the home page (index.html):

![image](https://user-images.githubusercontent.com/61311614/90414761-1c2c1500-e0a8-11ea-9117-c50845506519.png) 

There they are presented with the information that the website is for a Nottingham-based cinema showing classic movies and the price per film.

They are given three options to navigate through the site - there is the top naviagation bar, with the first option being Book. Next there is a call to action in inviting green, also to book. Finally there is a peep of the section below the hero image inviting them to look at what films are on now.

On scrolling down the customer are presented with the four films showing this week, below a small description ensuring the customer knows how they can proceed - Book the film, then go over to the vote page to vote for the next film and then learn more at the about page:

![image](https://user-images.githubusercontent.com/61311614/90415776-7d081d00-e0a9-11ea-8ef9-de8033df90a8.png)

The Call to Action buttons are below each film, along with a short description of the film and eye catching images. On clicking to see more details, they are sent to the book.html page. Below this is the footer which has the cinema address and social media links - this is present on every page.

The next natural step is book.html. Coming here from the nav or hero calls to action brings the user to the top of the page

![image](https://user-images.githubusercontent.com/61311614/90415898-a6c14400-e0a9-11ea-9795-00735459cd12.png)

The user is encouraged to make their booking from the selection below and then afterwards head to vote.
Below the hero image the user can see a peep of a 'book with us' section. On scrolling down (or clicking the 'more details' buttons on the home page) the user is given the essential movie details, an imdb link for further details, a fun film note and the ability to dropdown select the day and time. 

![image](https://user-images.githubusercontent.com/61311614/90415990-cc4e4d80-e0a9-11ea-84ab-ffe9f18abf70.png)

![image](https://user-images.githubusercontent.com/61311614/90416059-e2f4a480-e0a9-11ea-8f2d-dbc8c72722c1.png)

![image](https://user-images.githubusercontent.com/61311614/90416137-fe5faf80-e0a9-11ea-89d7-7e66ed2d15e3.png)

Both fields are required to proceed and on submission, the user is this case is presented with a new page which uses Code Institutes confirmation page as a stand in for the booking database. 

![image](https://user-images.githubusercontent.com/61311614/90416182-0d466200-e0aa-11ea-9ec6-0efc95184ed1.png)

Utilising either the navbar or the call to action at the top of the page, the new user can then proceed onto the vote page. There is also the option of them wanting to know where the cinema is at this point - the initial information on the homepage has told them that they can head to about.html, using the navbar or if they were to click on the address in the footer on any page, they will be taken to the location map.

Regarding the vote page:

![image](https://user-images.githubusercontent.com/61311614/90416783-d3c22680-e0aa-11ea-8a92-b00e76984a76.png)

On the vote page, the user is presented initially with the instruction to cast their vote for the next film selection below. They are instructed afterwards to find out more at the about page. The user can see a peek of the 'Have your say' section, encouraging scrolling down.

![image](https://user-images.githubusercontent.com/61311614/90416863-ee949b00-e0aa-11ea-9334-500da87095f3.png)

![image](https://user-images.githubusercontent.com/61311614/90416905-fbb18a00-e0aa-11ea-8757-b449465577ab.png)

The user can look at a title image for six possible upcoming films along with a short description and the ability to click through to the imdb page for more information.
Should they want to cast a vote - the vote button takes them to a confirmation page.

Should none of the options appeal to the user, they are able to scroll slightly further and provide the name and year of a film of their choosing, submitting their choice after typing in both boxes.

![image](https://user-images.githubusercontent.com/61311614/90417085-2f8caf80-e0ab-11ea-9e26-31f9c13e6879.png)

![image](https://user-images.githubusercontent.com/61311614/90417265-619e1180-e0ab-11ea-91ff-b478ede74567.png)


Finally the user is able to use the navbar or call to action button at the top of the vote page in order to find out more information from about.html.

![image](https://user-images.githubusercontent.com/61311614/90417543-c194b800-e0ab-11ea-8cc6-820e9c0d1999.png)

At the top of about.html, the user is presented with a guide to the information that they'll find below, along with the option to go back to the home page. This makes the journey cyclical should the user wish to do so.

![image](https://user-images.githubusercontent.com/61311614/90417587-d3765b00-e0ab-11ea-80a7-bc08450732ab.png)

The user is also given a peek at the below information, where they are able to learn the story of the cinema, an overview again of the process of booking, voting, visiting along with appropriate calls to action.

![image](https://user-images.githubusercontent.com/61311614/90417636-e8eb8500-e0ab-11ea-9e8d-1d222409fafc.png)

Finally the user is given an interactive map showing the location that they would visit when they attended. The user can scroll this around or click to view a larger map which allows them to program directions on the google maps site.


### User B - Return Customer

The primary difference between a new user and an existing user is that they likely already know the cinema details and how the process works.

For this reason, the navigation and schedule are prominent infront of them on the homepage. 

![image](https://user-images.githubusercontent.com/61311614/90417732-0d476180-e0ac-11ea-9cec-9ade968bfac8.png)

Therefore they can easily book a new film if they havent been that week, else have their say on upcoming films as the vote navigation is easy to get to from arriving at the website.

Otherwise, due to the nature of the changing films, they share a journey in booking a film to watch and having the ability to vote for what they prefer to see upcoming. 

![image](https://user-images.githubusercontent.com/61311614/90417797-25b77c00-e0ac-11ea-8a0d-f2fbb1d02441.png)

They may wish to see if the film that they have voted for has made it into the cinema and for that reason, the schedule being prominent on the homepage still fits their purpose well.

This can be improved in future with a mailing list database, where the returning user is alerted to their chosen film being selected for showing. This will also require a sign-up database and appropriate data-capture and email functionality.

In the current absence of this, the concept of the vote system is specifically made to try to drive repeat custom. Allowing the repeat user to come to the site and have a say in the cinemas upcoming films encourages more regular traffic to check in on new films and whether their suggestions have come into the new line-up.


The journey satisfies the proposed user story expectations listed at the beginning of the readme. 







