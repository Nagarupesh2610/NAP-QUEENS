QA ASSIGNMENT
1. Preparation
 Log in to your account and navigate to the Business Intelligence section.
 Tools:Ensure you have the necessary testing tools 
Script testing by (TEST COMPLETE TOOL) :-
 Now,I am performing the anarix company website which was given to do the testing 
tasks to the website now I am performing the automation testing to the website of 
business intelligence feature.
 LOGIN PAGE TESTING:
function Test3()
{
 //Opens the specified URL in a running instance of the specified browser.
 Browsers.Item(btChrome).Navigate("https://test.anarix.ai/user/login");
 //Maximizes the specified Window object.
 Aliases.browser.BrowserWindow.Maximize();
 //Clicks the 'textboxEmail' control.
 Aliases.browser.pageAnarix2.formWelcomeBack.textboxEmail.Click();
 //Sets the text 'qa-assement@mailinator.com' in the 'textboxEmail' text editor.
 Aliases.browser.pageAnarix2.formWelcomeBack.textboxEmail.SetText("qaassement@mailinator.com");
 //Clicks the 'textboxPassword' control.
 Aliases.browser.pageAnarix2.formWelcomeBack.textboxPassword.Click();
 //Sets the text Project.Variables.Password1 in the 'textboxPassword' text editor.
 
Aliases.browser.pageAnarix2.formWelcomeBack.textboxPassword.SetText(Project.Variables.Passw
ord1);
 //Clicks the 'buttonLogin' button.
 Aliases.browser.pageAnarix2.formWelcomeBack.buttonLogin.ClickButton();
 //Clicks the 'button' button.
 Aliases.browser.pageAnarix2.formWelcomeBack.button.ClickButton();
 //Clicks the 'button' button.
 Aliases.browser.pageAnarix2.formWelcomeBack.button.ClickButton();
 //Clicks the 'BrowserWindow' object.
 Aliases.browser.BrowserWindow.Click(1048, 11);
 //Clicks the 'BrowserWindow' object.
 Aliases.browser.BrowserWindow.Click(1256, 39);
 //Clicks the 'textboxEmail' control.
 Aliases.browser.pageAnarix2.formWelcomeBack.textboxEmail.Click();
 //Sets the text 'qa-assessment@mailinator.com' in the 'textboxEmail' text editor.
 Aliases.browser.pageAnarix2.formWelcomeBack.textboxEmail.SetText("qaassessment@mailinator.com");
 //Clicks the 'buttonLogin' button.
 Aliases.browser.pageAnarix2.formWelcomeBack.buttonLogin.ClickButton();
}
 BUSINESS INTELLIGENCE TO KEYWORD TRACKER TESTING:
function Test4()
{
 //Opens the specified URL in a running instance of the specified browser.
 Browsers.Item(btChrome).Navigate("https://test.anarix.ai/marketintelligence?marketplace=amazon");
 //Maximizes the specified Window object.
 Aliases.browser.BrowserWindow.Maximize();
 //Clicks the 'textnodeKeywordTracker2' control.
 
Aliases.browser.pageAnarix.textnodeAdvertising.textnodeKeywordTracker.textnodeKeywordTracke
r2.Click();
}
 KEYWORD ACTIONS:
SELECTION AND DESELECTION ACTIONS OF KEYWORD:-
function Test5()
{
 //Opens the specified URL in a running instance of the specified browser.
 Browsers.Item(btChrome).Navigate("https://test.anarix.ai/market-intelligence/keywordtracker?marketplace=amazon");
 Aliases.browser.BrowserWindow.Maximize();
 //Sets the state of the 'checkbox' checkbox to True.
 Aliases.browser.pageAnarix.checkbox.ClickChecked(true);
 //Sets the state of the 'checkbox2' checkbox to True.
 Aliases.browser.pageAnarix.checkbox2.ClickChecked(true);
 //Sets the state of the 'checkbox3' checkbox to True.
 Aliases.browser.pageAnarix.checkbox3.ClickChecked(true);
 //Sets the state of the 'checkbox4' checkbox to True.
 Aliases.browser.pageAnarix.checkbox4.ClickChecked(true);
 //Sets the state of the 'checkbox5' checkbox to True.
 Aliases.browser.pageAnarix.checkbox5.ClickChecked(true);
 //Sets the state of the 'checkbox6' checkbox to False.
 Aliases.browser.pageAnarix.checkbox6.ClickChecked(false);
}
SELECTION AND DESELECTION ACTION OF KEYWORDS DONE.
 MAKING KEYWORD ACTIVE AND DE-ACTIVE ACTIONS:
