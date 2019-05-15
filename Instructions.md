Mobile first approach

Working log and instructions

Step 1.
- created mobilefirst workspace

Step 2.
- created index.html file
- created div element class .Container in index.html
- created three nested div elements class .column
- href set for main.css

Step 3.
- created main.css and main2.css files

Step 4.
- in main.css gave the class .column float: left; proprty and set the width to 100% 
    and the height to 50px (for empty float elemnts not to collaps)
- set the back-ground color to black (#000)

Step 5.
- created a media query for tablet size viewports (default width 768px)
- set the .column class width to 30% and gave them margin of 10px (for the elemnts to appear apart)
- set the background color to persimmon (#e84610)
- 
Step 6.
- created a second overwriting media query for desktop size viewports min-width of 992px
- set the .column class background color to blue (#0997d3) 

Step 7.
- copied the main.css code to main2.css and change the order of the media queries
- change the href to main2.css
- when running the code the color scheme did not respond to the changing viewport size. 
    The element did not change blue on the break point of viewport size 992px
- as the code was not running as inteded the order was changed back to the original

Step 8.
- created main3.css file and copied the original code there
- change the code according the challenge instructions:
    1. Make the div element 30% of the window size. Now make this change only for the devices that are wider than or equal to 992px
    2. Set the margin to 10px on all sides for each column for the devices taht are wider tahn or equal to 992px
    3. Keep the full-size width for the devices below the 992px
    4. Remeber to keep in mind the mobile-first approach
- chenged the href to main3.css and run the code
- the behavior was a expected: 
    1. the stacked black elements covering the full width of the screen till 767px
    2. between widths 768px and 991px the elemnts changed the color to persimmon
    3. from 992px the elements changed to blue and were in line with a separating margin between them

Step 9.
- initialized an empty Git repositroy
- created a GitHub mobile first repository remotely
- staged the mobilefirst local repository and pushed it to GitHub mobilefirst repository
