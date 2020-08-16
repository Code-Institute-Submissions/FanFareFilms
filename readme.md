Outline

Readme Tasks:

  Write a README.md file for the web application that explains its purpose, the value that it provides to its users, and the deployment procedure.

  Insert screenshots of the finished project that align to relevant user stories

  Attribute all code from external sources to its original source via comments above the code and (for larger dependencies) in the README.

Site Owner Goal
  Site Owner also owns a cinema - FanFare Films. Site Owner is looking for a website that firstly allows online bookings - for classic films that users can find details about on the website itself. These should be prominent and eye catching.
  Secondly - a voting system which allows returning users to vote for their next chosen classic, in order to drive repeat custom.

  The motivation is to draw custom and revenue to the venue, by facilitating online bookings and establishing interactivity from the end users. Make them feel invested.

  The films are the focus, instead of the venue. The venue is merely the site, the draw is the films.


User Stories

  User A - New Customer
    A new customer will want to know what they can watch at this cinema
    A new customer will want details of the film to aid in selection
    Price, runtime, days and times that the film shows.
    Ability to book chosen film at chosen times
    Confirmation that booking as been successful
    Location of the cinema. Parking.
    Details of snacks availability and policy



  User B - Returning Customer
    Returning customer will also want to see the schedule, film details
    Ability to book film
    confirmation of film booking
    ability to vote for upcoming film from selection - details of said films.


Pages
  Home Page
    Eye catching hero image
    Call to action - These are consistent through the site leading on a journey - Home --> Book --> Vote --> About Us --> Home
    Short description of what they are looking at - location, theme and what how they can interact and participate
    Schedule prominent, calls to action eye catching for more details

  bookings
    Booking page to capture details.
    Users arrive here after wanting to 'see more' from the schedule. They are presented with film details and the ability to select their day and time to book. There is a prominent imdb logo so they can see reviews if they want to also.

  voting
    After you book you are encouraged to go and vote, there is a reminder on the homepage text also, along with about. This is the call for return custom, giving users a choice in what they can see. There is also a selection box should none of the current votes take their fancy.

  about
    Here the users find more about us, our drive for films and our encouragement for them to join us in it. The personal writing leads to people (ideally) being more invested, feeling like they are being written to individually to try to drive repeat custom from film enthusiasts, like the site creators.

Design Decisions

  General colouration:
  Grey/black and white was chosen for two reasons - one as it gives a nice clean feel (in my opinion) and doesnt detract from the feel of the black and white films on show. Bright, brash colours would have done so I believe.

  The calls to action are the exception here - green throughout due to it not being shocking, whilst invoking a positive feel.

  Vote page:
  Center alignment was the main decision made here - left alignment as before looked messy due to the lack of images. Finding license allowed images for big classic movies was a struggle so design aesthetic was amended whilst keeping the same feel.
  This decision then lead to a liking for centre alignment, so it was adopted throughout the site. 
  I felt that it kept the user eyes focused down from the centre aligned hero text, flowing down the page.

  Getting everything centered then changed the margin design - additional styling was needed to bring the right spacing in between the elements - code commented where this is applicable for future explanation.

  Code:
  The code has been commented into general sections throughout, however I have chosen to add additional comments to book.html and vote.html due to them having large blocks of code within each card element. 
  The comments split this a little making it easier to read along with highlighting where changes can be targeted if needed.


Technologies
  replit
  Bootstrap for card framework, container code

Deployment procedure
  Github pages utilised for deployment - process as follows:

