# dig-deeper
A set of Automator services that use AppleScript to perform various LinkedIn and Glassdoor searches on selected text via the macOS Services menu.

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
* It helps to be logged in to the appropriate website(s) in Safari, but Safari need not be open.

Installation

1. Download the workflow.zip files.
2. Move them to your ~/Library/Services folder.
3. (Possibly optional) Change permissions for those files so that you have read, write and execute permissions.

To run
1. Select some text or right click a word.
2. From the Services submenu, choose your search.
3. After a pause (AppleScript is not renowned for its speed) the appropriate LinkedIn and/or Glassdoor web page should load with the selected text as your search term(s).
