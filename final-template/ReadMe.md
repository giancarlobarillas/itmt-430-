# Final Report

## ITMT 430 2019 - Giancarlo Barillas

### Sprint 4

In this sprint this is where we first began constructing the user interface with react. I was project manager of this sprint. My job at this sprint was to manage people. This sprint I made it important to all of us about our availability. I made everyone create a schedule of their availability using a site called when is good. The purpose of this was to show the team times where you could meet up with someone else. Some of the schedules created were like the figures below. These were made on march 29.

![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/gbWhenisgood.PNG 'pmschedules')
![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/theoWhenisgood.PNG 'pmschedules2')

As project manager I was in constant communication with the team. I made sure that people were on time with their task. This was also the first sprint where we all joined together on Thursday and made substantial commit. Unfortunate this was the only time where we were all able to meetup for extended periods of time.

At the start of this sprint we did not have an organized folder structure for the development of react components. I made the hierarchy for the folder structure so that we would be able to store our new react components in folder that made sense for easier access. I also broke down the index.js page so that it can call react component by importing them. This can be shown in the commits: **f6cfcb3** and **f9166dd**. These commits are shown below.

![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/commit1.PNG 'indexjsChanges')

I also created the initial react components for the sign up and log in page so that we could developed those component simultaneously as show in commit **5cf08a5**.
![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/createLoginandSignup.PNG 'signupandLogin')

While other teammates were building the CSS of those pages I dealt with the logic behind those pages. At the time we initial thought that we would use states to control the way that buttons connected to each other. This initial logic can be seen the commit: **1a58173**. This logic was tedious, we later changed this in the following sprint by using react router and Navlinks. This logic was not scalable since it would require us to make new states for every page. I created the initial aboutme page for sign up so that we could build that page while I continued to work with button functionality in commit: **49ed4b7**. I dealt with some of the CSS on the initial pages in commit: **7947b2c**. I also created the first logic to pass properties throughout pages. These properties were used to capture inputs throughout multiple react components. This was used to later create the user via the API calls. This was further developed in the following sprint. These commits are shown below
![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/sprint4%20commits.PNG 'sprint4Commits')

### Sprint 5

In this sprint we continued with the same development methodology of the prior sprint. I oversaw building out the react logic. I also dealt with some merge request throughout the sprint in commits: **226f98c** and **0ab83da**. In this sprint I also started the development of the listing forms but did not push my code since it was not in a functional state. We redesigned the listing form between sprint 5 and 6.

In this sprint we realized that changing states to connect buttons was tedious and we shifted logic to using react router. I started to change the components call to routes as shown in commit **d4ebecd**. I also changed the button states to call Navlinks so that they can call the react components. This allowed us to quickly build new react components that have functional buttons that call other components. This is show in commit: **07d8b18**. These commits will be shown below.

![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/sprint5part1.PNG 'routerReact')

I also dealt with more merge request and checking of merges to ensure that we did not delete anything. Unfortunate in between sprint 4 and 5 we had an issue where we lost track of a certain file and we had to backtrack to find the missing page. The merges can be seen in the following commits: **9497c92**, **349525c** and **cd0ab7d**.

This was also the first sprint that we started to us the API calls. I designed the way to save values across react components. I did this by created a central state in the same format of the API so that once all the data was collected we would then be able to call the API and populate the database with a new user. Then in each component, I would store the data of that component in a state and pass that state to the parent. The final page of the sign-up form is where I would call the parent component’s state and call the API. The first version of this is in the commit **6f884cd**. In the commit **88711b3** is where I stored all the information about a new user so that it could be called by the API. I completed the functionality of creating a new user in the with the API call in **0821a7f** and **aeac2e1**. This is shown below throughout the commits

![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/sprint5part2.PNG 'finshFunction')

### Sprint 6

1. Each team member should comment on their own accomplishments (Taken word for word from the sprint reports) and describe what they did and explain any decisions referencing any lectures or material from the text book or web.
1. Correlate the personal sprint report with completed goals stated in the sprint report
1. Trello Card(s) that shows the completed artifact (screen shot of card)
1. Github code commits
   1. Under the History tab in GitHub you will see the repo commit history and each commit has a SHA-1 hash, supply this URL