Attributation
  Header and Nav from Code Institute Love Running Project.
  Hero Image -  Home https://www.pexels.com/photo/abstract-analog-art-camera-390089/

  Hero Image - Booking
  https://www.pexels.com/photo/multi-colored-chairs-in-row-257385/

  Hero image - Vote
  https://www.pexels.com/photo/person-dropping-paper-on-box-1550337/

  Hero image - About
  https://www.pexels.com/photo/board-cinema-cinematography-clapper-board-274937/

  The Big Sleep image
  https://pixabay.com/photos/humphrey-bogart-lauren-bacall-619157/

  Angel and the Badman Image
  https://pixabay.com/photos/john-wayne-gail-russell-actor-394468/

  Detour image
  https://pixabay.com/photos/ann-savage-tom-neal-actress-actor-394472/

  Prisoner of Zenda image
  https://pixabay.com/photos/ronald-colman-madeleine-carroll-403399/

  Citizen Kane image https://commons.wikimedia.org/wiki/File:Citizen-Kane-Cotten-Welles-Sloane-Sanford.jpg

  The Maltese Falcon image
  https://commons.wikimedia.org/wiki/File:Maltese-Falcon-Tell-the-Truth-1941.jpg

  Treasures of the Sierra Madre image
  https://commons.wikimedia.org/wiki/File:Humphrey_Bogart_Walter_Huston_The_Treasure_of_the_Sierra_Madre_Still.jpg

  Dark Passage image
  https://pl.wikipedia.org/wiki/Plik:Dark_Passage_1947_Lobby_Card_1.jpg

  Casablanca image
  https://www.flickr.com/photos/72006245@N05/6506075403
  Creative commons licence located on a page link there which follows through to:
  https://creativecommons.org/licenses/by/2.0/

  The Great Dictator image
  https://www.flickr.com/photos/tom-margie/1535376771
  Creative commons licence located on a page link there which follows through to:
  https://creativecommons.org/licenses/by/2.0/


  Assistance on name and value for form button submission on book page:
  https://stackoverflow.com/questions/37973455/pass-additional-data-with-submit-button 

  Assistance on how to jump to a specific part of another page - namely the bookings section of book.html for this project:
  https://stackoverflow.com/questions/17687328/getting-a-link-to-go-to-a-specific-section-on-another-page

  Readme screenshot information guide found here: https://medium.com/@justynagolawska/how-to-easily-add-screenshots-into-your-readme-file-on-github-d806a01d6ffd


Features to add:
  Date validation - currently using this week/next week. Calendar dropdown with valid dates available. Would be linked to a database of upcoming.
  Likely would go with something such as: https://bootstrap-datepicker.readthedocs.io/en/latest/
  Or:
  https://formvalidation.io/guide/getting-started as this one has some useful built in abilities to only specify a certain date range.

  Requires additional knowledge of JS and Jquery, though appears achievable. Carepoints would include ensuring past bookings are not possible and only future bookings that fall on appropriate scheduled days.


Testing
  Between-page links
    Top header bar 
      Index
      Book 
      Vote 
      About

  Server submissions

  Responsiveness

  UX and screenreader compatibility


  (Functionality, Usability, Respon)

  User story walkthroughs
    Decided to move the IMDB details to the front page and the book option to 'more'. This gives return users a more accessible intro to the information they seek immediately as they visit the page.

    On mentor advice, most of the information has been transferred from the home page to encourage people to click through to Book. Keep the schedule on home with a teaser of information and then the meat of the content right before they confirm their booking.

    User A - New Customer
      Immediately on visiting, the customer is presented with the home page (index.html):
      (Index Link)
      There they are presented with the information that the website is for a Nottingham-based cinema showing classic movies and the price per film.
      They are given three options to navigate through the site - there is the top naviagation bar, with the first option being Book. Next there is a call to action in inviting green, also to book. Finally there is a peep of the section below the hero image inviting them to look at what films are on now.

      On scrolling down the customer are presented with the four films showing this week, below a small description ensuring the customer knows how they can proceed - Book the film, then go over to the vote page to vote for the next film and then learn more at the about page:
      (Scrolled down index link)

      The Call to Action buttons are below each film, along with a short description of the film and eye catching images. On clicking to see more details, they are sent to the book.html page. Below this is the footer which has the cinema address and social media links - this is present on every page.

      The next natural step is book.html. Coming here from the nav or hero calls to action brings the user to the top of the page
      (book top image)

      The user is encouraged to make their booking from the selection below and then afterwards head to vote.
      Below the hero image the user can see a peep of a 'book with us' section. On scrolling down (or clicking the 'more details' buttons on the home page) the user is given the essential movie details, an imdb link for further details, a fun film note and the ability to dropdown select the day and time. 
      (book films image)

      Both fields are required to proceed and on submission, the user is this case is presented with a new page which uses Code Institutes confirmation page as a stand in for the booking database. 

      Utilising either the navbar or the call to action at the top of the page, the new user can then proceed onto the vote page.

      (vote image)


    User B - Return Customer



  

