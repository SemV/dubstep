![dubstep](https://data.whicdn.com/images/57739397/original.gif)


[View website on Github Pages.](https://semv.github.io/dubstep/)

This website is dedicated to my love for dubstep, the music genre.

The purpose of this website is to showcase some of my favorite artists and tracks in the hope that people will discover a new genre they like. The site is mostly set out to entertain the audience and is targeted towards young partygoers who enjoy electronic dance music.

# UX

**User stories:**

- I want to get a good overview of the website and have no trouble navigating through it.
- If an artist caught my attention, I want to hear his music as quick as possible.
- I want to look at pictures and videos of events to decide if they are worth visiting.
- I want to be able to contact the author of the site.
- I want to follow the website's social media for more content.
- I want to view the site in Dutch.

**Wireframes:**

- [Desktop](https://i.imgur.com/oRnByBo.png)
- [Mobile view](https://i.imgur.com/5S4pFXK.png)

# Features

- Navigation bar - allows users to browse through the sections of the website.
- Soundcloud links - allows users to listen to my favorite tracks.
- Youtube links - allows users to see videos of events.
- Contact form - allows users to contact me.

**Features Left to Implement**

I think it would be cool if you could click on an artist cover and it would turn around, presenting a soundcloud (or other) iframe where you can listen the track. Some animations in or around the site heading could also be cool. Maybe even some sort of visual equalizer that is reacting to the music.
I also tried to adding background pictures to some of the sections but that would mess up the layout of the page. This is something that can be looked into later. 
Some copyright information in the footer could also be added.

# Technologies used

- HTML and CSS markup languages.
- [AWS Cloud9](https://aws.amazon.com/cloud9/).
- [Bootstrap](https://getbootstrap.com/) for the grid system.
- [jQuery](https://jquery.com/) for for the cascading navbar in mobile view.
- [Font awesome](https://fontawesome.com/) for the social media buttons in the footer.
- Google font for the [Montserrat font](https://fonts.google.com/specimen/Montserrat).

# Testing

I tested the website using Google Chrome (v75.0) developer tools on Windows and macOS at 1440p and lower resolutions. The following browsers were also used: 

- Firefox Quantum v67.0
- Internet Explorer 11
- Safari v12.1.1
- Microsoft Edge

I also used my Galaxy S8 and iPhone 6 to make sure the developer tools are not lying to me.

The site's HTML and CSS are validated by the [W3C validation service](https://validator.w3.org/).

<u>There are no known bugs.</u>

**Scenarios:**

- *I want to get a good overview of the website and have no trouble navigating through it.*

  1. Content on the site is placed logically.
  2.  The navigation bar sticking to the top makes it easy to go to any section regardless of where you are on the page. 
  3. In mobile view the navigation bar unfolds and retracts with a button.
  4. The dubstep site header shrinks in lower resolutions with the use of media queries.

- *If an artist caught my attention, I want to hear his music as quick as possible.*

  1. Artist covers are big and centered to draw attention.
  2. Clicking on the cover of an artist directs you to his music.
  3. Pictures shrink from 3 next to each on other on desktop view to 2 on tablet resolution and 1 on mobile view.

- *I want to look at pictures and videos of events to decide if they are worth visiting.*

  1. Pictures and video's in this section shrink accordingly.

- *I want to be able to contact the author of the site.*

  1. Submitting an empty form will trigger an error message. Every field needs to be filled in with at least one character.

- *I want to follow the website's social media for more content.*

  1. The social media buttons are clickable. They also have a title when hovering and change color. This makes for a good UX experience.

- *I want to view the site in Dutch.*

  1. The navigation bar provides a button for this.

# Deployment

The project was committed to a local git repository in the AWS Cloud9 environment. The repository was pushed to the master branch of a newly created github repository with the following command:

`git remote add origin https://github.com/SemV/dubstep.git`

I deployed this site on github pages as follows:

1. Sign in to github.
2. Select dubstep repository from the left.
3. Go to the settings tab.
4. Scroll down to the github pages section.
5. Select the master branch as the source.
6. The page is now now deployed.

Run this project locally:

1. [Go to my repository.](https://github.com/SemV/dubstep/)
2. On the right upper side of the screen click the green button 'Clone or download'.
3. Extract the ZIP and open index.html with your browser of choice.
4. The website is now running locally on your machine.

How to run this project in your own IDE:

1. Install git if you don't have it already.
2. Create a new workspace.
3. Clone my repository with the following command:

   `git clone https://github.com/SemV/dubstep`

# Credits

### Media

The pictures used in the artists section were obtained from the artists' soundcloud page. Here are the links per artist:
- [Code:pandorum](https://soundcloud.com/codepandorum/sets/gods-army-2) 
- [Calcium](https://soundcloud.com/calcium-dubs/sets/2018-free-dl)

- [Diskirz](https://soundcloud.com/diskirz/sets/sequence-ep-out-3-26-19-on) 

- [Samplifire](https://soundcloud.com/samplifire)

- [Mastadon](https://soundcloud.com/mastadontunes/sets/decimate-ep-out-now)
- [Virtual Riot](https://soundcloud.com/virtual-riot)

The images in the events section were obtained from the following links:

- [Rampage](https://www.festicket.com/nl/festivals/rampage/2019/)
- [Ignition](https://www.facebook.com/ignitioneventsnl/photos/a.273363119486773/559713754185040/?type=3&theater)


The GIF on top of this readme was obtained from [here](https://data.whicdn.com/images/57739397/original.gif).

