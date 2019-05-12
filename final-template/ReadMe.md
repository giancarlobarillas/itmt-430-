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

#### Here is a view of the that reflect my contributions to the sprint:

![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/trelloSprint4.PNG 'Trello1')

![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/trelloSprint4part2.PNG 'Trello2')

### Sprint 5

In this sprint we continued with the same development methodology of the prior sprint. I oversaw building out the react logic. I also dealt with some merge request throughout the sprint in commits: **226f98c** and **0ab83da**. In this sprint I also started the development of the listing forms but did not push my code since it was not in a functional state. We redesigned the listing form between sprint 5 and 6.

In this sprint we realized that changing states to connect buttons was tedious and we shifted logic to using react router. I started to change the components call to routes as shown in commit **d4ebecd**. I also changed the button states to call Navlinks so that they can call the react components. This allowed us to quickly build new react components that have functional buttons that call other components. This is show in commit: **07d8b18**. These commits will be shown below.

![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/sprint5part1.PNG 'routerReact')

I also dealt with more merge request and checking of merges to ensure that we did not delete anything. Unfortunate in between sprint 4 and 5 we had an issue where we lost track of a certain file and we had to backtrack to find the missing page. The merges can be seen in the following commits: **9497c92**, **349525c** and **cd0ab7d**.

This was also the first sprint that we started to us the API calls. I designed the way to save values across react components. I did this by created a central state in the same format of the API so that once all the data was collected we would then be able to call the API and populate the database with a new user. Then in each component, I would store the data of that component in a state and pass that state to the parent. The final page of the sign-up form is where I would call the parent component’s state and call the API. The first version of this is in the commit **6f884cd**. In the commit **88711b3** is where I stored all the information about a new user so that it could be called by the API. I completed the functionality of creating a new user in the with the API call in **0821a7f** and **aeac2e1**. This is shown below throughout the commits

![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/sprint5part2.PNG 'finshFunction')

#### Here is a view of the that reflect my contributions to the sprint:

![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/trelloSprint5.PNG 'trello3')

### Sprint 6

In this sprint we rebuilt the react flow of the application while also switching to a different css framework. I dealt with the complete listing view and some of the functionality of the admin page. I also dealt with verifying merge request.

The admin page already had the functionality to hide the admin button. I used the same logic to verify if a user was logged in as a buyer or a seller. This was important since a buyer should not have the option to create a listing. I added the hiding logic to the listing button in the commit **ffdf872**.

#### Buyer View

![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/buyerview.PNG 'Buyer')

#### Seller View

![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/sellerView.PNG 'Seller')

I had struggled earlier in my environment to dynamically display components from an array. I learned that react can call the same component multiple times in a parent component but cannot render the same component from a for loop. This was tested in the commit: **06967ba**. I learned that by using map to iterate an array would give me what I needed. I used that logic to display the components in a list view. I made this logic in commit: **b33700b**. I also designed the list view and started that in commit: **79ce3bf**. The initial component for the list view used hardcoded information so that I could understand how this would look. Once I had the logic to display a list of components from an array I used the API to call the listing information and then I passed that to the component. This allowed to populate the component with real information from the database. This logic is shown in commit: **a16b87f**. I also then created the logic to call the images from our database and display them in the list view. I used map again to go through the image object in each list and the display the image from the source. This is shown in the commit: **f7cc45b**. I then added css to the listview so that it would look like how the final presentation looked like. I also designed the logic behind the expaneded view of the list component. Each component has an expended view that looks like the following below. The expanded part has the ability to now contain much more information about each listing and can be styled in any way.

#### Normal View

![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/listviewshort.PNG 'normal')

#### Expaneded View

![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/listviewexpand.PNG 'expanded')

These commits the spring 6 are shown below
![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/Sprint6Commits.PNG 'Sprint6')

#### Trello view of Sprint 6

I completed what i was supposed to complete for that sprint and also completed the list view for the main page during this sprint.
![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/finalImages/trelloSprint6.PNG 'trello4')
