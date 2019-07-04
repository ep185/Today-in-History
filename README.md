# Today-in-History

The main purpose of this website is for it to attract a user who has a interest in history or is drawn into the website to find out what events took place today in the past. They will then, hopefully, subscribe to our website so that they can receive newsletters every week giving them a timetable of the events that have happened and the main event the website will be covering.
Today in History Website will tell you what events happened today in the past and provide podcasts, Videos and magazine on the events that took place on this day throughout history. 

The example day that I am using is for the 18 June with the main event being the battle of waterloo that took place on that day. As this is the main event the user will be directed to the first image and text giving a general overview of the event. Will then provide links to see a video and a podcast relating to the main event.
There will be 3 minor events that will aslo be included that hopefully they have not encountered before and the website will provide either a podcast and a documentary video on the subject or at least a video for them to learn more. 

# UX

My goal is to design a website that provides interesting fact about events that took place without bombarding them with to much text that could result in the user getting bored.
As the user progresses down the page I want to provied the user with quick and easy way of learning about different events. First they will focus on the main event, in this case is the battle of waterloo,
and they will hopefully be drawn in by the other events which will keep their attention as the head down the page. As they reach the end of the website they will hopefully subscribe to the 
website which will provide them with daily headlines about the new content that the website will provide.

For a casual user who enters the site for the first time i would like them to see the main event in a large photo that took place on this day and then press the read more button that will take them to the description regarding this event.
Then once they have read about the event they will have the option "for the main event" if they would like to learn more there will be buttons at the end of the article to take them to either the watch or listen sections to learn more. Hopefully they will find
the website interesting and click the subscribe button on the navbar that will remain fixed to the top.

Another experience is that someone once they are at the landing page is only interested in watching video about the event so will press the watch item on the navbar that will direct them to their desired destination.
But as the navbar will remain fixed and therfore follow the user they will be able to navigate to different sections.

Want the user to be drawn in by the photos and the video's/podcasts whilst keeping the amont of text to a minimum to help the website feel less cluttered.

Please look at the wireframes for the website below (https://wireframepro.mockflow.com/view/M1f98d5950d990a46260f8e82a8f8bb5d1560703082215#/page/bdf4310e165641e990fff6f5492edd99).


# Technologies

1. HTML
2. CSS
3. Bootstrap (4.3.1)

# Features

* Will provide a fixed navbar that will provied easy navigation of the website, with a subscribe button so they can subscribe to the website at any time.
* A read more button on the landing page to immediately take the use to the main event .
* Buttons on each title event to direct the user to an outside document goint into more detail regarding the event.
* First podcast that allows the user to listen to the speech with a quote from the speech beside it (or under in on the mobile)
* Will show the user an image with some description describing the contents of this month's magazine (subscribe button on the navbar will provide a check box so that we can email the user about how to set up a magazine subscription)
footer that will show today in history's email contact and contact numbers which the user will be able to click for easy use and will also include social links.

## features left to implement.
* create links to full articles regarding events so that the user can read about the event in more detail.
* include some outside links to further articles.
* be able to add social media accounts behind the social links button.
* more advanced forms allowung the user to purchase magazines from the website.
* create and archive of articles, videos and podcasts to allow the user to see more events.
* main front screen of the website will be a taster of content for today and the user will have to subscribe to unlock more content.

# Testing
As this website has been deployed via github it does not support internet explorer which makes the website unavailable on this browser
The ability for the user to go straight from page to other sections of the website has been acheived. Have tested the nav links on all web servers and they worked correctly.
It does not cause any slowdwons or errors if the user uses the back or forward button and does not cause any unresponsive pages.

Tested the subscribe button to make sure that it remains in the navbar on both mobile, ipad and desktop. whist testin the subscribe button on the mobile it would 
join the dropdown list with the other nave items, this requried me to fix the position of the subscribe button by adding *"position:fixed; right: 75px; top: 8px;"* for all screen resolutions to prevent it 
Also had a problem with the subscribe button as when the navbar was orginally fixed to the top it would open but be greyed out and you were unable to close it. This reuired me to add the *.modal-backdrop {position: unset !important;}* properties
to allow the form to pop up.

The form on the subscribe button has been tested on mulitple browesers. It prevents the user from submitting the form withou filling in the email address and the 2 paswwords, on chrome 
there will be a pop up saying please fill out this field - whilst microsoft edge it will hightlight the content green if completed correctly and red with text reminidng the user that
this needs to be filled in. **The checkboxes are optional as this is to provide the user different options for additional content and therefoe do not need to be filled in.**

# Deployment
I have deployed the site directly from the master branch on the github website, which required me to call my landing pgae index.html so it would deploy correctly.
I also have changed the name of the branch master from origin to history to give my github page a flavour of the website theme.

The repository website is under name `http://ep185.github.io/Today-in-History`. This can be cloned to your repository by adding `git clone http://ep185.github.io/Today-in-History`
and if you want to break from my git hub page you will need to `git remote rm history` not `git remote rm origin` as mentioned above I have changed origin to history in keeping with
the theme of the website.

I deployed my website by going to my repository for Today in History on Github, then I selected settings on the options below `ep185/Today-in-History`. Then i scrolled down to the *GitHub Pages* section
and clicked on the dropdown list below _source_. There I changed it from none to master branch which published my website under `https://ep185.github.io/Today-in-History/`.

# Media
All the images where found from google searches on the topics in question.
All the videos on the website come from different youtube channels
* egyptian revolution from jehan 345
* battle of waterloo from Epic Histoy Tv
* Tang dynasty from the very good Kings and Generals channel
* Finest hour speech from Warllam Stureon channel.*

The audio podcasts also came from youtube which I converted to mp3 format by using 4k youtube to mp3 converter.

# Acknowledgements
* Got my topic ideas from https://en.wikipedia.org/wiki/June_18 and copied the text for the egyptian revolution from there aswell.*
* Used the text for the Battle of Waterloo card from https://www.britannica.com/event/Battle-of-Waterloo.
* Used some text for the Finest Hour speech from https://www.cfr.org/blog/twe-remembers-winston-churchills-finest-hour-speech
* Used similar code for the social links as that used in the resume project - used similar class name and css properties
* Used Footer template from similar code and css https://codepen.io/scanfcode/pen/MEZPNd and  https://bootsnipp.com/snippets/2eMK5
* Used text from website https://www.historyextra.com/period/second-world-war/8-historical-events-that-happened-in-june/ for magazine events.
* got favicon image from https://www.freefavicon.com/freefavicons/objects/iconinfo/black-and-blue-globe-152-243993.html
* Used subscribe form from https://mdbootstrap.com/docs/jquery/modals/forms/
* Used https://www.youtube.com/watch?v=kEf1xSwX5D8 to add my favicon
* learnt how to make my youtube videos responsive by watching https://www.youtube.com/watch?v=9YffrCViTVk*