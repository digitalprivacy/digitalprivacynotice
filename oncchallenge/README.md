digitalprivacynotice
====================

Digital Privacy Notice code for the medical field and health insurance industries

Description:
------------

This entry was designed to present an unobtrusive but constantly present button to access the notice. Once clicked it opens a dialog with interactive accordians that nest the information from the layered notices developed by the ONC/OCR collaboration. The intention is to provide a simple yet effecitve way to browse the information in the notice. At the bottom of the dialog is a link to a filled out copy of the PDF taken from the HHS/OCR website for printing.

It was designed to not require any modifications to an existing page except to include the javascript and css files in the header.


Instructions:
-------------

Simply fill out the nppConfig variables at the top of npp.js file. Most of the fields will work with html tags so you can include custom formatting based on ids/classes and css. The fields follow the instructions in the model notice files from ONC/OCR.

Include jQuery, jQuery UI, your selected jQuery UI theme, npp.js and npp.css into you webpage header.


Dependencies:
-------------

* jQuery UI -- provides the accordian and button theming and a cross browser way to keep the button on screen. 
* jQuery -- required for jQuery UI
