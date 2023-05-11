# chrome-extension-leads-tracker
PROJECT TITLE : Chrome Extension Leads Tracker
PROJEECT DESCRIPTION : This extension is used to save the link by either typing in input box  or save url from current tab .
In JSON getting permission from chrome tabs to save the current tab url to the extensions.
In extensions ,url is always there even the tab is refreshed ,it is done by push  the url into local storage in browser by localStorage.setItem("", JSON.stringify())command ,
then get the url from local storage by JSON.parse(localStorage.getItem("")). 
