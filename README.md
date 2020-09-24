# SmartJen Front-End Developer Technical Assessment Answer

1. Redesign the "Customize" page
<!--
Requirements :
- Existing feature: https://youtu.be/_3I5AXXg2Yw?t=68
- Ideally, this page should have the same easy-to-use feature like Google Form, where users can drag and drop to change the sequence of the question. 
- Allow users to add section header and instruction (similar to Google form)
- Example: https://www.dropbox.com/s/115nf1c9u57g1ey/Screenshot%202020-09-02%20at%2010.40.01%20AM.png?dl=0
-->
- Feature are roughly provided in html/index.html
- Main idea is to use jQuery-UI Sortable feature to allow drag-and-drop feature
- And to add a hidden field "sequence" on each row of data to allow user(s) to re-arrange objects
- to add a button to add new "section" that the type can be selected again.
- the "new section" type can be changed using a combo-box to allow it to be changed to add text-area with different CSS class-styling to accomodate Title/Description text box.
- Also in-case user accidentally added wrong type of section, allow user to delete it (and also delete question if needed) by adding a "remove" button on each section / question.

2. Redesign the "Worksheet Generator"
<!--
Requirements:
- This is an existing features in SmartJen: https://youtu.be/_3I5AXXg2Yw?t=17
- Please redesign the user interface so it is more up-to-trend, less “technical” and easier to use. 
- Technology: HTML/CSS/Javascript/Bootstrap
- You may use Figma for this project
-->
- User interface :
  - Number of question to use Range Input : https://getbootstrap.com/docs/4.1/components/forms/#range-inputs
  - Level & Subject either keep as is, or change to use select2 to group by Subject / Level : https://select2.org/
  - Strands and Topic to change to using select2 instead : https://select2.org/
  - To disable/enable strands/topics based on subject and levels selected can build based on methods used on : https://stackoverflow.com/a/31263496
  - Learning Objectives / Strategy : Need further inspection as to how the options appears, but changing to select2 is a good choice.
  - Question Types : as is
  - Difficulty Level : as is
