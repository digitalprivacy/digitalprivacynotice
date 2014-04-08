digitalprivacynotice
====================

Digital Privacy Notice code for the medical field and health insurance industries

Description:
------------

This entry was designed to present an unobtrusive but constantly present button to access the notice. Once clicked it opens a dialog with interactive accordians that nest the information taken from the layered notices developed by the ONC/OCR collaboration. The intent is to provide a simple yet effecitve way to browse the information in the notice. At the bottom of the dialog is a link to a filled out copy of the PDF taken from the HHS/OCR website for printing.

It was designed to not require any modifications to an existing page except to include the javascript and css files in the head and edit the variables at the top to display appropriate localized information.

Styling also becomes easy by creating your own UI variation with JQuery UI.


Instructions/Requirements:
-------------

1. Include jQuery on your page.
2. Include jQuery UI.
3. Include your chosen jQuery UI Theme. (We used ui-darkness and it is only included as an example.)
4. Include npp.css. You might need to customize the 'example' class to fit your theme.
5. Include npp.css. 
6. Fill in your information.
    1. Remove all the temp data from the nppConfig variable at the top of the npp.js file.
    2. Fill in all relevent fields for your situation in the nppConfig variable.
    3. Fill in your chosen PDF and include a reference to it in 'nppConfig.printableCopyLocation'. A copy of the layered PDF for both providers and healther care are included in the project. But you are free to use any of the model notices or your own.
7. Try it out. Tweek it. Most of the fields will work with html tags to allow you to customize the ids/classes for your own css.


N.B. Currently this project uses the jQuery '$'. You might have conflicts with some older code.

Dependencies:
-------------

* jQuery UI -- provides the accordian and button theming and a cross browser way to keep the button on screen. 
* jQuery -- required for jQuery UI and the npp.js
