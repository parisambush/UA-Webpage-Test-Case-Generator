UA Webpage Test Case Generator
========================

This is a Javascript app designed to generate Selenium IDE test cases for multiple versions of UA pages. This app is to be used to assist with automation testing of UA (User Agreement) pages for legal entities with multiple countires. This includes such entities as ROW (Rest of World), which has pages spanning over 146 countries. Test cases created in Selenium IDE can be imported into the app, which will then generate test cases for all of the pages' English country versions. The code generated can then be inserted back into Selenium IDE and then run to start testing.

Version History:

R002:
- Created separate functions for all country sets.
- Added custom country set function.
- Added radio button selectors for country sets.

R003:
- Users can now choose from preset country sets or create their own.
- Added country set for SENE, Nordics, and EUSO group.
- Some cleanup of page styling and code cleanup.

R004:
- Users can now choose from stage or live domains of SR2 or CAT CMS.

R005:
- Users can now input the page name they want to test on.
- Appended English locales to all created URLs.

Usage:
1 - Download the Selenium IDE plugin in Firefox through Firefox addons (Ctrl+Shift+A). Then open up both the Selenium IDE addon and the UA Webpage Test Case Generator.
2 - Create your test case in Selenium IDE. Make sure your test case has just one open tag in it. This tag will be modified with generated URLs based on what you choose.
3 - Click on the source tab in Selenium IDE and copy and paste the code in the filed which says "Insert Selenium IDE test code here".
4 - Set your parameters for country set, domain set, and page name in their respective fields. Once done, click the "Generate Code" button at the bottom of the screen.
5 - The code for your test cases will be generated in the code field. Copy this code back into the source under the "source" tab in Selenium IDE. You can now run you test cases for all the country versions of the page you specified.

System Requirements:
To use this app, you must have a current version of Firefox with the Selenium IDE add on installed. You must have JavaScript enabled.
