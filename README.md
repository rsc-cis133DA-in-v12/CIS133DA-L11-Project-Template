# Lesson 11 Project
Your client is happy to hear you have learned JavaScript and has hired you to add script elements to the project form you created for them before. Be sure to view and test your webpage before you submit your work, testing that each script element works appropriately.

##

## Project Prep
1. If you haven't done so already, clone the repo to your computer within your course folder.
2. Open the repo within VS Code. You can open this `readme.md` file within VS Code to view the project directions there. 

   > **TIP:** Right click on the file and choose the `Open Preview` option.
3. If there are files and folders present other than this `readme.md` file, take some time to familiarize yourself with the files within the repo so you know where they are located. This will help you when asked to use them within the project directions.

   > **TIP:** Before beginning any work on the project, read through all the steps to understand what you will be doing.
4. Create a subfolder to the Lesson 11 course folder called:` scripts`
5. Create a new file within the scripts subfolder called: `javascript.js` 

<br>


## Create the Script
1. If necessary, open the `javascript.js` file.
2. Create a multi-line comment listing your name as the author and your course and section number.
3. Create a JavaScript statement to:
   1. Target an element with an id of "lastmodified"
   2. Set the inner HTML of that element to be the document's last modified property.
4. Create a function that will create an alert for when the form is submitted:
   1. Give the function a name.
   2. Create a code block. 
   3. Within the code block, write a JavaScript statement to display an alert with a message letting the user know the form has been submitted.
5. Create another function that will unhide a hidden element when the reset button is pressed:
   1. Give the function a name.
   2. Create a code block.
   3. Within the code block, write a JavaScript statement to target an element with an id of "resetmessage" and set the visibility style value to visible.
6. Create single-line comments before the two functions and the last modified statement explaining what each one does.

## Update the Schedule Page
1. If necessary, open the `schedule.html` file.
2. Update the comment within the header element with the correct information.
3. Update the metadata for the page to appropriately reflect the information that the page will contain.
4. Utilize the appropriate element so the external JavaScript file is loaded as the last element of the body.
5. On the reset button, add the onclick attribute with a function name of your choosing for your reset message as the value.
6. On the submit button, add the onclick attribute with a function name of your choosing for the form submission message as the value.
7. After the closing form tag, add a paragraph with a statement letting the user know the form has been reset.
   1. Apply an id to the paragraph with the appropriate value that matches the appropriate JavaScript statement.
8. Within the footer element, within the same paragraph as the copyright information, utilize the appropriate elements and attributes to achieve the following:
   1. After the small element, add the text and dash: Last Modified -
   2. Create an inline element with an id and value of your choosing. This is where the last modified information will be placed.

## Example Reset Message
This is an example of what should happen when you click the reset button.

![Screenshot of reset button message]()

## Example Submit Button
This is an example of should happen when you click the submit button

![Screenshot of submit button alert]()

## Style the Schedule Page
1. Within the external stylesheets, style the reset message paragraph with the following:
   1. Visibility is hidden by default.
   2. Apply a dark background color. Be sure that the text is legible.
   3. Adjust the width so that it does not span the full width of the page.
   4. Adjust the white space of the element for better text readability.
2. Apply the necessary CSS properties (including, but not limited to: box model properties, font information, and color) so the form is readable and usable within the mobile and tablet views.

## Example Project
This is an example of what the project should look similar to before you submit.

![Screenshot of the Schedule Page]()

## Submit the Project
Before you submit your project:
1. Save your files and apply any final commits to your work.
0. Push (i.e., sync) the repo on your computer with GitHub to ensure all files are uploaded for your instructor to see.
0. Verify that all files appear on GitHub.

   > **TIP:** You can view any of your repos by going to the GitHub organization for the course - [RSC-computer-technology](https://github.com/rsc-computer-technology). You can bookmark the page for future reference. 
0. Open the Pull Requests tab within GitHub (or using the GitHub Extension within VS Code).
0. In the comment field, 
   - Type in your instructor's username with an `@` before. See the course announcements for their username to use. 
   - Put a note to your instructor that the assignment is ready to grade.
0. Click on the `Comment` button to finalize and submit your assignment to GitHub for review.
0. Lastly, submit the Project to your **Gradebook** using the steps within **Assessing Your Learning** in Lesson 11.