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
