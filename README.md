# Basics #

Video Tutorial on Survey123 available here: http://youtu.be/ww7oh3p4_Vo

To get started navigate to http://survey123.esri.com and login with your ArcGIS Online credentials

1) Ask Questions: Download the Survey123 Connect tool into your Desktop to transform your own XLSForms into ArcGIS Surveys. In the Survey Gallery at survey123.esri.com, click on Create New Survey to access Survey123 Connect.

2) Get the Facts from the field: Share your Surveys with people in your organization. Ask folks in the field to download the Survey123 app and the Survey/s shared with them

[Download Survey123 App](https://github.com/Esri/Survey123Community/issues/39)
  
3) Make better decisions: As people submit data from the field, you will be able to analyze it in Survey123.esri.com or with any ArcGIS tools.

Some more tips available at our blog: http://survey123.esri.com/#/blog 

___________________________________________________________________________________________________________________

## Latest Version (22-05-2015) ##

Survey123 (Build 1.0.131)  
Survey123 Connect (Build 1.0.95)
- Calculate fields supported.
- Date fields displaying correctly in survey snippets.
- General bug fixes.

___________________________________________________________________________________________________________________

## Latest Version (15-05-2015) ##

Survey123 (Build 1.0.124)  
Survey123 Connect (Build 1.0.89)
- Read-only support for geopoint fields. WIll display location on the map, but location cannot be captured manually. 
- UI scaling improved on high resolution devices.
- General bug fixes.
 
___________________________________________________________________________________________________________________

## Latest Version (05-05-2015) ##

Survey123 (Build 1.0.114)  
- Select ones are now legible in Android if you use an appearance setting 
- Look and feel of the app has changed (a work in progress still)
- Location is now captured automatically as long as your device provides location. If you have a geopoint question, your location becomes the default for that question. If you have no geopoint question, we capture the location anyways.
- The map control now includes a basemap switcher (supports tiled services from ArcGIS Online, ArcGIS for Server as well as OpenStreetMap)
- Compact appearance for select_multiple fields improved
- Improved support for Image type of questions
 
Survey123 Connect (Build 1.0.81)
- You can now update a survey without having to delete the underlying feature service
- More options added so you can set the default basemap, the color scheme of your survey as well as a snippets


___________________________________________________________________________________________________________________

## Latest Version (01-05-2015) ##

Survey123 (Build 1.0.88)  
- Select Basemap in GeoPoint Control
- UI Improvements
 
Survey123 Connect (Build 1.0.75)
- UI Improvements
- Settings Tab allows you to set General, Display, Style, Map and Data options e.g.,
  - Set Form and Text Colors
  - Set Default Basemap and Basemap Extent
  - Set Form Background

Survey123 Web Site
- Updated XLSForm compatibility help page
- Added quick links in the Survey Gallery to the blog, community and installers for the Survey123 App and Connect

Other
- Works better when working behind a proxy


___________________________________________________________________________________________________________________

## Latest Version (01-04-2015) ##

Survey123 (Build 1.0.83)  
Survey123 Connect (Build 1.0.65)

- Survey123 web site:
  - Quick links to download Survey123 Connect available in the Survey123 web site. Log in and look at the bottom.
  - Minor usability fixes.
- Survey123 App:
  - Delete functionality added. Select a survey to find a 'Delete' option in the menu.
  - Minor usability fixes. 
- Survey123 workflows now are compatible with ArcGIS Online organizations set to work over https only.
  - Note that SAML\Enterprise users are not supported in ArcGIS Online. You will only be able to work with built-in users.
- Survey123 workflows are compatible with Portal for ArcGIS 10.3.1. Specify your portal address in the 'Sign In' dialog to point Survey123 at your ArcGIS Portal.
  - Note that only token based authentication is supported. No IWA, PKI or oAuth are supported at this moment.
  - Support is limited to Portal for ArcGIS 10.3.1 configured with the ArcGIS Data Store.

___________________________________________________________________________________________________________________

## Previous Version (02-04-2015) ##

Survey123 (Build 1.0.79)  
Survey123 Connect (Build 1.0.60)

-  Improved scaling of text and buttons for the Review Completed Survey messages

___________________________________________________________________________________________________________________


## Previous Version (31-03-2015) ##

Survey123 (Build 1.0.64)  
Survey123 Connect (Build 1.0.60)

- Number fields on iOS are will use the standard keyboard instead of the numeric keyboard. Unlike the numeric keyboard, this keyboard has the ability to be dismissed.

- Improved scaling of text and buttons for the following:
  - Constraint messages
  - Required Fields messages
  - Cancel Survey messages
  - Save Draft messages
  - Complete Survey messages
 
- Option to begin a new survey added when leaving the current survey (Save Draft, Completed Survey & Cancel Survey).

- ComboBox has no initial selection if default value has been set. 

___________________________________________________________________________________________________________________

## Previous Version (27-03-2015) ##

Survey123 (Build 1.0.61)

- Calendar Widget / Date Picker closes after date is selected 
- Improve regex handling for Relevant and Constraint fields
- Images are honoring Relevant expressions
- Sign In dialog reporting errors correctly

Survey123 Connect (Build 1.0.59)

- Browse to import existing spreadsheet added to New Survey menu
- When publishing a survey, you can choose to publish a WebMap
- When publishing a survey, you can choose to use labels as field alias names
- When publishing a survey, you can choose to enable Editor Tracking
- When publishing a survey, you can choose to create domains from survey choices
- Sign In dialog reporting errors correctly

___________________________________________________________________________________________________________________

## Previous Version (19-03-2015) ##

Survey123 (Build 1.0.52)  
Survey123 Connect (Build 1.0.41)

- Small icons on Android are now resizing correctly
- Image fields are honoring relevant constraints as expected
- Text color legibility issue on Android fixed
 

___________________________________________________________________________________________________________________

## Previous Version (27-02-2015) ##

Survey123 (Build 0.0.42)

Favorites:
Mark a set of answers as a favorite using the menu on the top right of the survey form. Once you have a favorite, use the same menu to paste the answers into a new survey. If you have already provided answers, they will not be overwritten by the paste. Your favorite survey will be saved in your Review list.

Submitted Surveys:
Submitted surveys are now automatically deleted from your device (unless they are set as the favorite).

Survey123 Connect (Build 0.0.39)

Defaults:
Use the default column in your spreadsheets to define the default values for your survey questions. Use today() in date fields to default to today's date. Use a comma separated list for more than one default value for multiple_select fields.

Required Fields:
Put a value of 'yes' in the required fields column of your spreadsheet to ensure a question is answered before it is submitted. If required fields are empty, the survey can only be saved as a draft, not completed.

Survey 123 Webpage:

Download CSV:
Locations are correctly exported to CSV.
