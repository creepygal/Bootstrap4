# Bootstrap4 Coursera
Front-End Web UI Frameworks and Tools: Bootstrap 4
The Hong Kong University of Science and Technology

WEEK1:
Objectives and Outcomes

In this assignment, you will continue to work with the website that you have been developing in the exercises. You will add the About Us web page to the website. To get you started, you are provided with a partially formatted aboutus.html.zip file given above that you need to download, unzip and move the aboutus.html to the conFusion folder that contains your website. At the end of this assignment, you should have completed the following tasks:

Updated the page to make use of Bootstrap classes and Bootstrap grid
Formatted the contents of the web page using the container, row and column classes
Use the responsive utilities (hidden-* classes) to enable hiding of the detailed descriptions in the extra small screen size devices
Assignment Requirements

This assignment requires you to complete the following tasks. Detailed instructions for each task are given below. The picture of the completed web page included below indicates the location within the web page that will be updated by the three tasks.

Task 1

In this task you will be updating the aboutus.html page to make use of the Bootstrap classes and components:

Update the page to make use of the Bootstrap CSS classes.
Update the page to also use your custom styles defined in your styles.css file, and
Update the page to make use of all the Bootstrap JS components.
Task 2

In this task you will be adding appropriate formatting to the web page contents using container, row and column classes using the Bootstrap grid so that the web page is formatted to look like the figure given below.

The "About Us" title should stretch the entire width of the row.
The "Our History" part should occupy only half the width of the row for small to extra large screens, leaving space on the right side for more content to be added later. The content should be stacked for extra small screens.
The "Corporate Leadership" section should stretch the entire width of the row.

Task 3

In this task you will use some responsive utilities provided by Bootstrap to hide some of the content only for extra small screens. You will make use of the d-none and d-sm-block CSS classes provided by Bootstrap. To understand how to use these classes, please read the documentation here (in particular see how the combination of classes shown here enables you to hide the content for xs screen sizes) to learn how to apply the d-none and d-sm-block classes. This will get you into the habit of consulting the Bootstrap documentation whenever you need to learn more about the various components and classes of Bootstrap. You should apply the classes so that the <p> elements containing the detailed descriptions of the corporate leadership is hidden only for extra small screens. Thus, your page should look like the figure below on extra small screens.


More details about the d-none and d-sm-block CSS classes can be found at http://getbootstrap.com/docs/4.0/utilities/display/.

Assignment 1(COMPLETED)
![Larger Screen](img/Large%20screen.png)
![Smaller screen](img/small%20screen.png)

Week2:
Objectives and Outcomes

In this assignment, you will continue to work with the website that you have been developing in the exercises. You will edit the home page (index.html). You will start with the current home page at the end of the last exercise in this module. At the end of this assignment, you should have completed the following tasks:

Designed a form to enable users to submit a reservation request for a table. Note that at this stage the form will be inactive. This form should have been included in a new content row that you create just before the footer of the page.
Formatted the contents of the second row of the page using media class. The content column of the row should have been converted to a media object. In addition it should include a badge.
Added a button to the Jumbotron to enable users to access the form to reserve a table at the restaurant. Clicking on this button should take you to the reservation form at the bottom of the page.
Assignment and Requirements

This assignment requires you to complete the following three tasks. Detailed instructions for each task are given below. The picture of the completed web page included below indicates the location within the web page that will be updated by the three tasks.

Task 1

In this task you will be adding another content row to the page. The content row should contain the following:

You should create a reservation form for the user to reserve a table. The reservation form should contain a field using radio that enables the users to specify the number of guests (1-6).
The form should contain fields to specify the date and time of the reservation. The fields should contain appropriate placeholder information to identify the purpose of the fields.
The form should contain a button named Reserve to initiate reservation of the table.
The form should be enclosed inside a card with the heading "Reserve a Table". The card should occupy 8 columns and centred in the row for small to extra-large screens. For extra-small screens, the card should span the entire row.
Task 2

In this task you will be formatting the content in the second row of the page. The formatting should result in the following:

Format the content of the second column with the media class together with the media object class. Use the buffet.png image file provided for you in the img folder. The image should displayed to the right of the content description. See figure below.
Add a badge with the word “NEW” to the content as shown in the figure below.
Task 3

In this task you will be adding a block-sized button to the Jumbotron to the right of the restaurant logo:

The block-level button and the restaurant logo should share the right six columns of the row. The restaurant name and description can now be reduced to occupy the left six columns. Use the small button (btn-sm).
Clicking on the button should take you down to the form for reserving a table.

Assignment2 (COMPLETED)
![](img/screencapture-localhost-3000-index-html-2020-09-01-21_24_04.png)
WEEK3:
Objectives and Outcomes

In this assignment, you will continue to work with the website that you have been developing in the exercises. You will edit the home page (index.html). You will start with the current home page at the end of the last exercise in this module. At the end of this assignment, you should have completed the following tasks:

Moved the table reservation form from the last content row into a modal.
Included a radio button group in the table reservation form to enable diners to ask for a table in the smoking/non-smoking section of the restaurant.
Removed the tooltip from the Reserve Table button.
Updated the Reserve Table button to show the modal containing the table reservation form when the button is clicked.
Assignment Requirements

This assignment requires you to complete the following four tasks. Detailed instructions for each task are given below. The picture of the completed web page included below indicates the location within the web page that will be updated by the four tasks.

Task 1

In this task you will move the table reservation form from the last content row into a modal. You should also remove the last content row.

The form should be completely shifted to a modal.
Add a Cancel button in the form that will dismiss the modal when clicked.
The modal header should contain a X button to dismiss the modal.
Task 2

In this task you will be adding a radio button group to the form to allow the selection of the smoking/non-smoking section of the restaurant.

The radio button group should start out with the non-smoking section selected by default.
The row containing the button group will have the label Section displayed preceding it in the form.
Note: Read Bootstrap Buttons Checkbox/Radio for more information on how to design checkbox/radio buttons.

Task 3

In this task you will be updating the Reserve Table button in the Jumbotron:

Remove the tooltip from the button. This is to facilitate the button to be used to trigger the modal containing the table reservation form in the later tasks. A single button can support only one Javascript plugin via the data-* attributes. Make sure to remove the JavaScript script at the bottom of the page. Also remove the corresponding JavaScript code for the tooltip from the bottom of the page.
You will update the Reserve Table button to show the modal containing the table reservation form when the button is clicked.
