# Here is my first project in angular

The first one of a long strike (I hope!)



## Where it comes from

It was a project proposed to Code Académie's students. It's an accountant application which aim to solve all yours friends party's/event's money problems! Simple to use and easy view to manage your and their debts, all local so can bring it anywhere as long as you have your computer (no need of wifi and so on).  

Students in the promo were divided into two parts : front-end and back-end. As the trainer of the front-end, my role was to make sure they can manage the app to be nice looking (althought I didn't design anything myself, just giving them tips with colors and proportion) and, above all, make sure it answer the UX and UI problems of a potential user. As a additionnary task, they had to run it with Angular.  

Since I was new to the techno, I practised a bit along with them. In this repositery you can see how I managed some view in my angular app (sorry for the short amount of commits in this project, I cut it from the symphony 2 "web" folder in the main application).  

## Problems I encounter and how I managed to resolve it.

Angular documentation is quite rich, so I didn't have real problem to find and understand it. Althought, the initialisation and creation of first components is still something to understand, but still quite easy.  

The real "problem" we encounter (even if it's probably nothing for a experimented javascript user) was due to the database. It's two json files, _users.json_ and _depenses.json_ (later generated with an API from the symphony application back-end students created). In the first one, _users.json_, we had the username and usergroup binded to an ID. In the second data file, _depenses.json_, we used these IDs and binded it to anothers IDs : the expanditure ones (you can check how it looks in the [**json**](elements/json) folder). So we had to transform those ID into name for a better user experience. I think it's not the better solution, but I managed to do it by using step by step tables where I transfer the information I want and read it later. You can check it [there](elements/js/app.js).  

## Ok you started, and what's next ?

Well, I admit it's a not a lot, but it was enough to make me really like angular. I know it's an old and depreciated angular, so I'm going to try angular 2 (or even 4!) in a new personnal project. It's going to be a entertainment manager (movie, game, series and so on). To start with, I will focus on movies and I will use [moviedb](https://www.themoviedb.org) api. The application will run with angular 2 (at least), SASS, and I will try to give a Netflix/Flex look.  

Thanks for reading ! 
