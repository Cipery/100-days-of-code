# 100 Days Of Code - Log

### Day 0: February 8th, 2021 - TlustyZmrdi.net

**Today's Progress**: Added a service for loading data of sound quotes

**Thoughts:** I had some issues with Blazor WASM. Also I should really work on CI/CD pipeline, so there's always latest version of app deployed. Maybe I should not include the data (audio files etc) in source control, in case of some.. copyright issues :>

**Link to work:** No link :)

### Day 2: February 9th, 2021 - TlustyZmrdi.net

**Today's Progress**: Worked on CI/CD pipeline - but I haven't finished it, yet. Image gets built from source, then pushed to dockerhub, then GitHub action connects via SSH to server and.. so far, just does "ls" :-)

**Thoughts:** GitHub is kinda nice!

**Link to work:** No link :|

### Day 3: February 10th, 2021 - TlustyZmrdi.net

**Today's Progress**: Worked on CI/CD pipeline - finished it! Every change to master branch now builds and deploys new version of FatFucks to production! Also, after struggle with creating new ca-sln project, made it work! so tomorrow - cleanup of this project (mainly removing the angular part)

**Thoughts:** WSL rocks!

**Link to work:** No link :|

### Day 4: February 11th, 2021 - TlustyZmrdi.net

**Today's Progress**: Refactored project to use clean architecture on backend. Added one sound from 13th Warrior.

**Thoughts:** Super tired! But still did it! 

