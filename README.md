# dig-deeper

A set of macOS Automator services that use AppleScript to perform LinkedIn and Glassdoor searches on selected text in most applications. 

![Services menu screenshot showing Dig Deeper services](Screenshot.jpg?raw=true)

#### Services:

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

The services that search Glassdoor make use of Apple's [findAndReplaceInText](https://developer.apple.com/library/archive/documentation/LanguagesUtilities/Conceptual/MacAutomationScriptingGuide/ManipulateText.html) script. 

#### Limitations

* Certain special characters (such as '&'), may produce undesired results.
* A small minority of applications don't support Services, hence these won't run everywhere.

#### Installation

1. Download and unzip the `workflow.zip` files.
2. Move them to `~/Library/Services`, or just open them and confirm installation.
3. (Possibly optional) Change permissions for the files so that you have read, write and execute permissions.

#### Usage
1. Select some text and right click* it or just right click a word.
2. From the Services submenu, choose your search.
3. After a pause (AppleScript is not fast) the LinkedIn and/or Glassdoor search results should load in your default browser with the selected text as the search terms.

\* Alternatively, the Services submenu is available from the Apple Menu.

It helps to be already logged in to LinkedIn and Glassdoor (but your browser doesn't have to be open).

#### Source code

The best way to see how the services work is to open them in Automator. For just the inner AppleScript, download the `.scpt` files and view them in Script Editor.