While testing the the active and de-active actions the testing results getting the issues and 
bugs reports.(script testing cannot be performed).
 Deletion action of keyword:-
function Test7()
{
 //Opens the specified URL in a running instance of the specified browser.
 Browsers.Item(btChrome).Navigate("https://test.anarix.ai/market-intelligence/keywordtracker?marketplace=amazon");
 //Maximizes the specified Window object.
 Aliases.browser.BrowserWindow.Maximize();
 //Clicks the 'button' button.
 Aliases.browser.pageAnarix.button.ClickButton();
 //Clicks the 'buttonDelete' button.
 Aliases.browser.pageAnarix.buttonDelete.ClickButton();
}
ADD KEYWORD ACTION:
IN THIS WAY THE TOTAL SCRIPT TESTING OF AUTOMATION TESTING OF 
TEST COMPLETE TOOL HAVE BEEN PERFORMED TO THE BUSINNES 
INTELLUGENCE FEATURE OF ANARIX WEBSITE GIVEN BY THE 
COMPANY.
2. Testing the SOV Dashboard
Objective: Verify the functionality and data accuracy of the SOV Dashboard.
 Open the Dashboard: Start by navigating to the SOV Dashboard within the Business 
Intelligence feature.
 Check the Data:
o Look at the Data: Ensure that SOV data for various brands and keywords is 
visible and clearly presented.
o Data Accuracy: Cross-check the data with known information, if available, to 
ensure it is correct.
 Apply Filters:
o Find Filters: Locate filters for date range, categories, brands, or keywords.
o Test Filters: Apply different filters one by one and observe if the data updates 
correctly.
o Multiple Filters: Apply multiple filters simultaneously to see if the dashboard 
handles complex queries properly.
 Test Pagination:
o Navigate Pages: Use pagination controls to move to the next and previous 
pages. Check if the data loads correctly and transitions smoothly.
o Direct Page Jump: If available, use options to jump to a specific page and 
ensure it works correctly.
 Transition to Brand Analytics:
o Select a Brand: Click on a brand name or link within the SOV Dashboard.
o Verify Transition: Ensure you are taken to the Brand Analytics page without 
any issues.
o Check Data: Verify that the data on the Brand Analytics page corresponds to 
the selected brand, showing details like product appearance, average rank, and 
more.
3. Testing the Keyword Tracker
Objective: Ensure that adding, removing, and tracking keywords works as expected.
 Navigate to Keyword Tracker: Go to the Keyword Tracker section within the 
Business Intelligence feature.
 Adding a Keyword:
o Enter Keyword: Type a new keyword into the input field.
o Add Keyword: Click the "Add Keyword" button.
o Verify Addition: Check that the keyword appears in the list of tracked 
keywords with initial data for appearance and ranking.
 Removing a Keyword:
o Select Keyword: Choose a keyword from the list.
o Remove Keyword: Use the "Remove" option to delete the keyword.
o Verify Removal: Ensure the keyword is no longer in the list.
 Bulk Upload:
o Use Bulk Upload: Test the bulk upload feature to add multiple keywords at 
once.
o Check for Issues: Ensure all keywords are added correctly and their data is 
displayed.
4. General UI and UX Testing
Objective: Verify that the user interface is stable and the user experience is consistent.
 Cross-Browser Testing:
o Test in Different Browsers: Open the feature in various browsers (Chrome, 
Firefox, Edge, etc.) to ensure it works consistently.
 Check Responsiveness:
o Different Screen Sizes: Test the feature on different devices (desktop, tablet, 
mobile) to ensure it is responsive.
 Evaluate UI/UX:
o Intuitive Design: Ensure the interface is user-friendly and easy to navigate.
o Visual Consistency: Look for any visual issues such as broken links or 
misaligned elements.
5. Bug Reporting and Summary
Objective: Document any issues found and provide a summary of testing.
 Bug Reporting:
o Document Issues: Create a bug report for any issues, including a description, 
steps to reproduce, and expected vs. actual results.
o Include Evidence: Attach screenshots or videos if possible.
 Write a Summary:
o Overview: Summarize what was tested.
o Key Findings: Highlight any critical issues found.
o Suggestions: Provide any suggestions for improvement.
By following these steps, you will be able to systematically test the Business Intelligence 
feature, ensuring it functions correctly and provides a good user experience.
