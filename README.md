# Ashley & Caleb's Wedding Website
## Video Demo
URL: https://youtu.be/NMQoV0ame5I
### Description
For my CS50 final project, I decided to build a wedding website for my upcoming wedding. I wanted to create something that I could
 actually use in real life instead of just building a random project. This website allows guests to find all the important wedding
  information in one place and also gives them a way to RSVP online.

The homepage introduces the wedding and includes a hero section with our names, the wedding date, and a welcome message. I also added a
 countdown timer using JavaScript that shows how much time is left until the wedding day. I thought this was a fun feature to include
  because it adds a little bit of interactivity to the page.

The website uses a navigation bar at the top so guests can easily move between different sections. These sections include Our Story,
Wedding Details, Travel information, the Honeymoon Fund, and RSVP. I used anchor links so that when someone clicks a link in the
navigation bar it smoothly scrolls to that section of the page.

The Our Story section briefly explains how my fiancé and I met and how we got to this point. I added this because a lot of wedding
websites include something like this and it helps guests feel a little more connected to the couple.

The Wedding Details section includes the most important information guests need to know, like the ceremony time, the venue, and the
dress code. I also added a link that opens directions to the venue in Google Maps so guests can easily find the location.

I also included a small Travel section for guests who might be flying in. It lists the closest airport, Orlando International Airport,
which is about 40–45 minutes away from the venue.

Instead of creating a traditional registry, we decided to include a Honeymoon Fund section. This lets guests contribute to our honeymoon
if they want to. The link opens in a new browser tab so guests can still easily return to the website.

One of the main features of the site is the RSVP page. Guests can enter their name, say whether they will be attending, list anyone
coming with them, and even request a song for the reception playlist.

When someone submits the RSVP form, the information is saved using the browser’s localStorage feature. This means the responses can be
stored without needing to set up a database. I also created a page called responses.html that retrieves and displays the RSVP responses
so they can be reviewed easily.

The website was built using HTML, CSS, and JavaScript. HTML is used for the structure of the site, CSS controls the design and layout,
and JavaScript powers features like the countdown timer and the RSVP form.

One of my main goals while building this site was to keep everything simple and easy to use. Since wedding guests can be from all
different age groups, I wanted the layout to be clean and straightforward so that anyone could find the information they need without
confusion.

In the future, I would like to expand this project by adding a real database for RSVP responses instead of using localStorage. Another
improvement I'm considering is adding a photo sharing feature so guests can upload pictures from the wedding.

Overall, this project was a fun way to apply what I learned in CS50 while building something that I will actually use for my wedding.
### Project Files

- *index.html* – Main homepage of the website containing the navigation bar and all main sections such as Our Story, Wedding Details,
Travel, and Honeymoon Fund.

- *rsvp.html* – RSVP form where guests can submit attendance information and song requests.

- *responses.html* – Page used to view RSVP responses stored using localStorage.

- *engagement.jpg* – Background image used in the hero section of the homepage.