**Link to work:** This project is not public, so :( probably not the best project for this challenge?

### Day 5: February 12th, 2021 - TlustyZmrdi.net

**Today's Progress**: Bad day :/ I added IdentityServer yesterday and I really had.. I'm having a really hard time getting certificate to work in docker.. so I worked on that, with no success

**Thoughts:** Frustrated? No! But tired.. will work more than a hour tomorrow.

**Link to work:** This project is not public, so :( probably not the best project for this challenge?

### Day 6: February 13th, 2021 - TlustyZmrdi.net

**Today's Progress**: Another day that did not go as well as I wanted it to go. Had some success with the certificates locally, but I havent managed to get it working on remote server. I hope I'll be able to make it work tomorrow

**Thoughts:** Do I really need certs and identity server? Should really think about that tomorrow. I could just generate JWT and be done with that. In the other hand, this could be a nice way ho to learn about identity server

**Link to work:** This project is not public, so :( probably not the best project for this challenge?

### Day 7: February 14th, 2021 - TlustyZmrdi.net

**Today's Progress**: Https/Certificate hell - After hours of research and try/error, I have managed to understand and half-ass implement correct https handling for the server.

**Thoughts:** I wish I went to bed sooner

**Link to work:** This project is not public, so :( probably not the best project for this challenge?

### Day 8: February 15th, 2021 - TlustyZmrdi.net

**Today's Progress**: I decided not to remove IdentityServer, as it is something that I am avoiding to learn for such a long time.. I will use this "challenge" to finally learn something about it! 

**Thoughts:** Super tired again! Also, IdentityServer is a huge overkill.. I might remove it in following days, but first, I just want it to work!

**Link to work:** :>

### Day 9: February 16th, 2021 - TlustyZmrdi.net

**Today's Progress**: Hah, not only I removed IdentityServer, I removed the clean architecture template alltogether! And used a different one, from https://codewithmukesh.com/project/aspnet-core-webapi-clean-architecture%e2%80%8b/ . It should fit better for my type of project

**Thoughts:** No thoughts today.. glad I did some work

**Link to work:** :>

### Day 10: February 17th, 2021 - TlustyZmrdi.net

**Today's Progress**: Good day today! Lot's of work done on adding entities, setting up mappings, project rearrangements/cleanup. 

**Thoughts:** Viking prayer!

**Link to work:** :>

### Day 11: February 18th, 2021 - TlustyZmrdi.net

**Today's Progress**: Continued work on client / server data communication, did not managed to finish it :( But sh*t's on!

**Thoughts:** Viking prayer!

**Link to work:** :>

### Day 12: February 19th, 2021 - TlustyZmrdi.net

**Today's Progress**: Added loading of quotes server side. Files server side. Client now loads all metadata and data from server. Added Sentry.io

**Thoughts:** Worked hard today! Also Diablo 2 Ressurected was announced today!

**Link to work:** :>

### Day 13: February 20th, 2021 - TlustyZmrdi.net

**Today's Progress**: Today I've added lots of quotes from one popular TV show, reworked data loading from server a little bit, added instant random quote button. 

**Thoughts:** I think I should not store the data files in Git :> Tomorrow - think about uploading data directly to server

**Link to work:** :>

### Day 14: February 21th, 2021 - TlustyZmrdi.net

**Today's Progress**: Pretty productive day today. docker run had lots of arguments, so I have created docker-compose file and now I use docker-compose instead of docker run. Also remove (possibly) copyright protected materials from git and moved it to folder on server, that is mounted as volume to container in docker-compose. Redone sidebar so it now correctly works on mobile. Also started another project for monitoring/controlling large number of zigbee devices. Also in BlazorWASM!

**Thoughts:** Sunday Funday!

**Link to work:** :>

### Day 15: February 22th, 2021 - TlustyZmrdi.net

**Today's Progress**: Content day - did not code as much today, I spent most time on adding content. But thought about database - I will use MySQL running in docker to store metadata about quotes (name, description, times played). But thats for another time

**Thoughts:** Not feeling well.. at all :/ 

**Link to work:** :>

### Day 16: February 23th, 2021 - TlustyZmrdi.net

**Today's Progress**: Started working on project two - a Blazor Server side app that would allow me to controll a large number of zigbee smart power plugs, with energy monitoring (so energy charts included!). Basically just created the project and tinkered with blazor<->mosqitto<->zigbee2mqtt

**Thoughts:** Feeling rly bad today, hope it's not.. you know what.. but feeling good about this project!

**Link to work:** :>

### Day 17: February 24th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: Feeling sick, absent from work, slept for most of the day, still managed to work on this second project for over one hour! Created the project from template, upgraded to net5, made auth work and chosen https://blazority.com as the lib that I will use to create nice user interface

**Thoughts:** Blazor is just.. the best thing

**Link to work:** :>

### Day 18: February 25th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: Managed to connect to the zigbee coordinator, read data from it, use MediatR to propagate it thru layers of the app. Frontend now shows list of connected devices and list of all messages received and sent =) A good day!

**Thoughts:** I'm feeling kinda better today!

**Link to work:** :>

### Day 19: February 26th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: I'll keep it short today - I've managed to deploy the prototype app to productin, and after lots of linux struggle, it works!!!

**Thoughts:** I'm feeling kinda better today!

**Link to work:** :>

### Day 20: February 27th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: Not much coding today (I know I should code!), spent two hours setting up ssh tunnel that will be used for both production and debugging.

**Thoughts:** Jaffa!

**Link to work:** :>

### Day 21: February 28th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: Added https://www.hangfire.io/ with commands and queries required to publish messages to MQTT topics, and added flow to read them back. So far, received data is not mapped to the device

**Thoughts:** Last day of February. Three week lockdown of Czechia starts tomorrow..

**Link to work:** :>

### Day 22: March 1st, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: Spent most of my time debugging stuck zigbee devices :(

**Thoughts:** Gotta have this in beta stage before friday!

**Link to work:** :>

### Day 23: March 2nd, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: Lot's of work done today! Finally fetching power plug data, and real-time displaying the data in Dashboard! But - this app should present realtime data and I am already starting to feel like it's gonna be Hellheim :( Thinking about using Stl.Fusion

**Thoughts:** Gotta have this in beta stage before friday!

**Link to work:** :>

### Day 24: March 3rd, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: Mainly worked with Hangfire - added mqtt client reconnects, periodical device fetching. Also improved error handling so the app does not crash so easily :))

**Thoughts:** STL.Fusion - on the way?

**Link to work:** :>

### Day 25: March 4th 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: Focused on Github Actions -> automatic docker image build, push to registry, then pull on server and docker-compose up -d :) Works like a charm! Until it breaks, I guess.

**Thoughts:** STL.Fusion - on the way?

**Link to work:** :>

### Day 26: March 5th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: Posting update a day late, but worked on the app for ~4 hours =) Autodeploy works flawlessly, fixed a ton of bugs, and the app just works really nicely, power plugs report their state, can be turned off/on.. just sweet :)

**Thoughts:** STL.Fusion - on the way?

**Link to work:** :>

### Day 27: March 6th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: Refactored some frontend code to their own components, added some more static information to the power plug detail pages 

**Thoughts:** STL.Fusion - on the way?

**Link to work:** :>

### Day 28: March 7th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: Spent my whole "work time" on STL.Fusion research. It seems like something really helpfull and powerful, but the learning curve is so steeeep :(

**Thoughts:** STL.Fusion - on the way?

**Link to work:** :>

### Day 29: March 8th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: Again: I've spent my whole "work time" on STL.Fusion research. I have created a sample project and toyed with the thing.. it's works like magic.. but seems complicated. However, the dev is responsive and really helpful!

**Thoughts:** STL.Fusion - on the way?

**Link to work:** :>

### Day 30: March 9th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: Today I have moved code from non-STL.Fusion project to the STL.Fusion based project. Fusion is not implemented yet, but the project compiles and runs without any issues. So that's a good place to be before implementing this framework

**Thoughts:** STL.Fusion - on the way?

**Link to work:** :>

### Day 31: March 10th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor

**Today's Progress**: I worked on reimplementing the logic from first version of app to the Fusion version. And to my surprise - it was soooooo easy :O And the code is much cleaner. I am 90% done with the transfer

**Thoughts:** :<

**Link to work:** :>

### Day 32: March 12th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor + Fusion

**Today's Progress**: Skipped a day!!! My first skip :/ Today I have studied STL.Fusion a bit more, added lots of code, deleted 95% of the added code because it sucked!! Left only the "Updated X seconds ago", that is currently calculated/updated on server side. But I think I'll do it client (javascript side) soon.

**Thoughts:** Even though its my first "skip" in 32 day, it feels bad man :(

**Link to work:** :>

### Day 33: March 13th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor + Fusion

**Today's Progress**: Today was a debugging / deployment.. Who am I kidding? Debugging&Development on Production! No new features, just bug fixing. 

**Thoughts:** 

**Link to work:** :>

### Day 34: March 14th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor + Fusion

**Today's Progress**: I made things purdier today :> I suck at front-end stuff, luckily MudBlazor is really a great library and it makes things way easier for us backend devs

**Thoughts:** 

**Link to work:** :>

### Day 35: March 14th, 2021 - Zigbee2Mqtt device monitoring in .Net 5 + Blazor + Fusion

**Today's Progress**: I have worked on user experience - nicer cards, more descriptive texts, less information displayed and yet more info at the same time! 

**Thoughts:** 

**Link to work:** :>
