### Research & Planning Log for Epicodus Capstone Project

#### Friday, 4.28

* 8:12: Create Figjam file for planning : https://www.figma.com/file/7ccXDVSTxf9EsU8eO2a3xP/Capstone-Planning?node-id=2%3A62&t=G9DfON0TAEaXD923-1

* 9:45: researching using React with ASP.NET Core. Compiled a list complete with videos and got a little overwhelmed at the general concept of incorporating C# and React. Will come back to this information to review. Coming to an understanding that I might need to set up a .NET API to fetch data from MySQL database and import data into React components. Will need to research this further and possibly read further into the lesson plan homework to see if this is something we'll cover in the coming weeks.

* 10:30 building out a react component diagram and schema diagram in figma to try to organize my project structure and see if it helps refine my needs for above research findings.

*  11:40 distracted away from building out my component becuase I think it's getting ahead of myself a little bit. File folder/project strucutre still needs some refining. Back to research and compiling a list of videos to watch after lunch. 

* 1:00p amassed a pretty solid amount of tutorial videos to help me streamline my overall project stucutre file build and components. will begin viewing and deciding what is/isn't helpful or able to contribute to my vision for my mvp/finished project.

* 1:45 take a break from tutorials to partially update capstone-proposal.md as the project starts to form a little bit more in my mind. pushing the partially complete project proposal and back to internet tutorials for research purposes.

* 2:23 update README with a screen shot from figam project file with "soft" component mock up for React front end, still diving into some research to see if it'll be usable, but slowly starting to put pieces together in my mind and on "paper". :) returning to tutorial-style research vidoes and reading.

* 4:00 WIP research and gathering inspo for styling, content, and layout: still working on research and updating figma.

* 4:50 solid day of research and project set up. looking forward to diving into the code and putting it all together. hopefully without too many big pivots!


#### Friday 5/5:

* 8:00a Starting day off with finishing planning and considering either starting to get right into the project or attempting a practice proj to make sure I can get everything connected between C#/SQL API and React without all the bells and whistles.

* 8:45a Stuck on a name. Impossible to start creating MVP app without it! I don't want to have to re-start my in-app naming conventions after the fact. Why is landing a usable title feel like such a hurdle? Market research happening currently.

* 9:07a Continuing planning and organizing in Figma now that I have a name and a general idea for which frameworks I'm going to use and in what way.

* 9:47a WIP: planning API endpoints, and how to utilize authentication and jwt.

* 10:35a Begin work on API! https://github.com/elgrons/GratShiftSaveApi.Solution

* 11:48a WIP: Buildout of .NET Api almost ready to do my first EF Migration. https://github.com/elgrons/GratShiftSaveApi.Solution/tree/main/GratShiftSaveApi

* 1:08p Back from lunch and ready to start my database migrations!

* 1:59 Got diverted from intial EF Migrations because I'm actully not sure how to set up authentication/authorization and whether or not I need a user class.. Hesistant to do an initial build without a bit further research. Tutorials collecting then watching happening now for a bit.

* 2:20 Softly considering switching to Firebase/Firestore by EOD if I can't form a plan of attack for ASP.NET authorization/authentication.

* 3:51p WIP: thinking of changing to Firestore/Firebase for auth.

* 5pm End of day- thinking I might make a firebase backup database this weekend in case I can't get SQL/.NET Core API to work how I like.

Sunday 5/7

* 1:20p Trying to get this API in working(ish) order so that I can start on front end by or before Friday. Working on how to correctly format seed data with EF Core using DateTime.

* 2:19p Was following a JWT token/authentication YouTube tutorial and remembered that I never double checked the Lesson Plan's further exploration material back from Week 6 of C#. Pausing my tutorial and going back to reference the Lesson Plan material.

* 3:00 Following tutorials to attempt to get JWT Tokens to work with authentication, but it seems like most every example utilizes Visual Studio and there is a significant "under the hood"-level of stuff happening with connection to SQL database. Considering switching to Firebase by Wednesday if I can't get this nailed down.

#### Wednesday 5/10:

* 4:00pm Successfully deployed My .NET Api to Azure and am ready to start my React front end! 
https://github.com/elgrons/GratShiftSaveApi.Solution/tree/main/GratShiftSaveApi

#### Friday 5/12:

* 7:55a Finishing up my README for my Api, then will start mocking up my component diagrams and should begin making an new npx-create-react-app by EOD if all goes to plan.

* 10:03a Time flies! Still working on README, documenting endpoints and making a Postman screen shot-style documentation. Hit a snag with login/register and need to go back and rework the fact that every user needs to be registered as Admin for access to GratShift api. I fixed it locally, but need to update my Azure domain so both instances of urls are in working order.

* 11:59 Realized while I was documenting that I wanted my API to correlate users with their data as well as allowing them to only view their own data and have reached a stopgap in terms of functionality. Just when I thought I was done with the Api....


* 12:36 Thinking that this might end up being a stretch goal, just so I can finish documenting this README and get to my front end.

* 12:56 Worked through lunch to attempt to recover Put functionality from the Api. Had to remover UserId variable from GratShift.cs in Models. Back to square one that I was at this morning. Will do a little more research about how to secure a users data so only they have access to it, but will consider this a stretch goal if time gets away from me. I want to make sure I'm finishing the README and starting my front end by EOD.

* 2:09 Thinking again I'm maybe overthinking this. I may only need a foreign key that correspondes GratShift input with a User Id. Work in progress!

* 2:42 Try two on re-adding UserId to GratShift.cs in Models as an attempt to get Authentication and UserId associated with Api Get and Post requests.