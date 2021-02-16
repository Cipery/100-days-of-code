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
