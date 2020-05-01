# Hang In There Project - Application for a poster developer - Redo

## About Project:

This project is being redone to better Jenna's knowledge. The main GitHub to where this was done is located here;

Leigh Larson and Jenna DiLullo's original project: https://github.com/leighlars/hang-in-there-boilerplate

In this project, an application was created where the user could make a poster with a randomly selected poster, quote, and title. That poster could then be saved if the user liked it as such. The user could also make their own poster with their own image, quote, and title. The user could then save the poster and see it in their saved posters page. If the user did not like that saved poster, they then could delete it.

## Project Goals:

- Build the querySelectors, eventListeners, and eventHandlers
- Properly perform GitFlow
- Randomize poster as application is loaded
- Click the buttons to be able to switch to different forms
- Create a new poster and display that poster in the main form
- Save the newly created poster in the saved posters form

#### Wins:

- Developed an application with no bugs
- Checking console for errors
- Properly using classList to add and remove a hidden class
- Displaying newly made poster
- Adding HTML into an event Handler to properly display saved posters in the saved poster form

#### Challenges:

- Understanding to check the console
- Understanding how the DOM and data model communicate with each other
- Using the correct syntax to display newly made poster
- Using correct variables

#### Technologies Used:

- HTML
- CSS
- JavaScript
- Git/GitHub

## In Action:

### Iteration 0:

The giph will show;

- When the page loads, we should see a poster with a randomly selected image, title, and quote;

<img src = "https://recordit.co/emqBT9Xnqh.gif" alt="Random posters" height=auto width=75%/>

### Iteration 1:

The giph will show;

- When a user clicks the "Make Your Own Poster" button, we should see the form, and the main poster should be hidden
- When a user clicks the "Show Saved Posters" button, we should see the saved posters area, and the main poster should be hidden
- When a user clicks the "Nevermind, take me back!" or "Back to Main" buttons, we should only see the main poster section

<img src = "https://recordit.co/xFNYYPbMny.gif" alt="Switch Views" height=auto width=75%/>

## Iteration 2:

The giph will show;

- In the new poster form the user will be able to fill out the inputs
- When the save button is clicked and the user goes back to the main poster form, the saved poster will be displayed

<img src = "http://g.recordit.co/cuadFkcTEt.gif" alt="Display Saved Poster" height=auto width=75%/>

## Iteration 3:

The giph will show;

- When the user makes a new poster and clicks the "Save Poster" button and then clicks on the "Show Saved", the saved poster will be displayed
- If a user clicks the "Save This Poster" more than once on a single poster, it will still only be saved once (no duplicates)

<img src = "https://recordit.co/iGFyQd2dYX.gif" alt="Display Saved Poster" height=auto width=75%/>

## Iteration 4 - Deleting Saved Posters

- From the saved posters view, if a user double clicks a saved poster, it will be deleted

_Hint: How will you update the data model to achieve this?_
