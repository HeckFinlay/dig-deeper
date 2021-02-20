# dig-deeper
A set of macOS Automator services that use AppleScript to perform LinkedIn and Glassdoor searches on selected text in most applications. 

![Services menu screenshot showing Dig Deeper services](Screenshot.jpg?raw=true)

Services:

* LinkedIn and Glassdoor Companies Search
* LinkedIn and Glassdoor Jobs Search
* LinkedIn Companies Search
* LinkedIn Content Search
* LinkedIn Groups Search
* LinkedIn Jobs Search
* LinkedIn People Search
* LinkedIn Schools Search
* Glassdoor Companies Search
* Glassdoor Interview Questions Search
* Glassdoor Jobs Search
* Glassdoor Salaries Search

The services that search Glassdoor make use of Apple's findAndReplaceInText script, which can be found at https://developer.apple.com/library/archive/documentation/LanguagesUtilities/Conceptual/MacAutomationScriptingGuide/ManipulateText.html

Limitations

* When certain special characters, such as the ampersand (&), appear in company names the results may not be as desired.
* Can only be run on selected text where the Services menu is available.
* It helps to be logged in to the appropriate website(s) in your default browser, but your browser doesn't have to be open.

Installation

1. Download and unzip the workflow.zip files.
2. Move them to your ~/Library/Services folder, or just open them and confirm you want to install them.
3. (Possibly optional) Change permissions for the workflow files so that you have read, write and execute permissions.

To run
1. Select some text and right click it or right click a word.
2. From the Services submenu, choose your search.
3. After a pause (AppleScript is not renowned for its speed) the appropriate LinkedIn and/or Glassdoor web page should load with the selected text as the search terms.

Source code

The best way to see how the services work is to open them in Automator but, if you just want to read the inner AppleScript, you can download the .scpt files and view them in Script Editor.
