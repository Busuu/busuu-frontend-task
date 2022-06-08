# React / Next.js Take Home Test

## Introduction
Welcome to the Busuu frontend challenge! We are excited to see your coding skills in action within the Star Wars universe. 

### Time
We recommend spending around 1.5 hours on the whole task. We are not going to time you, but this is the general guideline we are giving regarding the completion.

### Technology
At a glance, we are looking to gauge your knowledge across a similar stack which we use at Busuu from NodeJS through to React. But you can use React or Next.js as a base for building the views - feel free to add extra libraries as well.

### Additional Details:
If you do not have time to finish it, please edit this `README` with a technical walkthrough of what you wanted to achieve. If any of the tasks are unclear you can reach out to us and we will clarify as soon as possible!

### Format of Submission:
Please clone this repository, and name as you like. When you are done, send the link to the Busuu representative you have been in touch with - remembering to make it public or share with the relevant users so as to allow our team to review it.

## Task
Feel free to consume Star Wars data from either:
* REST: https://swapi.dev/documentation
* GraphQL: https://studio.apollographql.com/public/star-wars-swapi/home?variant=current

From this data, we want you to create a user experience that'll allow someone to interact with it. Details upcoming below.

Wireframes are only a rough reference. You are free to create a UI that suits the data and be as imaginative as you want!

<br><br>

### Full list view 
* URL: `/list`
* Preview containers should:
    * Show, at least: a main name, a date, some description - any layout you wish!
    * Have the same height and width, where maximum height = 500px
    * Allow up to 3 columns
    * Allow vertical scroll if all exercises don’t fit in the screen
* ‘Search’ button on the top bar takes you to `/search`

<img src="https://user-images.githubusercontent.com/14952750/172342321-a693db3a-5d80-4d87-b686-3c3464082265.jpg" width="500" />

<br><br>

### Search view 
* URL: `/search`
* Top navigation should change to include filters: 
    * Include at least 2 types of filters - can be text based, radio, dropdown, etc.
    * Empty state should show a message to the user
* ‘Media’ button on the top bar takes you to `/list`

<img src="https://user-images.githubusercontent.com/14952750/172342324-e8d1b064-174f-4e7c-8de4-8a5a9ccb74a6.jpg" width="500" />

<br><br>

## Notes
* Use React or Next.js as a base for building the views - feel free to add extra libraries 
* Styling can be done with stylesheets, styled components, etc. 
* Views should be usable and fluid from large (>1440px) to small (<500px) viewports
* Bonus points:
    * Using TypeScript
    * Error and loading states
    * Sticky top navigation bar

<br><br>

## What we will be grading
* Architecture of React components
* Reusability of styles
* Fluidity of layout
* Readability

