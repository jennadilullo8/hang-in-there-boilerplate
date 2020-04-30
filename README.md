# Hang In There Project - Application for a poster developer - Redo

## About Project:

This project is being redone for knowledge purposes. The main GitHub to where this was done is located here;

Leigh Larson and Jenna DiLullo's original project: https://github.com/leighlars/hang-in-there-boilerplate

In this project, an application was created where the user could make a poster with a randomly selected poster, quote, and title. That poster could then be saved if the user liked it as such. The user could also make their own poster with their own image, quote, and title. The user could then save the poster and see it in their saved posters page. If the user did not like that saved poster, they then could delete it.

## Project Goals:

- Build the querySelectors, eventListeners, and eventHandlers.
- Properly perform GitFlow
- Randomize poster as application is loaded

#### Wins:

- Developed an application with no bugs
- Checking console for errors

#### Challenges:

- Understanding to check the console

#### Technologies Used:

- HTML
- CSS
- JavaScript
- Git/GitHub

## In Action:

### Iteration 0:

The giph will show;

When the page loads, we should see a poster with a randomly selected image, title, and quote;

<img src = "https://recordit.co/emqBT9Xnqh.gif" alt="Random posters" height=auto width=75%/>

### Iteration 1 - Switching Views

Form page:
![screenshot of form](/readme-imgs/form.png)

Saved posters page (once working with extra saved posters):
![screenshot of saved posters page](/readme-imgs/saved.png)

- When a user clicks the "Make Your Own Poster" button, we should see the form, and the main poster should be hidden
- When a user clicks the "View Saved Posters" button, we should see the saved posters area, and the main poster should be hidden
- When a user clicks the "Nevermind, take me back!" or "Back to Main" buttons, we should only see the main poster section
- In summary: Be able to switch between the three views (main poster, form, and saved posters) on the correct button clicks

_Hint: go check out the HTML and CSS files to see how the form and saved posters sections are being hidden in the first place_

## Iteration 2 - Creating a New Poster

Form being filled out:
![screenshot of form](/readme-imgs/form.png)

Once poster is saved:
![screenshot of result](/readme-imgs/form-result.png)

- On the new poster form view, users should be able to fill out the three input fields and then hit the save button
- When the save button is clicked, several things will happen:
  - Save the submitted data into the respective arrays (image URL into the images array, etc) so that future random posters can use the user-created data
  - Use the values from the inputs to create a new instance of our Poster class
  - Change back to the main poster view (hiding the form view again)
  - Display the newly created poster image, title, and quote in the main view

## Iteration 3 - Saving & Viewing Posters

Saved posters view:
![screenshot of saved posters section](/readme-imgs/saved.png)

- When a user clicks the "Save This Poster" button, the current main poster will be added to the `savedPosters` array.
- If a user clicks the "Save This Poster" more than once on a single poster, it will still only be saved once (no duplicates)
- When a user clicks the "Show Saved Posters" button, we should see the saved posters section
- All the posters in the `savedPosters` array should be displayed in the saved posters grid section

## Iteration 4 - Deleting Saved Posters

- From the saved posters view, if a user double clicks a saved poster, it will be deleted

_Hint: How will you update the data model to achieve this?_

## Optional Extensions - Gettin' fancy

Here's a list of possible extensions to implement - but **ONLY IF** your team has completed all the previous iterations **AND** have cleaned up your code to make it DRYer and more readable.

You are welcome to add your own extensions. Be sure they are thoughtful in terms of UX/UI, and that they do not break any prior functionality.

- Implement data validation and error handling into the form (disable button, provide error messages if data entered is not correct, etc)
- In the main poster view, allow users to click each piece of the poster (image, title, quote) to update just that piece with another random item from the appropriate array
- When a user single clicks a saved poster, create a modal to view it larger
- Allow users to drag and drop saved posters into whatever order they want them to appear


Project spec & rubric can be found [here](https://frontend.turing.io/projects/module-1/hang-in-there.html)
