# 100 Days Of Code - Log

### Day 1: Tues 3rd January 2017

**Today's Progress**: Started FreeCodeCamp Wikipedia View challenge. Layout done and random button working.

**Thoughts:** Trying to use material design - not sure if it was worth using bootstrap as I've had to override a lot of its values.

**Link to work:** [Wikipedia Viewer](http://codepen.io/christie/full/dNyZMN/)

### Day 2: Wed 4th January 2017

**Today's Progress**: Continued FreeCodeCamp Wikipedia View challenge. Investigated API and got search results working.

**Thoughts:** Not sure if using API correctly or not - using search and then getting URL by just using given title. Still need to do clean up option for exiting out of then current search and style panels better. Also look at how I'm getting search input contents, I've having to seperately handle an enter press and a button press which I think should be simplier. 

**Link to work:** [Wikipedia Viewer](http://codepen.io/christie/full/dNyZMN/)

### Day 3: Thurs 5th January 2017

**Today's Progress**: Continued FreeCodeCamp Wikipedia View challenge. Functionality and some error handling added.

**Thoughts:** Think I've improved on UX of original by providing feedback when search term is blank or search returns zero results. I think it now meets the requirements of the challenge, however page results are long, think I might want to dearrange how results are shown in the panels.

**Link to work:** [Wikipedia Viewer](http://codepen.io/christie/full/dNyZMN/)

### Day 4: Fri 6th January 2017

**Today's Progress**: Picked up FreeCodeCamp TwitchTv challenge again. Returns logo and stream info.

**Thoughts:** I started this a while ago but got confused when it stopped working - there is now an update on how to get round this on FCC. I got it working again and havemoved from having the users listed in the html to being created programatically. This means FreeCodeCamp is currently lower case and I need to get the proper display name from the returned json instread(TODO). I haven't styled it at all yet so it looks very basic.

**Link to work:** [TwitchTv JSON API](http://codepen.io/christie/full/zKqNag/)

### Day 5: Sat 7th January 2017

**Today's Progress**: Added returning of the users icon and display name. Started styling.

**Thoughts:** Learnt that you can't do border radius on a tr only the td'd within it, so to create a table row that looks like it has rounded edges need to style first and last td child of the tr.

**Link to work:** [TwitchTv JSON API](http://codepen.io/christie/full/zKqNag/)

### Day 6: Sunday 8th January 2017

**Today's Progress**: Minor styling. Added buttons to toggle between all/online only/offline only.

**Thoughts:** Getting radio buttons in to choose between online/offline was easy to do with Jquery, just needed to have some classes on to identify which was which, but I'd added these today so I could differentiate byt coloured background. This didn't look to be a requirement of the project but they had done it in the example. The styling is OK but I think I could do better, but for now I'd prefer to move on to a more interesting project (the difficult bit/learn for this task was getting the return from the API which is in).

**Link to work:** [TwitchTv JSON API](http://codepen.io/christie/full/zKqNag/)

### Day 7: Mon 9th January 2017

**Today's Progress**: Picked up FreeCodeCamp Pomorodo clock again.

**Thoughts:** Started again getting an arc border to fill on a timer. Have just got circle arc stopping and starting, need to fit this into the rest of the clock section next.

**Link to work:** [Pomorodo clock](http://codepen.io/christie/pen/PWPRwN/)

### Day 8: Tues 10th January 2017

**Today's Progress**: Updated portfolio for FreeCodeCamp challenge on CodePen.

**Thoughts:** Set up a Cloudinary account to host assets. Took pictures of completed projects to update portfolio (was previously using placeKittens). Some of the earlier FCC challenges I completed look to have stopped working - may need to go back and look at the Weather App and quote generator.

In general the challenges have quite different looking UI's. I'd like to bring the look and feel of them together to give a more unified feel.

**Link to work:** [FreeCodeCamp Portfolio](https://codepen.io/christie/full/QKyAwP/)

### Day 9: Sat 21st January 2017

**Today's Progress**: Started Google's [First Progressive Web App](https://codelabs.developers.google.com/codelabs/your-first-pwapp/#0) codelab

**Thoughts:** Slow progress - think I managed to get my enviroment into an inconsistent state (managed to get undefined into the cached json). Managed to clear up when I cleared the data out.

**Link to work:** [Weather PWA](https://weatherpwacodelab.firebaseapp.com/)

### Day 10: Sun 22nd January 2017

**Today's Progress**: Contined First Progressive Web App Codelab

**Thoughts:** Only got basics covered in tutorial working. There we more learning points e.g. minifying the CSS and using indexDB that I should look further into. Have had problems deploying to Firebase - I seem to have deployed something but can't see what files it's deployed in the Firebase console and it doesn't need to be working.

**Link to work:** [Weather PWA](https://weatherpwacodelab.firebaseapp.com/)

### Day 11: Sat 28th January 2017

**Today's Progress**: Started Udemy course [Angular Zero to Hero](https://www.udemy.com/angularjs-from-zero-to-hero/learn/v4/overview)

**Thoughts:** First time with Angular, taking a while to go through trying to understand what I'm doing. Watched form validation section.

**Link to work:** [Form Validation Codepen](http://codepen.io/christie/pen/d8f4d1420ad4862704f5f9598364b170)

### Day 12: Sun 29th January 2017

**Today's Progress**: Continued [Angular Zero to Hero](https://www.udemy.com/angularjs-from-zero-to-hero/learn/v4/overview)

**Thoughts:** Set up codepen to do my own version of form - considering what you would want for a cafe table reservation form. Have had a bit of trouble getting checkboxes to work as I wanted; I has trying to get an array with those ticked as values in it, rather than true/false for each attribute. There did look to be a directive [checklist-model](https://vitalets.github.io/checklist-model/) that did this but I couldn't figureout how to get it into codepen, need to have another look at this.

**Link to work:** [Form Validation Codepen](http://codepen.io/christie/pen/d8f4d1420ad4862704f5f9598364b170)

### Day 13: Mon 30th January 2017

**Today's Progress**: Eventually got the hosting working on Weather Progressive Web App

**Thoughts:** The [tutorial](https://weatherpwacodelab.firebaseapp.com/) isn't clear what options you need to select to deploy to Firebase. Originally I started trying to init from the folder I wanted to deploy but I hvae eventually got it working by deploying from above folder and listing work as the public folder. I like that Firebase makes https hosting easy but I find the console confusing; I am unclear how you can see what files you've actually deployed.  

**Link to work:** [Weather PWA](https://weatherpwacodelab.firebaseapp.com/)

### Day 14: Sun 5th February 2017

**Today's Progress**: Working through Udacity course [Angular Zero to Hero](https://www.udemy.com/angularjs-from-zero-to-hero/learn/v4/overview)

**Thoughts:** Working through list app alone with the tutorial. Would prefer it if the course had challenges to go off and create something. Going to use what I've learnt here to do an angular todo app. 

### Day 15: Thur 9th February 2017

**Today's Progress**: Started todo app on codepen using AngularJS

**Thoughts:** Slight confusion as Codepen have changed there defualt Bootstrap from V3 to V4. Getting used to doing everything in an angular way, i.e. binding, rather than grabbing things out of the DOM myself is taking a bit of getting used to.

**Link to work:** [Todo app on Codepen](http://codepen.io/christie/full/3b31571a6a6f7177cecaaf54aafcd17b/)

### Day 16: Sun 11th February 2017

**Today's Progress**: Basic Todo app working

**Thoughts:** Worked out basic adding and removing elements wiwth Angular. I want to make a more advanced version, multiple lists etc and then build it into a progressive wep app. Probably want to start with designing what it will look like - the basic version I've got now is very rough in Bootstrap just so I could get my head around Angular.

**Link to work:** [Todo app on Codepen](http://codepen.io/christie/full/3b31571a6a6f7177cecaaf54aafcd17b/)

<!--- ### Day 0: February 30, 2016 (Example 2)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link(s) to work**: [Calculator App](http://www.example.com)


### Day 1: June 27, Monday

**Today's Progress**: I've gone through many exercises on FreeCodeCamp.

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.

**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence) --->
