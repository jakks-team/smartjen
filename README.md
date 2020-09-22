# SmartJen Front-End Developer Technical Assessment Answer

1. Redesign the "Customize" page
<!--
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
