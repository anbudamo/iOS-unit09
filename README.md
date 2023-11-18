Final App Design
===

# Supersets/ExerciseBook/First Set Done

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)

## Overview

### Description

Supersets (current name for app) is a workout assistant that helps you log your daily workouts. It is hard to stay motivated in fitness with our daily distractions, be it work, education, technology, etc. Supersets logs your daily workouts and keeps you motivated to hit the gym everyday. Have you wondered whether you are going in the right direction or if your workout is really working for you? By keeping track of your workout statistics, Supersets helps you realize real time progress and helps you re-orient your workout/fitness goals. Think of it as a daily journal, but for working out! 

### App Evaluation

[Evaluation of your app across the following attributes]
- **Mobile:** People usually take their phones to the gym. This is where the app will come into use. Therefore, the experience of using this app is uniquely mobile. The user will probably be in the gym listening to music playing from their phone. they can switch apps every once in a while to update the exercise/number of sets/number of reps/any notes about their set. 
- **Story:** The audience is clear. The audience isn't particularly niche as they target all gym goers. However, the idea of the app targets a very specific audience who are particular in tracking their workout progress and splits. The story of the app is also deliverable and easy to convey in a sentence: a workout tracker app to follow your progress and achieve your fitness goals
- **Market:** The market for the app is large and will attract a niche user base from the gym/workout community. 
- **Habit:** Working out is a habit. Since the app is a complement to this activity the app will definitely cultivate a habit and repetition among users. The user will use the app every time they go to the gym or workout basically. 
- **Scope:** There is a lot of scope in the app. For starters I will be using everything from a custom tableview, calendar view, navigation to each workout and all types of UI elements. There is scope to create the app with just the basic functionality and also if I can to implement more advanced features and challenge myself

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

- [x] I want to be able to add a workout to a table view
- [x] I want to be able to modify things like number of sets/reps, exercise name, and weight in the custom table view cells
- [x] A database/array of exercises which you can choose from and add. Can search for it on a bar that has auto-complete
- [x] I want a main page with date and time that I can modify so that I can record the start time

**Optional Nice-to-have Stories**

* I want the app to support entering a superset or custom workout types 
* I want a calendar view where I can choose and access specific time stamps
* I want a weight tracking page
* I want a bar that I can slide to indicate the intensity with which I did an exercise
* I want a page dedicated to tracking the big three lifts- bench, squat, deadlift
* I want a page that displays the progress I have made

### 2. Screen Archetypes

- [ ] calendar (decided not to do it)
* I want to have the days I worked out in highlighted in the calendar
* I want to be able to choose a day that I worked out in the calendar and see what I did that day
- [x] creation
* I want to be able to add a new cell to a list/tableview and edit it
* I want the most recent workouts to show up at the top
- [ ] stream (was planning on having another tab with a stream view - to ambitious)
* I want to be able to stream through the list of workouts
- [x] detail
* I want to have a detail view where I can see a detailed summary of my workout with all the data that I entered

calendar, creation, stream, detail
### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Main tab where workout is added to a tableview
* Data and statistics page 
* [optional] weight tracker

**Flow Navigation** (Screen to Screen)

- [ ] [list first screen here]
* [list screen navigation here]
* ...
- [ ] [list second screen here]
* [list screen navigation here]
* ...

## Wireframes

<img src="https://imgur.com/K3CB2Tk.jpg" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 

[This section will be completed in Unit 9]

### Models

### Week 8+9 progress

Progress screenshots:
1. Designed such that start time could be changed and resetted. Also made sure that time updates and refelcts current time
2. Designed the landing page when the start button is clicked. It has a stopwatch that lets the user see how much time they are
   spending. I also designed a tableview populated with an almost exhaustive list of exercises that the user can choose while
   working out.
<img src="https://imgur.com/iI7IQh4.jpg" width=600>
<img src="https://imgur.com/gnjFx8A.jpg" width=600>

Video of build progress: https://imgur.com/QhuzWu1.gif

Week 8:
I worked on actually developing my app after the brainstorming activity. I created a basic form of the homepage, with the app banner,
a start button for the workout, and date/time that updates with the current time. The main challenge I faced was with starting the app 
as I worried I hadn't done enough planning to execute my ideas. After I started developing it was smooth sailing.

Week 9:
The bulk of my time this week was figuring out how to make an API call to an exercise API and populate my tableview with all those exercise. 
A lot of time was also spent on figuring out how to navigate between viewcontroller and pass data inbetween them. It was very challenging building 
the app from scratch. Unlinke some of the labs there weren't hints that I could follow. I had to figure it out by sheer force with the help of 
the codepath lectures, cp resources, stack overflow, and chatGPT. At some points I was so stuck I had to revisit the project the next day.

[Add table of models]

### Networking

- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
