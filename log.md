# 100 Days Of Code - Log


### Day 64: June 17, 2019 Monday

**Today's Progress**: Just did some interactive reading of Eloquent JavaScript. I also picked ahead into the HTML course/lesson by Mozilla. They're going to go over forms and validation. Until I get to that I'm going to hold off on it for my app(s).

**Thoughts** None.

### Day 63: June 16, 2019 Sunday*

**Today's Progress**: So I didn't do any "formal" studying today or yesterday. I tried to do some more validation. I put `.includes()` in my code for name.js. I'm thinking name.js is really my pilot app for the todo list and my website. I use it to test things. 

I also wrote my first JS for loop since the the todo list tutorial. It includes `.includes()` This added code makes sure the user's name isn't all spaces. So they can have a name like "J" and still pass. If it's " J" JavaScript or the browsers ignore the spaces before the letter anyways. Even in the old code it would pass it but ignore it. The problem is it doesn't ignore all the spaces behind the visual characters(letters, numbers, punctuation). If you have "J   " it will render "J ". 

I remember from class, at least in Python, you could bring in code for the alphabet called ascii or something like that.

**Thoughts** I'm calling it quits today. Back tomorrow!

**Link(s) to work**
[validation preventing all spaces in input](https://github.com/iamvalecia/name.js/commit/8650c5cbf26a0196343b175e2193dee7ae073219)(changes in log entry. I committed it late.)

### Day 62: June 14, 2019 Friday

**Today's Progress**: I realized that I do not have all the features of the original todo app. This new one can not toggle all. That's okay. `document.getElementsByTagName` and anything other than `document.getElementById` aren't working like I think they should, thus I can't make a solution. That's okay, too, I suppose. Since I have just now realized it, it must not be something that's needed. Besides I feel good when I check things off my todo list. And toggle all ruins that. 

Made two more commits today.

The above code didn't work on any other functions I tried them with either.

**Thoughts** Hoping to do some studying tomorrow...Before that I just need to add a minimum word count to this.

**Link(s) to work**
1. [added function editCompleteKeyDown(e)](https://github.com/iamvalecia/todo-list/commit/19da3b8f6c88a714b9a897b2d87c37e518a6923a)(latest commit)

### Day 61: June 13, 2019 Thursday

**Today's Progress**: I'm almost done with my todo app. It functions exactly like the first one. You can add, change, and delete todos. It's just more user friendly in my opinion. 

I would love to add drag to the list items but I find it too complicated at the moment. I saw some code on codepen for `<li>` and it was 75 lines long! Yeah, I could copy the code into my app, but I would like to have a better grasp of it. And having a good grasp of 75 lines in one day isn't happening. It didn't happen.
  
Today I found a function via a website, via a contribution on stackoverflow, that allows you to put html entities/utf-8 characters into your document via JS. It's only four lines and I can explain it. Perhaps not the best explanation, but I can. I don't feel guilty for copying it, unlike how I would have felt if I copied the drag and drop code. By the way I want drag and drop to allow users to reorder their todos.

The only JS I have left in the near future is to add keyboard controls. And I already know how to do that!

Then the only thing to do is aesthetics. Even when I do that I have a ways to go in my CSS skills to make it look good on different size screens and windows.Even now when HTML elements change because of JavaScript things might move to the next line. I don't know when I'll be able to fix things like that.

**Thoughts** I sure used via a lot here. Just realized my first and last sentences of my progress contradict each other. Let me clarify. This will continue to be a work in progress as I learn more stuff. But I am approaching a checkpoint. Once I cross it this won't be a daily project, because I will be learning more stuff. Also at this approaching point I wouldn't mind showing it off to certain people.

**Link(s) to work**
1. [added ondblclick](https://github.com/iamvalecia/todo-list/commit/cef480741e594af0d9c5c497d15bd7d9eeaa37a2)(latest commit)
2. [Decoding HTML entities with vanilla JavaScript ](https://gomakethings.com/decoding-html-entities-with-vanilla-javascript/)(resource)
3. [Drag & Drop List Items](https://codepen.io/retrofuturistic/pen/tlbHE)(resource)

### Day 60: June 12, 2019 Wednesday

**Today's Progress**: Yesterday I just read about binding from Eloquent JavaScript, the book. It didn't amount to an hour.

Today I worked on my todoList app. I made a new branch for its repository. It felt like the right thing to since I'm totally revamping the code, but I'm not quite sure. Especially now since git put the old files in the new branch. I've already read about drag and ondblclick. So I will incorporate that later. 

**Thoughts** Today was good. 60% done with this challenge!

**Link(s) to work**
1. [changed CSS and JS for edit and delete buttonss](https://github.com/iamvalecia/todo-list/commit/6c04620d8518b9454fdbad4759923a7ca4686aac)(latest commit)

### Day 59: June 10, 2019 Monday

**Today's Progress**: I did some reading and practice on HTML. Nothing's wrong with name.js as I mostly thought. It worked fine for me today and my tester(s). Strange. Got a little CSS tip from slack.

**Thoughts** Not very productive.

### Day 58: June 8, 2019 Saturday

**Today's Progress**: I did some reading and practice on HTML and JS.

**Thoughts** Going to construct my question for someone who is going to help me on Slack.

### Day 57: June 7, 2019 Friday

**Today's Progress**: I played around with my name.js code. It's still not working. I'm using similar code on my site and it's working on everything except Microsoft Edge; all I need was change some things as it still functions the same. I am baffled. Was there some kind of update? I reached out for help. 

I also read about HTML from Mozilla.

**Thoughts** I feel like that programmer meme.

### Day 56: June 6, 2019 Thursday

**Today's Progress**: I'm convinced my programs don't like me. Nothing's working except the todo list.

**Thoughts** I will probably focus on learning content tomorrow.

### Day 55: June 5, 2019 Wednesday

**Today's Progress**: This update is a day late, again.

Sometimes you just have to be comfortable in your code.

I was working on some code in one file. It was my todo list, seeing what worked and how it worked. So I decide to copy and paste everything into a new file. I deleted everything that I didn't need in the new file. I did this because I wanted to preserve all the things I was playing around with in the old file.

So in the file I realize a couple variables in my code would need to be global variables. So I make them such, but now the function(s) won't work. I try and try and waste time. I then go back into the old file, make the same changes, and it works! What gives? So I think I had to `save as` the old file along with the css and html for it to work. But even then it gave me a red squiggly line on a line of code in the new, no squiggly line in the old. But when I took a break, shut the computer down, and returned there was no line. However, I now had "errors" in my CSS. They are no longer there now(Thursday). 

I just wanted to document the above.

This doesn't help me clear local storage on name.js either. `window.localStorage.setItem('name', '');`  On the todo list I don't need this, so I'm considering changing my name.js code to be like the todo list.

**Thoughts** Be confident.


### Day 54: June 4, 2019 Tuesday

**Today's Progress**: I am making this log entry a day late.

Worked on my todo list. But I'm not using the model I already have. I nearly started from scratch. I'm adding things to my list without objects and arrays, sort of how I'm working with the DOM on name.js. Actually on my site I'm doing name.js with local storage. So my todolist is more like that in my opinion. 

I did try to modify the old todo list, but I couldn't figure out how to modify the UI/UX position number. Now I feel like old the todolist has everything it needs to function as a todo list, but maybe too much. Do you really need a toggle like that? I'm grateful that in making it, it taught me about JavaScript.

I will commit soon.

**Thoughts** :-)

### Day 53: June 3, 2019 Monday

**Today's Progress**: Had some fun with my website. Yesterday I learned about local storage so I added that to my site. The frustrating part was getting it to work with input and modifying the DOM then fixing the CSS. But I got it to work and look good if I say so myself.

Two methods didn't work for me. `localStorage.clear()` and `localStorage.removeItem()`. I just declared a variable in a function to get around it.

I read a lesson by Mozilla about how the web works. The recommended reading at the end of it looks good, so I'm saving a link to it.

**Thoughts** Today was fun.

**Link(s) to work**
1. [How the Web works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)(lesson)

### Day 52: June 2, 2019 Sunday

**Today's Progress**: Made headway on an old repository. It was a really simple fix. I just needed one line of code. I thought I wasn't grasping something new, but it was a beginner oversight. A function can't run unless it's called. 

I worked more on my site. I am going through the Mozilla 'Learn Web Development' lessons from beginning to end. 

**Thoughts** I fill proud of myself. But I still feel like I waste so much time on simple things.

**Link(s) to work**
1. [successfully added keyboard control](https://github.com/iamvalecia/name.js/commit/bb9fdc20cadac19318f4a898fa91e850e0f14db1)

### Day 51: June 1, 2019 Saturday

**Today's Progress**: I saw that providing the initials from a string was a common challenge, so I decided to work on that before work in JavaScript. I've already done it in Python.

I also read the webfonts article. I decided to put it in the vault until I'm ready for it.

I did the JS portion of the video series. I tried to do it solo before watching, but I didn't know how. Some of the stuff, I think, could be done like my todo list. Even after watching I still don't understand. But it was a 45 minute JS lesson trying to teach shopping cart.

**Thoughts**: Still laying out the plan for the next 50 days. I also started my website coding.

### Day 50: May 31, 2019 Friday

**Today's Progress**: I am done with the CSS portion of my band site. I've also found two useful search terms for my CSS problem. 

`responsive web design`
`css consistent across browsers`

I looked at a source which came from the latter search and it mentioned things like viewport and width: device-width. I remember those from a Phaser tutorial.

**Thoughts**: Once I finish this I'm not sure what to do next. I have a couple of options in mind. I don't know which to pick first.

### Day 49: May 30, 2019 Thursday

**Today's Progress**: More CSS. I thought I knew better than the instructor when I applied HTML elements to my content, so while doing the CSS, to get things to work, I had to redo the tags.

On slack I got a link from someone on CSS consistency across browsers. I haven't looked into it yet. Hopefully he can help me as I do.

**Thoughts**: Almost done with my band site!

[How to load web fonts...](https://www.freecodecamp.org/news/web-fonts-in-2018-f191a48367e8/)(link from slack, haven't attempted yet)

### Day 48: May 29, 2019 Wednesday

**Today's Progress**: I did not meet my goal set on Day 46. I did some more CSS.

**Thoughts**: Having things not look the same across browsers is getting frustrating. 

### Day 47: May 28, 2019 Tuesday

**Today's Progress**: I've been studying CSS the last couple days. The good: I made a really nice-looking page. The bad: Even with the studying I can't get CSS to load in my Phaser game properly and consistently.

In my tutorial the guy imports a google font. I had been embedding it the standard way with this in the  head of the html.

` <link href="https://fonts.googleapis.com/css?family=Press+Start+2P&display=swap" rel="stylesheet"> `
According to Google this goes in the stylesheet CSS:

` font-family: 'Press Start 2P', cursive; `
But there's a place to declare font-family in the game.js file. So I have two declarations.

Today I tried importing with this in the stylesheet:

` @import url('https://fonts.googleapis.com/css?family=Press+Start+2P&display=swap'); `
No avail. Same inconsistencies. I'm sure I tried before, but maybe I should do it with an actual CSS file next. Though I don't see it making much difference; but you never know.

But it works great in my webpage! I've already sort of mentioned that.

**Thoughts**: Gotta keep going. Keep reading. Keep listening. Keep studying.

### Day 46: May 27, 2019 Monday

**Today's Progress**: I worked on CSS for this band site in the YouTube tutorial I was doing earlier in the challenge.

**Thoughts**: I've been doing this series of videos for too long. It's my goal to finish it my the end of Wednesday. 

### Day 45: May 26, 2019 Sunday*

**Today's Progress**: I'm still taking a break from my game. I decided to work on Web Dev, CSS to be more specific. I'm also planning how I want my portfolio site to look.

**Thoughts**: I've imagined a portfolio site for a while now. But now I'm actually planning it and drawing it out. It's getting real.

### Day 44: May 24, 2019 Friday

**Today's Progress**: I'm making this entry a day late.

I read two lessons on web dev. I also did some quick experimenting with my game. The commit on Day 43 - May 23 didn't need a refresh to load the text. It did it on the first try.

I added the css attribute to the html file, not committed yet. It didn't seem to help consistently, especially  across browsers. That's something I want to learn. Keeping things the same across browsers as much as possible. Sometimes when it loads on the first try it's not the correct font-style.

**Thoughts**: None.

**Link(s) to work**
1. [Webpages, Website, Server, & Engine](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines)(lesson)
2. [What is a web server?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_web_server)(lesson)


### Day 43: May 23, 2019 Thursday

**Today's Progress**: To turn my asteroid into an explosion I added to the asteroidExplosion(); I added a spritesheet. **One of the problems** is that the explosion sprite won't collide with the ground. It falls off the game area. The **second problem** is that my font style loads to another style. I don't know what those two things have to do with one another. The **third problem** is that whenever I try to fix things I get an error message, mostly referring to line 255 in the commit. 

So asteroid.disableBody works in the commit. But if I tried to fix any of the problems, it would say that it wasn't a function or asteroid(s) was simply undefined. Maybe Phaser/JS doesn't like how I added the asteroid or the explosion. 

I've since went back to the sixth commit before the asteroids to try to work on gameplay and actually making it look and perform nice. 

**Thoughts**: Tomorrow I'm going to take a break from my game. Maybe I will play some games. I will do basic JS stuff.

**Link(s) to work**
1. [added explosion, explosion won't collide and font style is off](https://github.com/iamvalecia/save-a-dino/commit/e6f4e78977e782679a0059eea85dff0b4da2e3df)(with explosion sprite)

### Day 42: May 22, 2019 Wednesday

**Today's Progress**: Yesterday I said that I sort of regretted going with Phaser 3 instead of an earlier version. I still sort of do. I'm managing with docs and examples, or labs as they call them. One example on events led me to adding a loop event for my asteroids. I still need to mess around with numbers. Then again I have a lot of things to mess around with for my game.

I've played around with the source code for the Phaser tutorial. That was fun making the game extremely difficult.

**Thoughts**: I **think** I've almost incorporated everything I need for my game. This isn't referring to being done, just all the tools I might need from Phaser and JS. I know I have a ways to go before completion. Time will tell.

**Link(s) to work**
1. [added asteroids with .addEvent loop](https://github.com/iamvalecia/save-a-dino/commit/7b79680d3a12775560044d6c49ef786898f17514)
2. [Looped Event](http://labs.phaser.io/edit.html?src=src\time\looped%20event.js)(example)


### Day 41: May 21, 2019 Tuesday

**Today's Progress**: The font spritesheet that I intended to use is no longer on the table. I ended up finding a really good font at google. 

I started to add asteroids to my game. Hopefully an organized commit will come tomorrow.

Also I wanted to add that yesterday when dealing with my heart animating, I learned that 165 is different from 164.333. That's what kept my heart from animating.

**Issues** It takes a reload to see healthText; it's not there on the initial load of the page. But maybe I can find a way to preload. That seems to be the way. I just thought of it, so I haven't tried it.

**Thoughts** I'm starting to think programming with Phaser 3 instead of an earlier version was a bad idea. There's tons of info on earlier versions. Plus My code is 250 lines at the moment. It's getting to be a lot to handle.

**Link(s) to work**
1. [added healthText](https://github.com/iamvalecia/save-a-dino/commit/768540c375b7824e79fc5949eebd2def00e05a2c)

### Day 40: May 20, 2019 Monday

**Today's Progress**: I made two commits on game today. The first one I was able to get the health meter animating correctly. I have some test code in it now since I haven't finished the game plans.

My second commit was flipping my dino and manuevering him left.

Also today was at least the secoond day of looking at Phaser documentation. I still often end up finishing my search with an answer on a forum, because I don't understand how it's given in the docs. Or sometimes, like yesterday, I can find something more official but it's for Phaser 2.

Right now I'm trying to use a sprite of text to put into my game, instead stright text. But I might not work on that tomorrow.

**Thoughts** Life's good.

**Link(s) to work**
1. [health meter is spritesheet, no freeze](https://github.com/iamvalecia/save-a-dino/commit/ffc0c31b5ac9228bbcb57f6d39d202282213ed0e)
2. [dino can move left](https://github.com/iamvalecia/save-a-dino/commit/19965d69c5e5d719fe93cbd678d0071dd9f4bfec)

### Day 39: May 19, 2019 Sunday

**Today's Progress**: So I want a health meter for my game instead of a scoreboard. The health meter will use hearts. I needed a way for the hearts to remain static in the top left corner, yet animate to the different frames. Putting it in a static group didn't work. But I found out that I could adjust the gravity on it specifically. I just had to figure how to do. 

These DID NOT WORK.
- //heart.body.gravity.y = 0;
- //heart.setGravityY(0);
- //heart.body.setGravityY(0);
- //heart.setAllowGravity(false);

This one DID WORK.

- heart.body.setAllowGravity(false);

Also the .disableBody() method appears to be only for dynamic sprites.

So now my dino can collect food with the heart meter. In my last commit(May 18) whenever he overlapped with food he froze. Other tries had everything falling off game area. However, the meter isn't animating correctly, though it is animating. I will fix it.

I will commit tomorrow.

**Thoughts** I am so happy about that. 


### Day 38.5: May 18, 2019 Saturday

**Today's Progress**: No coding today. And I don't think I read or studied for an hour. I read about local servers and how the internet works. I opened my dino game using a server that came with my Python installation. I still don't completely understand how a Phaser game I downloaded can only be opened on a server, but the game I created can be opened as a local file. And since it can be opened as a local file then why is it recommended that set up a server.

**Thoughts** I may have to go over this a lot.

**Link(s) to work**
1. [Setting up local testing server](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/set_up_a_local_testing_server)(lesson)
2. [How the internet works](https://developer.mozilla.org/en-US/docs/Learn/How_the_Internet_works)(lesson)

### Day 38: May 17, 2019 Friday

**Today's Progress**: Thanks to some advice that put me in the right direction I was able work through a phaser animation for with I was having problems. So that was a good thing! To accomplish it I created two variables but after commiting the changes I found that I didn't need them. So they may get axed. 

Also these animations aren't perfect. They just work.

**Thoughts** The advice came from Phaser's forum. Glad someone answered my question.

**Link(s) to work**
1. [Save-a-Dino](https://github.com/iamvalecia/save-a-dino/commit/36d0d84f530496ab712ce248f0004d13bd09bc39)

### Day 37: May 16, 2019 Thursday

**Today's Progress**: I commited some changes to my game. The changes are from a day or two ago. I haven't pushed them yet. I worked some more on my game. 

**Thoughts** I am frustrated because I can't animate things the way I would like.

### Day 36: May 15, 2019 Wednesday

**Today's Progress**: I searched for answers about my jump animation problem from Day 34. I couldn't find one. I asked for help avenues but no reply yet. I got just a little more done on the game. Mostly just a bunch of trial and control-z.

**Thoughts** I think I wasted time looking for help when I should have just going.

### Day 35: May 14, 2019 Tuesday

**Today's Progress**: I worked some more on my game. He's collecting food now.

I have some experience with servers, not a lot though. Every Phaser tutorial says to set one up for the game for security reasons. But I think they leave out some steps after the server recommendations and download. I did notice a difference between my files and files from others. I tried to follow through with the suggestion but to no avail. 

Also I submitted my first README. It's for my todoList.

**Thoughts** Still fun.

**Link(s) to work**
1. [Todo-List README](https://github.com/iamvalecia/todo-list/blob/master/README.md)

### Day 34: May 13, 2019 Monday

**Today's Progress**: After last night's update I did manage to load my spritesheet. Funny thing is the solution looks similar to something I had already tried. Maybe I was missing something really small or the page needed to reload.

Anyways I got the little guy moving and jumping. I'm following along with a different tutorial. I'll be making my own game as I follow along. Of course, when the tutorial is over it'll be up to me to finish the specifics of my game. It's going to be called Save-A-Dino, or something to the effect. I tried an animation for his jumping, so that he can have a different motion rather than him remaining in the same pose while moving up. This wasn't in the tutorial, but it seemed easy to create on my own. But I couldn't get it to work.

I pushed two things to github -- the game and an old todo list. The todo-list is in JavaScript. I don't want to forget the roots of JS! Plus this is in need of a retouch.

I will be adding readMe files soon.

**Thoughts** This was a good day.

**Link(s) to work**
1. [Save-a-Dino](https://academy.zenva.comhttps://github.com/iamvalecia/save-a-dino) 
2. [Todo-List](https://github.com/iamvalecia/todo-list) 
3. [Phaser.io Tutorial](http://phaser.io/tutorials/making-your-first-phaser-3-game/part1) (tutorial)

### Day 33: May 12, 2019 Sunday

**Today's Progress**: I tried to incorporate a spritesheet, not just a sole image, into my code. I wanted the appearance of movement. I couldn't get it to work. I'm still trying at the moment. Maybe I will get it tomorrow. #Phaser

**Thoughts** The more I read, the more their knowledge will become my own.

### Day 32: May 11, 2019 Saturday

**Today's Progress**: I continued to work through the Phaser game tutorial. 

**Thoughts** I'm thinking of ways to branch out from tutorials once I'm done with this. I want to know that I know it.

### Day 31: May 10, 2019 Friday*

**Today's Progress**: I was working on Phaser tutorial. I wanted to know what made a picture a sprite, so I ventured out and made my own. It happens to look just like a simple square. That's okay for now. 

**Thoughts** This seems fun...Also I need to finish listing my new plans and meaningfully work on them.

**Link(s) to work**
1. [Frogger Game](https://academy.zenva.com) (tutorial)...I will try to find direct link to free tutorial.

### Day 30: May 8, 2019 Wednesday*

**Today's Progress**: I looked into Phaser again. I just followed along a video introducing it. I also started to put together new goals for the remainder of the challenge and revisited old code. 

**Thoughts** Let's have some fun.

### Day 29: May 6, 2019 Sunday

**Today's Progress**: I forgot to update for May 6. I did some more SQL problem queries. I solved them, but I don't think I did them efficiently.

**Thoughts** Time will tell how well I solved those problems I suppose. I probably will have pages of code when others have three lines.

### Day 28: May 5, 2019 Sunday

**Today's Progress**: I worked on some SQL query problems. One that challenged me was combining join, count, and where.

**Thoughts** I did okay with the time that I had today.

### Day 27: May 4, 2019 Saturday*

**Today's Progress**: Yesterday I skipped. Today I got in some time on my band website, the site I'm building for web dev YouTube tutorial. It's by a guy named Kyle, the same man whose tutorial I used for SQL. I also worked a little on classwork. Going to combine SQL with Python finally.

**Thoughts** I would have been really proud of myself if I had coded more after work. I managed to code before work. 

**Link(s) to work**
1. [Intro to Web Development](https://www.youtube.com/watch?v=HfTXHrWMGVY&list=PLZlA0Gpn_vH-cEDOofOujFIknfZZpIk3a) (tutorial)

### Day 26: May 2, 2019 Thursday

**Today's Progress**: Trying to get back in sync with LC101 curriculum. Finished up SQL basics. Laying out plan to complete my next assignment. Also looking into SQL hosting.

**Thoughts** I wasted a lot of time on the class resources for SQL. YouTube did me fine. But I may still need to fill in the gaps on things the video didn't cover as to not be behind my classmates. The video was really good though.

### Day 25: May 1, 2019 Wednesday

**Today's Progress**: Worked with the youtube video from yesterday. Also set up the environment for my classwork in the recommended server. 

**Thoughts** I feel so much more confident with SQL now. I also like the server used in the YouTube tutorial better.

### Day 24: April 30, 2019 Tuesday

**Today's Progress**: I may finally be making a headway with SQL. I'm abandoning the curriculum for a second for something I think is more concise. Then I'm going to dive into the graded assignment.

**Thoughts** I hope to keep up the momentum.

**Link(s) to work**
1. [Learn SQL In 60 Minutes](https://www.youtube.com/watch?v=p3qvj9hO_Bo) (tutorial)

### Day 23: April 29, 2019 Monday

**Today's Progress**: I didn't intend to make a GitHub page today but I did. Nothing big on my part, I just selected an option from a drop-down menu. But I think it's cool that I can share this page with an actual URL now. I also worked more on HTML. I hope to do some SQL reading before I go to bed.

**Thoughts** Again I think GitHub pages is cool. I want to look more into hosting a whole website here. My reading and experiment tells me it's a no-go for Python or Node.js though.

**Link(s) to work**
1. [HTML-Me-Something](https://github.com/iamvalecia/html-me-something)
2. [HTML-Me-Something Pages](http://iamvalecia.github.io/html-me-something)

### Day 22: April 28, 2019 Sunday*

**Today's Progress**: No classwork today. Just HTML.

**Thoughts**: I skipped a day. I needed a break. Today I eased back in with non-classwork.

### Day 21: April 26, 2019 Friday

**Today's Progress**: More SQL. 

**Thoughts**: Hoping to get to a point where I can integrate this with the Python I've been learning.

### Day 20: April 25, 2019 Thursday

**Today's Progress**: More SQL. 

**Thoughts**: I can do better tomorrow. I got my hour in, but it was very sporadic.

### Day 19: April 24, 2019 Wednesday

**Today's Progress**: More SQL. 

**Thoughts**: It seems like a cool language. I hope to dig more into it tomorrow.

### Day 18: April 23, 2019 Tuesday

**Today's Progress**: I started off working on SQL for class. It seemed a bit tedious, so I switched to HTML and JavaScript, my personal endeavors.

**Thoughts**: Maybe I need a better resource than w3schools.com, which I was pointed to by the curriculum. 

### Day 17: April 22, 2019 Monday

**Today's Progress**: Today was a bit of a rest day. I did make a correction in my assignment just moments before it was due. I noticed it and rewrote the function in a couple of minutes.

**Thoughts**: Tomorrow more SQL.

### Day 16: April 21, 2019 Sunday

**Today's Progress**: Finished my assignment.

**Thoughts**: I would like to make it better. I would like the URL to match the content of the page. But I'm not sure how to do that without displaying sensitive info in the URL(get method). What I want isn't a requirement, so I won't exhaust myself too much about it.

**Link(s) to work**
1. [user-signup](https://github.com/iamvalecia/user-signup)

### Day 15: April 20, 2019 Saturday

**Today's Progress**: Started to read up on SQL, but main focus is on my assignment called User-Signup. It includes forms, validation, templates, html, and Python.

**Thoughts**: I think it's possible to complete this by Monday. I'm a bit behind. This challenge has helped me stay focused. Based on my thoughts during the tutorials, I'm surprised that I feel so confident. But I do. If I continue to work hard I think I got this.

### Day 14: April 19, 2019 Friday

**Today's Progress**: Crash course in templates. Template Extensions. render_template method. 

**Thoughts**: It wasn't officially named a crash course, but it felt like a lot of info in a short period. Time to move on to the graded assignment. On the upside I sort of know how to make a todo list in Python and Javascript. But despite the time since I performed the task I believe doing it with JavaScript is more comfortable.

**Link(s) to work**
1. [Using Jinja2 Templates in Flask](https://www.youtube.com/watch?v=exR1kxpd1cY)(tutorial, one of)

### Day 13: April 18, 2019 Thursday

**Today's Progress**: Moved on to Jinja2. 

**Thoughts**: So many new downloads. This is so different from the vanilla JavaScript I was doing beforehand. I downloaded Phaser and Ruby to check it out, but that's it. Some of the downloads has been git related so I won't completely blame python. Something new to learn and import.

### Day 12: April 17, 2019 Wednesday

**Today's Progress**: Validation day 3. It's coming together slowly.

**Thoughts**: I feel better about validation today than I did yesterday. I can't write anything from scratch but the syntax is looking clearer. 

### Day 11: April 16, 2019 Tuesday

**Today's Progress**: More validation study. I didn't get as much done as I would have liked. 

**Thoughts**: Validation confuses me.

### Day 10: April 15, 2019 Monday

**Today's Progress**: Today was a study day. Validation in python.

**Thoughts**: None about today's content. But I'm looking forward to tomorrow! Also it's day 10!

### Day 9: April 14, 2019 Sunday

**Today's Progress**: I did hands-on stuff for class. But I also restarted on an old project that was started on GitHub, then worked on elsewhere, and is now returning. I had to delete one unneeded branch and rename another. It wasn't too bad.

**Thoughts** Why did I create two branches? And from where did the name "iamvalecia-patch-1" come? Was it auto-generated? Also I've learned how to name a git file since then, but I'm keeping this name for simplicity and nostalgia.

**Link(s) to work**
1. [name.js](https://github.com/iamvalecia/name.js)

### Day 8: April 13, 2019 Saturday

**Today's Progress**: Polishing up on HTML forms.

**Thoughts** I think I found a solution to an old problem with some code I wrote months ago. 

### Day 7: April 12, 2019 Friday

**Today's Progress**: Today was just a video tutorial day. I took some notes, as well. I'm learning how the web works.

**Thoughts** I hope to do more tomorrow with my classwork, as well as with my personal projects. Today wasn't very hands-on.

### Day 6: April 11, 2019 Thurday

**Today's Progress**: I learned a lot of git commands that I haven't had to use in my classwork yet. Installed live server for Visual Studio Code, but it wasn't very live.

**Thoughts** These commands make me want to find another's repository so that I can practice...I believe I can do more towards my goal than I'm currently doing.

### Day 5: April 10, 2019 Wednesday

**Today's Progress**: I started a YouTube tutorial for creating a webpage. For my class, I am going back to the beginning of Unit 2(three weeks in) with the readings, videos and homework assignments. I fell behind and did a lot of spot reading. So I want some depth this time. In all I may have did 1-1.5 hours outside of class. 

**Thoughts** I'm not expecting the YouTube playlist to change my life with HTML, CSS or even JS. It's been in my saved playlists for a while so with all the coding for class I've been doing I want to jump back into coding for me. I was doing JavaScript before the course. Class has been Python with stint of HTML and CSS.

### Day 4: April 9, 2019 Tuesday

**Today's Progress**: I got miniconda set up like the coursework intended. It works fine at the moment. I also completed Web Caesar assignment.

**Thoughts** Why do things that work one day fail the next?

**Link(s) to work**
1. [Web Caesar](https://github.com/iamvalecia/web-caesar)

### Day 3: April 8, 2019 Monday

**Today's Progress**: Completed a Flask tutorial and started to work with conda. Both are needed to complete another assignment, web-caesar. This assignment is based off some code from the ceasar encryption I wrote a couple of weeks ago. Most of my conda commands can only be completed in Anaconda Prompt which was still trial and error to get started. Some of my classmates can work in GitBash.

**Thoughts** Getting more comfortable with my limited knowledge of git commands. But conda is a whole new ball game.

**Link(s) to work**
1. [Hello Flask](https://education.launchcode.org/web-fundamentals/tutorials/hello-flask/)(instructions)
2. [Web Caesar](https://education.launchcode.org/web-fundamentals/assignments/web-caesar/)(instructions)

### Day 2: April 7, 2019 Sunday

**Today's Progress**: I finished my HTML-me-something assignment. It has CSS.

**Thoughts** I'm still getting the hang of Git and Github and the terminal, as well. I meant to have four commits instead of five.  I feel better about than I did a year ago when I started my Github account. 

**Link(s) to work**
1. [html-me-something](https://github.com/iamvalecia/html-me-something/blob/master/index.html)

### Day 1: April 6, 2019 Saturday

**Today's Progress**: I did the HTML portion of my LaunchCode 101 assignment. It's called HTML Me Something. I used images as links. I used news html elements - article, main, footer, and header.

**Thoughts** I want to edit the content of the HTML, but I believe I can go ahead to the CSS portion. I hope I used the new HTML elements correctly. First day of challenge!!!

**Link(s) to work**
1. [html-me-something](https://github.com/iamvalecia/html-me-something/blob/master/index.html)

